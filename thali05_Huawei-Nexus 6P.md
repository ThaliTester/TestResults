#### Test 87460634d91a0a5_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-30 11:21:53.851   929  2874 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 11:21:54.331  5526  5526 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 11:21:54.337  5526  5526 D AndroidRuntime: CheckJNI is OFF
09-30 11:21:54.366  5526  5526 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 11:21:54.402  5526  5526 I Radio-JNI: register_android_hardware_Radio DONE
09-30 11:21:54.420  5526  5526 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-30 11:21:54.427   929  3056 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 11:21:54.471   929  3056 I ActivityManager: Start proc 5535:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 11:21:54.493  5526  5526 D AndroidRuntime: Shutting down VM
,09-30 11:21:54.819   929   939 I WindowManager: Screenshot max retries 4 of Token{115634d ActivityRecord{4b482e4 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{13b4a7c u0 Starting com.test.thalitest} drawState=4
,09-30 11:21:54.904  5535  5535 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 11:21:54.940  5535  5535 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 11:21:54.963  5535  5535 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 3302-3320)
,09-30 11:21:54.963  5535  5535 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 11:21:54.983  5535  5535 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {41aac32}
,09-30 11:21:54.983  5535  5535 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-30 11:21:54.984  5535  5535 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 11:21:54.989  5535  5535 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 11:21:54.990  5535  5535 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 11:21:55.022  5535  5535 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 11:21:55.038  5535  5535 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 11:21:55.039  5535  5535 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 11:21:55.039  5535  5535 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 11:21:55.039  5535  5535 I Adreno  : Build Date                       : 12/06/15
09-30 11:21:55.039  5535  5535 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 11:21:55.039  5535  5535 I Adreno  : Local Branch                     : mybranch17112971
09-30 11:21:55.039  5535  5535 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 11:21:55.039  5535  5535 I Adreno  : Remote Branch                    : NONE
09-30 11:21:55.039  5535  5535 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 11:21:55.085   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29ff703:true
,09-30 11:21:55.117  2454  2454 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15063]" dev="sockfs" ino=15063 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 11:21:55.117  2454  2454 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[15063]" dev="sockfs" ino=15063 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 11:21:55.130  5535  5535 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 11:21:55.139  5535  5535 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 11:21:55.160   407   407 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32995]" dev="sockfs" ino=32995 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-30 11:21:55.160   407   407 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32995]" dev="sockfs" ino=32995 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 11:21:55.163  3309  3309 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24271]" dev="sockfs" ino=24271 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 11:21:55.163  3309  3309 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[24271]" dev="sockfs" ino=24271 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 11:21:55.169  5535  5559 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 11:21:55.191  5535  5572 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 11:21:55.251   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +431ms (total +805ms)
,09-30 11:21:55.286  5535  5535 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5535
,09-30 11:21:55.378  5535  5535 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 11:21:55.516  5535  5574 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -582747856
,09-30 11:21:55.520  5535  5574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 11:21:55.520  5535  5574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 11:21:55.520  5535  5574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 11:21:55.520  5535  5574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 11:21:55.520  5535  5574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-30 11:21:55.521  5535  5574 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbdf9bb added. We now have 1 listener(s)
,09-30 11:21:55.523  5535  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-30 11:21:55.524  5535  5574 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 11:21:55.525  5535  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:21:55.525  5535  5574 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-30 11:21:55.528  5535  5574 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80a0d16 added. We now have 1 listener(s)
,09-30 11:21:55.528  5535  5574 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:21:55.533   929  2875 D WifiService: New client listening to asynchronous messages
09-30 11:21:55.534  5535  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 11:21:55.534  5535  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-30 11:21:55.534  5535  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-30 11:21:55.534  5535  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-30 11:21:55.534  5535  5574 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-30 11:21:55.536  5535  5574 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 11:21:55.536  5535  5574 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-30 11:21:55.542  5535  5574 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:21:55.542  5535  5574 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:21:55.542  5535  5574 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-30 11:21:55.542  5535  5574 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:21:55.542  5535  5574 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 11:21:55.545  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:21:55.548  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:21:55.564  5535  5535 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 11:21:55.847  5535  5581 W jxcore-log: Initializing JXcore engine
,09-30 11:21:55.843  5581  5581 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11180 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-30 11:21:55.847  5535  5581 W jxcore-log: JXcore engine is ready
09-30 11:21:55.843  5581  5581 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[17436]" dev="sockfs" ino=17436 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-30 11:21:55.843  5581  5581 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=6259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 11:21:55.843  5581  5581 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32971]" dev="sockfs" ino=32971 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-30 11:21:55.878  5535  5544 I art     : Background sticky concurrent mark sweep GC freed 86181(8MB) AllocSpace objects, 18(1892KB) LOS objects, 26% free, 24MB/32MB, paused 5.047ms total 115.234ms
,09-30 11:21:55.887  5535  5581 W jxcore-log: Starting JXcore engine
,09-30 11:21:55.957  5535  5581 W jxcore-log: Platform android
09-30 11:21:55.957  5535  5581 W jxcore-log: 
09-30 11:21:55.957  5535  5581 W jxcore-log: Process ARCH arm
09-30 11:21:55.957  5535  5581 W jxcore-log: 
,09-30 11:21:56.077  5535  5581 I jxcore-log: JXcore Cordova bridge is ready!
09-30 11:21:56.077  5535  5581 I jxcore-log: 
,09-30 11:21:56.077  5535  5581 W jxcore-log: JXcore engine is started
,09-30 11:21:56.082  5535  5574 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 11:21:56.085  5535  5535 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 11:21:59.693   929  5285 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 11:21:59.782  5535  5581 I jxcore-log: 2016-09-30 15:21:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 11:21:59.782  5535  5581 I jxcore-log: 
,09-30 11:21:59.784  5535  5581 I jxcore-log: 2016-09-30 15:21:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 11:21:59.784  5535  5581 I jxcore-log: 
,09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:21:59.787  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:21:59.788  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:21:59.789  5535  5581 I jxcore-log: 2016-09-30 15:21:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 11:21:59.789  5535  5581 I jxcore-log: 
,09-30 11:21:59.789  5535  5581 I jxcore-log: 2016-09-30 15:21:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 11:21:59.789  5535  5581 I jxcore-log: 
,09-30 11:21:59.884  5535  5581 I jxcore-log: 2016-09-30 15:21:59 - DEBUG UnitTest_app: 'Running unit tests'
09-30 11:21:59.884  5535  5581 I jxcore-log: 
,09-30 11:21:59.884  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:21:59.884  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c77312c added. We now have 2 listener(s)
09-30 11:21:59.885  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:21:59.885  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:21:59.885  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 11:21:59.885  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:21:59.885  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c387f5 added. We now have 2 listener(s)
09-30 11:21:59.885  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:21:59.885  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 11:21:59.887  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:21:59.889  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:21:59.890  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:59.890  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:21:59.890  5535  5581 D executeNativeTests: Running unit tests
,09-30 11:21:59.896  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:21:59.900  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:21:59.927  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 11:21:59.927  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb added. We now have 3 listener(s)
09-30 11:21:59.928  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 11:21:59.928  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:21:59.928  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 11:21:59.928  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 11:21:59.928  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 added. We now have 3 listener(s)
09-30 11:21:59.928  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:21:59.928  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 11:21:59.930  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:21:59.932  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:21:59.933  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:59.933  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:21:59.934  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-30 11:21:59.934  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 11:21:59.934  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-30 11:21:59.934  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 11:21:59.935  5535  5581 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-30 11:21:59.935  5535  5581 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 11:21:59.935  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 11:21:59.935  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 11:21:59.935  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-30 11:21:59.935  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 11:21:59.936  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:21:59.936  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:21:59.936  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 11:21:59.936  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:21:59.936  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.936  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:21:59.936  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:21:59.936  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:21:59.936  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb removed from the list
09-30 11:21:59.936  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:21:59.936  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 removed from the list
09-30 11:21:59.938  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:21:59.938  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 11:21:59.938  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.938  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.938  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.939  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 11:21:59.939  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:21:59.939  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:21:59.939  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:21:59.940  5535  5581 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-30 11:21:59.940  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:21:59.940  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:21:59.940  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:21:59.940  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 11:21:59.940  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.940  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.940  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:21:59.940  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:21:59.940  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:21:59.941  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:21:59.941  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:21:59.941  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.941  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.941  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.941  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.941  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:21:59.941  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 11:21:59.941  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:21:59.941  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:21:59.943  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 11:21:59.944  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 11:21:59.944  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:21:59.944  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:21:59.945  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:21:59.945  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:21:59.945  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.945  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.945  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:21:59.945  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:21:59.945  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:21:59.945  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:21:59.945  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:21:59.945  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.945  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.945  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:21:59.945  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:21:59.945  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:21:59.945  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:21:59.945  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:21:59.945  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:21:59.946  5535  5581 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 11:21:59.947  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:21:59.949  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:21:59.950  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:21:59.950  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:21:59.950  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:21:59.950  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 11:21:59.950  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 11:21:59.950  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:21:59.950  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 11:21:59.953  5535  5581 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 11:21:59.954  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 11:21:59.954  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:21:59.958  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:21:59.958  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 11:21:59.959  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 11:21:59.959  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 11:21:59.960  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 11:21:59.961  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 11:21:59.961  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 11:21:59.962  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 11:21:59.962  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 11:21:59.962  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 11:21:59.962  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 11:21:59.962  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:21:59.964  4494  4747 D BtGatt.GattService: registerClient() - UUID=9482413a-3354-451a-a1c8-fc3a28d703f5
09-30 11:21:59.966  4494  4576 D BtGatt.GattService: onClientRegistered() - UUID=9482413a-3354-451a-a1c8-fc3a28d703f5, clientIf=5
09-30 11:21:59.966  5535  5546 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 11:21:59.967  4494  4732 D BtGatt.GattService: start scan with filters
09-30 11:21:59.970  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 11:21:59.970  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 11:21:59.970  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:21:59.970  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 11:21:59.970  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 11:21:59.970  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 11:21:59.971  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 11:21:59.972  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 11:21:59.972  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 11:21:59.972  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 11:21:59.972  4494  4581 D BtGatt.ScanManager: handling starting scan
09-30 11:21:59.972  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 11:21:59.974  4494  4581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:21:59.975  5535  5581 I io.jxcore.node.ConnectionHelper: start: OK
09-30 11:21:59.981  4494  4576 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 11:21:59.981  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:21:59.982  4494  4581 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 11:21:59.986  4494  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 11:21:59.987  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:21:59.987  4494  4581 D BtGatt.ScanManager: Starting BLE batch scan
09-30 11:21:59.987  4494  4581 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 11:21:59.996  4494  4576 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 11:21:59.996  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:00.001  4494  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 11:22:00.001  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:00.321   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 11:22:00.473  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 11:22:00.474  5535  5535 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:22:00.474  5535  5535 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 11:22:03.346   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 11:22:04.979  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:04.980  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 11:22:04.980  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 11:22:04.980  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:04.980  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 11:22:04.980  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 11:22:04.980  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 11:22:04.980  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 11:22:04.980  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 11:22:04.980  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 11:22:04.981  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 11:22:04.981  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 11:22:04.982  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:22:04.983  4494  4747 D BtGatt.GattService: stopScan() - queue size =1
09-30 11:22:04.985  4494  4732 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 11:22:04.986  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 11:22:04.986  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 11:22:04.987  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-30 11:22:04.987  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 11:22:04.987  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 11:22:04.987  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 11:22:04.987  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 11:22:04.988  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 11:22:04.991  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 11:22:04.992  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-30 11:22:04.992  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-30 11:22:04.992  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 11:22:04.993  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 11:22:04.996  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 11:22:05.000  4494  4494 D BtGatt.ScanManager: awakened up at time 213357
09-30 11:22:05.001  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:05.001  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:05.001  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:05.001  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:05.001  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:22:05.001  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 11:22:05.001  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:05.001  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:05.002  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:05.002  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:05.002  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:05.002  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:05.006  4494  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-30 11:22:05.007  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:05.007  4494  4581 D BtGatt.ScanManager: stopping BLe Batch
,09-30 11:22:05.020  4494  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 11:22:05.020  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:05.021  4494  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 11:22:05.047  4494  4576 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-30 11:22:05.047  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:05.047  4494  4576 D BtGatt.GattService: current time is 213405225313
,09-30 11:22:05.048  4494  4576 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -76, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -74, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-30 11:22:05.050  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-30 11:22:05.053  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 11:22:05.054  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 11:22:05.054  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 11:22:05.054  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-30 11:22:05.140  3475  5584 I VacuumService: Vacuum at: now=1475248925140 tag=VacuumService
,09-30 11:22:05.182  3475  5587 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,09-30 11:22:05.211  3475  5585 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-30 11:22:05.213  3475  5585 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-30 11:22:05.254  3475  5585 W Uploader:  no longer exists, so no auth token.
,09-30 11:22:05.265  3475  5587 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-30 11:22:05.502  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 11:22:06.188  3475  5594 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-30 11:22:06.359  3475  5595 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-30 11:22:06.426  3475  5585 W Uploader:  no longer exists, so no auth token.
,09-30 11:22:06.435  3475  5594 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-30 11:22:06.540  3475  5595 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,09-30 11:22:10.005  5535  5581 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 11:22:10.011  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:10.023  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:22:10.028  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:22:10.029  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:22:10.030  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:22:10.030  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 11:22:10.030  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 11:22:10.030  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:22:10.030  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 11:22:10.037  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:10.041  5535  5581 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 11:22:10.041  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 11:22:10.043  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:10.051  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 11:22:10.052  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 11:22:10.053  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 11:22:10.058  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
,09-30 11:22:10.058  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 11:22:10.058  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 11:22:10.058  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 11:22:10.058  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 11:22:10.059  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:22:10.063  4494  4747 D BtGatt.GattService: registerClient() - UUID=f99e9c08-6c7f-4007-9a7f-a44e347a91f4
,09-30 11:22:10.064  4494  4576 D BtGatt.GattService: onClientRegistered() - UUID=f99e9c08-6c7f-4007-9a7f-a44e347a91f4, clientIf=5
,09-30 11:22:10.064  5535  5546 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 11:22:10.065  4494  4514 D BtGatt.GattService: start scan with filters
09-30 11:22:10.068  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 11:22:10.069  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 11:22:10.069  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:22:10.069  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-30 11:22:10.069  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 11:22:10.069  4494  4581 D BtGatt.ScanManager: handling starting scan
09-30 11:22:10.069  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 11:22:10.069  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 11:22:10.073  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 11:22:10.073  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 11:22:10.073  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 11:22:10.074  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 11:22:10.078  4494  4576 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 11:22:10.078  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:10.078  5535  5581 I io.jxcore.node.ConnectionHelper: start: OK
09-30 11:22:10.078  4494  4581 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 11:22:10.081  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:22:10.081  5535  5581 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-30 11:22:10.081  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 11:22:10.081  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 11:22:10.082  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:10.082  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-30 11:22:10.082  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:10.082  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 11:22:10.082  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 11:22:10.082  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 11:22:10.082  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 11:22:10.082  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 11:22:10.082  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 11:22:10.083  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:22:10.084  4494  4747 D BtGatt.GattService: stopScan() - queue size =1
09-30 11:22:10.085  4494  4514 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 11:22:10.085  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 11:22:10.086  4494  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 11:22:10.086  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:10.086  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-30 11:22:10.086  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 11:22:10.086  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:22:10.086  4494  4581 D BtGatt.ScanManager: Starting BLE batch scan
09-30 11:22:10.086  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 11:22:10.086  4494  4581 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 11:22:10.087  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 11:22:10.087  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 11:22:10.087  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 11:22:10.088  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:22:10.088  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 11:22:10.088  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 11:22:10.088  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-30 11:22:10.088  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 11:22:10.089  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:22:10.091  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:10.091  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:10.091  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:10.091  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:10.092  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 11:22:10.092  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:22:10.092  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:10.092  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:10.092  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:10.092  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:10.092  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:10.092  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:10.093  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:10.093  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:10.094  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:10.094  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:10.094  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:10.094  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:10.095  5535  5581 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 11:22:10.098  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:22:10.099  4494  4576 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 11:22:10.099  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:10.104  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:22:10.106  4494  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 11:22:10.106  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:10.108  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:22:10.108  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:22:10.108  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:22:10.108  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 11:22:10.108  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 11:22:10.108  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:22:10.108  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 11:22:10.111  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:10.114  5535  5581 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 11:22:10.114  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:10.114  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 11:22:10.115  4494  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 11:22:10.115  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:10.115  4494  4581 D BtGatt.ScanManager: stopping BLe Batch
,09-30 11:22:10.118  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 11:22:10.119  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 11:22:10.119  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 11:22:10.120  4494  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 11:22:10.120  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:10.121  4494  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 11:22:10.122  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 11:22:10.123  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 11:22:10.123  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 11:22:10.123  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 11:22:10.123  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 11:22:10.123  5535  5581 D BluetoothAdapter: STATE_ON
,09-30 11:22:10.126  4494  4511 D BtGatt.GattService: registerClient() - UUID=fec3ffd3-c797-46e4-92e9-ee8c0d51b692
09-30 11:22:10.126  4494  4576 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-30 11:22:10.126  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:10.127  4494  4576 D BtGatt.GattService: onClientRegistered() - UUID=fec3ffd3-c797-46e4-92e9-ee8c0d51b692, clientIf=5
,09-30 11:22:10.127  5535  5545 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 11:22:10.127  4494  4747 D BtGatt.GattService: start scan with filters
09-30 11:22:10.130  4494  4581 D BtGatt.ScanManager: handling starting scan
09-30 11:22:10.130  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 11:22:10.130  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 11:22:10.130  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 11:22:10.130  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 11:22:10.130  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 11:22:10.130  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 11:22:10.131  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 11:22:10.134  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 11:22:10.134  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 11:22:10.134  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 11:22:10.135  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 11:22:10.137  4494  4576 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 11:22:10.137  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:10.137  4494  4581 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 11:22:10.138  5535  5581 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 11:22:10.142  4494  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 11:22:10.142  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:10.142  4494  4581 D BtGatt.ScanManager: Starting BLE batch scan
09-30 11:22:10.142  4494  4581 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 11:22:10.151  4494  4576 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-30 11:22:10.151  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:10.155  4494  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 11:22:10.155  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:10.280   929  5285 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 11:22:10.373   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 11:22:10.374   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 11:22:10.634  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 11:22:10.635  5535  5535 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:22:10.635  5535  5535 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 11:22:13.853   929  2874 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 11:22:15.138  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:22:15.138  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 11:22:15.139  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-30 11:22:15.139  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:15.139  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 11:22:15.139  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:15.139  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 11:22:15.140  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 11:22:15.140  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 11:22:15.140  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 11:22:15.140  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 11:22:15.140  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 11:22:15.143  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:22:15.144  4494  4747 D BtGatt.GattService: stopScan() - queue size =1
09-30 11:22:15.146  4494  4732 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 11:22:15.147  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 11:22:15.147  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 11:22:15.148  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 11:22:15.148  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:22:15.148  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 11:22:15.148  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 11:22:15.148  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 11:22:15.148  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 11:22:15.152  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:22:15.152  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 11:22:15.152  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 11:22:15.152  4494  4494 D BtGatt.ScanManager: awakened up at time 223509
09-30 11:22:15.152  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-30 11:22:15.153  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 11:22:15.156  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:22:15.158  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:15.158  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:15.158  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:22:15.160  4494  4576 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 11:22:15.160  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:15.160  4494  4581 D BtGatt.ScanManager: stopping BLe Batch
,09-30 11:22:15.167  4494  4576 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 11:22:15.167  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:22:15.168  4494  4581 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 11:22:15.186  4494  4576 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-30 11:22:15.186  4494  4576 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:22:15.186  4494  4576 D BtGatt.GattService: current time is 223543995901
09-30 11:22:15.187  4494  4576 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -77, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -76, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -74, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 11:22:15.187  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 11:22:15.187  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 11:22:15.187  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 11:22:15.187  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 11:22:15.188  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 11:22:15.188  4494  4576 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 11:22:15.659  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 11:22:15.660  5535  5535 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:15.660  5535  5535 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 11:22:18.457   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 11:22:20.159  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:22:20.160  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.160  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.160  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.160  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:20.161  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:22:20.161  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.161  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.161  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:22:20.161  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.161  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.162  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.163  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.164  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.167  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 11:22:20.167  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.167  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.167  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.169  5535  5581 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-30 11:22:20.171  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:22:20.171  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.171  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.171  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.171  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.172  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.172  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 11:22:20.172  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.172  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.172  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.173  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.173  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:20.173  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.173  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.173  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.176  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.176  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.177  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.177  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:20.178  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 11:22:20.178  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:22:20.178  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.178  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.179  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.179  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.179  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.179  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.179  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.179  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.179  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.179  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.179  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:20.179  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.179  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.179  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.181  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.181  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.181  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.181  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:20.182  5535  5581 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-30 11:22:20.182  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:20.182  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.182  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.182  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.183  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.183  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.183  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.183  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.183  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.183  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:20.183  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.183  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.183  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.183  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.183  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.184  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.185  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.185  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.185  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:20.186  5535  5581 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 11:22:20.186  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:20.186  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.186  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.186  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.186  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.186  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.186  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.187  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
,09-30 11:22:20.187  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.187  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.187  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.187  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.187  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.187  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.187  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.188  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.188  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.188  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.189  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:20.189  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 11:22:20.190  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-30 11:22:20.190  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 11:22:20.190  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 11:22:20.190  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 11:22:20.190  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 11:22:20.190  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 11:22:20.190  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 11:22:20.190  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 11:22:20.190  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:22:20.191  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.191  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.191  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.191  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.191  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.191  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.191  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.191  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.191  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.191  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.191  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.191  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.191  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.191  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.193  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.193  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 11:22:20.193  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.193  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.194  5535  5581 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 11:22:20.194  5535  5581 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 11:22:20.195  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-30 11:22:20.199  5535  5581 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 11:22:20.199  5535  5581 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-30 11:22:20.199  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 11:22:20.200  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 11:22:20.201  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 11:22:20.201  5535  5581 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 11:22:20.201  5535  5581 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 11:22:20.201  5535  5581 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 11:22:20.201  5535  5581 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 11:22:20.201  5535  5581 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-30 11:22:20.201  5535  5581 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 11:22:20.201  5535  5581 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 11:22:20.201  5535  5581 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 11:22:20.202  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-30 11:22:20.205  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-30 11:22:20.206  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-30 11:22:20.206  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-30 11:22:20.207  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-30 11:22:20.207  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-30 11:22:20.207  5535  5581 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 11:22:20.207  5535  5581 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 11:22:20.207  5535  5581 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 11:22:20.207  5535  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-30 11:22:20.208  5535  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 11:22:20.208  5535  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-30 11:22:20.208  5535  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-30 11:22:20.208  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:20.208  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 11:22:20.208  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.208  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.209  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.209  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.209  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.209  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-30 11:22:20.211  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.211  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.211  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.211  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.211  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.211  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.211  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.211  5535  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-30 11:22:20.211  5535  5597 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-30 11:22:20.211  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:20.211  5535  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-30 11:22:20.211  5535  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-30 11:22:20.211  5535  5597 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
09-30 11:22:20.212  5535  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 11:22:20.212  5535  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-30 11:22:20.213  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.213  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.213  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.213  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.214  5535  5581 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 11:22:20.215  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:20.215  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.215  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.215  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.215  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.215  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.215  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.215  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
,09-30 11:22:20.215  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.216  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.216  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.216  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.216  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.216  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.216  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.217  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.217  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.217  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.218  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:20.219  5535  5581 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-30 11:22:20.219  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:20.219  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.219  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.219  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.219  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.219  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.219  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.219  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.219  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.219  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.220  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.220  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.220  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:20.220  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.220  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.221  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.221  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.221  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.221  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.222  5535  5581 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-30 11:22:20.223  5535  5581 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 11:22:20.223  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 11:22:20.223  5535  5581 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-30 11:22:20.223  5535  5581 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 11:22:20.223  5535  5581 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 11:22:20.223  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 11:22:20.223  5535  5581 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 11:22:20.223  5535  5581 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-30 11:22:20.223  5535  5581 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 11:22:20.223  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 11:22:20.224  5535  5581 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 11:22:20.224  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:20.224  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:20.224  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:20.224  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.224  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.224  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.224  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:20.224  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.224  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:22:20.224  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.224  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.224  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.224  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.225  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.225  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:20.226  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:20.226  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:20.226  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.227  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.227  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:20.227  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.227  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:20.227  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 11:22:20.227  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:20.228  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:20.228  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:20.228  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:20.228  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:20.228  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:20.375   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:21.375   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:21.479   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 11:22:22.377   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:23.378   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:24.379   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:25.229  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:22:25.229  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.230  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 11:22:25.230  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.230  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.230  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:25.230  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
,09-30 11:22:25.230  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:25.231  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:25.231  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:25.231  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 11:22:25.231  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.231  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.232  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:25.232  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
,09-30 11:22:25.232  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.232  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.232  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:25.232  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.233  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:25.233  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.233  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.237  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:25.237  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:25.237  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.237  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:25.243  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-30 11:22:25.244  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:22:25.246  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 11:22:25.248  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-30 11:22:25.248  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-30 11:22:25.248  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-30 11:22:25.249  5535  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,09-30 11:22:25.249  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-30 11:22:25.250  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 11:22:25.250  5535  5535 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-30 11:22:25.250  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:25.250  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-30 11:22:25.251  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-30 11:22:25.251  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 11:22:25.251  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.251  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,09-30 11:22:25.251  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 11:22:25.251  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:25.252  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.252  5535  5535 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-30 11:22:25.252  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 11:22:25.252  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 11:22:25.252  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 11:22:25.252  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.252  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:25.253  5535  5599 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:22:25.253  4732  4732 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32108]" dev="sockfs" ino=32108 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 11:22:25.253  4732  4732 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32108]" dev="sockfs" ino=32108 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 11:22:25.254  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 11:22:25.255  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.255  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:25.255  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:25.255  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:22:25.255  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:25.255  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:22:25.255  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 11:22:25.255  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:25.255  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.256  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.256  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 11:22:25.256  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
,09-30 11:22:25.256  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:22:25.256  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.256  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:25.256  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:25.256  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.257  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.257  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.258  5535  5599 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-30 11:22:25.258  5535  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-30 11:22:25.259  5535  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-30 11:22:25.259  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:25.259  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:25.259  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.259  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.259  5535  5535 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 11:22:25.260  5535  5535 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:25.261  5535  5581 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-30 11:22:25.261  5535  5581 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-30 11:22:25.261  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-30 11:22:25.262  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 11:22:25.262  5535  5581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 11:22:25.262  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:22:25.262  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:25.262  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 11:22:25.262  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:25.263  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.263  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.263  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:25.263  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:25.263  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.263  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:25.263  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:25.263  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:25.263  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.263  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.264  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.266  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:25.266  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:25.266  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.266  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:25.272  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:25.273  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:25.273  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:25.273  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:22:25.273  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.273  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.273  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:25.273  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
,09-30 11:22:25.273  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.273  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.273  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:25.274  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.274  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.274  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.274  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:25.276  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:25.276  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:25.276  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.276  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.278  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:22:25.278  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:22:25.278  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:22:25.278  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 11:22:25.278  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.278  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.278  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:22:25.278  5535  5581 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b619eb not in the list
09-30 11:22:25.278  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.278  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
09-30 11:22:25.278  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:25.279  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:25.279  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.279  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:25.279  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:25.280  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:22:25.281  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:22:25.281  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:25.281  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@430d348 not in the list
,09-30 11:22:25.282  5535  5581 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 11:22:25.282  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 11:22:25.283  5535  5581 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-30 11:22:25.283  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 11:22:25.283  5535  5581 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-30 11:22:25.283  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-30 11:22:25.286  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-30 11:22:25.286  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-30 11:22:25.288  5535  5581 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-30 11:22:25.288  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 11:22:25.288  5535  5581 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-30 11:22:25.288  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 11:22:25.289  5535  5581 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 11:22:25.289  5535  5581 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-30 11:22:25.290  5535  5581 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-30 11:22:25.290  5535  5581 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-30 11:22:25.290  5535  5581 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-30 11:22:25.290  5535  5581 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 11:22:25.290  5535  5581 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-30 11:22:25.291  5535  5581 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-30 11:22:25.291  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:22:25.292  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37ec4ea added. We now have 3 listener(s)
09-30 11:22:25.292  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:22:25.293  5535  5581 D BluetoothAdapter: enable(): BT is already enabled..!
,09-30 11:22:25.294   929   940 D WifiService: setWifiEnabled: true pid=5535, uid=10077
09-30 11:22:25.294   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 11:22:25.379   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 11:22:25.757  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 11:22:30.299  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:22:30.300  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f553db added. We now have 4 listener(s)
,09-30 11:22:30.300  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:22:30.314  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:22:30.314  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f553db removed from the list
09-30 11:22:30.315  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:30.315  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:22:30.315  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:30.317  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 11:22:30.317  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5639e78 added. We now have 4 listener(s)
09-30 11:22:30.317  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:22:30.322  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:30.322  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5639e78 removed from the list
09-30 11:22:30.322  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:30.323  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:30.323  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:30.324  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 11:22:30.325  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e833951 added. We now have 4 listener(s)
,09-30 11:22:30.325  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:22:30.330   929  3723 D WifiService: setWifiEnabled: false pid=5535, uid=10077
09-30 11:22:30.330   929  3723 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 11:22:30.335   929  2874 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-30 11:22:30.335   929  2874 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-30 11:22:30.335   929  2874 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 11:22:30.336   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 11:22:30.342  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:22:30.342  4494  4572 D BluetoothAdapterState: Current state: ON, message: 23
09-30 11:22:30.342  4494  4572 D BluetoothAdapterProperties: Setting state to 13
09-30 11:22:30.342  4494  4572 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 11:22:30.345  4494  4572 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 11:22:30.346  4494  4572 I BluetoothAdapterState: Entering PendingCommandState
09-30 11:22:30.347  4494  4576 D BluetoothAdapterProperties: Scan Mode:20
,09-30 11:22:30.348  4494  4572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 11:22:30.349  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:30.349  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:22:30.351  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.351  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:30.352  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:22:30.352  4494  4494 D HeadsetService: Received stop request...Stopping profile...
,09-30 11:22:30.354   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:30.355  3690  3722 D BluetoothHeadset: Proxy object disconnected
,09-30 11:22:30.355  3027  3039 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:30.355  4494  4494 D A2dpService: Received stop request...Stopping profile...
09-30 11:22:30.355  3027  3027 D HeadsetProfile: Bluetooth service disconnected
09-30 11:22:30.356   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:30.356  4494  4742 D A2dpStateMachine: Exit Disconnected: -1
09-30 11:22:30.356   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:30.356  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:30.357   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-30 11:22:30.357   929  5286 D DhcpClient: Clearing IP address
,09-30 11:22:30.361   929   929 D BluetoothA2dp: Proxy object disconnected
,09-30 11:22:30.362  3027  3027 D BluetoothA2dp: Proxy object disconnected
,09-30 11:22:30.364  4494  4494 D HidService: Received stop request...Stopping profile...
,09-30 11:22:30.364  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:30.364  4494  4494 D HidService: Stopping Bluetooth HidService
09-30 11:22:30.365  3027  3027 D BluetoothInputDevice: Proxy object disconnected
09-30 11:22:30.365  3027  3027 D HidProfile: Bluetooth service disconnected
,09-30 11:22:30.366  4494  4494 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:30.366  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.366  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 11:22:30.366  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:30.367  4494  4494 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 11:22:30.367  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.368  4494  4494 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:30.368  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:22:30.368  4494  4576 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 11:22:30.368  4494  4697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:30.368  4494  4697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:30.368  4494  4697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:30.368  4494  4494 D HealthService: Received stop request...Stopping profile...
09-30 11:22:30.368  4494  4576 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 11:22:30.368  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.368  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:30.369  4494  4494 D PanService: Received stop request...Stopping profile...
09-30 11:22:30.370   507   922 D CommandListener: Setting iface cfg
09-30 11:22:30.370  3027  3027 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 11:22:30.370  3027  3027 D PanProfile: Bluetooth service disconnected
09-30 11:22:30.371  4494  4494 D BluetoothMapService: Received stop request...Stopping profile...
09-30 11:22:30.371  4494  4494 D BluetoothMapService: stop()
09-30 11:22:30.372  3475  5342 V NativeCrypto: Read error: ssl=0x7f837e0380: I/O error during system call, Connection timed out
,09-30 11:22:30.372  4494  4494 D BluetoothMapAppObserver: deinitObservers()
09-30 11:22:30.372  4494  4494 D BluetoothMapAppObserver: removeReceiver()
09-30 11:22:30.374  3475  5342 V NativeCrypto: SSL shutdown failed: ssl=0x7f837e0380: I/O error during system call, Broken pipe
09-30 11:22:30.374  4494  4494 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:30.374  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.374  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:30.374  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:30.376  3027  3027 D BluetoothMap: Proxy object disconnected
09-30 11:22:30.376  4494  4576 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 11:22:30.376  3027  3027 D MapProfile: Bluetooth service disconnected
09-30 11:22:30.376  4494  4697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:30.376  4494  4697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:30.376  4494  4697 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 11:22:30.376  4494  4697 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 11:22:30.376  4494  4697 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 11:22:30.376  4494  4697 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 11:22:30.377   929   940 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-30 11:22:30.377   929  5284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-30 11:22:30.378  4494  4494 D SapService: Received stop request...Stopping profile...
,09-30 11:22:30.378  4494  4494 V SapService: stop()
09-30 11:22:30.379  4494  4494 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:30.379  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.379  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:30.379  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:30.379   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:30.380  4494  4494 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-30 11:22:30.380  4494  4494 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 11:22:30.380  4494  4576 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 11:22:30.380  4494  4494 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:30.380  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.379  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.380  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:30.380  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:22:30.380  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:30.381  4494  4494 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 11:22:30.381  4494  4576 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 11:22:30.381  4494  4494 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-30 11:22:30.381  4494  4494 V BluetoothAdapterState: isTurningOff()=true
,09-30 11:22:30.382  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.382  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:30.382  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:30.382  4494  4494 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 11:22:30.382  4494  4494 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-30 11:22:30.383   929  5284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-30 11:22:30.384  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.384  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:30.385  4494  4494 D BluetoothMapService: MAP Service closeService in
09-30 11:22:30.386  4494  4494 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 11:22:30.386  4494  4494 D ObexServerSockets0: shutdown(block = true)
09-30 11:22:30.387  4494  4494 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 11:22:30.386   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 11:22:30.387  4494  4494 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 11:22:30.387   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-30 11:22:30.387   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-30 11:22:30.387  4494  4725 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 11:22:30.388   929  2876 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-30 11:22:30.388  4494  4750 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 11:22:30.388   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-30 11:22:30.389  4494  4749 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-30 11:22:30.389  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:30.389  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:22:30.390   929   929 D RttService: SCAN_AVAILABLE : 1
09-30 11:22:30.390  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.390  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:30.390   537   537 E Parcel  : Reading a NULL string not supported here.
09-30 11:22:30.391  4494  4494 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:30.391  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.391  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 11:22:30.391   929  2980 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 11:22:30.391  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:30.391  4494  4494 D BluetoothMapService: cleanup()
09-30 11:22:30.391  4494  4494 D BluetoothMapService: MAP Service closeService in
09-30 11:22:30.392   929  5287 D DhcpClient: Receive thread stopped
09-30 11:22:30.393  4494  4494 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:30.393  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.393  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:30.393  4494  4494 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:30.394  4494  4572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 11:22:30.394  4494  4572 D BluetoothAdapterProperties: Setting state to 15
09-30 11:22:30.394  4494  4572 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 11:22:30.394  4494  4572 I BluetoothAdapterState: Entering BleOnState
,09-30 11:22:30.396  4494  4494 I BtOppRfcommListener: stopping Accept Thread
09-30 11:22:30.396  4494  5223 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 11:22:30.396  4494  5223 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 11:22:30.397   929  2876 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-30 11:22:30.397   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:30.398  3027  3049 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 11:22:30.399  3649  3799 W QCNEJ   : |CORE| network lost: 100
09-30 11:22:30.402  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:30.402  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:22:30.403  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.403  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:30.405  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:30.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:30.406  3649  3799 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-30 11:22:30.406  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 11:22:30.406  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:30.409  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:30.409  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 11:22:30.416   929  5460 I ActivityManager: Start proc 5611:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-30 11:22:30.417  3027  3039 D BluetoothPan: onBluetoothStateChange on: false
,09-30 11:22:30.420   929  2874 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 11:22:30.420   929  2874 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 11:22:30.421   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 11:22:30.421  3690  4054 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 11:22:30.421  3027  3234 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:30.422  3027  3049 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 11:22:30.423   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 11:22:30.423   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:30.423  3027  3039 D BluetoothMap: onBluetoothStateChange: up=false
09-30 11:22:30.424  3027  3234 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 11:22:30.425  4494  4572 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 11:22:30.425  4494  4572 D BluetoothAdapterProperties: Setting state to 16
09-30 11:22:30.425  4494  4572 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-30 11:22:30.426  4494  4572 D BluetoothAdapterProperties: onBleDisable
,09-30 11:22:30.426  4494  4572 I BluetoothAdapterState: Entering PendingCommandState
,09-30 11:22:30.426  4494  4573 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-30 11:22:30.427  4494  4576 D BluetoothAdapterProperties: Scan Mode:20
,09-30 11:22:30.428   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 11:22:30.429  4494  4697 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 11:22:30.429  4494  4697 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:30.430  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:30.430  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:30.432  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:30.433  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:30.435  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:30.437  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:30.439  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:30.447  3757  5605 I EventLogService: Aggregate from 1475247147254 (log), 1475247147254 (data)
,09-30 11:22:30.452   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 11:22:30.453   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-30 11:22:30.453   507   922 D TetherController: Setting IP forward enable = 0
,09-30 11:22:30.454   929  2876 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-30 11:22:30.455   929  2876 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 11:22:30.456   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-30 11:22:30.457   929  2874 D DhcpClient: doQuit
09-30 11:22:30.458   929  2874 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 11:22:30.458   929  5286 D DhcpClient: onQuitting
09-30 11:22:30.458  5166  5166 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9adb43e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-30 11:22:30.459  3375  3375 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-30 11:22:30.459  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:30.462  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:30.463  4951  4975 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-30 11:22:30.463  4951  4975 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 11:22:30.464  4951  4975 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 11:22:30.465  4951  4975 E SarControlService: no key has been found,reset the power
09-30 11:22:30.465  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 11:22:30.465  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 11:22:30.465  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:30.465  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:30.465  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-30 11:22:30.465  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:22:30.465  4976  4976 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 11:22:30.466  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.466  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 11:22:30.466  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-30 11:22:30.466  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 11:22:30.467  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 11:22:30.467  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:22:30.467  4976  4976 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 11:22:30.471  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000ea03000000000000ffffffff]
,09-30 11:22:30.471  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 11:22:30.471  4976  4990 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 11:22:30.471  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:22:30.472  4951  4961 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 11:22:30.472  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000eb03000000000000ffffffff]
09-30 11:22:30.472  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 11:22:30.472  4976  4990 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 11:22:30.473  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:22:30.473  4951  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 11:22:30.474  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:30.474  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 11:22:30.475  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.475  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:30.477  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:30.477  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:30.478  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:30.478  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:30.480  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:30.488  5611  5611 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-30 11:22:30.490  3375  3375 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-30 11:22:30.495  3375  3375 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 11:22:30.502  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 11:22:30.508   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c26a58:true
,09-30 11:22:30.509  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 11:22:30.517   507   922 E Netd    : netlink response contains error (No such file or directory)
,09-30 11:22:30.519   929  2876 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 11:22:30.522   929  3724 I ActivityManager: Start proc 5632:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-30 11:22:30.526  3375  3375 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 11:22:30.540  5611  5611 D LocalBluetoothProfileManager: Adding local MAP profile
,09-30 11:22:30.544  3375  3375 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 11:22:30.551  5611  5611 D BluetoothMap: Create BluetoothMap proxy object
,09-30 11:22:30.561  5632  5632 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 11:22:30.563  5611  5611 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 11:22:30.573  5611  5611 D DockEventReceiver: finishStartingService: stopping service
,09-30 11:22:30.634  4494  4576 I bt_hci  : shut_down
,09-30 11:22:30.638  4494  4583 D bt_hwcfg: hw_epilog_process
,09-30 11:22:30.638  4494  4583 I bt_vendor: low_power_mode_cb
,09-30 11:22:30.640  4494  4583 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 11:22:30.640  4494  4583 I bt_vendor: epilog_cb
09-30 11:22:30.640  4494  4583 I bt_hci  : epilog_finished_callback
,09-30 11:22:30.643  4494  4576 I bt_hci_h4: hal_close
,09-30 11:22:30.643  4494  4576 I bt_userial_vendor: device fd = 54 close
,09-30 11:22:30.646   929  2874 D wifi    : In wifi stop Hal
,09-30 11:22:30.646   929  2874 D wifi    : halHandle = 0x7f82827e00, mVM = 0x7f9ee0d140, mCls = 0x100a02
09-30 11:22:30.646  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 11:22:30.646   929  3374 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 11:22:30.646   929  3374 D WifiHAL : Got a signal to exit!!!
09-30 11:22:30.646   929  3374 I WifiHAL : Exit wifi_event_loop
09-30 11:22:30.646   929  2874 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-30 11:22:30.647   929  2874 E WifiHAL : Event processing terminated
,09-30 11:22:30.647   929  2874 D wifi    : In wifi cleaned up handler
09-30 11:22:30.647   929  2874 I WifiHAL : Internal cleanup completed
09-30 11:22:30.649  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:30.651  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:30.651  4033  4135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 11:22:30.652  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:30.665   929  3374 D wifi    : set interface wlan0 flags (DOWN)
,09-30 11:22:30.665   929  2874 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 11:22:30.747  4494  4573 D bt_stack_manager: event_shut_down_stack finished.
,09-30 11:22:30.748  4494  4572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 11:22:30.749  4494  4572 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 11:22:30.749  4494  4494 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 11:22:30.750  4494  4494 D BtGatt.GattService: Received stop request...Stopping profile...
,09-30 11:22:30.750  4494  4494 D BtGatt.GattService: stop()
09-30 11:22:30.750  4494  4494 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 11:22:30.752  4494  4494 V BluetoothAdapterState: isTurningOff()=false
09-30 11:22:30.752  4494  4494 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:30.752  4494  4494 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:30.752  4494  4494 V BluetoothAdapterState: isBleTurningOff()=true
09-30 11:22:30.752  4494  4572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 11:22:30.753  4494  4572 D BluetoothAdapterProperties: Setting state to 10
09-30 11:22:30.753  4494  4572 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 11:22:30.753  4494  4572 I BluetoothAdapterState: Entering OffState
,09-30 11:22:30.755   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-30 11:22:30.761  4494  4494 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 11:22:30.761  4494  4494 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 11:22:30.761  4494  4494 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 11:22:30.763  4494  4573 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 11:22:30.773  4494  4494 I art     : System.exit called, status: 0
,09-30 11:22:30.773  4494  4494 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
,09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:,22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.refl,ect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.814  5632  5632 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 11:22:30.814  5632  5632 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 11:22:30.818  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 11:22:30.820   929  3309 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-30 11:22:30.821   929  3309 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-30 11:22:30.822   929  3309 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-30 11:22:30.822   929  3309 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-30 11:22:30.822   929  3309 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-30 11:22:30.840   929  3309 I ActivityManager: Start proc 5664:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-30 11:22:30.841   929  3310 W ActivityManager: Spurious death for ProcessRecord{3e1a563 5664:com.android.bluetooth/1002}, curProc for 4494: null
09-30 11:22:30.842  5611  5611 D DockEventReceiver: finishStartingService: stopping service
09-30 11:22:30.844   929  3723 I ActivityManager: Killing 4891:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 11:22:30.868   929   946 D Tethering: InitialState.processMessage what=4
09-30 11:22:30.877   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-30 11:22:30.894   929  3024 I ActivityManager: Killing 5025:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-30 11:22:30.970  5664  5664 D AdapterServiceConfig: Adding HeadsetService
,09-30 11:22:30.971  5664  5664 D AdapterServiceConfig: Adding A2dpService
09-30 11:22:30.971  5664  5664 D AdapterServiceConfig: Adding HidService
09-30 11:22:30.971  5664  5664 D AdapterServiceConfig: Adding HealthService
09-30 11:22:30.971  5664  5664 D AdapterServiceConfig: Adding PanService
09-30 11:22:30.971  5664  5664 D AdapterServiceConfig: Adding GattService
09-30 11:22:30.971  5664  5664 D AdapterServiceConfig: Adding BluetoothMapService
09-30 11:22:30.972  5664  5664 D AdapterServiceConfig: Adding SapService
,09-30 11:22:30.981   929   939 I ActivityManager: Killing 5360:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-30 11:22:31.008  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 11:22:31.015  3757  3757 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 11:22:31.018  3757  3757 D SystemUpdateService: onCreate
,09-30 11:22:31.021  3757  3757 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 11:22:31.029  3757  3757 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 11:22:31.031  3757  5311 I iu.UploadsManager: num queued entries: 0
,09-30 11:22:31.031  3757  5311 I iu.UploadsManager: num updated entries: 0
09-30 11:22:31.032  3757  5311 I iu.SyncManager: NEXT; no task
,09-30 11:22:31.036  3757  3757 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 11:22:31.038  3757  3757 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 11:22:31.040  3757  5677 I SystemUpdateService: active receiver: enabled
,09-30 11:22:31.050   929   940 I ActivityManager: Start proc 5679:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-30 11:22:31.060  3757  5677 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 11:22:31.066  3757  5677 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 11:22:31.067  3757  5677 I SystemUpdateService: now status is 0 (complete)
09-30 11:22:31.067  3757  5677 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 11:22:31.067  3757  5677 I SystemUpdateService: file has been verified
09-30 11:22:31.067  3757  5677 I SystemUpdateService: OTA package size = 21989297
,09-30 11:22:31.085  5679  5679 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-30 11:22:31.090  5679  5679 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 11:22:31.093  3757  5677 I SystemUpdateService: showing system update notification
,09-30 11:22:31.098  5679  5679 D SprintDMHelper: simOperator: 
,09-30 11:22:31.099  5679  5679 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 11:22:31.110   929   940 I ActivityManager: Start proc 5691:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-30 11:22:31.132  3757  3757 D SystemUpdateService: onDestroy
,09-30 11:22:31.133   929  3309 I ActivityManager: Killing 5166:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 11:22:31.214  4926  5705 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 11:22:31.225   929  5460 I ActivityManager: Start proc 5706:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-30 11:22:31.227   929  3024 I ActivityManager: Killing 4587:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 11:22:31.267  5706  5706 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 11:22:31.277   929  3309 I ActivityManager: Killing 5409:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-30 11:22:31.294  5632  5657 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 11:22:31.311   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67d4a15:true
,09-30 11:22:31.380   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:31.525   507   922 D TetherController: Setting IP forward enable = 0
,09-30 11:22:32.381   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:33.382   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:34.383   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:35.354   929   939 D WifiService: setWifiEnabled: true pid=5535, uid=10077
09-30 11:22:35.355   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 11:22:35.368   507   922 D SoftapController: Softap fwReload - Ok
,09-30 11:22:35.371   507   922 D CommandListener: Setting iface cfg
09-30 11:22:35.371   507   922 D CommandListener: Trying to bring down wlan0
09-30 11:22:35.372   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-30 11:22:35.374   929  2874 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 11:22:35.383   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 11:22:35.943   929  2874 D wifi    : set interface wlan0 flags (UP)
,09-30 11:22:35.946   929  2874 I WifiHAL : Initializing wifi
09-30 11:22:35.946   929  2874 I WifiHAL : Creating socket
09-30 11:22:35.947   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 11:22:35.950   929  2874 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 11:22:35.950   929  2874 D wifi    : Did set static halHandle = 0x7f82827e00
09-30 11:22:35.950   929  2874 D wifi    : halHandle = 0x7f82827e00, mVM = 0x7f9ee0d140, mCls = 0x201806
09-30 11:22:35.951   929  2874 D wifi    : array field set
09-30 11:22:35.951   929  2874 I WifiNative-HAL: interface[0] = wlan0
09-30 11:22:35.952   929  5728 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547650436608
09-30 11:22:35.953   929  5728 D wifi    : waitForHalEvents called, vm = 0x7f9ee0d140, obj = 0x201806, env = 0x7f8360b040
,09-30 11:22:36.024  5729  5729 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 11:22:36.046  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 11:22:36.054   929  2874 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 11:22:36.062  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:36.063  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:36.065  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:36.094  5729  5729 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 11:22:36.095  5729  5729 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 11:22:36.111   929  2874 D WifiConfigStore: Loading config and enabling all networks 
,09-30 11:22:36.111  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:36.112  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 11:22:36.112  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:36.112  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:36.113  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:36.113  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:36.113  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:36.114  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:36.115  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:36.115  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:36.115  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 11:22:36.115  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 11:22:36.122   929  2874 D WifiConfigStore: loaded 0 passpoint configs
,09-30 11:22:36.123   929  2874 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 11:22:36.123   929  2874 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-30 11:22:36.124   929  2874 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 11:22:36.125   929  2874 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 11:22:36.126   929  2874 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 11:22:36.126   929  2874 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 11:22:36.126   929  2874 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 11:22:36.130   929  2874 D WifiNative-HAL: Setting external_sim to 1
,09-30 11:22:36.130  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 11:22:36.130   929  2874 D wifi    : setting dfs flag to true, 0x7f87a76860
09-30 11:22:36.131   929  2874 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 11:22:36.131   929  2874 D wifi    : setting scan oui 0x7f87a76860
09-30 11:22:36.131   929  2874 D WifiHAL : Sending mac address OUI
,09-30 11:22:36.135   929  2874 E native  : do suspend false
,09-30 11:22:36.142   929  2874 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 11:22:36.142   929   929 D RttService: SCAN_AVAILABLE : 3
09-30 11:22:36.142   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 11:22:36.142   929  2980 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 11:22:36.143   507   922 D CommandListener: Setting iface cfg
,09-30 11:22:36.148   929  2870 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-30 11:22:36.148   929  2870 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 11:22:36.158   929  2870 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 11:22:36.163   929  2870 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 11:22:36.163   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=244521 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-30 11:22:39.338  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:22:39.342  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:22:39.348  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:22:39.353  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:22:39.357  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:22:39.438   929  2874 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 11:22:39.439   929  2874 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 11:22:39.440   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 11:22:39.453   929  2874 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 11:22:39.487   929  2874 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 11:22:39.490  5729  5729 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 11:22:39.910  5729  5729 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 11:22:39.947  5729  5729 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 11:22:39.948  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 11:22:39.961   929  2874 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 11:22:39.961   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 11:22:39.961   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 11:22:39.979   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 11:22:39.994   507   922 D CommandListener: Setting iface cfg
,09-30 11:22:40.000   929  2874 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 11:22:40.006   929  5737 D DhcpClient: Receive thread started
,09-30 11:22:40.010   929  2874 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-30 11:22:40.010   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-30 11:22:40.011   929  2876 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 11:22:40.091   929  2874 E native  : do suspend false
,09-30 11:22:40.105   929  5736 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 11:22:40.120   929  5737 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172594, domain null
,09-30 11:22:40.121   929  5736 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172594 seconds
,09-30 11:22:40.123   929  5736 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 11:22:40.144   929  5737 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 11:22:40.145   929  5736 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 11:22:40.148   507   922 D CommandListener: Setting iface cfg
,09-30 11:22:40.153   929  2874 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 11:22:40.159   929  5736 D DhcpClient: Scheduling renewal in 86399s
,09-30 11:22:40.166   929  2874 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-30 11:22:40.167   929  2874 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 11:22:40.168   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 11:22:40.169   929  2876 D ConnectivityService: Adding iface wlan0 to network 101
,09-30 11:22:40.178   929  2874 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 11:22:40.212   929  2876 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 11:22:40.213   929  2876 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-30 11:22:40.218   929  2876 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 11:22:40.221   929  2876 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 11:22:40.223   929  2876 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 11:22:40.231   929  2876 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 11:22:40.236   929  2876 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-30 11:22:40.236   929  2876 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 11:22:40.237   929  2876 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-30 11:22:40.237   929  2874 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 11:22:40.237   929  2876 D ConnectivityService:    accepting network in place of null
09-30 11:22:40.237   929  2874 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 11:22:40.238   929  2876 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -64]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 11:22:40.256   929  5735 D NetlinkSocketObserver: NeighborEvent{elapsedMs=248613, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 11:22:40.260   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 11:22:40.282   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 11:22:40.285   929  2876 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-30 11:22:40.285  3649  3799 W QCNEJ   : |CORE| network available: 101
09-30 11:22:40.285   929  2876 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 11:22:40.287  3649  3799 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-30 11:22:40.288   929  2876 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-30 11:22:40.289   929   946 D Tethering: MasterInitialState.processMessage what=3
09-30 11:22:40.289  3649  3799 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 11:22:40.290  3649  3799 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-30 11:22:40.294  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:40.295  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:22:40.295  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.295  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:22:40.298  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:40.299  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:22:40.299  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.299  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:22:40.300  4951  4975 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 11:22:40.300  4951  4975 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 11:22:40.300  4951  4975 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 11:22:40.301  4951  4975 E SarControlService: no key has been found,reset the power
09-30 11:22:40.301  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 11:22:40.301  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 11:22:40.301  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 11:22:40.301  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:22:40.301  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:22:40.301  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.301  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:22:40.301  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:22:40.302  4976  4976 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-30 11:22:40.303  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-30 11:22:40.303  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 11:22:40.303  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 11:22:40.303  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:22:40.304  4976  4976 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-30 11:22:40.308  3757  3757 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 11:22:40.309  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000ec03000000000000ffffffff]
09-30 11:22:40.309  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 11:22:40.309  4976  4990 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,09-30 11:22:40.312  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000ed03000000000000ffffffff]
,09-30 11:22:40.312  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 11:22:40.312  4976  4990 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-30 11:22:40.313  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:22:40.313  4951  4961 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 11:22:40.313  3757  3757 D SystemUpdateService: onCreate
09-30 11:22:40.314  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:22:40.314  4951  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 11:22:40.317  3757  3757 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 11:22:40.326  3757  3757 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 11:22:40.329   929  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-30 11:22:40.331  3757  5311 I iu.UploadsManager: num queued entries: 0
09-30 11:22:40.332  3757  5311 I iu.UploadsManager: num updated entries: 0
,09-30 11:22:40.334  3757  5747 I SystemUpdateService: active receiver: enabled
,09-30 11:22:40.337  3757  3757 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-30 11:22:40.338  3757  3757 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 11:22:40.340  5679  5679 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 11:22:40.343  5679  5679 D SprintDMHelper: simOperator: 
09-30 11:22:40.343  5679  5679 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 11:22:40.364   929  3309 D WifiService: setWifiEnabled: false pid=5535, uid=10077
09-30 11:22:40.364   929  3309 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 11:22:40.365   929  2874 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 11:22:40.365  3757  5747 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-30 11:22:40.365   929  2874 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 11:22:40.366   929  2874 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 11:22:40.366   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 11:22:40.366  3757  5311 I iu.SyncManager: NEXT; no task
,09-30 11:22:40.374   929  5736 D DhcpClient: Clearing IP address
,09-30 11:22:40.374   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-30 11:22:40.376   507   922 D CommandListener: Setting iface cfg
,09-30 11:22:40.380  3757  5747 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 11:22:40.380  3757  5747 I SystemUpdateService: now status is 0 (complete)
09-30 11:22:40.380  3757  5747 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 11:22:40.380  3757  5747 I SystemUpdateService: file has been verified
09-30 11:22:40.380  3757  5747 I SystemUpdateService: OTA package size = 21989297
,09-30 11:22:40.383   929  5734 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-30 11:22:40.383   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-30 11:22:40.386   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-30 11:22:40.386   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-30 11:22:40.390   537   537 E Parcel  : Reading a NULL string not supported here.
,09-30 11:22:40.393   929   929 D RttService: SCAN_AVAILABLE : 1
09-30 11:22:40.393  3757  5747 I SystemUpdateService: showing system update notification
,09-30 11:22:40.394   929  2876 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-30 11:22:40.394   929  2980 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 11:22:40.397  3649  3799 W QCNEJ   : |CORE| network lost: 101
09-30 11:22:40.397  3649  3799 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-30 11:22:40.399   929  5737 D DhcpClient: Receive thread stopped
,09-30 11:22:40.405  3757  3757 D SystemUpdateService: onDestroy
,09-30 11:22:40.409   929  2874 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 11:22:40.415   929  2874 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 11:22:40.416   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 11:22:40.436   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 11:22:40.437   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-30 11:22:40.437   929  2876 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 11:22:40.437   929  2876 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 11:22:40.438   929   946 D Tethering: MasterInitialState.processMessage what=3
09-30 11:22:40.440   929  2874 D DhcpClient: doQuit
09-30 11:22:40.440   929  2874 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 11:22:40.440   929  5736 D DhcpClient: onQuitting
09-30 11:22:40.441  5729  5729 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-30 11:22:40.441  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:40.441  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 11:22:40.441  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 11:22:40.441  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:40.444  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:40.444  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:40.444  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.444  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:40.445  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:40.445  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:40.445  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.445  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 11:22:40.446  4951  4975 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-30 11:22:40.447  4951  4975 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 11:22:40.447  4951  4975 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 11:22:40.447  4951  4975 E SarControlService: no key has been found,reset the power
09-30 11:22:40.447  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-30 11:22:40.447  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 11:22:40.447  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:40.447  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:40.447  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:40.448  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:40.448  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 11:22:40.448  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:40.449  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:40.451  3757  3757 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 11:22:40.450  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:22:40.451  4976  4976 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 11:22:40.452  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 11:22:40.453  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 11:22:40.453  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 11:22:40.453  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:22:40.453  4976  4976 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 11:22:40.456  3757  3757 D SystemUpdateService: onCreate
09-30 11:22:40.457  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000ee03000000000000ffffffff]
09-30 11:22:40.457  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 11:22:40.457  4976  4990 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-30 11:22:40.457  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:22:40.458  4951  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 11:22:40.460  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000ef03000000000000ffffffff]
09-30 11:22:40.460  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 11:22:40.460  4976  4990 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-30 11:22:40.460  5729  5729 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 11:22:40.460  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:22:40.461  4951  4961 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 11:22:40.461  3757  3757 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 11:22:40.464  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-30 11:22:40.468  3757  5764 I SystemUpdateService: active receiver: enabled
,09-30 11:22:40.470  3757  3757 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 11:22:40.475  3757  5311 I iu.UploadsManager: num queued entries: 0
,09-30 11:22:40.475  3757  5311 I iu.UploadsManager: num updated entries: 0
,09-30 11:22:40.477  3757  3757 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 11:22:40.479  3757  3757 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 11:22:40.480  5679  5679 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 11:22:40.484  5679  5679 D SprintDMHelper: simOperator: 
09-30 11:22:40.484  5679  5679 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 11:22:40.491  3757  5764 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 11:22:40.494  3757  5311 I iu.SyncManager: NEXT; no task
,09-30 11:22:40.495  3757  5764 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-30 11:22:40.495  3757  5764 I SystemUpdateService: now status is 0 (complete)
09-30 11:22:40.496  3757  5764 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 11:22:40.496  3757  5764 I SystemUpdateService: file has been verified
,09-30 11:22:40.496   507   922 E Netd    : netlink response contains error (No such file or directory)
09-30 11:22:40.496  3757  5764 I SystemUpdateService: OTA package size = 21989297
09-30 11:22:40.497   929  2876 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 11:22:40.497   929  2876 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 11:22:40.506  5729  5729 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 11:22:40.507  3757  5764 I SystemUpdateService: showing system update notification
,09-30 11:22:40.517  5729  5729 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 11:22:40.521  3757  3757 D SystemUpdateService: onDestroy
,09-30 11:22:40.619   929  2874 D wifi    : In wifi stop Hal
,09-30 11:22:40.619   929  2874 D wifi    : halHandle = 0x7f82827e00, mVM = 0x7f9ee0d140, mCls = 0x201806
09-30 11:22:40.619   929  5728 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 11:22:40.619   929  5728 D WifiHAL : Got a signal to exit!!!
09-30 11:22:40.619   929  5728 I WifiHAL : Exit wifi_event_loop
09-30 11:22:40.620   929  2874 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
,09-30 11:22:40.620   929  2874 E WifiHAL : Event processing terminated
09-30 11:22:40.620  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 11:22:40.620   929  2874 D wifi    : In wifi cleaned up handler
,09-30 11:22:40.621   929  2874 I WifiHAL : Internal cleanup completed
09-30 11:22:40.621  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:40.623  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:40.624  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:40.624  4033  4135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 11:22:40.643   929  5728 D wifi    : set interface wlan0 flags (DOWN)
,09-30 11:22:40.643   929  2874 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 11:22:40.848   929   946 D Tethering: InitialState.processMessage what=4
,09-30 11:22:40.856   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 11:22:41.287   929  2876 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 11:22:45.374  4926  5752 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-30 11:22:45.375  4926  5752 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 11:22:45.378  4926  5752 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 11:22:45.385   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:45.399   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1eaa42:true
,09-30 11:22:45.400  5664  5664 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 11:22:45.405  5664  5664 I bt_bluedroid: init
,09-30 11:22:45.405  5664  5769 I BluetoothAdapterState: Entering OffState
,09-30 11:22:45.408  5664  5770 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 11:22:45.409  5664  5770 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 11:22:45.409  5664  5770 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 11:22:45.409  5664  5770 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 11:22:45.410  5664  5664 I bt_bluedroid: get_profile_interface socket
,09-30 11:22:45.413  5664  5773 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 11:22:45.414  5664  5664 I bt_bluedroid: get_profile_interface sdp
09-30 11:22:45.415  5664  5773 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 11:22:45.421  5664  5675 I bt_bluedroid: config_hci_snoop_log
,09-30 11:22:45.423   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-30 11:22:45.430  5664  5769 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 11:22:45.430  5664  5769 D BluetoothAdapterProperties: Setting state to 14
09-30 11:22:45.431  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 11:22:45.433  5664  5769 D BluetoothBondStateMachine: make
,09-30 11:22:45.436  5664  5774 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 11:22:45.440  5664  5769 I BluetoothAdapterState: Entering PendingCommandState
,09-30 11:22:45.442  5664  5664 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 11:22:45.446  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:22:45.447  5664  5664 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 11:22:45.448  5664  5664 D BtGatt.GattService: Received start request. Starting profile...
09-30 11:22:45.448  5664  5664 D BtGatt.GattService: start()
09-30 11:22:45.448  5664  5664 I bt_bluedroid: get_profile_interface gatt
,09-30 11:22:45.450  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:22:45.450  5664  5664 D BtGatt.AdvertiseManager: advertise manager created
,09-30 11:22:45.458  5664  5664 V BluetoothAdapterState: isTurningOff()=false
,09-30 11:22:45.458  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:45.458  5664  5664 V BluetoothAdapterState: isBleTurningOn()=true
09-30 11:22:45.458  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:45.459  5664  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 11:22:45.461  5664  5769 I bt_bluedroid: bt_bluedroid
09-30 11:22:45.461  5664  5770 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 11:22:45.462  5664  5770 I bt_hci  : start_up
,09-30 11:22:45.470  5664  5770 I bt_vendor: alloc value 0xf3bf8871
,09-30 11:22:45.470  5664  5770 I bt_vendor: init
09-30 11:22:45.471  5664  5770 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 11:22:45.471  5664  5770 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 11:22:45.583  5664  5770 D bt_hci  : start_up starting async portion
,09-30 11:22:45.583  5664  5777 I bt_hci  : event_finish_startup
,09-30 11:22:45.583  5664  5777 I bt_hci_h4: hal_open
09-30 11:22:45.583  5664  5777 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-30 11:22:45.580  5778  5778 W irq/448-msm_hs_: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-30 11:22:45.590  5664  5777 I bt_userial_vendor: device fd = 54 open
,09-30 11:22:45.606  5664  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 11:22:45.608  5664  5777 D bt_hwcfg: Chipset BCM4358A3
,09-30 11:22:45.608  5664  5777 D bt_hwcfg: Target name = [BCM4358A3]
09-30 11:22:45.608  5664  5777 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 11:22:45.997  5664  5777 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 11:22:45.998  5664  5777 D bt_hwcfg: Settlement delay -- 100 ms
09-30 11:22:45.998  5664  5777 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 11:22:46.134  5664  5777 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 11:22:46.134  5664  5777 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 11:22:46.136  5664  5777 I bt_hwcfg: vendor lib fwcfg completed
09-30 11:22:46.137  5664  5777 I bt_vendor: firmware callback
09-30 11:22:46.137  5664  5777 I bt_hci  : firmware_config_callback
,09-30 11:22:46.145  5664  5780 I bt_btu  : btu_task pending for preload complete event
,09-30 11:22:46.145  5664  5780 I bt_btu_task: Bluetooth chip preload is complete
09-30 11:22:46.146  5664  5780 I bt_btu  : btu_task received preload complete event
,09-30 11:22:46.153  5664  5780 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 11:22:46.153  5664  5780 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 11:22:46.153  5664  5780 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 11:22:46.153  5664  5780 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-30 11:22:46.153  5664  5780 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_A2D
,09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_PAN
,09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_GATT
,09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 11:22:46.154  5664  5780 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 11:22:46.155  5664  5780 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 11:22:46.239  5664  5780 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b76549
09-30 11:22:46.239  5664  5780 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b76549 
,09-30 11:22:46.258  5664  5773 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 11:22:46.259  5664  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 11:22:46.260  5664  5773 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 11:22:46.262  5664  5773 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 11:22:46.265  5664  5773 D BluetoothAdapterProperties: Scan Mode:20
,09-30 11:22:46.265  5664  5773 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 11:22:46.265  5664  5773 D bt_hci  : do_postload posting postload work item
09-30 11:22:46.266  5664  5777 I bt_hci  : event_postload
09-30 11:22:46.266  5664  5777 I bt_vendor: sco_config_cb
,09-30 11:22:46.266  5664  5777 I bt_hci  : sco_config_callback postload finished.
,09-30 11:22:46.271  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:46.273  5664  5773 D bt_bte_conf: Device ID record 1 : primary
09-30 11:22:46.273  5664  5773 D bt_bte_conf:   vendorId            = 000f
09-30 11:22:46.273  5664  5773 D bt_bte_conf:   vendorIdSource      = 0001
09-30 11:22:46.274  5664  5773 D bt_bte_conf:   product             = 1200
09-30 11:22:46.274  5664  5773 D bt_bte_conf:   version             = 1436
09-30 11:22:46.274  5664  5773 D bt_bte_conf:   clientExecutableURL = 
09-30 11:22:46.274  5664  5773 D bt_bte_conf:   serviceDescription  = 
09-30 11:22:46.274  5664  5773 D bt_bte_conf:   documentationURL    = 
09-30 11:22:46.274  5664  5773 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 11:22:46.274  5664  5770 D bt_stack_manager: event_start_up_stack finished
,09-30 11:22:46.275  5664  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 11:22:46.275  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:46.277  5664  5769 D BluetoothAdapterProperties: Setting state to 15
,09-30 11:22:46.277  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 11:22:46.278  5664  5769 I BluetoothAdapterState: Entering BleOnState
09-30 11:22:46.279  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:46.281  5664  5769 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 11:22:46.281  5664  5769 D BluetoothAdapterProperties: Setting state to 11
09-30 11:22:46.282  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-30 11:22:46.282  5664  5777 I bt_vendor: low_power_mode_cb
,09-30 11:22:46.287  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:22:46.289  5664  5664 D HeadsetService: Received start request. Starting profile...
09-30 11:22:46.291  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:46.293  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:46.293  5664  5664 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 11:22:46.294  5664  5664 D HeadsetStateMachine: make
09-30 11:22:46.295  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:46.303  5664  5664 D HeadsetStateMachine: max_hf_connections = 1
09-30 11:22:46.304  5664  5664 I bt_bluedroid: get_profile_interface handsfree
,09-30 11:22:46.304  5664  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 11:22:46.304  5664  5773 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-30 11:22:46.308  5664  5769 I BluetoothAdapterState: Entering PendingCommandState
,09-30 11:22:46.309  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:22:46.310  5664  5664 D A2dpService: Received start request. Starting profile...
,09-30 11:22:46.311  5664  5664 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 11:22:46.311  5664  5664 I bt_bluedroid: get_profile_interface avrcp
,09-30 11:22:46.316  5664  5664 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 11:22:46.316  5664  5664 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 11:22:46.317  5664  5664 D A2dpStateMachine: make
09-30 11:22:46.318  5664  5664 I bt_bluedroid: get_profile_interface a2dp
,09-30 11:22:46.318  5664  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 11:22:46.320  5664  5788 D A2dpStateMachine: Enter Disconnected: -2
,09-30 11:22:46.321  5664  5664 I BluetoothHidServiceJni: classInitNative: succeeds
,09-30 11:22:46.322  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:22:46.322  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 11:22:46.323  5611  5611 D BluetoothInputDevice: Proxy object connected
09-30 11:22:46.323  5664  5664 D HidService: Received start request. Starting profile...
09-30 11:22:46.323  5664  5664 I bt_bluedroid: get_profile_interface hidhost
09-30 11:22:46.324  5664  5664 D HidService: setHidService(): set to: null
09-30 11:22:46.324  5611  5611 D HidProfile: Bluetooth service connected
09-30 11:22:46.324  5664  5773 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b5756d
09-30 11:22:46.324  5664  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-30 11:22:46.325  5664  5664 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-30 11:22:46.326  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:22:46.327  5664  5664 D HealthService: Received start request. Starting profile...
,09-30 11:22:46.328  5664  5664 I bt_bluedroid: get_profile_interface health
,09-30 11:22:46.329  5664  5664 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 11:22:46.330  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:22:46.331  5611  5611 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 11:22:46.331  5664  5664 D PanService: Received start request. Starting profile...
09-30 11:22:46.332  5664  5664 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 11:22:46.332  5664  5664 I bt_bluedroid: get_profile_interface pan
09-30 11:22:46.332  5611  5611 D PanProfile: Bluetooth service connected
09-30 11:22:46.332  5664  5773 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 11:22:46.334  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:22:46.335  5611  5611 D BluetoothMap: Proxy object connected
,09-30 11:22:46.335  5664  5664 D BluetoothMapService: Received start request. Starting profile...
09-30 11:22:46.335  5664  5664 D BluetoothMapService: start()
09-30 11:22:46.336  5611  5611 D MapProfile: Bluetooth service connected
09-30 11:22:46.336  5611  5611 D BluetoothMap: getConnectedDevices()
09-30 11:22:46.337  5611  5611 D BluetoothMap: Bluetooth is Not enabled
,09-30 11:22:46.338  5664  5664 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-30 11:22:46.339  5664  5664 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-30 11:22:46.339  5664  5664 D BluetoothMapAppObserver: createReceiver()
09-30 11:22:46.340  5664  5664 D BluetoothMapAppObserver: initObservers()
09-30 11:22:46.341  5664  5664 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 11:22:46.346  5664  5664 V SapService: SapBinder()
09-30 11:22:46.346  5664  5664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:22:46.346  5664  5664 D SapService: Received start request. Starting profile...
09-30 11:22:46.347  5664  5664 V SapService: start()
,09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isTurningOff()=false
,09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:46.348  5664  5786 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isTurningOff()=false
,09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:46.348  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:46.349  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:46.350  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-30 11:22:46.350  5664  5664 V BluetoothAdapterState: isTurningOn()=true
09-30 11:22:46.350  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:46.350  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:46.350  5664  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-30 11:22:46.350  5664  5769 D BluetoothAdapterProperties: ScanMode =  20
09-30 11:22:46.350  5664  5769 D BluetoothAdapterProperties: State =  11
09-30 11:22:46.351  5664  5769 D BluetoothAdapterProperties: Setting state to 12
09-30 11:22:46.351  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 11:22:46.351   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:22:46.351  5664  5769 I BluetoothAdapterState: Entering OnState
09-30 11:22:46.351  3027  3039 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 11:22:46.354  5664  5773 D BluetoothAdapterProperties: Scan Mode:21
,09-30 11:22:46.354  5664  5773 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 11:22:46.354  5535  5535 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 11:22:46.355  3027  3049 D BluetoothPan: onBluetoothStateChange on: true
,09-30 11:22:46.356  3027  3027 D BluetoothA2dp: Proxy object connected
09-30 11:22:46.357   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 11:22:46.357  5611  5625 D BluetoothPbap: onBluetoothStateChange: up=true
,09-30 11:22:46.359  5611  5623 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 11:22:46.359  3027  3027 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 11:22:46.359  3027  3027 D PanProfile: Bluetooth service connected
09-30 11:22:46.359  3690  3720 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:46.360  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:46.360  5611  5625 D BluetoothPan: onBluetoothStateChange on: true
09-30 11:22:46.360  3027  3039 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 11:22:46.360  3027  3049 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 11:22:46.361  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:46.362   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 11:22:46.362   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:22:46.362   929   929 D BluetoothA2dp: Proxy object connected
09-30 11:22:46.362  3027  3234 D BluetoothMap: onBluetoothStateChange: up=true
09-30 11:22:46.364  3027  3027 D BluetoothMap: Proxy object connected
09-30 11:22:46.364  3027  3049 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 11:22:46.364  3027  3027 D MapProfile: Bluetooth service connected
09-30 11:22:46.364  3027  3027 D BluetoothMap: getConnectedDevices()
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:46.364  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:46.365  5664  5664 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 11:22:46.366  5611  5623 D BluetoothMap: onBluetoothStateChange: up=true
09-30 11:22:46.366  5664  5664 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 11:22:46.366  3027  3027 D BluetoothInputDevice: Proxy object connected
09-30 11:22:46.366  3027  3027 D HidProfile: Bluetooth service connected
09-30 11:22:46.367  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:46.367   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-30 11:22:46.370  5611  5611 D LocalBluetoothProfileManager: Adding local A2DP profile
09-30 11:22:46.370  5664  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:46.372  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 11:22:46.373  5664  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 11:22:46.374  5611  5611 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-30 11:22:46.375  5664  5664 D ObexServerSockets: Succeed to create listening sockets 
09-30 11:22:46.375  5664  5664 D ObexServerSockets0: startAccept()
09-30 11:22:46.375  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 11:22:46.375  5664  5664 D ObexServerSockets0: prepareForNewConnect()
,09-30 11:22:46.375  5535  5535 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-30 11:22:46.377  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:46.378  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:46.379  5664  5664 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 11:22:46.379  5664  5664 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 11:22:46.379  5664  5796 D ObexServerSockets0: Accepting socket connection...
09-30 11:22:46.379  5664  5664 D BluetoothMapService: onReceive
09-30 11:22:46.379  5664  5664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 11:22:46.379  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:46.380  5664  5664 D BluetoothMapService: STATE_ON
09-30 11:22:46.380  5664  5797 D ObexServerSockets0: Accepting socket connection...
,09-30 11:22:46.382  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 11:22:46.385  5664  5798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 11:22:46.385  5611  5611 D BluetoothA2dp: Proxy object connected
09-30 11:22:46.385   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:46.389  5664  5798 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-30 11:22:46.389  5664  5798 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 11:22:46.390  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 11:22:46.393  5611  5611 D DockEventReceiver: finishStartingService: stopping service
,09-30 11:22:46.398  3027  3027 D BluetoothPbap: Proxy object connected
,09-30 11:22:46.398  3027  3027 D PbapServerProfile: Bluetooth service connected
09-30 11:22:46.398  5611  5611 D BluetoothPbap: Proxy object connected
09-30 11:22:46.399  5611  5611 D PbapServerProfile: Bluetooth service connected
,09-30 11:22:46.403  5664  5664 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 11:22:46.403  5664  5664 D ObexServerSockets0: prepareForNewConnect()
09-30 11:22:46.404  5664  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:22:46.417  5664  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:22:46.418  5664  5806 I BtOppRfcommListener: Accept thread started.
,09-30 11:22:46.454   929   929 D BluetoothHeadset: Proxy object connected
,09-30 11:22:46.454  3690  4054 D BluetoothHeadset: Proxy object connected
09-30 11:22:46.454  3027  3049 D BluetoothHeadset: Proxy object connected
09-30 11:22:46.455  3027  3027 D HeadsetProfile: Bluetooth service connected
09-30 11:22:46.455   929   929 D BluetoothHeadset: Proxy object connected
09-30 11:22:46.455   929   929 D BluetoothHeadset: Proxy object connected
,09-30 11:22:46.458   929   946 D BluetoothHeadset: Proxy object connected
,09-30 11:22:46.460  3690  3903 D BluetoothHeadset: Proxy object connected
,09-30 11:22:46.461  3027  3234 D BluetoothHeadset: Proxy object connected
09-30 11:22:46.461  3027  3027 D HeadsetProfile: Bluetooth service connected
,09-30 11:22:46.461   929   946 D BluetoothHeadset: Proxy object connected
,09-30 11:22:46.477  5611  5625 D BluetoothHeadset: Proxy object connected
,09-30 11:22:46.478  5611  5611 D HeadsetProfile: Bluetooth service connected
,09-30 11:22:47.386   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:48.244   929  2876 D ConnectivityService: handlePromptUnvalidated 101
,09-30 11:22:48.387   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:49.388   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:22:50.381  5664  5769 D BluetoothAdapterState: Current state: ON, message: 23
09-30 11:22:50.381  5664  5769 D BluetoothAdapterProperties: Setting state to 13
,09-30 11:22:50.381  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-30 11:22:50.382  5664  5769 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 11:22:50.385  5664  5769 I BluetoothAdapterState: Entering PendingCommandState
,09-30 11:22:50.388  5664  5664 D BluetoothMapService: onReceive
,09-30 11:22:50.389  5664  5664 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 11:22:50.389  5664  5664 D BluetoothMapService: STATE_TURNING_OFF
09-30 11:22:50.389   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
09-30 11:22:50.390  5664  5664 D BluetoothMapService: MAP Service closeService in
09-30 11:22:50.390  5664  5664 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 11:22:50.390  5664  5664 D ObexServerSockets0: shutdown(block = true)
09-30 11:22:50.391  5664  5664 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 11:22:50.392  5664  5796 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 11:22:50.392  5664  5797 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 11:22:50.396  5664  5773 D BluetoothAdapterProperties: Scan Mode:20
,09-30 11:22:50.397  5664  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 11:22:50.401  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:50.401  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:50.401  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 11:22:50.401  5664  5664 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 11:22:50.402  5664  5782 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 11:22:50.402  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:50.402  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:50.402  5664  5664 I BtOppRfcommListener: stopping Accept Thread
,09-30 11:22:50.403  5664  5806 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-30 11:22:50.403  5664  5806 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-30 11:22:50.406  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:50.406  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 11:22:50.406  5664  5664 D HeadsetService: Received stop request...Stopping profile...
09-30 11:22:50.407  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:50.407  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:50.410  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:22:50.411  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:22:50.411   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:50.411  3690  3720 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:50.411  5611  5625 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:50.412  5664  5664 D A2dpService: Received stop request...Stopping profile...
09-30 11:22:50.412  5535  5535 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 11:22:50.412  3027  3039 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:50.412  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:22:50.412  5664  5788 D A2dpStateMachine: Exit Disconnected: -1
09-30 11:22:50.412   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:50.412   929   929 D BluetoothHeadset: Proxy object disconnected
09-30 11:22:50.414  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.415   929   929 D BluetoothA2dp: Proxy object disconnected
,09-30 11:22:50.415  3027  3027 D HeadsetProfile: Bluetooth service disconnected
09-30 11:22:50.416  3027  3027 D BluetoothA2dp: Proxy object disconnected
09-30 11:22:50.416  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.418  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.418  5611  5611 D DockEventReceiver: finishStartingService: stopping service
09-30 11:22:50.419  5664  5664 D HidService: Received stop request...Stopping profile...
09-30 11:22:50.419  5664  5664 D HidService: Stopping Bluetooth HidService
09-30 11:22:50.419  5611  5611 D HeadsetProfile: Bluetooth service disconnected
09-30 11:22:50.420  5611  5611 D BluetoothA2dp: Proxy object disconnected
09-30 11:22:50.420  3027  3027 D BluetoothInputDevice: Proxy object disconnected
09-30 11:22:50.420  3027  3027 D HidProfile: Bluetooth service disconnected
09-30 11:22:50.421  5611  5611 D BluetoothInputDevice: Proxy object disconnected
,09-30 11:22:50.421  5611  5611 D HidProfile: Bluetooth service disconnected
09-30 11:22:50.423  5664  5664 D HealthService: Received stop request...Stopping profile...
09-30 11:22:50.425  5664  5664 D PanService: Received stop request...Stopping profile...
09-30 11:22:50.425  3027  3027 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 11:22:50.425  3027  3027 D PanProfile: Bluetooth service disconnected
09-30 11:22:50.425  5611  5611 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 11:22:50.425  5611  5611 D PanProfile: Bluetooth service disconnected
09-30 11:22:50.426  5664  5664 D BluetoothMapService: Received stop request...Stopping profile...
09-30 11:22:50.426  5664  5664 D BluetoothMapService: stop()
09-30 11:22:50.426  5664  5664 D BluetoothMapAppObserver: deinitObservers()
09-30 11:22:50.427  5664  5664 D BluetoothMapAppObserver: removeReceiver()
,09-30 11:22:50.428  3027  3027 D BluetoothMap: Proxy object disconnected
09-30 11:22:50.428  3027  3027 D MapProfile: Bluetooth service disconnected
,09-30 11:22:50.428  5664  5664 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:50.428  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:50.428  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:50.428  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:50.428  5611  5611 D BluetoothMap: Proxy object disconnected
09-30 11:22:50.428  5611  5611 D MapProfile: Bluetooth service disconnected
,09-30 11:22:50.429  5664  5664 D SapService: Received stop request...Stopping profile...
,09-30 11:22:50.429  5664  5664 V SapService: stop()
09-30 11:22:50.431  5664  5664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 11:22:50.431  5664  5664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 11:22:50.431  5664  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:50.431  5664  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:50.431  5664  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:50.431  5664  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 11:22:50.432  5664  5773 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 11:22:50.432  5664  5664 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:50.432  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:50.432  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 11:22:50.432  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:50.433  5664  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:50.433  5664  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 11:22:50.433  5664  5664 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:50.433  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:50.433  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:50.433  5664  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 11:22:50.433  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:50.433  5664  5780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 11:22:50.433  5664  5780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 11:22:50.433  5664  5780 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 11:22:50.433  5664  5780 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 11:22:50.433  5664  5664 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-30 11:22:50.434  5664  5664 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 11:22:50.434  5664  5773 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 11:22:50.437  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 11:22:50.434  5664  5664 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:50.442  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:50.442  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:50.442  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:50.442  5664  5664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 11:22:50.442  5664  5773 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 11:22:50.442  5664  5664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 11:22:50.443  5664  5664 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:50.443  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:50.443  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:50.443  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:50.443  5664  5664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 11:22:50.443  5664  5664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 11:22:50.444  5664  5664 D BluetoothMapService: MAP Service closeService in
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:50.444  5664  5664 D BluetoothMapService: cleanup()
09-30 11:22:50.444  5664  5664 D BluetoothMapService: MAP Service closeService in
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isTurningOff()=true
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isTurningOn()=false
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:50.444  5664  5664 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:22:50.444  5664  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 11:22:50.445  5664  5769 D BluetoothAdapterProperties: Setting state to 15
09-30 11:22:50.445  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 11:22:50.445  5664  5769 I BluetoothAdapterState: Entering BleOnState
09-30 11:22:50.446  3027  3027 D BluetoothPbap: Proxy object disconnected
09-30 11:22:50.446  3027  3027 D PbapServerProfile: Bluetooth service disconnected
09-30 11:22:50.447   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:50.448  3027  3039 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-30 11:22:50.449  3027  3049 D BluetoothPan: onBluetoothStateChange on: false
09-30 11:22:50.450   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 11:22:50.451  5611  5625 D BluetoothPbap: onBluetoothStateChange: up=false
,09-30 11:22:50.451  5611  5623 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 11:22:50.452  3690  4054 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:50.452  5611  5625 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 11:22:50.453  5611  5623 D BluetoothPan: onBluetoothStateChange on: false
09-30 11:22:50.454  3027  3234 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:50.454  3027  3039 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 11:22:50.455   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 11:22:50.455  5611  5625 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:50.455   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 11:22:50.455  3027  3049 D BluetoothMap: onBluetoothStateChange: up=false
09-30 11:22:50.455  3027  3234 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 11:22:50.456  5611  5623 D BluetoothMap: onBluetoothStateChange: up=false
09-30 11:22:50.457  5664  5769 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 11:22:50.457  5664  5769 D BluetoothAdapterProperties: Setting state to 16
09-30 11:22:50.457  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 11:22:50.457  5664  5769 D BluetoothAdapterProperties: onBleDisable
09-30 11:22:50.457  5664  5769 I BluetoothAdapterState: Entering PendingCommandState
09-30 11:22:50.458  5664  5770 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 11:22:50.459  5664  5773 D BluetoothAdapterProperties: Scan Mode:20
09-30 11:22:50.459  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.460  5664  5780 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 11:22:50.460  5664  5780 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 11:22:50.461  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.461  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 11:22:50.462  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.463  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.464  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:22:50.466  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 11:22:50.466  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:22:50.469  5611  5611 D DockEventReceiver: finishStartingService: stopping service
,09-30 11:22:50.672  5664  5773 I bt_hci  : shut_down
,09-30 11:22:50.685  5664  5777 I bt_vendor: low_power_mode_cb
,09-30 11:22:50.688  5664  5777 D bt_hwcfg: hw_epilog_process
,09-30 11:22:50.691  5664  5777 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 11:22:50.691  5664  5777 I bt_vendor: epilog_cb
09-30 11:22:50.691  5664  5777 I bt_hci  : epilog_finished_callback
,09-30 11:22:50.695  5664  5773 I bt_hci_h4: hal_close
,09-30 11:22:50.696  5664  5773 I bt_userial_vendor: device fd = 54 close
,09-30 11:22:50.812  5664  5770 D bt_stack_manager: event_shut_down_stack finished.
,09-30 11:22:50.812  5664  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 11:22:50.816  5664  5664 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 11:22:50.816  5664  5769 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-30 11:22:50.817  5664  5664 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 11:22:50.817  5664  5664 D BtGatt.GattService: stop()
,09-30 11:22:50.818  5664  5664 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 11:22:50.821  5664  5664 V BluetoothAdapterState: isTurningOff()=false
09-30 11:22:50.821  5664  5664 V BluetoothAdapterState: isTurningOn()=false
,09-30 11:22:50.821  5664  5664 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:22:50.821  5664  5664 V BluetoothAdapterState: isBleTurningOff()=true
09-30 11:22:50.822  5664  5769 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 11:22:50.823  5664  5769 D BluetoothAdapterProperties: Setting state to 10
,09-30 11:22:50.823  5664  5769 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 11:22:50.824  5664  5769 I BluetoothAdapterState: Entering OffState
,09-30 11:22:50.825   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 11:22:50.840  5664  5664 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 11:22:50.840  5664  5664 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 11:22:50.841  5664  5664 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 11:22:50.841  5664  5770 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 11:22:50.850  5664  5664 I art     : System.exit called, status: 0
,09-30 11:22:50.850  5664  5664 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 11:22:50.877   929   939 I ActivityManager: Process com.android.bluetooth (pid 5664) has died
,09-30 11:22:55.379  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:55.379  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:55.384  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:22:55.384  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e833951 removed from the list
,09-30 11:22:55.384  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:55.384  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:55.385  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:22:55.388  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 11:22:55.389  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f6b52b7 added. We now have 4 listener(s)
09-30 11:22:55.389  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:22:55.390  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:22:55.391  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f6b52b7 removed from the list
,09-30 11:22:55.391  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:22:55.391  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 11:22:55.391  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:22:55.394  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:22:55.394  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4702a24 added. We now have 4 listener(s)
09-30 11:22:55.394  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:23:00.404  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:00.438   929   946 I ActivityManager: Start proc 5814:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 11:23:00.517  5814  5814 D AdapterServiceConfig: Adding HeadsetService
,09-30 11:23:00.517  5814  5814 D AdapterServiceConfig: Adding A2dpService
09-30 11:23:00.517  5814  5814 D AdapterServiceConfig: Adding HidService
09-30 11:23:00.518  5814  5814 D AdapterServiceConfig: Adding HealthService
09-30 11:23:00.518  5814  5814 D AdapterServiceConfig: Adding PanService
,09-30 11:23:00.518  5814  5814 D AdapterServiceConfig: Adding GattService
09-30 11:23:00.518  5814  5814 D AdapterServiceConfig: Adding BluetoothMapService
09-30 11:23:00.518  5814  5814 D AdapterServiceConfig: Adding SapService
,09-30 11:23:00.529   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3296902:true
,09-30 11:23:00.530  5814  5814 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 11:23:00.533  5814  5814 I bt_bluedroid: init
,09-30 11:23:00.533  5814  5826 I BluetoothAdapterState: Entering OffState
,09-30 11:23:00.535  5814  5827 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 11:23:00.535  5814  5827 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 11:23:00.535  5814  5827 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 11:23:00.535  5814  5827 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-30 11:23:00.536  5814  5814 I bt_bluedroid: get_profile_interface socket
,09-30 11:23:00.538  5814  5830 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 11:23:00.538  5814  5814 I bt_bluedroid: get_profile_interface sdp
09-30 11:23:00.540  5814  5830 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 11:23:00.549  5814  5825 I bt_bluedroid: config_hci_snoop_log
09-30 11:23:00.550   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-30 11:23:00.555  5814  5826 D BluetoothAdapterState: Current state: OFF, message: 0
09-30 11:23:00.555  5814  5826 D BluetoothAdapterProperties: Setting state to 14
09-30 11:23:00.556  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 11:23:00.557  5814  5826 D BluetoothBondStateMachine: make
09-30 11:23:00.559  5814  5831 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 11:23:00.562  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
,09-30 11:23:00.563  5814  5814 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-30 11:23:00.566  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:00.566  5814  5814 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 11:23:00.567  5814  5814 D BtGatt.GattService: Received start request. Starting profile...
,09-30 11:23:00.568  5814  5814 D BtGatt.GattService: start()
09-30 11:23:00.568  5814  5814 I bt_bluedroid: get_profile_interface gatt
09-30 11:23:00.569  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:00.569  5814  5814 D BtGatt.AdvertiseManager: advertise manager created
,09-30 11:23:00.576  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,09-30 11:23:00.576  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-30 11:23:00.577  5814  5814 V BluetoothAdapterState: isBleTurningOn()=true
09-30 11:23:00.577  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 11:23:00.577  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 11:23:00.579  5814  5826 I bt_bluedroid: bt_bluedroid
,09-30 11:23:00.579  5814  5827 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 11:23:00.580  5814  5827 I bt_hci  : start_up
,09-30 11:23:00.585  5814  5827 I bt_vendor: alloc value 0xf3c4f871
09-30 11:23:00.585  5814  5827 I bt_vendor: init
,09-30 11:23:00.585  5814  5827 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 11:23:00.585  5814  5827 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 11:23:00.693  5814  5827 D bt_hci  : start_up starting async portion
09-30 11:23:00.694  5814  5834 I bt_hci  : event_finish_startup
09-30 11:23:00.694  5814  5834 I bt_hci_h4: hal_open
09-30 11:23:00.694  5814  5834 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 11:23:00.690  5835  5835 W irq/448-msm_hs_: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-30 11:23:00.698  5814  5834 I bt_userial_vendor: device fd = 54 open
,09-30 11:23:00.716  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 11:23:00.719  5814  5834 D bt_hwcfg: Chipset BCM4358A3
09-30 11:23:00.720  5814  5834 D bt_hwcfg: Target name = [BCM4358A3]
,09-30 11:23:00.720  5814  5834 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 11:23:01.171  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 11:23:01.172  5814  5834 D bt_hwcfg: Settlement delay -- 100 ms
09-30 11:23:01.172  5814  5834 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 11:23:01.306  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 11:23:01.306  5814  5834 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-30 11:23:01.307  5814  5834 I bt_hwcfg: vendor lib fwcfg completed
09-30 11:23:01.308  5814  5834 I bt_vendor: firmware callback
,09-30 11:23:01.308  5814  5834 I bt_hci  : firmware_config_callback
,09-30 11:23:01.317  5814  5837 I bt_btu  : btu_task pending for preload complete event
,09-30 11:23:01.317  5814  5837 I bt_btu_task: Bluetooth chip preload is complete
09-30 11:23:01.318  5814  5837 I bt_btu  : btu_task received preload complete event
,09-30 11:23:01.325  5814  5837 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 11:23:01.325  5814  5837 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 11:23:01.325  5814  5837 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-30 11:23:01.326  5814  5837 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 11:23:01.326  5814  5837 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 11:23:01.326  5814  5837 I         : BTE_InitTraceLevels -- TRC_A2D
,09-30 11:23:01.326  5814  5837 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-30 11:23:01.326  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTM
,09-30 11:23:01.326  5814  5837 I         : BTE_InitTraceLevels -- TRC_GAP
,09-30 11:23:01.326  5814  5837 I         : BTE_InitTraceLevels -- TRC_PAN
,09-30 11:23:01.327  5814  5837 I         : BTE_InitTraceLevels -- TRC_SDP
,09-30 11:23:01.327  5814  5837 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 11:23:01.327  5814  5837 I         : BTE_InitTraceLevels -- TRC_SMP
,09-30 11:23:01.327  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 11:23:01.327  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 11:23:01.408  5814  5837 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bcd549
,09-30 11:23:01.408  5814  5837 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bcd549 
,09-30 11:23:01.435  5814  5830 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 11:23:01.437  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 11:23:01.437  5814  5830 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 11:23:01.439  5814  5830 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 11:23:01.442  5814  5830 D BluetoothAdapterProperties: Scan Mode:20
,09-30 11:23:01.443  5814  5830 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 11:23:01.443  5814  5830 D bt_hci  : do_postload posting postload work item
,09-30 11:23:01.443  5814  5834 I bt_hci  : event_postload
09-30 11:23:01.443  5814  5834 I bt_vendor: sco_config_cb
09-30 11:23:01.444  5814  5834 I bt_hci  : sco_config_callback postload finished.
,09-30 11:23:01.448  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:01.450  5814  5834 I bt_vendor: low_power_mode_cb
09-30 11:23:01.451  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:01.454  5814  5830 D bt_bte_conf: Device ID record 1 : primary
09-30 11:23:01.454  5814  5830 D bt_bte_conf:   vendorId            = 000f
09-30 11:23:01.454  5814  5830 D bt_bte_conf:   vendorIdSource      = 0001
09-30 11:23:01.454  5814  5830 D bt_bte_conf:   product             = 1200
09-30 11:23:01.454  5814  5830 D bt_bte_conf:   version             = 1436
09-30 11:23:01.454  5814  5830 D bt_bte_conf:   clientExecutableURL = 
09-30 11:23:01.454  5814  5830 D bt_bte_conf:   serviceDescription  = 
09-30 11:23:01.454  5814  5830 D bt_bte_conf:   documentationURL    = 
,09-30 11:23:01.454  5814  5830 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 11:23:01.455  5814  5827 D bt_stack_manager: event_start_up_stack finished
09-30 11:23:01.455  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 11:23:01.456  5814  5826 D BluetoothAdapterProperties: Setting state to 15
,09-30 11:23:01.456  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 11:23:01.456  5814  5826 I BluetoothAdapterState: Entering BleOnState
,09-30 11:23:01.459  5814  5826 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-30 11:23:01.459  5814  5826 D BluetoothAdapterProperties: Setting state to 11
09-30 11:23:01.459  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 11:23:01.466  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:01.469  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:01.469  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:01.470  5814  5814 D HeadsetService: Received start request. Starting profile...
09-30 11:23:01.472  5814  5814 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 11:23:01.472  5814  5814 D HeadsetStateMachine: make
,09-30 11:23:01.478  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
,09-30 11:23:01.481  5814  5814 D HeadsetStateMachine: max_hf_connections = 1
,09-30 11:23:01.482  5814  5814 I bt_bluedroid: get_profile_interface handsfree
09-30 11:23:01.482  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-30 11:23:01.482  5814  5830 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-30 11:23:01.486  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:01.487  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 11:23:01.487  5814  5814 D A2dpService: Received start request. Starting profile...
09-30 11:23:01.488  5814  5814 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 11:23:01.488  5814  5814 I bt_bluedroid: get_profile_interface avrcp
,09-30 11:23:01.494  5814  5814 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 11:23:01.494  5814  5814 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 11:23:01.494  5814  5814 D A2dpStateMachine: make
09-30 11:23:01.496  5814  5814 I bt_bluedroid: get_profile_interface a2dp
,09-30 11:23:01.496  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 11:23:01.498  5814  5846 D A2dpStateMachine: Enter Disconnected: -2
09-30 11:23:01.498  5814  5814 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 11:23:01.499  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:23:01.500  5814  5814 D HidService: Received start request. Starting profile...
09-30 11:23:01.500  5814  5814 I bt_bluedroid: get_profile_interface hidhost
09-30 11:23:01.500  5814  5814 D HidService: setHidService(): set to: null
09-30 11:23:01.500  5814  5830 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bae56d
09-30 11:23:01.501  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 11:23:01.501  5814  5814 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-30 11:23:01.502  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:01.503  5814  5814 D HealthService: Received start request. Starting profile...
,09-30 11:23:01.505  5814  5814 I bt_bluedroid: get_profile_interface health
,09-30 11:23:01.506  5814  5814 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 11:23:01.507  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:01.507  5814  5814 D PanService: Received start request. Starting profile...
09-30 11:23:01.507  5814  5814 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 11:23:01.507  5814  5814 I bt_bluedroid: get_profile_interface pan
09-30 11:23:01.509  5814  5830 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 11:23:01.510  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:01.510  5814  5814 D BluetoothMapService: Received start request. Starting profile...
09-30 11:23:01.511  5814  5814 D BluetoothMapService: start()
09-30 11:23:01.513  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 11:23:01.514  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 11:23:01.514  5814  5814 D BluetoothMapAppObserver: createReceiver()
09-30 11:23:01.515  5814  5814 D BluetoothMapAppObserver: initObservers()
09-30 11:23:01.515  5814  5814 D BluetoothMapAppObserver: getEnabledAccountItems()
09-30 11:23:01.521  5814  5814 V SapService: SapBinder()
09-30 11:23:01.521  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
09-30 11:23:01.522  5814  5814 D SapService: Received start request. Starting profile...
,09-30 11:23:01.522  5814  5814 V SapService: start()
,09-30 11:23:01.526  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,09-30 11:23:01.526  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-30 11:23:01.526  5814  5844 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 11:23:01.526  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:23:01.526  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:23:01.526  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-30 11:23:01.527  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:23:01.528  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 11:23:01.530  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,09-30 11:23:01.530  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-30 11:23:01.530  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-30 11:23:01.530  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-30 11:23:01.530  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 11:23:01.530  5814  5826 D BluetoothAdapterProperties: ScanMode =  20
09-30 11:23:01.530  5814  5826 D BluetoothAdapterProperties: State =  11
09-30 11:23:01.532  5814  5830 D BluetoothAdapterProperties: Scan Mode:21
09-30 11:23:01.532  5814  5830 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 11:23:01.532  5535  5535 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 11:23:01.532  5814  5826 D BluetoothAdapterProperties: Setting state to 12
09-30 11:23:01.532  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 11:23:01.533   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 11:23:01.534  3027  3049 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:23:01.536  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:23:01.537  5814  5826 I BluetoothAdapterState: Entering OnState
09-30 11:23:01.537  3027  3039 D BluetoothPan: onBluetoothStateChange on: true
09-30 11:23:01.538  3027  3027 D BluetoothA2dp: Proxy object connected
09-30 11:23:01.538  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 11:23:01.539   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:23:01.539  5611  5623 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 11:23:01.540  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 11:23:01.540  3027  3027 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 11:23:01.540  3027  3027 D PanProfile: Bluetooth service connected
09-30 11:23:01.541  5814  5814 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 11:23:01.541  5611  5625 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:23:01.542  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:23:01.542  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:23:01.543  3690  4054 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:23:01.543  5611  5623 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 11:23:01.544  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 11:23:01.545  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:23:01.545  5611  5625 D BluetoothPan: onBluetoothStateChange on: true
09-30 11:23:01.545  5814  5814 D ObexServerSockets: Succeed to create listening sockets 
09-30 11:23:01.546  5814  5814 D ObexServerSockets0: startAccept()
09-30 11:23:01.546  5814  5814 D ObexServerSockets0: prepareForNewConnect()
09-30 11:23:01.547  3027  3039 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:23:01.547  5611  5611 D BluetoothA2dp: Proxy object connected
09-30 11:23:01.548  5814  5814 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 11:23:01.548  5814  5814 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-30 11:23:01.548  5814  5852 D ObexServerSockets0: Accepting socket connection...
09-30 11:23:01.548  3027  3234 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 11:23:01.548  5814  5853 D ObexServerSockets0: Accepting socket connection...
,09-30 11:23:01.550   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 11:23:01.551   929   929 D BluetoothA2dp: Proxy object connected
09-30 11:23:01.551  5611  5625 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:23:01.551   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 11:23:01.551  3027  3049 D BluetoothMap: onBluetoothStateChange: up=true
09-30 11:23:01.553  3027  3039 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 11:23:01.554  3027  3027 D BluetoothMap: Proxy object connected
09-30 11:23:01.554  3027  3027 D MapProfile: Bluetooth service connected
,09-30 11:23:01.554  3027  3027 D BluetoothMap: getConnectedDevices()
09-30 11:23:01.554  5611  5611 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 11:23:01.554  5611  5611 D PanProfile: Bluetooth service connected
09-30 11:23:01.554  5611  5611 D BluetoothInputDevice: Proxy object connected
09-30 11:23:01.554  5611  5611 D HidProfile: Bluetooth service connected
09-30 11:23:01.555  5611  5623 D BluetoothMap: onBluetoothStateChange: up=true
,09-30 11:23:01.556  3027  3027 D BluetoothInputDevice: Proxy object connected
,09-30 11:23:01.556  3027  3027 D HidProfile: Bluetooth service connected
09-30 11:23:01.560  5611  5611 D BluetoothMap: Proxy object connected
09-30 11:23:01.560  5611  5611 D MapProfile: Bluetooth service connected
09-30 11:23:01.560  5611  5611 D BluetoothMap: getConnectedDevices()
09-30 11:23:01.561  5535  5535 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 11:23:01.561  5814  5814 D BluetoothMapService: onReceive
09-30 11:23:01.561  5814  5814 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 11:23:01.561  5814  5814 D BluetoothMapService: STATE_ON
09-30 11:23:01.561   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-30 11:23:01.562  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:01.564  5814  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:23:01.564  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:01.566  5814  5855 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 11:23:01.566  5814  5855 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 11:23:01.568  5611  5611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 11:23:01.574  5611  5611 D DockEventReceiver: finishStartingService: stopping service
,09-30 11:23:01.574  3475  3475 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 11:23:01.581  5611  5611 D BluetoothPbap: Proxy object connected
,09-30 11:23:01.581  5611  5611 D PbapServerProfile: Bluetooth service connected
,09-30 11:23:01.586  3027  3027 D BluetoothPbap: Proxy object connected
,09-30 11:23:01.586  3027  3027 D PbapServerProfile: Bluetooth service connected
,09-30 11:23:01.588  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-30 11:23:01.588  5814  5814 D ObexServerSockets0: prepareForNewConnect()
,09-30 11:23:01.590  5814  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:23:01.604  5814  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 11:23:01.606  5814  5863 I BtOppRfcommListener: Accept thread started.
,09-30 11:23:01.635   929   929 D BluetoothHeadset: Proxy object connected
,09-30 11:23:01.636  3690  3903 D BluetoothHeadset: Proxy object connected
09-30 11:23:01.637  5611  5851 D BluetoothHeadset: Proxy object connected
,09-30 11:23:01.637  3027  3049 D BluetoothHeadset: Proxy object connected
,09-30 11:23:01.637   929   929 D BluetoothHeadset: Proxy object connected
09-30 11:23:01.637   929   929 D BluetoothHeadset: Proxy object connected
09-30 11:23:01.637  3027  3027 D HeadsetProfile: Bluetooth service connected
09-30 11:23:01.639  5611  5611 D HeadsetProfile: Bluetooth service connected
09-30 11:23:01.639   929   946 D BluetoothHeadset: Proxy object connected
,09-30 11:23:01.643  3690  3722 D BluetoothHeadset: Proxy object connected
,09-30 11:23:01.648  3027  3039 D BluetoothHeadset: Proxy object connected
,09-30 11:23:01.648  3027  3027 D HeadsetProfile: Bluetooth service connected
,09-30 11:23:01.651  5611  5625 D BluetoothHeadset: Proxy object connected
,09-30 11:23:01.651   929   946 D BluetoothHeadset: Proxy object connected
09-30 11:23:01.651  5611  5611 D HeadsetProfile: Bluetooth service connected
,09-30 11:23:05.390   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:23:05.419  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:23:05.425  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:23:05.426  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:05.426  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4702a24 removed from the list
09-30 11:23:05.426  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:23:05.426  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:05.427  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:05.428  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:05.429  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c71198d added. We now have 4 listener(s)
09-30 11:23:05.429  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:23:05.433   929  5460 D WifiService: setWifiEnabled: false pid=5535, uid=10077
,09-30 11:23:05.434   929  5460 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 11:23:06.391   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:07.392   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:08.393   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:09.394   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:10.395   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 11:23:10.443  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:10.444   929   939 D WifiService: setWifiEnabled: true pid=5535, uid=10077
09-30 11:23:10.444   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 11:23:10.453   507   922 D SoftapController: Softap fwReload - Ok
,09-30 11:23:10.458   507   922 D CommandListener: Setting iface cfg
,09-30 11:23:10.459   507   922 D CommandListener: Trying to bring down wlan0
09-30 11:23:10.460   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-30 11:23:10.465   929  2874 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 11:23:11.109   929  2874 D wifi    : set interface wlan0 flags (UP)
09-30 11:23:11.110   929  2874 I WifiHAL : Initializing wifi
,09-30 11:23:11.110   929  2874 I WifiHAL : Creating socket
,09-30 11:23:11.118   929  2874 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-30 11:23:11.118   929  2874 D wifi    : Did set static halHandle = 0x7f82827e00
09-30 11:23:11.118   929  2874 D wifi    : halHandle = 0x7f82827e00, mVM = 0x7f9ee0d140, mCls = 0x1562
09-30 11:23:11.119   929  2874 D wifi    : array field set
09-30 11:23:11.119   929  2874 I WifiNative-HAL: interface[0] = wlan0
09-30 11:23:11.121   929  5868 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547650436608
09-30 11:23:11.121   929  5868 D wifi    : waitForHalEvents called, vm = 0x7f9ee0d140, obj = 0x1562, env = 0x7f9438f840
09-30 11:23:11.121   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-30 11:23:11.169  5869  5869 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 11:23:11.191  5869  5869 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 11:23:11.217  5869  5869 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 11:23:11.218  5869  5869 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 11:23:11.223   929  2874 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 11:23:11.234  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:11.236  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:11.241   929  2874 D WifiConfigStore: Loading config and enabling all networks 
,09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:23:11.246  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 11:23:11.248  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:23:11.252   929  2874 D WifiConfigStore: loaded 0 passpoint configs
09-30 11:23:11.253   929  2874 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 11:23:11.253   929  2874 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 11:23:11.253  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 11:23:11.254   929  2874 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 11:23:11.255   929  2874 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 11:23:11.255  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 11:23:11.255   929  2874 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 11:23:11.255   929  2874 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 11:23:11.255   929  2874 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 11:23:11.259  4926  4926 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 11:23:11.259   929  2874 D WifiNative-HAL: Setting external_sim to 1
09-30 11:23:11.260   929  2874 D wifi    : setting dfs flag to true, 0x7f87a76200
09-30 11:23:11.260   929  2874 D WifiStateMachine: Setting OUI to DA-A1-19
,09-30 11:23:11.260   929  2874 D wifi    : setting scan oui 0x7f87a76200
09-30 11:23:11.260   929  2874 D WifiHAL : Sending mac address OUI
,09-30 11:23:11.264   929  2874 E native  : do suspend false
,09-30 11:23:11.275   929  2874 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 11:23:11.276   929   929 D RttService: SCAN_AVAILABLE : 3
09-30 11:23:11.276   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-30 11:23:11.276   929  2980 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-30 11:23:11.277   507   922 D CommandListener: Setting iface cfg
,09-30 11:23:11.280   929  2870 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-30 11:23:11.280   929  2870 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 11:23:11.291   929  2870 D WifiNative-HAL: p2pGetDeviceAddress
09-30 11:23:11.291   929  2870 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 11:23:11.296   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=279654 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-30 11:23:14.449  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:23:14.455  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:23:14.461  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:23:14.465  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:23:14.526   929  2874 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-30 11:23:14.527   929  2874 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 11:23:14.527   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 11:23:14.538   929  2874 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 11:23:14.571   929  2874 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 11:23:14.572  5869  5869 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 11:23:14.997  5869  5869 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 11:23:15.027  5869  5869 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 11:23:15.028  5869  5869 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 11:23:15.039   929  2874 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 11:23:15.039   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 11:23:15.039   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 11:23:15.056   929  2874 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 11:23:15.070   507   922 D CommandListener: Setting iface cfg
,09-30 11:23:15.077   929  2874 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 11:23:15.083   929  5874 D DhcpClient: Receive thread started
,09-30 11:23:15.088   929  2874 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-30 11:23:15.088   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 11:23:15.088   929  2876 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 11:23:15.170   929  2874 E native  : do suspend false
,09-30 11:23:15.180   929  5873 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 11:23:15.192   929  5874 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-30 11:23:15.193   929  5873 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
09-30 11:23:15.195   929  5873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 11:23:15.209   929  5874 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 11:23:15.210   929  5873 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-30 11:23:15.213   507   922 D CommandListener: Setting iface cfg
09-30 11:23:15.217   929  2874 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 11:23:15.221   929  5873 D DhcpClient: Scheduling renewal in 86399s
,09-30 11:23:15.230   929  2874 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-30 11:23:15.231   929  2874 D WifiConfigStore: No blacklist allowed without epno enabled
,09-30 11:23:15.231   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-30 11:23:15.234   929  2876 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 11:23:15.241   929  2874 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 11:23:15.280   929  2876 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 11:23:15.280   929  2876 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-30 11:23:15.284   929  2876 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 11:23:15.286   929  2876 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 11:23:15.290   929  2876 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 11:23:15.295   929  2876 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 11:23:15.299   929  2876 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 11:23:15.299   929  2876 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 11:23:15.299   929  2876 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 11:23:15.299   929  2876 D ConnectivityService:    accepting network in place of null
09-30 11:23:15.299   929  2874 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-30 11:23:15.299   929  2874 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 11:23:15.300   929  2876 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 11:23:15.312   929  5872 D NetlinkSocketObserver: NeighborEvent{elapsedMs=283669, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 11:23:15.323   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 11:23:15.344   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 11:23:15.349   929  2876 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-30 11:23:15.349  3649  3799 W QCNEJ   : |CORE| network available: 102
,09-30 11:23:15.349   929  2876 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 11:23:15.350   929  2876 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-30 11:23:15.351   929   946 D Tethering: MasterInitialState.processMessage what=3
09-30 11:23:15.351  3649  3799 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 11:23:15.353  3649  3799 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 11:23:15.353  3649  3799 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:15.358  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:23:15.362  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:23:15.365  3757  3757 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:15.367  5535  5535 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:23:15.367  4951  4975 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 11:23:15.367  4951  4975 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 11:23:15.367  4951  4975 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 11:23:15.367  4951  4975 E SarControlService: no key has been found,reset the power
09-30 11:23:15.367  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 11:23:15.367  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 11:23:15.368  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 11:23:15.368  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:23:15.368  4976  4976 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 11:23:15.368  5535  5535 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:15.369  4951  4988 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 11:23:15.369  4951  4988 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-30 11:23:15.369  4951  4988 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-30 11:23:15.369  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 11:23:15.370  4976  4976 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 11:23:15.373  3757  3757 D SystemUpdateService: onCreate
09-30 11:23:15.375  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000f003000000000000ffffffff]
09-30 11:23:15.376  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 11:23:15.376  4976  4990 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,09-30 11:23:15.376  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:23:15.376  4951  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 11:23:15.377  4976  4990 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a1ea994 HexData = [00000000f103000000000000ffffffff]
09-30 11:23:15.377  4976  4990 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 11:23:15.377  4976  4990 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-30 11:23:15.377  3757  3757 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 11:23:15.378  4976  4976 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 11:23:15.379  4951  4961 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 11:23:15.384   929  5871 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-30 11:23:15.390  3757  3757 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 11:23:15.394  3757  5311 I iu.UploadsManager: num queued entries: 0
09-30 11:23:15.394  3757  5311 I iu.UploadsManager: num updated entries: 0
09-30 11:23:15.395  3757  5311 I iu.SyncManager: NEXT; no task
,09-30 11:23:15.397  3757  5884 I SystemUpdateService: active receiver: enabled
,09-30 11:23:15.399  3757  3757 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 11:23:15.400  3757  3757 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 11:23:15.402  5679  5679 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 11:23:15.405  5679  5679 D SprintDMHelper: simOperator: 
09-30 11:23:15.405  5679  5679 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 11:23:15.433  3757  5884 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 11:23:15.440   929  5871 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 15:23:15 GMT], X-Android-Received-Millis=[1475248995439], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475248995406]}
,09-30 11:23:15.440  3757  5884 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-30 11:23:15.440  3757  5884 I SystemUpdateService: now status is 0 (complete)
09-30 11:23:15.440  3757  5884 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 11:23:15.440  3757  5884 I SystemUpdateService: file has been verified
09-30 11:23:15.440   929  2876 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-30 11:23:15.440  3757  5884 I SystemUpdateService: OTA package size = 21989297
,09-30 11:23:15.441   929  2876 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-30 11:23:15.441   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 11:23:15.442   929  2876 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 11:23:15.445  3757  5884 I SystemUpdateService: showing system update notification
,09-30 11:23:15.454  3757  3757 D SystemUpdateService: onDestroy
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:15.455  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:23:15.457  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:23:15.458  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:15.458  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c71198d removed from the list
09-30 11:23:15.458  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:23:15.458  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:15.458  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:15.461  5535  5894 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-30 11:23:15.461  5535  5894 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 11:23:15.513  4926  5888 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 11:23:18.107   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 11:23:18.471  5535  5894 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-30 11:23:18.473  5535  5894 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 11:23:18.473  5535  5897 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-30 11:23:18.473  5535  5894 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 11:23:18.474  5535  5897 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-30 11:23:18.474  5535  5897 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 11:23:18.475  5535  5894 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 11:23:18.476  5535  5897 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 11:23:18.478  5535  5894 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-30 11:23:18.478  5535  5899 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:18.478  5535  5899 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:18.481  5535  5897 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 11:23:18.481  5535  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:18.481  5535  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:18.483  5535  5902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:18.483  5535  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 11:23:18.483  5535  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:18.483  5535  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:18.484  5535  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:18.484  5535  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:18.484  5535  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 11:23:18.484  5535  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 11:23:18.485  5535  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 11:23:18.485  5535  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 11:23:18.485  5535  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 11:23:18.487  5535  5902 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:18.487  5535  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 11:23:18.487  5535  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:18.487  5535  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 11:23:18.487  5535  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 11:23:18.487  5535  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 11:23:18.488  5535  5902 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 11:23:18.488  5535  5902 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 11:23:18.488  5535  5902 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 11:23:18.489  5535  5902 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 11:23:18.489  5535  5901 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 11:23:18.489  5535  5902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:18.489  5535  5902 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 11:23:18.490  5535  5899 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 156, thread name: OutgoingSocketThread/Sender): Socket closed
09-30 11:23:18.490  5535  5899 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 156, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:18.490  5535  5899 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 11:23:18.490  5535  5900 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:18.490  5535  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 11:23:18.490  5535  5899 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 11:23:18.490  5535  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:18.490  5535  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 11:23:18.490  5535  5899 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 11:23:18.491  5535  5899 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:18.491  5535  5899 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 11:23:18.491  5535  5900 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
09-30 11:23:18.491  5535  5900 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:18.491  5535  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 11:23:18.491  5535  5900 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,09-30 11:23:18.491  5535  5900 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 11:23:18.492  5535  5900 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:18.492  5535  5900 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 11:23:21.474  5535  5581 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-30 11:23:21.475  5535  5581 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 11:23:21.481  5535  5581 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d2fa18 Bundle[{}]
,09-30 11:23:21.482  5535  5581 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 11:23:21.482  5535  5581 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-30 11:23:21.483  5535  5581 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-30 11:23:21.484  5535  5581 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-30 11:23:21.485  5535  5581 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-30 11:23:21.487  5535  5581 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 11:23:21.493  5535  5581 I System.out: Running OutgoingSocketThread
,09-30 11:23:21.496  5535  5903 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-30 11:23:21.496  5535  5903 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 11:23:23.305   929  2876 D ConnectivityService: handlePromptUnvalidated 102
,09-30 11:23:24.145   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 11:23:24.507  5535  5904 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-30 11:23:24.507  5535  5904 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 11:23:24.507  5535  5903 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-30 11:23:24.507  5535  5903 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 11:23:24.507  5535  5904 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 11:23:24.508  5535  5903 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 11:23:24.509  5535  5904 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 11:23:24.510  5535  5903 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 11:23:24.511  5535  5904 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 11:23:24.513  5535  5906 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:24.513  5535  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 11:23:24.514  5535  5907 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:24.514  5535  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:24.518  5535  5903 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 11:23:24.521  5535  5908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:24.521  5535  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 11:23:24.522  5535  5909 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:24.522  5535  5909 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:24.523  5535  5908 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:24.523  5535  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 11:23:24.523  5535  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:24.523  5535  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 11:23:24.523  5535  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 11:23:24.524  5535  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 11:23:24.524  5535  5908 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 11:23:24.524  5535  5906 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 168, thread name: IncomingSocketThread/Sender): Socket closed
,09-30 11:23:24.524  5535  5908 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 11:23:24.524  5535  5908 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 11:23:24.524  5535  5906 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:24.524  5535  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 11:23:24.524  5535  5908 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 11:23:24.525  5535  5906 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,09-30 11:23:24.525  5535  5908 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:24.525  5535  5908 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 11:23:24.525  5535  5906 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 11:23:24.525  5535  5906 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:24.525  5535  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 11:23:24.526  5535  5909 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:24.526  5535  5909 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:24.526  5535  5907 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:24.526  5535  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:24.526  5535  5907 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:24.526  5535  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:24.526  5535  5907 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 11:23:24.526  5535  5907 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 11:23:24.526  5535  5909 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:24.526  5535  5909 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:24.527  5535  5907 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 11:23:24.527  5535  5907 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 11:23:24.527  5535  5909 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 11:23:24.527  5535  5907 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 11:23:24.527  5535  5909 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 11:23:24.527  5535  5907 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-30 11:23:24.527  5535  5907 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 11:23:24.527  5535  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 11:23:24.528  5535  5909 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 11:23:24.528  5535  5909 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 11:23:24.528  5535  5909 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 11:23:24.529  5535  5909 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 11:23:24.529  5535  5909 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-30 11:23:24.529  5535  5909 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 11:23:24.529  5535  5909 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-30 11:23:26.292   929  2874 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,09-30 11:23:27.507  5535  5581 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
,09-30 11:23:27.509  5535  5581 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-30 11:23:27.509  5535  5581 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-30 11:23:27.516  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 11:23:27.517  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ff0742 added. We now have 3 listener(s)
,09-30 11:23:27.519  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.520  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.520  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 11:23:27.520  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.520  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd86353 added. We now have 4 listener(s)
09-30 11:23:27.520  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.522  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 11:23:27.528  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:27.535  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:23:27.538  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.538  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 11:23:27.538  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.538  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e2c189 added. We now have 4 listener(s)
,09-30 11:23:27.540  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.540  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 11:23:27.540  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 11:23:27.541  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.541  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47a558e added. We now have 5 listener(s)
09-30 11:23:27.541  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.541  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:23:27.541  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:23:27.541  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:23:27.541  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.541  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.541  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:23:27.541  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.541  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.542  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ff0742 removed from the list
09-30 11:23:27.542  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.542  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd86353 removed from the list
09-30 11:23:27.542  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.542  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 11:23:27.542  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.543  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.543  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.545  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.545  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.545  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:23:27.545  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd86353 not in the list
09-30 11:23:27.545  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.545  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.546  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.547  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.547  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.547  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47a558e removed from the list
09-30 11:23:27.547  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.547  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.547  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.547  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.547  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 11:23:27.547  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e2c189 removed from the list
09-30 11:23:27.547  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.548  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.548  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fbe1af added. We now have 3 listener(s)
09-30 11:23:27.550  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.550  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.550  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 11:23:27.550  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.550  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15c99bc added. We now have 4 listener(s)
09-30 11:23:27.550  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:23:27.551  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 11:23:27.554  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:27.558  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:23:27.561  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:23:27.561  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:23:27.561  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.561  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84a3c9a added. We now have 4 listener(s)
09-30 11:23:27.563  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.563  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.563  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 11:23:27.563  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.563  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2ee9cb added. We now have 5 listener(s)
09-30 11:23:27.563  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.563  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:23:27.564  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 11:23:27.564  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-30 11:23:27.564  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.564  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:23:27.564  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 11:23:27.567  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:27.567  5535  5581 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 11:23:27.568  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 11:23:27.571  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 11:23:27.572  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 11:23:27.572  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 11:23:27.576  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 11:23:27.576  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 11:23:27.576  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-30 11:23:27.576  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 11:23:27.576  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 11:23:27.576  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:23:27.579  5814  5843 D BtGatt.GattService: registerClient() - UUID=c150177e-ff5c-4a35-8930-23b8310a57f7
09-30 11:23:27.580  5814  5830 D BtGatt.GattService: onClientRegistered() - UUID=c150177e-ff5c-4a35-8930-23b8310a57f7, clientIf=5
09-30 11:23:27.581  5535  5546 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 11:23:27.582  5814  5854 D BtGatt.GattService: start scan with filters
,09-30 11:23:27.585  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 11:23:27.585  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 11:23:27.585  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:23:27.585  5814  5833 D BtGatt.ScanManager: handling starting scan
09-30 11:23:27.585  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 11:23:27.585  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 11:23:27.586  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 11:23:27.586  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 11:23:27.587  5814  5833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@560f5f5
,09-30 11:23:27.588  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 11:23:27.588  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 11:23:27.588  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 11:23:27.589  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 11:23:27.592  5535  5581 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 11:23:27.592  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 11:23:27.592  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 11:23:27.592  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.592  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 11:23:27.592  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.592  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 11:23:27.592  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 11:23:27.592  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 11:23:27.592  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 11:23:27.592  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-30 11:23:27.592  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 11:23:27.593  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:23:27.594  5814  5843 D BtGatt.GattService: stopScan() - queue size =1
09-30 11:23:27.594  5814  5830 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 11:23:27.595  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.595  5814  5854 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-30 11:23:27.595  5814  5833 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 11:23:27.595  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 11:23:27.595  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 11:23:27.595  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 11:23:27.595  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:23:27.595  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 11:23:27.595  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 11:23:27.595  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 11:23:27.595  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 11:23:27.597  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:23:27.597  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 11:23:27.597  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 11:23:27.597  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 11:23:27.597  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 11:23:27.597  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:23:27.598  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 11:23:27.598  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:23:27.598  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:23:27.600  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:23:27.601  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:23:27.601  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:23:27.601  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.601  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.601  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:23:27.601  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 11:23:27.601  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 11:23:27.601  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.601  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.601  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7fbe1af removed from the list
09-30 11:23:27.601  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.601  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15c99bc removed from the list
09-30 11:23:27.601  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:23:27.601  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.601  5814  5833 D BtGatt.ScanManager: Starting BLE batch scan
09-30 11:23:27.602  5814  5833 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 11:23:27.602  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.602  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:23:27.603  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 11:23:27.603  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.603  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.603  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15c99bc not in the list
09-30 11:23:27.603  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.603  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.605  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.605  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.605  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.605  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2ee9cb removed from the list
09-30 11:23:27.605  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.605  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.605  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:23:27.605  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.605  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.605  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84a3c9a removed from the list
09-30 11:23:27.607  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.607  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34057a7 added. We now have 3 listener(s)
,09-30 11:23:27.608  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.608  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.609  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 11:23:27.609  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.609  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f446454 added. We now have 4 listener(s)
09-30 11:23:27.609  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 11:23:27.610  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 11:23:27.612  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 11:23:27.614  5814  5830 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 11:23:27.614  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:27.618  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:23:27.619  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 11:23:27.619  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:23:27.620  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 11:23:27.620  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:23:27.620  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.620  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bc4f2 added. We now have 4 listener(s)
09-30 11:23:27.621  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.622  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.622  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 11:23:27.622  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.622  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@910c743 added. We now have 5 listener(s)
09-30 11:23:27.622  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.622  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 11:23:27.623  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.623  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:23:27.623  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 11:23:27.623  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 11:23:27.623  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:23:27.623  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 11:23:27.626  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 11:23:27.626  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.626  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.626  5814  5833 D BtGatt.ScanManager: stopping BLe Batch
,09-30 11:23:27.627  5535  5581 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 11:23:27.627  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 11:23:27.631  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 11:23:27.632  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-30 11:23:27.632  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 11:23:27.633  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 11:23:27.633  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.634  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 11:23:27.635  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 11:23:27.635  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 11:23:27.635  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 11:23:27.635  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-30 11:23:27.635  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 11:23:27.636  5535  5581 D BluetoothAdapter: STATE_ON
,09-30 11:23:27.638  5814  5854 D BtGatt.GattService: registerClient() - UUID=110618e2-3fc3-4c28-8d8d-2f96127546bd
,09-30 11:23:27.639  5814  5830 D BtGatt.GattService: onClientRegistered() - UUID=110618e2-3fc3-4c28-8d8d-2f96127546bd, clientIf=5
09-30 11:23:27.639  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 11:23:27.639  5535  5545 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 11:23:27.639  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:23:27.639  5814  5824 D BtGatt.GattService: start scan with filters
09-30 11:23:27.641  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 11:23:27.641  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 11:23:27.641  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:23:27.641  5814  5833 D BtGatt.ScanManager: handling starting scan
09-30 11:23:27.641  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 11:23:27.641  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 11:23:27.642  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 11:23:27.642  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 11:23:27.644  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 11:23:27.644  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 11:23:27.644  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 11:23:27.645  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 11:23:27.647  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 11:23:27.647  5535  5581 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 11:23:27.648  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:23:27.648  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:23:27.648  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:23:27.648  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.648  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.648  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 11:23:27.648  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.648  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.648  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34057a7 removed from the list
09-30 11:23:27.648  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.648  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f446454 removed from the list
,09-30 11:23:27.648  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:23:27.648  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 11:23:27.649  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.649  5814  5830 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 11:23:27.649  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.649  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 11:23:27.649  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.649  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:23:27.649  5814  5833 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 11:23:27.650  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.650  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.650  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.650  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f446454 not in the list
09-30 11:23:27.650  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 11:23:27.650  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 11:23:27.650  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 11:23:27.650  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 11:23:27.650  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 11:23:27.651  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:23:27.652  5814  5843 D BtGatt.GattService: stopScan() - queue size =1
,09-30 11:23:27.653  5814  5842 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 11:23:27.653  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 11:23:27.653  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-30 11:23:27.654  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 11:23:27.654  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:23:27.654  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 11:23:27.654  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 11:23:27.654  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 11:23:27.654  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 11:23:27.655  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 11:23:27.655  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.655  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 11:23:27.655  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 11:23:27.655  5814  5833 D BtGatt.ScanManager: Starting BLE batch scan
09-30 11:23:27.655  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 11:23:27.655  5814  5833 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 11:23:27.655  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 11:23:27.655  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 11:23:27.655  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.656  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.656  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.656  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.656  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:23:27.656  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@910c743 removed from the list
09-30 11:23:27.657  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.657  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:23:27.657  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.657  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 11:23:27.657  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.657  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.657  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.657  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bc4f2 removed from the list
09-30 11:23:27.657  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.657  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ee949f added. We now have 3 listener(s)
09-30 11:23:27.658  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.658  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.659  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 11:23:27.659  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.659  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e9ec added. We now have 4 listener(s)
09-30 11:23:27.659  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.659  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 11:23:27.661  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:23:27.664  5814  5830 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 11:23:27.665  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:27.665  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 11:23:27.671  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-30 11:23:27.671  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.671  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:23:27.671  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 11:23:27.671  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.671  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7b004a added. We now have 4 listener(s)
09-30 11:23:27.672  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.672  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.672  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 11:23:27.673  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.673  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b1dbbb added. We now have 5 listener(s)
09-30 11:23:27.673  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.673  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:23:27.673  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 11:23:27.673  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 11:23:27.673  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:23:27.673  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-30 11:23:27.673  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.676  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 11:23:27.677  5535  5581 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 11:23:27.677  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 11:23:27.677  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.677  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 11:23:27.677  5814  5833 D BtGatt.ScanManager: stopping BLe Batch
,09-30 11:23:27.681  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 11:23:27.681  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 11:23:27.681  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 11:23:27.682  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 11:23:27.682  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.683  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 11:23:27.685  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 11:23:27.685  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 11:23:27.685  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 11:23:27.685  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 11:23:27.686  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 11:23:27.687  5535  5581 D BluetoothAdapter: STATE_ON
09-30 11:23:27.687  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 11:23:27.687  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.688  5814  5843 D BtGatt.GattService: registerClient() - UUID=1cc52cd0-e851-4fab-9296-0b1067294ecf
09-30 11:23:27.689  5814  5830 D BtGatt.GattService: onClientRegistered() - UUID=1cc52cd0-e851-4fab-9296-0b1067294ecf, clientIf=5
,09-30 11:23:27.689  5535  5546 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 11:23:27.689  5814  5854 D BtGatt.GattService: start scan with filters
,09-30 11:23:27.691  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-30 11:23:27.691  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 11:23:27.691  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:23:27.691  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 11:23:27.691  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 11:23:27.691  5814  5833 D BtGatt.ScanManager: handling starting scan
09-30 11:23:27.691  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 11:23:27.691  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 11:23:27.693  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 11:23:27.693  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 11:23:27.694  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 11:23:27.695  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-30 11:23:27.696  5814  5830 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 11:23:27.696  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.697  5814  5833 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 11:23:27.698  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 11:23:27.698  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:23:27.698  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 11:23:27.698  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.699  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.699  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 11:23:27.699  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.699  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.699  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ee949f removed from the list
09-30 11:23:27.699  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.699  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e9ec removed from the list
,09-30 11:23:27.699  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 11:23:27.699  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:23:27.700  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.700  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 11:23:27.700  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.700  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:23:27.701  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 11:23:27.701  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.701  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.701  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7e9ec not in the list
09-30 11:23:27.701  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 11:23:27.701  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 11:23:27.701  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-30 11:23:27.701  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 11:23:27.701  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 11:23:27.701  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 11:23:27.701  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.701  5814  5833 D BtGatt.ScanManager: Starting BLE batch scan
09-30 11:23:27.702  5814  5833 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 11:23:27.702  5535  5581 D BluetoothAdapter: STATE_ON
,09-30 11:23:27.702  5814  5843 D BtGatt.GattService: stopScan() - queue size =1
,09-30 11:23:27.703  5814  5854 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 11:23:27.703  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 11:23:27.703  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 11:23:27.703  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 11:23:27.703  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 11:23:27.703  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 11:23:27.703  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 11:23:27.703  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 11:23:27.703  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 11:23:27.704  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:23:27.704  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 11:23:27.704  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 11:23:27.704  5535  5581 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 11:23:27.704  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 11:23:27.705  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.706  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.706  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.706  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.706  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b1dbbb removed from the list
09-30 11:23:27.706  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.706  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.706  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.706  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:23:27.706  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.706  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.706  5535  5535 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 11:23:27.706  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7b004a removed from the list
09-30 11:23:27.706  5535  5535 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 11:23:27.707  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.707  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5987897 added. We now have 3 listener(s)
09-30 11:23:27.708  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.708  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.708  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 11:23:27.708  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.708  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2738a84 added. We now have 4 listener(s)
09-30 11:23:27.709  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.709  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 11:23:27.710  5814  5830 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 11:23:27.710  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.711  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 11:23:27.714  5535  5581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 11:23:27.714  553,5  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 11:23:27.714  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 11:23:27.714  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 11:23:27.714  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 11:23:27.714  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.714  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 11:23:27.714  5535  5581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 11:23:27.714  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 11:23:27.714  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.718  5535  5581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 11:23:27.718  5535  5581 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 11:23:27.718  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 11:23:27.718  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61b4ea2 added. We now have 4 listener(s)
,09-30 11:23:27.720  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 11:23:27.720  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 11:23:27.720  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 11:23:27.721  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 11:23:27.721  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee20733 added. We now have 5 listener(s)
09-30 11:23:27.721  5535  5581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 11:23:27.721  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.721  5535  5581 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 11:23:27.721  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:23:27.721  5535  5581 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 11:23:27.721  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.721  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.721  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 11:23:27.721  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.722  5814  5830 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 11:23:27.722  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.722  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.722  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5987897 removed from the list
09-30 11:23:27.722  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.722  5814  5833 D BtGatt.ScanManager: stopping BLe Batch
09-30 11:23:27.722  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2738a84 removed from the list
,09-30 11:23:27.723  5535  5535 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 11:23:27.723  5535  5581 D io.jxcore.node.ConnectivityMonitor: stop
09-30 11:23:27.723  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:23:27.724  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.724  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 11:23:27.727  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.727  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 11:23:27.727  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 11:23:27.727  5814  5830 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 11:23:27.727  5535  5581 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2738a84 not in the list
09-30 11:23:27.727  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 11:23:27.727  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.727  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.727  5814  5833 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 11:23:27.728  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 11:23:27.728  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 11:23:27.728  5535  5581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 11:23:27.728  5535  5581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee20733 removed from the list
09-30 11:23:27.729  5535  5581 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 11:23:27.729  5535  5581 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 11:23:27.729  5535  5581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 11:23:27.729  5535  5581 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 11:23:27.729  5535  5581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 11:23:27.729  5535  5581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61b4ea2 removed from the list
09-30 11:23:27.730  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 11:23:27.730  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-30 11:23:27.730  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-30 11:23:27.730  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 11:23:27.730  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-30 11:23:27.730  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 11:23:27.732  5814  5830 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 11:23:27.732  5814  5830 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 11:23:28.100  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 11:23:28.158  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 11:23:28.208  5535  5535 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 11:23:29.875  5535  5910 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 11:23:29.875  5535  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:30.396   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:30.682  5535  5910 W !!      : call onHalfStreamCopied
,09-30 11:23:30.682  5535  5910 I testCopyDataAndClose: closing input stream
,09-30 11:23:31.397   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 11:23:31.456  5535  5910 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 11:23:32.397   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:33.230   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 11:23:33.398   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:34.400   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:23:35.199  5535  5911 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:35.199  5535  5911 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:35.401   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 11:23:37.199  5535  5581 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 192. Connection data: Peer properties: [null null].
09-30 11:23:37.199  5535  5581 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:37.199  5535  5581 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 192, name: My test thread name)
,09-30 11:23:37.307  5535  5911 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-30 11:23:37.308  5535  5911 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:37.308  5535  5911 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-30 11:23:37.347  5535  5912 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 11:23:37.347  5535  5912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:38.932  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 11:23:38.984  5535  5912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 11:23:39.277   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 11:23:42.308   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 11:23:42.729  5535  5913 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:42.729  5535  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:42.730  5535  5913 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:42.730  5535  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:42.730  5535  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 11:23:42.730  5535  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 11:23:42.730  5535  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 11:23:42.730  5535  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 11:23:42.730  5535  5913 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 11:23:42.731  5535  5913 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 11:23:42.731  5535  5913 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 11:23:42.731  5535  5913 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:42.731  5535  5913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-30 11:23:42.733  5535  5581 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 11:23:42.735  5535  5914 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:42.735  5535  5914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 11:23:42.736  5535  5914 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
09-30 11:23:42.736  5535  5914 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:42.736  5535  5914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 11:23:42.737  5535  5914 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-30 11:23:42.737  5535  5914 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
09-30 11:23:42.737  5535  5914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 11:23:42.741  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 11:23:42.741  5535  5581 I jxcore-log: 
,09-30 11:23:42.741  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-30 11:23:42.741  5535  5581 I jxcore-log: 
09-30 11:23:42.741  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-30 11:23:42.741  5535  5581 I jxcore-log: 
09-30 11:23:42.742  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 11:23:42.742  5535  5581 I jxcore-log: 
09-30 11:23:42.742  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Total duration:  102812'
09-30 11:23:42.742  5535  5581 I jxcore-log: 
09-30 11:23:42.742  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Failures: 
09-30 11:23:42.742  5535  5581 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 11:23:42.742  5535  5581 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
09-30 11:23:42.742  5535  5581 I jxcore-log:      but: was ""
09-30 11:23:42.742  5535  5581 I jxcore-log: IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-30 11:23:42.742  5535  5581 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
09-30 11:23:42.742  5535  5581 I jxcore-log:      but: was ""
09-30 11:23:42.742  5535  5581 I jxcore-log: '
09-30 11:23:42.742  5535  5581 I jxcore-log: 
,09-30 11:23:42.742  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-30 11:23:42.742  5535  5581 I jxcore-log: 
09-30 11:23:42.744  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 11:23:42.744  5535  5581 I jxcore-log: 
,09-30 11:23:42.747  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.747  5535  5581 I jxcore-log: 
09-30 11:23:42.748  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.748  5535  5581 I jxcore-log: 
09-30 11:23:42.748  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.748  5535  5581 I jxcore-log: 
09-30 11:23:42.748  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.748  5535  5581 I jxcore-log: 
,09-30 11:23:42.749  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 11:23:42.749  5535  5581 I jxcore-log: 
09-30 11:23:42.749  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 11:23:42.749  5535  5581 I jxcore-log: 
09-30 11:23:42.749  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.749  5535  5581 I jxcore-log: 
09-30 11:23:42.749  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.749  5535  5581 I jxcore-log: 
09-30 11:23:42.750  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 11:23:42.750  5535  5581 I jxcore-log: 
09-30 11:23:42.750  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 11:23:42.750  5535  5581 I jxcore-log: 
,09-30 11:23:42.750  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 11:23:42.750  5535  5581 I jxcore-log: 
09-30 11:23:42.750  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.750  5535  5581 I jxcore-log: 
09-30 11:23:42.750  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.750  5535  5581 I jxcore-log: 
09-30 11:23:42.751  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.751  5535  5581 I jxcore-log: 
09-30 11:23:42.751  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.751  5535  5581 I jxcore-log: 
09-30 11:23:42.751  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.751  5535  5581 I jxcore-log: 
09-30 11:23:42.751  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.751  5535  5581 I jxcore-log: 
09-30 11:23:42.751  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.751  5535  5581 I jxcore-log: 
09-30 11:23:42.752  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.752  5535  5581 I jxcore-log: 
09-30 11:23:42.752  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.752  5535  5581 I jxcore-log: 
09-30 11:23:42.752  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.752  5535  5581 I jxcore-log: 
09-30 11:23:42.752  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.752  5535  5581 I jxcore-log: 
09-30 11:23:42.753  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.753  5535  5581 I jxcore-log: 
,09-30 11:23:42.753  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.753  5535  5581 I jxcore-log: 
09-30 11:23:42.753  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.753  5535  5581 I jxcore-log: 
09-30 11:23:42.753  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.753  5535  5581 I jxcore-log: 
09-30 11:23:42.754  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.754  5535  5581 I jxcore-log: 
09-30 11:23:42.754  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.754  5535  5581 I jxcore-log: 
09-30 11:23:42.754  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.754  5535  5581 I jxcore-log: 
09-30 11:23:42.754  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.754  5535  5581 I jxcore-log: 
,09-30 11:23:42.755  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.755  5535  5581 I jxcore-log: 
09-30 11:23:42.755  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.755  5535  5581 I jxcore-log: 
09-30 11:23:42.755  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.755  5535  5581 I jxcore-log: 
09-30 11:23:42.755  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.755  5535  5581 I jxcore-log: 
09-30 11:23:42.756  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.756  5535  5581 I jxcore-log: 
09-30 11:23:42.756  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.756  5535  5581 I jxcore-log: 
,09-30 11:23:42.757  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.757  5535  5581 I jxcore-log: 
09-30 11:23:42.757  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.757  5535  5581 I jxcore-log: 
09-30 11:23:42.757  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 11:23:42.757  5535  5581 I jxcore-log: 
09-30 11:23:42.757  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.757  5535  5581 I jxcore-log: 
09-30 11:23:42.757  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 11:23:42.757  5535  5581 I jxcore-log: 
09-30 11:23:42.758  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.758  5535  5581 I jxcore-log: 
09-30 11:23:42.758  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.758  5535  5581 I jxcore-log: 
09-30 11:23:42.758  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.758  5535  5581 I jxcore-log: 
,09-30 11:23:42.758  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.758  5535  5581 I jxcore-log: 
09-30 11:23:42.759  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.759  5535  5581 I jxcore-log: 
09-30 11:23:42.759  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 11:23:42.759  5535  5581 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-30 11:23:42.759  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.759  5535  5581 I jxcore-log: 
09-30 11:23:42.759  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.759  5535  5581 I jxcore-log: 
09-30 11:23:42.759  5535  5581 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-30 11:23:42.759  5535  5581 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-30 11:23:42.760  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 11:23:42.760  5535  5581 I jxcore-log: 
09-30 11:23:42.760  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 11:23:42.760  5535  5581 I jxcore-log: 
09-30 11:23:42.760  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 11:23:42.760  5535  5581 I jxcore-log: 
09-30 11:23:42.760  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 11:23:42.760  5535  5581 I jxcore-log: 
09-30 11:23:42.764  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 11:23:42.764  5535  5581 I jxcore-log: 
09-30 11:23:42.765  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - WARN testUtils: 'myNameCallback not set!'
09-30 11:23:42.765  5535  5581 I jxcore-log: 
09-30 11:23:42.767  5535  5581 I jxcore-log: 2016-09-30 15:23:42 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 11:23:42.767  5535  5581 I jxcore-log: 
,09-30 11:23:42.772  5535  5535 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-30 11:23:43.412  5535  5581 I jxcore-log: 2016-09-30 15:23:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 11:23:43.412  5535  5581 I jxcore-log: 
,09-30 11:23:43.531  5535  5581 I jxcore-log: 2016-09-30 15:23:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 11:23:43.531  5535  5581 I jxcore-log: 
,09-30 11:23:43.540  5535  5581 I jxcore-log: 2016-09-30 15:23:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 11:23:43.540  5535  5581 I jxcore-log: 
,09-30 11:23:43.946  5535  5581 I jxcore-log: 2016-09-30 15:23:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 11:23:43.946  5535  5581 I jxcore-log: 
,09-30 11:23:44.040  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 11:23:44.040  5535  5581 I jxcore-log: 
,09-30 11:23:44.043  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 11:23:44.043  5535  5581 I jxcore-log: 
,09-30 11:23:44.047  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 11:23:44.047  5535  5581 I jxcore-log: 
,09-30 11:23:44.418  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 11:23:44.418  5535  5581 I jxcore-log: 
,09-30 11:23:44.460  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 11:23:44.460  5535  5581 I jxcore-log: 
,09-30 11:23:44.468  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 11:23:44.468  5535  5581 I jxcore-log: 
,09-30 11:23:44.471  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 11:23:44.471  5535  5581 I jxcore-log: 
,09-30 11:23:44.647  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 11:23:44.647  5535  5581 I jxcore-log: 
,09-30 11:23:44.693  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 11:23:44.693  5535  5581 I jxcore-log: 
,09-30 11:23:44.782  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 11:23:44.782  5535  5581 I jxcore-log: 
,09-30 11:23:44.788  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 11:23:44.788  5535  5581 I jxcore-log: 
,09-30 11:23:44.790  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 11:23:44.790  5535  5581 I jxcore-log: 
,09-30 11:23:44.794  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 11:23:44.794  5535  5581 I jxcore-log: 
,09-30 11:23:44.797  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 11:23:44.797  5535  5581 I jxcore-log: 
,09-30 11:23:44.818  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 11:23:44.818  5535  5581 I jxcore-log: 
,09-30 11:23:44.836  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 11:23:44.836  5535  5581 I jxcore-log: 
,09-30 11:23:44.841  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 11:23:44.841  5535  5581 I jxcore-log: 
,09-30 11:23:44.844  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 11:23:44.844  5535  5581 I jxcore-log: 
,09-30 11:23:44.851  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 11:23:44.851  5535  5581 I jxcore-log: 
,09-30 11:23:44.854  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 11:23:44.854  5535  5581 I jxcore-log: 
,09-30 11:23:44.857  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 11:23:44.857  5535  5581 I jxcore-log: 
,09-30 11:23:44.860  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 11:23:44.860  5535  5581 I jxcore-log: 
,09-30 11:23:44.864  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 11:23:44.864  5535  5581 I jxcore-log: 
,09-30 11:23:44.876  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 11:23:44.876  5535  5581 I jxcore-log: 
,09-30 11:23:44.883  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 11:23:44.883  5535  5581 I jxcore-log: 
,09-30 11:23:44.891  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 11:23:44.891  5535  5581 I jxcore-log: 
,09-30 11:23:44.898  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 11:23:44.898  5535  5581 I jxcore-log: 
,09-30 11:23:44.903  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 11:23:44.903  5535  5581 I jxcore-log: 
,09-30 11:23:44.909  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 11:23:44.909  5535  5581 I jxcore-log: 
,09-30 11:23:44.911  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 11:23:44.911  5535  5581 I jxcore-log: 
,09-30 11:23:44.923  5535  5581 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 11:23:44.924  5535  5581 I jxcore-log: 2016-09-30 15:23:44 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 11:23:44.924  5535  5581 I jxcore-log: 
,09-30 11:23:44.943  5535  5581 W jxcore-log: Warning: a promise was created in a handler at node.js:898:9 but was not returned from it, see http://goo.gl/rRqMUw
09-30 11:23:44.943  5535  5581 W jxcore-log:     at new Promise (/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:77:14)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at Object.module.exports.hasRequiredHardware (/data/data/com.test.thalitest/files/www/jxcore/lib/testUtils.js:143:10)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at Object.<anonymous> (/data/data/com.test.thalitest/files/www/jxcore/runTests.js:72:11)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at $w._compile (module.js:619:12)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at Object.$w._extensions..js (module.js:649:8)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at $w.load (module.js:440:20)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at Function.$w._load (module.js:405:8)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at $w.require (module.js:475:11)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at require (module.js:493:12)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at /data/data/com.test.thalitest/files/www/jxcore/app.js:76:13
09-30 11:23:44.943  5535  5581 W jxcore-log: From previous event:
09-30 11:23:44.943  5535  5581 W jxcore-log:     at /data/data/com.test.thalitest/files/www/jxcore/app.js:73:12
09-30 11:23:44.943  5535  5581 W jxcore-log:     at Array.reduce (native)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at /data/data/com.test.thalitest/files/www/jxcore/app.js:71:20
09-30 11:23:44.943  5535  5581 W jxcore-log:     at WrapFunction.callback (main.js:54:22)
09-30 11:23:44.943  5535  5581 W jxcore-log:     at JXMobile.ping (main.js:89:30)
09-30 11:23:44.943  5535  5581 W jxcore-log:     
,09-30 11:23:45.050  5535  5581 I jxcore-log: 2016-09-30 15:23:45 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 11:23:45.050  5535  5581 I jxcore-log: 
,09-30 11:23:45.335   929  2876 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 11:23:45.481  5535  5581 I jxcore-log: TAP version 13
09-30 11:23:45.481  5535  5581 I jxcore-log: 
,09-30 11:23:45.484  5535  5581 I jxcore-log: # setup
09-30 11:23:45.484  5535  5581 I jxcore-log: 
,09-30 11:23:46.304  5535  5581 I jxcore-log: # calling createNativeListener directly rejects
09-30 11:23:46.304  5535  5581 I jxcore-log: 
,09-30 11:23:46.685  5535  5581 I jxcore-log: 2016-09-30 15:23:46 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:46.685  5535  5581 I jxcore-log: 
,09-30 11:23:46.693  5535  5581 I jxcore-log: 2016-09-30 15:23:46 - DEBUG createNativeListener: 'listening 38599'
09-30 11:23:46.693  5535  5581 I jxcore-log: 
,09-30 11:23:46.705  5535  5581 I jxcore-log: ok 1 Should throw
09-30 11:23:46.705  5535  5581 I jxcore-log: 
,09-30 11:23:46.709  5535  5581 I jxcore-log: # teardown
09-30 11:23:46.709  5535  5581 I jxcore-log: 
,09-30 11:23:47.008  5535  5581 I jxcore-log: # setup
09-30 11:23:47.008  5535  5581 I jxcore-log: 
,09-30 11:23:47.913  5535  5581 I jxcore-log: # emits incomingConnectionState
09-30 11:23:47.913  5535  5581 I jxcore-log: 
,09-30 11:23:48.830  5535  5581 I jxcore-log: 2016-09-30 15:23:48 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:48.830  5535  5581 I jxcore-log: 
,09-30 11:23:48.837  5535  5581 I jxcore-log: 2016-09-30 15:23:48 - DEBUG createNativeListener: 'listening 49450'
09-30 11:23:48.837  5535  5581 I jxcore-log: 
,09-30 11:23:48.851  5535  5581 I jxcore-log: 2016-09-30 15:23:48 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:48.851  5535  5581 I jxcore-log: 
,09-30 11:23:48.857  5535  5581 I jxcore-log: 2016-09-30 15:23:48 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:48.857  5535  5581 I jxcore-log: 
,09-30 11:23:48.866  5535  5581 I jxcore-log: 2016-09-30 15:23:48 - DEBUG createNativeListener: 'new mux'
09-30 11:23:48.866  5535  5581 I jxcore-log: 
,09-30 11:23:48.874  5535  5581 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-30 11:23:48.874  5535  5581 I jxcore-log: 
,09-30 11:23:48.896  5535  5581 I jxcore-log: 2016-09-30 15:23:48 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:48.896  5535  5581 I jxcore-log: 
,09-30 11:23:48.897  5535  5581 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-30 11:23:48.897  5535  5581 I jxcore-log: 
,09-30 11:23:48.904  5535  5581 I jxcore-log: # teardown
09-30 11:23:48.904  5535  5581 I jxcore-log: 
,09-30 11:23:49.245  5535  5581 I jxcore-log: # setup
09-30 11:23:49.245  5535  5581 I jxcore-log: 
,09-30 11:23:49.440  5535  5581 I jxcore-log: # emits routerPortConnectionFailed
09-30 11:23:49.440  5535  5581 I jxcore-log: 
,09-30 11:23:50.370  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:50.370  5535  5581 I jxcore-log: 
,09-30 11:23:50.375  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'listening 45199'
09-30 11:23:50.375  5535  5581 I jxcore-log: 
,09-30 11:23:50.384  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:50.384  5535  5581 I jxcore-log: 
,09-30 11:23:50.386  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:50.386  5535  5581 I jxcore-log: 
,09-30 11:23:50.391  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'new mux'
09-30 11:23:50.391  5535  5581 I jxcore-log: 
,09-30 11:23:50.422  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:50.422  5535  5581 I jxcore-log: 
,09-30 11:23:50.426  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:50.426  5535  5581 I jxcore-log: 
,09-30 11:23:50.431  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
09-30 11:23:50.431  5535  5581 I jxcore-log:     at $c (net.js:837:7)
09-30 11:23:50.431  5535  5581 I jxcore-log:     at Object.$09 [as oncomplete] (net.js:829:13)'
09-30 11:23:50.431  5535  5581 I jxcore-log: 
,09-30 11:23:50.432  5535  5581 I jxcore-log: ok 4 tried to connect to right port
09-30 11:23:50.432  5535  5581 I jxcore-log: 
09-30 11:23:50.432  5535  5581 I jxcore-log: ok 5 failed due to refused connection
09-30 11:23:50.432  5535  5581 I jxcore-log: 
09-30 11:23:50.432  5535  5581 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-30 11:23:50.432  5535  5581 I jxcore-log: 
,09-30 11:23:50.436  5535  5581 I jxcore-log: # teardown
09-30 11:23:50.436  5535  5581 I jxcore-log: 
,09-30 11:23:50.438  5535  5581 I jxcore-log: 2016-09-30 15:23:50 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:50.438  5535  5581 I jxcore-log: 
,09-30 11:23:51.094  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'mux close'
09-30 11:23:51.094  5535  5581 I jxcore-log: 
,09-30 11:23:51.102  5535  5581 I jxcore-log: # setup
09-30 11:23:51.102  5535  5581 I jxcore-log: 
,09-30 11:23:51.106  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:51.106  5535  5581 I jxcore-log: 
,09-30 11:23:51.706  5535  5581 I jxcore-log: # native server connections all up
09-30 11:23:51.706  5535  5581 I jxcore-log: 
,09-30 11:23:51.907  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:51.907  5535  5581 I jxcore-log: 
,09-30 11:23:51.916  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'listening 39292'
09-30 11:23:51.916  5535  5581 I jxcore-log: 
,09-30 11:23:51.925  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:51.925  5535  5581 I jxcore-log: 
,09-30 11:23:51.930  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:51.930  5535  5581 I jxcore-log: 
,09-30 11:23:51.931  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'new mux'
09-30 11:23:51.931  5535  5581 I jxcore-log: 
,09-30 11:23:51.976  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:51.976  5535  5581 I jxcore-log: 
,09-30 11:23:51.979  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:51.979  5535  5581 I jxcore-log: 
,09-30 11:23:51.980  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:51.980  5535  5581 I jxcore-log: 
,09-30 11:23:51.983  5535  5581 I jxcore-log: 2016-09-30 15:23:51 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:51.983  5535  5581 I jxcore-log: 
,09-30 11:23:52.003  5535  5581 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-30 11:23:52.003  5535  5581 I jxcore-log: 
,09-30 11:23:52.004  5535  5581 I jxcore-log: ok 8 Send/recvd #1 should be same
09-30 11:23:52.004  5535  5581 I jxcore-log: 
09-30 11:23:52.005  5535  5581 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-30 11:23:52.005  5535  5581 I jxcore-log: 
09-30 11:23:52.005  5535  5581 I jxcore-log: ok 10 Send/recvd #2 should be same
09-30 11:23:52.005  5535  5581 I jxcore-log: 
09-30 11:23:52.005  5535  5581 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-30 11:23:52.005  5535  5581 I jxcore-log: 
,09-30 11:23:52.010  5535  5581 I jxcore-log: # teardown
09-30 11:23:52.010  5535  5581 I jxcore-log: 
,09-30 11:23:53.033  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:53.033  5535  5581 I jxcore-log: 
,09-30 11:23:53.036  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:53.036  5535  5581 I jxcore-log: 
,09-30 11:23:53.039  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'mux close'
09-30 11:23:53.039  5535  5581 I jxcore-log: 
,09-30 11:23:53.054  5535  5581 I jxcore-log: # setup
09-30 11:23:53.054  5535  5581 I jxcore-log: 
,09-30 11:23:53.055  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:53.055  5535  5581 I jxcore-log: 
,09-30 11:23:53.142  5535  5581 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-30 11:23:53.142  5535  5581 I jxcore-log: 
,09-30 11:23:53.256  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:53.256  5535  5581 I jxcore-log: 
,09-30 11:23:53.258  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'listening 40923'
09-30 11:23:53.258  5535  5581 I jxcore-log: 
,09-30 11:23:53.263  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:53.263  5535  5581 I jxcore-log: 
,09-30 11:23:53.263  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:53.263  5535  5581 I jxcore-log: 
,09-30 11:23:53.264  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new mux'
09-30 11:23:53.264  5535  5581 I jxcore-log: 
,09-30 11:23:53.269  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:53.269  5535  5581 I jxcore-log: 
,09-30 11:23:53.270  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:53.270  5535  5581 I jxcore-log: 
,09-30 11:23:53.283  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:53.283  5535  5581 I jxcore-log: 
,09-30 11:23:53.290  5535  5581 I jxcore-log: ok 12 socket shouldn't close until after stream
09-30 11:23:53.290  5535  5581 I jxcore-log: 
,09-30 11:23:53.291  5535  5581 I jxcore-log: ok 13 incoming remains open
09-30 11:23:53.291  5535  5581 I jxcore-log: 
,09-30 11:23:53.293  5535  5581 I jxcore-log: # teardown
09-30 11:23:53.293  5535  5581 I jxcore-log: 
,09-30 11:23:53.312  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'mux close'
09-30 11:23:53.312  5535  5581 I jxcore-log: 
,09-30 11:23:53.314  5535  5581 I jxcore-log: # setup
09-30 11:23:53.314  5535  5581 I jxcore-log: 
,09-30 11:23:53.316  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:53.316  5535  5581 I jxcore-log: 
,09-30 11:23:53.380  5535  5581 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-30 11:23:53.380  5535  5581 I jxcore-log: 
,09-30 11:23:53.410  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:53.410  5535  5581 I jxcore-log: 
,09-30 11:23:53.414  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'listening 44938'
09-30 11:23:53.414  5535  5581 I jxcore-log: 
,09-30 11:23:53.421  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:53.421  5535  5581 I jxcore-log: 
,09-30 11:23:53.422  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:53.422  5535  5581 I jxcore-log: 
,09-30 11:23:53.423  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new mux'
09-30 11:23:53.423  5535  5581 I jxcore-log: 
,09-30 11:23:53.430  5535  5581 I jxcore-log: ok 14 we should not have gotten an error
09-30 11:23:53.430  5535  5581 I jxcore-log: 
,09-30 11:23:53.433  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:53.433  5535  5581 I jxcore-log: 
,09-30 11:23:53.435  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:53.435  5535  5581 I jxcore-log: 
,09-30 11:23:53.441  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:53.441  5535  5581 I jxcore-log: 
,09-30 11:23:53.442  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:53.442  5535  5581 I jxcore-log: 
,09-30 11:23:53.446  5535  5581 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-30 11:23:53.446  5535  5581 I jxcore-log: 
,09-30 11:23:53.447  5535  5581 I jxcore-log: ok 16 incoming is cleaned up
09-30 11:23:53.447  5535  5581 I jxcore-log: 
,09-30 11:23:53.450  5535  5581 I jxcore-log: # teardown
09-30 11:23:53.450  5535  5581 I jxcore-log: 
,09-30 11:23:53.520  5535  5581 I jxcore-log: # setup
09-30 11:23:53.520  5535  5581 I jxcore-log: 
,09-30 11:23:53.563  5535  5581 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-30 11:23:53.563  5535  5581 I jxcore-log: 
,09-30 11:23:53.612  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:53.612  5535  5581 I jxcore-log: 
,09-30 11:23:53.616  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'listening 39743'
09-30 11:23:53.616  5535  5581 I jxcore-log: 
,09-30 11:23:53.622  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:53.622  5535  5581 I jxcore-log: 
,09-30 11:23:53.623  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:53.623  5535  5581 I jxcore-log: 
,09-30 11:23:53.624  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new mux'
09-30 11:23:53.624  5535  5581 I jxcore-log: 
,09-30 11:23:53.632  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:53.632  5535  5581 I jxcore-log: 
,09-30 11:23:53.635  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:53.635  5535  5581 I jxcore-log: 
,09-30 11:23:53.644  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:53.644  5535  5581 I jxcore-log: 
,09-30 11:23:53.651  5535  5581 I jxcore-log: ok 17 stream was closed
09-30 11:23:53.651  5535  5581 I jxcore-log: 
,09-30 11:23:53.651  5535  5581 I jxcore-log: ok 18 incoming should survive
09-30 11:23:53.651  5535  5581 I jxcore-log: 
09-30 11:23:53.651  5535  5581 I jxcore-log: ok 19 mux should have no streams
09-30 11:23:53.651  5535  5581 I jxcore-log: 
,09-30 11:23:53.655  5535  5581 I jxcore-log: # teardown
09-30 11:23:53.655  5535  5581 I jxcore-log: 
,09-30 11:23:53.686  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'mux close'
09-30 11:23:53.686  5535  5581 I jxcore-log: 
,09-30 11:23:53.689  5535  5581 I jxcore-log: # setup
09-30 11:23:53.689  5535  5581 I jxcore-log: 
,09-30 11:23:53.690  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:53.690  5535  5581 I jxcore-log: 
,09-30 11:23:53.763  5535  5581 I jxcore-log: # native server - closing the whole server cleans everything up
09-30 11:23:53.763  5535  5581 I jxcore-log: 
,09-30 11:23:53.830  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:53.830  5535  5581 I jxcore-log: 
,09-30 11:23:53.832  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'listening 43667'
09-30 11:23:53.832  5535  5581 I jxcore-log: 
,09-30 11:23:53.838  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:53.838  5535  5581 I jxcore-log: 
,09-30 11:23:53.839  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:53.839  5535  5581 I jxcore-log: 
,09-30 11:23:53.841  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new mux'
09-30 11:23:53.841  5535  5581 I jxcore-log: 
,09-30 11:23:53.849  5535  5581 I jxcore-log: ok 20 we should not have gotten an error
09-30 11:23:53.849  5535  5581 I jxcore-log: 
,09-30 11:23:53.853  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:53.853  5535  5581 I jxcore-log: 
,09-30 11:23:53.857  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:53.857  5535  5581 I jxcore-log: 
,09-30 11:23:53.865  5535  5581 I jxcore-log: ok 21 Buffers are identical
09-30 11:23:53.865  5535  5581 I jxcore-log: 
,09-30 11:23:53.867  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:53.867  5535  5581 I jxcore-log: 
,09-30 11:23:53.867  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'mux close'
09-30 11:23:53.867  5535  5581 I jxcore-log: 
09-30 11:23:53.869  5535  5581 I jxcore-log: ok 22 native server is nulled out
09-30 11:23:53.869  5535  5581 I jxcore-log: 
09-30 11:23:53.869  5535  5581 I jxcore-log: ok 23 native server should be closed
09-30 11:23:53.869  5535  5581 I jxcore-log: 
09-30 11:23:53.869  5535  5581 I jxcore-log: ok 24 incoming has been removed
09-30 11:23:53.869  5535  5581 I jxcore-log: 
09-30 11:23:53.869  5535  5581 I jxcore-log: ok 25 Incoming should be done
09-30 11:23:53.869  5535  5581 I jxcore-log: 
,09-30 11:23:53.869  5535  5581 I jxcore-log: ok 26 The mux object should be closed
09-30 11:23:53.869  5535  5581 I jxcore-log: 
09-30 11:23:53.870  5535  5581 I jxcore-log: ok 27 The mux stream should be closed
09-30 11:23:53.870  5535  5581 I jxcore-log: 
09-30 11:23:53.870  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:53.870  5535  5581 I jxcore-log: 
,09-30 11:23:53.881  5535  5581 I jxcore-log: # teardown
09-30 11:23:53.881  5535  5581 I jxcore-log: 
,09-30 11:23:53.905  5535  5581 I jxcore-log: # setup
09-30 11:23:53.905  5535  5581 I jxcore-log: 
,09-30 11:23:53.943  5535  5581 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-30 11:23:53.943  5535  5581 I jxcore-log: 
,09-30 11:23:53.974  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:53.974  5535  5581 I jxcore-log: 
,09-30 11:23:53.978  5535  5581 I jxcore-log: 2016-09-30 15:23:53 - DEBUG createNativeListener: 'listening 39527'
09-30 11:23:53.978  5535  5581 I jxcore-log: 
,09-30 11:23:54.006  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.006  5535  5581 I jxcore-log: 
,09-30 11:23:54.007  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.007  5535  5581 I jxcore-log: 
,09-30 11:23:54.008  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.008  5535  5581 I jxcore-log: 
,09-30 11:23:54.011  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.011  5535  5581 I jxcore-log: 
09-30 11:23:54.011  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.011  5535  5581 I jxcore-log: 
09-30 11:23:54.012  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.012  5535  5581 I jxcore-log: 
,09-30 11:23:54.015  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.015  5535  5581 I jxcore-log: 
,09-30 11:23:54.016  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.016  5535  5581 I jxcore-log: 
,09-30 11:23:54.016  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.016  5535  5581 I jxcore-log: 
09-30 11:23:54.018  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.018  5535  5581 I jxcore-log: 
09-30 11:23:54.018  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.018  5535  5581 I jxcore-log: 
09-30 11:23:54.019  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.019  5535  5581 I jxcore-log: 
,09-30 11:23:54.020  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.020  5535  5581 I jxcore-log: 
,09-30 11:23:54.021  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.021  5535  5581 I jxcore-log: 
09-30 11:23:54.022  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.022  5535  5581 I jxcore-log: 
09-30 11:23:54.023  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.023  5535  5581 I jxcore-log: 
09-30 11:23:54.023  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.023  5535  5581 I jxcore-log: 
09-30 11:23:54.023  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.023  5535  5581 I jxcore-log: 
09-30 11:23:54.024  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.024  5535  5581 I jxcore-log: 
09-30 11:23:54.025  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.025  5535  5581 I jxcore-log: 
09-30 11:23:54.025  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.025  5535  5581 I jxcore-log: 
,09-30 11:23:54.026  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.026  5535  5581 I jxcore-log: 
09-30 11:23:54.027  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.027  5535  5581 I jxcore-log: 
,09-30 11:23:54.028  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.028  5535  5581 I jxcore-log: 
,09-30 11:23:54.029  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.029  5535  5581 I jxcore-log: 
,09-30 11:23:54.029  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.029  5535  5581 I jxcore-log: 
,09-30 11:23:54.031  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.031  5535  5581 I jxcore-log: 
09-30 11:23:54.032  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:54.032  5535  5581 I jxcore-log: 
09-30 11:23:54.032  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:54.032  5535  5581 I jxcore-log: 
09-30 11:23:54.033  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new mux'
09-30 11:23:54.033  5535  5581 I jxcore-log: 
,09-30 11:23:54.085  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.085  5535  5581 I jxcore-log: 
,09-30 11:23:54.086  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.086  5535  5581 I jxcore-log: 
,09-30 11:23:54.087  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.087  5535  5581 I jxcore-log: 
,09-30 11:23:54.088  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.088  5535  5581 I jxcore-log: 
09-30 11:23:54.088  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.088  5535  5581 I jxcore-log: 
,09-30 11:23:54.089  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.089  5535  5581 I jxcore-log: 
,09-30 11:23:54.089  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.089  5535  5581 I jxcore-log: 
09-30 11:23:54.090  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.090  5535  5581 I jxcore-log: 
,09-30 11:23:54.090  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.090  5535  5581 I jxcore-log: 
,09-30 11:23:54.093  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.093  5535  5581 I jxcore-log: 
,09-30 11:23:54.094  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.094  5535  5581 I jxcore-log: 
,09-30 11:23:54.094  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.094  5535  5581 I jxcore-log: 
09-30 11:23:54.095  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.095  5535  5581 I jxcore-log: 
,09-30 11:23:54.095  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.095  5535  5581 I jxcore-log: 
09-30 11:23:54.096  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.096  5535  5581 I jxcore-log: 
,09-30 11:23:54.096  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.096  5535  5581 I jxcore-log: 
,09-30 11:23:54.097  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.097  5535  5581 I jxcore-log: 
,09-30 11:23:54.098  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.098  5535  5581 I jxcore-log: 
09-30 11:23:54.098  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.098  5535  5581 I jxcore-log: 
,09-30 11:23:54.098  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.098  5535  5581 I jxcore-log: 
09-30 11:23:54.099  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.099  5535  5581 I jxcore-log: 
,09-30 11:23:54.099  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.099  5535  5581 I jxcore-log: 
09-30 11:23:54.100  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.100  5535  5581 I jxcore-log: 
,09-30 11:23:54.101  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.101  5535  5581 I jxcore-log: 
,09-30 11:23:54.102  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.102  5535  5581 I jxcore-log: 
,09-30 11:23:54.103  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.103  5535  5581 I jxcore-log: 
,09-30 11:23:54.103  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.103  5535  5581 I jxcore-log: 
,09-30 11:23:54.104  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.104  5535  5581 I jxcore-log: 
09-30 11:23:54.104  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.104  5535  5581 I jxcore-log: 
,09-30 11:23:54.108  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.108  5535  5581 I jxcore-log: 
,09-30 11:23:54.109  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.109  5535  5581 I jxcore-log: 
,09-30 11:23:54.112  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.112  5535  5581 I jxcore-log: 
,09-30 11:23:54.112  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.112  5535  5581 I jxcore-log: 
,09-30 11:23:54.113  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.113  5535  5581 I jxcore-log: 
,09-30 11:23:54.113  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.113  5535  5581 I jxcore-log: 
09-30 11:23:54.114  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.114  5535  5581 I jxcore-log: 
,09-30 11:23:54.114  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.114  5535  5581 I jxcore-log: 
09-30 11:23:54.115  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.115  5535  5581 I jxcore-log: 
,09-30 11:23:54.115  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.115  5535  5581 I jxcore-log: 
,09-30 11:23:54.116  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.116  5535  5581 I jxcore-log: 
09-30 11:23:54.116  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.116  5535  5581 I jxcore-log: 
,09-30 11:23:54.117  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.117  5535  5581 I jxcore-log: 
09-30 11:23:54.117  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.117  5535  5581 I jxcore-log: 
,09-30 11:23:54.118  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.118  5535  5581 I jxcore-log: 
09-30 11:23:54.118  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.118  5535  5581 I jxcore-log: 
,09-30 11:23:54.119  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.119  5535  5581 I jxcore-log: 
09-30 11:23:54.119  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.119  5535  5581 I jxcore-log: 
,09-30 11:23:54.119  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.119  5535  5581 I jxcore-log: 
,09-30 11:23:54.120  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.120  5535  5581 I jxcore-log: 
,09-30 11:23:54.120  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.120  5535  5581 I jxcore-log: 
09-30 11:23:54.121  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.121  5535  5581 I jxcore-log: 
,09-30 11:23:54.122  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.122  5535  5581 I jxcore-log: 
,09-30 11:23:54.122  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.122  5535  5581 I jxcore-log: 
,09-30 11:23:54.123  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.123  5535  5581 I jxcore-log: 
09-30 11:23:54.123  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.123  5535  5581 I jxcore-log: 
,09-30 11:23:54.124  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.124  5535  5581 I jxcore-log: 
09-30 11:23:54.124  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.124  5535  5581 I jxcore-log: 
,09-30 11:23:54.125  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.125  5535  5581 I jxcore-log: 
09-30 11:23:54.125  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.125  5535  5581 I jxcore-log: 
,09-30 11:23:54.125  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.125  5535  5581 I jxcore-log: 
09-30 11:23:54.126  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.126  5535  5581 I jxcore-log: 
,09-30 11:23:54.126  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.126  5535  5581 I jxcore-log: 
09-30 11:23:54.127  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.127  5535  5581 I jxcore-log: 
,09-30 11:23:54.127  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.127  5535  5581 I jxcore-log: 
09-30 11:23:54.127  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.127  5535  5581 I jxcore-log: 
,09-30 11:23:54.128  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.128  5535  5581 I jxcore-log: 
,09-30 11:23:54.130  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.130  5535  5581 I jxcore-log: 
,09-30 11:23:54.130  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.130  5535  5581 I jxcore-log: 
09-30 11:23:54.131  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.131  5535  5581 I jxcore-log: 
09-30 11:23:54.131  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.131  5535  5581 I jxcore-log: 
,09-30 11:23:54.131  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.131  5535  5581 I jxcore-log: 
,09-30 11:23:54.133  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.133  5535  5581 I jxcore-log: 
,09-30 11:23:54.134  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.134  5535  5581 I jxcore-log: 
,09-30 11:23:54.135  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.135  5535  5581 I jxcore-log: 
09-30 11:23:54.135  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.135  5535  5581 I jxcore-log: 
09-30 11:23:54.135  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.135  5535  5581 I jxcore-log: 
,09-30 11:23:54.136  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.136  5535  5581 I jxcore-log: 
09-30 11:23:54.136  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.136  5535  5581 I jxcore-log: 
,09-30 11:23:54.137  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:54.137  5535  5581 I jxcore-log: 
09-30 11:23:54.137  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:54.137  5535  5581 I jxcore-log: 
,09-30 11:23:54.173  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.173  5535  5581 I jxcore-log: 
,09-30 11:23:54.173  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.173  5535  5581 I jxcore-log: 
09-30 11:23:54.174  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.174  5535  5581 I jxcore-log: 
09-30 11:23:54.174  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.174  5535  5581 I jxcore-log: 
,09-30 11:23:54.174  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.174  5535  5581 I jxcore-log: 
,09-30 11:23:54.175  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.175  5535  5581 I jxcore-log: 
09-30 11:23:54.175  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.175  5535  5581 I jxcore-log: 
,09-30 11:23:54.175  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.175  5535  5581 I jxcore-log: 
09-30 11:23:54.176  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.176  5535  5581 I jxcore-log: 
09-30 11:23:54.176  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.176  5535  5581 I jxcore-log: 
09-30 11:23:54.176  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.176  5535  5581 I jxcore-log: 
,09-30 11:23:54.177  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.177  5535  5581 I jxcore-log: 
09-30 11:23:54.177  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.177  5535  5581 I jxcore-log: 
09-30 11:23:54.177  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.177  5535  5581 I jxcore-log: 
09-30 11:23:54.177  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.177  5535  5581 I jxcore-log: 
,09-30 11:23:54.178  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.178  5535  5581 I jxcore-log: 
09-30 11:23:54.178  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.178  5535  5581 I jxcore-log: 
09-30 11:23:54.178  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.178  5535  5581 I jxcore-log: 
09-30 11:23:54.178  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.178  5535  5581 I jxcore-log: 
09-30 11:23:54.178  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.178  5535  5581 I jxcore-log: 
09-30 11:23:54.179  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.179  5535  5581 I jxcore-log: 
09-30 11:23:54.179  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.179  5535  5581 I jxcore-log: 
09-30 11:23:54.179  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.179  5535  5581 I jxcore-log: 
09-30 11:23:54.179  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.179  5535  5581 I jxcore-log: 
09-30 11:23:54.180  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.180  5535  5581 I jxcore-log: 
09-30 11:23:54.180  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.180  5535  5581 I jxcore-log: 
09-30 11:23:54.180  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.180  5535  5581 I jxcore-log: 
09-30 11:23:54.181  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.181  5535  5581 I jxcore-log: 
09-30 11:23:54.181  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.181  5535  5581 I jxcore-log: 
09-30 11:23:54.181  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.181  5535  5581 I jxcore-log: 
09-30 11:23:54.181  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.181  5535  5581 I jxcore-log: 
09-30 11:23:54.181  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.181  5535  5581 I jxcore-log: 
09-30 11:23:54.182  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.182  5535  5581 I jxcore-log: 
09-30 11:23:54.182  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.182  5535  5581 I jxcore-log: 
09-30 11:23:54.182  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.182  5535  5581 I jxcore-log: 
09-30 11:23:54.182  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.182  5535  5581 I jxcore-log: 
09-30 11:23:54.183  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.183  5535  5581 I jxcore-log: 
09-30 11:23:54.183  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.183  5535  5581 I jxcore-log: 
09-30 11:23:54.183  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.183  5535  5581 I jxcore-log: 
09-30 11:23:54.186  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.186  5535  5581 I jxcore-log: 
09-30 11:23:54.187  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.187  5535  5581 I jxcore-log: 
09-30 11:23:54.187  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.187  5535  5581 I jxcore-log: 
09-30 11:23:54.187  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.187  5535  5581 I jxcore-log: 
09-30 11:23:54.187  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.187  5535  5581 I jxcore-log: 
09-30 11:23:54.188  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.188  5535  5581 I jxcore-log: 
09-30 11:23:54.188  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.188  5535  5581 I jxcore-log: 
09-30 11:23:54.188  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.188  5535  5581 I jxcore-log: 
09-30 11:23:54.188  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.188  5535  5581 I jxcore-log: 
09-30 11:23:54.188  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:54.188  5535  5581 I jxcore-log: 
09-30 11:23:54.189  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'mux close'
09-30 11:23:54.189  5535  5581 I jxcore-log: 
09-30 11:23:54.190  5535  5581 I jxcore-log: ok 28 native server is nulled out
09-30 11:23:54.190  5535  5581 I jxcore-log: 
09-30 11:23:54.190  5535  5581 I jxcore-log: ok 29 native server should be closed
09-30 11:23:54.190  5535  5581 I jxcore-log: 
09-30 11:23:54.190  5535  5581 I jxcore-log: ok 30 incoming has been removed
09-30 11:23:54.190  5535  5581 I jxcore-log: 
09-30 11:23:54.191  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.191  5535  5581 I jxcore-log: 
09-30 11:23:54.191  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.191  5535  5581 I jxcore-log: 
09-30 11:23:54.191  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.191  5535  5581 I jxcore-log: 
09-30 11:23:54.192  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.192  5535  5581 I jxcore-log: 
09-30 11:23:54.192  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.192  5535  5581 I jxcore-log: 
09-30 11:23:54.192  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.192  5535  5581 I jxcore-log: 
09-30 11:23:54.192  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.192  5535  5581 I jxcore-log: 
09-30 11:23:54.192  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.192  5535  5581 I jxcore-log: 
09-30 11:23:54.192  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.192  5535  5581 I jxcore-log: 
09-30 11:23:54.193  5535  5581 I jxcore-log: 2016-09-30 15:23:54 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:54.193  5535  5581 I jxcore-log: 
,09-30 11:23:54.249  5535  5581 I jxcore-log: # teardown
09-30 11:23:54.249  5535  5581 I jxcore-log: 
,09-30 11:23:54.352  5535  5581 I jxcore-log: # setup
09-30 11:23:54.352  5535  5581 I jxcore-log: 
,09-30 11:23:55.282   929  2874 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 11:23:56.113  5535  5581 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-30 11:23:56.113  5535  5581 I jxcore-log: 
,09-30 11:23:56.141  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:56.141  5535  5581 I jxcore-log: 
,09-30 11:23:56.145  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'listening 42681'
09-30 11:23:56.145  5535  5581 I jxcore-log: 
,09-30 11:23:56.154  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:56.154  5535  5581 I jxcore-log: 
,09-30 11:23:56.157  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:56.157  5535  5581 I jxcore-log: 
,09-30 11:23:56.159  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'new mux'
09-30 11:23:56.159  5535  5581 I jxcore-log: 
,09-30 11:23:56.165  5535  5581 I jxcore-log: ok 31 we should not have gotten an error
09-30 11:23:56.165  5535  5581 I jxcore-log: 
,09-30 11:23:56.169  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:56.169  5535  5581 I jxcore-log: 
,09-30 11:23:56.172  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:56.172  5535  5581 I jxcore-log: 
,09-30 11:23:56.180  5535  5581 I jxcore-log: ok 32 Buffers are identical
09-30 11:23:56.180  5535  5581 I jxcore-log: 
,09-30 11:23:56.181  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:56.181  5535  5581 I jxcore-log: 
09-30 11:23:56.181  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'mux close'
09-30 11:23:56.181  5535  5581 I jxcore-log: 
,09-30 11:23:56.192  5535  5581 I jxcore-log: 2016-09-30 15:23:56 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:56.192  5535  5581 I jxcore-log: 
,09-30 11:23:56.192  5535  5581 I jxcore-log: ok 33 server should be fine
09-30 11:23:56.192  5535  5581 I jxcore-log: 
09-30 11:23:56.193  5535  5581 I jxcore-log: ok 34 server should be open
09-30 11:23:56.193  5535  5581 I jxcore-log: 
09-30 11:23:56.193  5535  5581 I jxcore-log: ok 35 incoming has been removed
09-30 11:23:56.193  5535  5581 I jxcore-log: 
09-30 11:23:56.194  5535  5581 I jxcore-log: ok 36 The mux object should be closed
09-30 11:23:56.194  5535  5581 I jxcore-log: 
,09-30 11:23:56.197  5535  5581 I jxcore-log: ok 37 The mux stream should be closed
09-30 11:23:56.197  5535  5581 I jxcore-log: 
,09-30 11:23:56.210  5535  5581 I jxcore-log: # teardown
09-30 11:23:56.210  5535  5581 I jxcore-log: 
,09-30 11:23:56.262  5535  5581 I jxcore-log: # setup
09-30 11:23:56.262  5535  5581 I jxcore-log: 
,09-30 11:23:57.432  5535  5581 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-30 11:23:57.432  5535  5581 I jxcore-log: 
,09-30 11:23:58.453  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'creating native server'
09-30 11:23:58.453  5535  5581 I jxcore-log: 
,09-30 11:23:58.458  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'listening 41036'
09-30 11:23:58.458  5535  5581 I jxcore-log: 
,09-30 11:23:58.466  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'new incoming socket'
09-30 11:23:58.466  5535  5581 I jxcore-log: 
,09-30 11:23:58.469  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'creating incoming mux'
09-30 11:23:58.469  5535  5581 I jxcore-log: 
,09-30 11:23:58.470  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'new mux'
09-30 11:23:58.470  5535  5581 I jxcore-log: 
09-30 11:23:58.474  5535  5581 I jxcore-log: ok 38 we should not have gotten an error
09-30 11:23:58.474  5535  5581 I jxcore-log: 
,09-30 11:23:58.477  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'new stream: '
09-30 11:23:58.477  5535  5581 I jxcore-log: 
,09-30 11:23:58.481  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'new outgoing socket'
09-30 11:23:58.481  5535  5581 I jxcore-log: 
,09-30 11:23:58.487  5535  5581 I jxcore-log: ok 39 Buffers are identical
09-30 11:23:58.487  5535  5581 I jxcore-log: 
,09-30 11:23:58.492  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'incoming socket timeout'
09-30 11:23:58.492  5535  5581 I jxcore-log: 
,09-30 11:23:58.494  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'stream close:'
09-30 11:23:58.494  5535  5581 I jxcore-log: 
,09-30 11:23:58.505  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'mux close'
09-30 11:23:58.505  5535  5581 I jxcore-log: 
,09-30 11:23:58.508  5535  5581 I jxcore-log: 2016-09-30 15:23:58 - DEBUG createNativeListener: 'incoming socket close'
09-30 11:23:58.508  5535  5581 I jxcore-log: 
,09-30 11:23:58.510  5535  5581 I jxcore-log: ok 40 server should be fine
09-30 11:23:58.510  5535  5581 I jxcore-log: 
,09-30 11:23:58.511  5535  5581 I jxcore-log: ok 41 server should be open
09-30 11:23:58.511  5535  5581 I jxcore-log: 
,09-30 11:23:58.511  5535  5581 I jxcore-log: ok 42 incoming has been removed
09-30 11:23:58.511  5535  5581 I jxcore-log: 
09-30 11:23:58.512  5535  5581 I jxcore-log: ok 43 The mux object should be closed
09-30 11:23:58.512  5535  5581 I jxcore-log: 
,09-30 11:23:58.512  5535  5581 I jxcore-log: ok 44 The mux stream should be closed
09-30 11:23:58.512  5535  5581 I jxcore-log: 
,09-30 11:23:58.521  5535  5581 I jxcore-log: # teardown
09-30 11:23:58.521  5535  5581 I jxcore-log: 
,09-30 11:23:58.643  5535  5581 I jxcore-log: # setup
09-30 11:23:58.643  5535  5581 I jxcore-log: 
,09-30 11:23:59.288  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-30 11:23:59.288  5535  5581 I jxcore-log: 
,09-30 11:23:59.943  5535  5581 I jxcore-log: 2016-09-30 15:23:59 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-30 11:23:59.943  5535  5581 I jxcore-log: 
,09-30 11:23:59.943  5535  5581 I jxcore-log: ok 45 Got right error
09-30 11:23:59.943  5535  5581 I jxcore-log: 
,09-30 11:23:59.947  5535  5581 I jxcore-log: # teardown
09-30 11:23:59.947  5535  5581 I jxcore-log: 
,09-30 11:24:00.315  5535  5581 I jxcore-log: # setup
09-30 11:24:00.315  5535  5581 I jxcore-log: 
,09-30 11:24:00.401   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-30 11:24:00.401   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 11:24:01.128  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-30 11:24:01.128  5535  5581 I jxcore-log: 
,09-30 11:24:02.616  5535  5581 I jxcore-log: 2016-09-30 15:24:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-30 11:24:02.616  5535  5581 I jxcore-log: 
09-30 11:24:02.617  5535  5581 I jxcore-log: ok 46 Got socket hang up
09-30 11:24:02.617  5535  5581 I jxcore-log: 
,09-30 11:24:02.622  5535  5581 I jxcore-log: # teardown
09-30 11:24:02.622  5535  5581 I jxcore-log: 
,09-30 11:24:03.474  5535  5581 I jxcore-log: # setup
09-30 11:24:03.474  5535  5581 I jxcore-log: 
,09-30 11:24:03.880  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-30 11:24:03.880  5535  5581 I jxcore-log: 
,09-30 11:24:04.704  5535  5581 I jxcore-log: 2016-09-30 15:24:04 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-30 11:24:04.704  5535  5581 I jxcore-log: 
,09-30 11:24:04.705  5535  5581 I jxcore-log: ok 47 Got 500 as expected
09-30 11:24:04.705  5535  5581 I jxcore-log: 
,09-30 11:24:04.710  5535  5581 I jxcore-log: # teardown
09-30 11:24:04.710  5535  5581 I jxcore-log: 
,09-30 11:24:05.240  5535  5581 I jxcore-log: # setup
09-30 11:24:05.240  5535  5581 I jxcore-log: 
,09-30 11:24:05.929  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-30 11:24:05.929  5535  5581 I jxcore-log: 
,09-30 11:24:07.345  5535  5581 I jxcore-log: ok 48 should be equal
09-30 11:24:07.345  5535  5581 I jxcore-log: 
,09-30 11:24:07.346  5535  5581 I jxcore-log: ok 49 revs are equal
09-30 11:24:07.346  5535  5581 I jxcore-log: 
,09-30 11:24:07.350  5535  5581 I jxcore-log: # teardown
09-30 11:24:07.350  5535  5581 I jxcore-log: 
,09-30 11:24:07.418  5535  5581 I jxcore-log: # setup
09-30 11:24:07.418  5535  5581 I jxcore-log: 
,09-30 11:24:08.309  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-30 11:24:08.309  5535  5581 I jxcore-log: 
,09-30 11:24:09.356  5535  5581 I jxcore-log: ok 50 should be equal
09-30 11:24:09.356  5535  5581 I jxcore-log: 
09-30 11:24:09.357  5535  5581 I jxcore-log: ok 51 revs are equal
09-30 11:24:09.357  5535  5581 I jxcore-log: 
09-30 11:24:09.360  5535  5581 I jxcore-log: # teardown
09-30 11:24:09.360  5535  5581 I jxcore-log: 
,09-30 11:24:10.089  5535  5581 I jxcore-log: # setup
09-30 11:24:10.089  5535  5581 I jxcore-log: 
,09-30 11:24:11.056  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-30 11:24:11.056  5535  5581 I jxcore-log: 
,09-30 11:24:11.897  5535  5581 I jxcore-log: ok 52 should be equal
09-30 11:24:11.897  5535  5581 I jxcore-log: 
,09-30 11:24:11.898  5535  5581 I jxcore-log: ok 53 revs are equal
09-30 11:24:11.898  5535  5581 I jxcore-log: 
,09-30 11:24:11.998  5535  5581 I jxcore-log: ok 54 should be equal
09-30 11:24:11.998  5535  5581 I jxcore-log: 
,09-30 11:24:11.999  5535  5581 I jxcore-log: ok 55 revs are equal
09-30 11:24:11.999  5535  5581 I jxcore-log: 
,09-30 11:24:12.094  5535  5581 I jxcore-log: ok 56 should be equal
09-30 11:24:12.094  5535  5581 I jxcore-log: 
,09-30 11:24:12.095  5535  5581 I jxcore-log: ok 57 revs are equal
09-30 11:24:12.095  5535  5581 I jxcore-log: 
,09-30 11:24:12.098  5535  5581 I jxcore-log: # teardown
09-30 11:24:12.098  5535  5581 I jxcore-log: 
,09-30 11:24:12.898  5535  5581 I jxcore-log: # setup
09-30 11:24:12.898  5535  5581 I jxcore-log: 
,09-30 11:24:13.710  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-30 11:24:13.710  5535  5581 I jxcore-log: 
,09-30 11:24:14.753  5535  5581 I jxcore-log: 2016-09-30 15:24:14 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-30 11:24:14.753  5535  5581 I jxcore-log: 
,09-30 11:24:14.754  5535  5581 I jxcore-log: ok 58 Our rev is old so we should fail
09-30 11:24:14.754  5535  5581 I jxcore-log: 
09-30 11:24:14.757  5535  5581 I jxcore-log: # teardown
09-30 11:24:14.757  5535  5581 I jxcore-log: 
,09-30 11:24:15.403   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:15.437  5535  5581 I jxcore-log: # setup
09-30 11:24:15.437  5535  5581 I jxcore-log: 
,09-30 11:24:16.156  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-30 11:24:16.156  5535  5581 I jxcore-log: 
,09-30 11:24:16.404   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:16.511  5535  5581 I jxcore-log: ok 59 confirm stop caused failure
09-30 11:24:16.511  5535  5581 I jxcore-log: 
,09-30 11:24:16.518  5535  5581 I jxcore-log: # teardown
09-30 11:24:16.518  5535  5581 I jxcore-log: 
,09-30 11:24:17.118  5535  5581 I jxcore-log: # setup
09-30 11:24:17.118  5535  5581 I jxcore-log: 
,09-30 11:24:17.406   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:17.915  5535  5581 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-30 11:24:17.915  5535  5581 I jxcore-log: 
,09-30 11:24:18.357  5535  5581 I jxcore-log: 2016-09-30 15:24:18 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-30 11:24:18.357  5535  5581 I jxcore-log: 
,09-30 11:24:18.358  5535  5581 I jxcore-log: ok 60 stop caused us to fail
09-30 11:24:18.358  5535  5581 I jxcore-log: 
09-30 11:24:18.358  5535  5581 I jxcore-log: ok 61 We specifically failed on a stop before put
09-30 11:24:18.358  5535  5581 I jxcore-log: 
09-30 11:24:18.361  5535  5581 I jxcore-log: # teardown
09-30 11:24:18.361  5535  5581 I jxcore-log: 
,09-30 11:24:18.407   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:18.498  5535  5581 I jxcore-log: # setup
09-30 11:24:18.498  5535  5581 I jxcore-log: 
,09-30 11:24:18.884  5535  5581 I jxcore-log: # #update - fail if stop is called
09-30 11:24:18.884  5535  5581 I jxcore-log: 
,09-30 11:24:19.300  5535  5581 I jxcore-log: ok 62 failed due to stop
09-30 11:24:19.300  5535  5581 I jxcore-log: 
,09-30 11:24:19.302  5535  5581 I jxcore-log: ok 63 failed due to stop
09-30 11:24:19.302  5535  5581 I jxcore-log: 
,09-30 11:24:19.308  5535  5581 I jxcore-log: # teardown
09-30 11:24:19.308  5535  5581 I jxcore-log: 
,09-30 11:24:19.409   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:19.971  5535  5581 I jxcore-log: # setup
09-30 11:24:19.971  5535  5581 I jxcore-log: 
,09-30 11:24:20.113  5535  5581 I jxcore-log: # #update - set seq for first time
09-30 11:24:20.113  5535  5581 I jxcore-log: 
,09-30 11:24:20.410   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 11:24:21.444  5535  5581 I jxcore-log: ok 64 should be equal
09-30 11:24:21.444  5535  5581 I jxcore-log: 
,09-30 11:24:21.451  5535  5581 I jxcore-log: # teardown
09-30 11:24:21.451  5535  5581 I jxcore-log: 
,09-30 11:24:22.420  5535  5581 I jxcore-log: # setup
09-30 11:24:22.420  5535  5581 I jxcore-log: 
,09-30 11:24:23.345  5535  5581 I jxcore-log: # #update - Fail on bad seq value
09-30 11:24:23.345  5535  5581 I jxcore-log: 
,09-30 11:24:24.350  5535  5581 I jxcore-log: 2016-09-30 15:24:24 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-30 11:24:24.350  5535  5581 I jxcore-log: 
,09-30 11:24:24.351  5535  5581 I jxcore-log: ok 65 Expected bad seq error
09-30 11:24:24.351  5535  5581 I jxcore-log: 
,09-30 11:24:24.384  5535  5581 I jxcore-log: # teardown
09-30 11:24:24.384  5535  5581 I jxcore-log: 
,09-30 11:24:24.881  5535  5581 I jxcore-log: # setup
09-30 11:24:24.881  5535  5581 I jxcore-log: 
,09-30 11:24:25.293  5535  5581 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-30 11:24:25.293  5535  5581 I jxcore-log: 
,09-30 11:24:25.411   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:26.413   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:27.239  5535  5581 I jxcore-log: ok 66 Different promises
09-30 11:24:27.239  5535  5581 I jxcore-log: 
,09-30 11:24:27.241  5535  5581 I jxcore-log: ok 67 Timer was cancelled
09-30 11:24:27.241  5535  5581 I jxcore-log: 
,09-30 11:24:27.356  5535  5581 I jxcore-log: ok 68 should be equal
09-30 11:24:27.356  5535  5581 I jxcore-log: 
,09-30 11:24:27.362  5535  5581 I jxcore-log: # teardown
09-30 11:24:27.362  5535  5581 I jxcore-log: 
,09-30 11:24:27.414   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:27.585  5535  5581 I jxcore-log: # setup
09-30 11:24:27.585  5535  5581 I jxcore-log: 
,09-30 11:24:27.629  5535  5581 I jxcore-log: # #update - do we wait for blocked update
09-30 11:24:27.629  5535  5581 I jxcore-log: 
,09-30 11:24:27.723  5535  5581 I jxcore-log: ok 69 One go and one blocked
09-30 11:24:27.723  5535  5581 I jxcore-log: 
,09-30 11:24:27.723  5535  5581 I jxcore-log: ok 70 All blocked
09-30 11:24:27.723  5535  5581 I jxcore-log: 
09-30 11:24:27.724  5535  5581 I jxcore-log: ok 71 Still blocked
09-30 11:24:27.724  5535  5581 I jxcore-log: 
,09-30 11:24:27.996  5535  5581 I jxcore-log: ok 72 should be equal
09-30 11:24:27.996  5535  5581 I jxcore-log: 
,09-30 11:24:27.999  5535  5581 I jxcore-log: # teardown
09-30 11:24:27.999  5535  5581 I jxcore-log: 
,09-30 11:24:28.113  5535  5581 I jxcore-log: # setup
09-30 11:24:28.113  5535  5581 I jxcore-log: 
,09-30 11:24:28.181  5535  5581 I jxcore-log: # #update - test that we wait long enough
09-30 11:24:28.181  5535  5581 I jxcore-log: 
,09-30 11:24:28.415   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:29.346  5535  5581 I jxcore-log: ok 73 We waited long enough
09-30 11:24:29.346  5535  5581 I jxcore-log: 
,09-30 11:24:29.396  5535  5581 I jxcore-log: ok 74 should be equal
09-30 11:24:29.396  5535  5581 I jxcore-log: 
,09-30 11:24:29.400  5535  5581 I jxcore-log: # teardown
09-30 11:24:29.400  5535  5581 I jxcore-log: 
,09-30 11:24:29.416   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:29.523  5535  5581 I jxcore-log: # setup
09-30 11:24:29.523  5535  5581 I jxcore-log: 
,09-30 11:24:29.567  5535  5581 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-30 11:24:29.567  5535  5581 I jxcore-log: 
,09-30 11:24:29.875  5535  5581 I jxcore-log: ok 75 Should have gotten same timer promise
09-30 11:24:29.875  5535  5581 I jxcore-log: 
,09-30 11:24:29.875  5535  5581 I jxcore-log: ok 76 Still same timer promise
09-30 11:24:29.875  5535  5581 I jxcore-log: 
,09-30 11:24:30.416   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 11:24:30.786  5535  5581 I jxcore-log: ok 77 We waited long enough
09-30 11:24:30.786  5535  5581 I jxcore-log: 
,09-30 11:24:30.844  5535  5581 I jxcore-log: ok 78 should be equal
09-30 11:24:30.844  5535  5581 I jxcore-log: 
,09-30 11:24:30.849  5535  5581 I jxcore-log: # teardown
09-30 11:24:30.849  5535  5581 I jxcore-log: 
,09-30 11:24:30.889  5535  5581 I jxcore-log: # setup
09-30 11:24:30.889  5535  5581 I jxcore-log: 
,09-30 11:24:30.981  5535  5581 I jxcore-log: # Coordinated seq test
09-30 11:24:30.981  5535  5581 I jxcore-log: 
,09-30 11:24:31.105  5535  5581 I jxcore-log: 2016-09-30 15:24:31 - DEBUG thaliWifiInfrastructure: 'listening 41307'
09-30 11:24:31.105  5535  5581 I jxcore-log: 
,09-30 11:24:34.274  5535  5581 I jxcore-log: 2016-09-30 15:24:34 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
09-30 11:24:34.274  5535  5581 I jxcore-log: 
,09-30 11:24:34.284  5535  5581 I jxcore-log: 2016-09-30 15:24:34 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
09-30 11:24:34.284  5535  5581 I jxcore-log: 
,09-30 11:24:35.285   929  2874 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 11:24:35.988  5535  5581 I jxcore-log: ok 79 should be equal
09-30 11:24:35.988  5535  5581 I jxcore-log: 
,09-30 11:24:40.167  5535  5581 I jxcore-log: ok 80 should be equal
09-30 11:24:40.167  5535  5581 I jxcore-log: 
,09-30 11:24:40.176  5535  5581 I jxcore-log: # teardown
09-30 11:24:40.176  5535  5581 I jxcore-log: 
,09-30 11:24:40.418   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:41.420   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:42.421   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:43.422   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:44.424   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:24:45.425   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 11:24:55.287   929  2874 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 11:25:00.426   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:01.427   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:02.429   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:03.430   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:04.431   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:05.432   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 11:25:25.433   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:26.434   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:27.436   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:28.437   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:29.438   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 11:25:30.439   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 11:25:35.293   929  2874 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 11:25:40.201  5535  5581 I jxcore-log: 2016-09-30 15:25:40 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError: timeout exceed while processing test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceed while processing test: 'Coordinated seq test'
09-30 11:25:40.201  5535  5581 I jxcore-log:     at Timer.$9 [as ontimeout] (timers.js:120:4)''
09-30 11:25:40.201  5535  5581 I jxcore-log: 
,09-30 11:25:40.205  5535  5581 I jxcore-log: 2016-09-30 15:25:40 - DEBUG CoordinatedClient: 'test client failed'
09-30 11:25:40.205  5535  5581 I jxcore-log: 
,09-30 11:25:40.217  5535  5581 I jxcore-log: 2016-09-30 15:25:40 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-30 11:25:40.217  5535  5581 I jxcore-log: 
,09-30 11:25:40.221  5535  5581 I jxcore-log: 2016-09-30 15:25:40 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError: timeout exceed while processing test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceed while processing test: 'Coordinated seq test'
09-30 11:25:40.221  5535  5581 I jxcore-log:     at Timer.$9 [as ontimeout] (timers.js:120:4)''
09-30 11:25:40.221  5535  5581 I jxcore-log: 
,09-30 11:25:40.222  5535  5581 I jxcore-log: 2016-09-30 15:25:40 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-30 11:25:40.222  5535  5581 I jxcore-log: 
,09-30 11:25:40.228  5535  5581 E jxcore-log: 
09-30 11:25:40.228  5535  5581 E jxcore-log: main.js:542
09-30 11:25:40.231  5535  5581 E jxcore-log:   Error.captureStackTrace(e);
09-30 11:25:40.231  5535  5581 E jxcore-log: illegal access
,09-30 11:25:40.782  5923  5923 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 11:25:40.787  5923  5923 D AndroidRuntime: CheckJNI is OFF
,09-30 11:25:40.812  5923  5923 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 11:25:40.841  5923  5923 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 11:25:40.857  5923  5923 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 11:25:40.867   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-30 11:25:40.867   929   942 I ActivityManager: Killing 5535:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 11:25:40.967   929  3658 I WindowState: WIN DEATH: Window{57ca6f3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-30 11:25:40.967   929  3024 D GraphicsStats: Buffer count: 2
09-30 11:25:40.967   929  2875 D WifiService: Client connection lost with reason: 4
,09-30 11:25:41.031   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-30 11:25:41.031   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-30 11:25:41.032   929   952 I art     : Starting a blocking GC Explicit
09-30 11:25:41.032   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-30 11:25:41.032   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 11:25:41.032   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:25:41.032   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:25:41.032   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 11:25:41.032   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 11:25:41.035   929   942 I ActivityManager:   Force finishing activity ActivityRecord{4b482e4 u0 com.test.thalitest/.MainActivity t2}
,09-30 11:25:41.045   929  3648 W ActivityManager: Spurious death for ProcessRecord{9883432 0:com.test.thalitest/u0a77}, curProc for 5535: null
,09-30 11:25:41.049   929   947 W WindowManager: Attempted to add application window with unknown token Token{115634d ActivityRecord{4b482e4 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 11:25:41.049   929   947 W WindowManager: Token{115634d ActivityRecord{4b482e4 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{115634d ActivityRecord{4b482e4 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 11:25:41.049   929   947 W WindowManager: view not successfully added to wm, removing view
09-30 11:25:41.050   929   947 W WindowManager: Exception when adding starting window
09-30 11:25:41.050   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{b9c9df5 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 11:25:41.050   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 11:25:41.050   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 11:25:41.050   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 11:25:41.050   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 11:25:41.050   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 11:25:41.050   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:25:41.050   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:25:41.050   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 11:25:41.050   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 11:25:41.126   929   952 I art     : Explicit concurrent mark sweep GC freed 94517(6MB) AllocSpace objects, 51(1876KB) LOS objects, 33% free, 29MB/43MB, paused 1.736ms total 94.152ms
,09-30 11:25:41.148   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 11:25:41.153  5923  5923 I art     : System.exit called, status: 0
,09-30 11:25:41.153  5923  5923 I AndroidRuntime: VM exiting with result code 0.
,09-30 11:25:41.166   929   952 I ActivityManager: Start proc 5934:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-30 11:25:41.167   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 11:25:41.170   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-30 11:25:41.175  5814  5814 D BluetoothMapAppObserver: onReceive
09-30 11:25:41.175  5814  5814 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-30 11:25:41.182   929  2860 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-30 11:25:41.185  3582  3582 I Keyboard.Facilitator: resetDictionaries() : en_US
09-30 11:25:41.189  4033  4092 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-30 11:25:41.210  3582  5946 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 11:25:41.212  3582  5946 I Decoder : createOrResetDecoder
,09-30 11:25:41.237  3292  5949 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-30 11:25:41.241  3690  3690 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 11:25:41.253  3475  3475 I ConfigService: onCreate
,09-30 11:25:41.268   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-30 11:25:41.290  3582  5946 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-30 11:25:41.305  3475  3475 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-30 11:25:41.305  3475  3475 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-30 11:25:41.334  3582  5946 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-30 11:25:41.336  3582  5946 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-30 11:25:41.346  3582  5946 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-30 11:25:41.349  3757  5955 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-30 11:25:41.353  3757  5955 D AccountUtils: Clearing selected account for com.test.thalitest
,09-30 11:25:41.360    28    28 W kworker/1:1: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 11:25:41.363    28    28 W kworker/1:1: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 11:25:41.367    28    28 W kworker/1:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 11:25:41.376  3582  5946 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-30 11:25:41.376  3582  5946 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-30 11:25:41.378  3582  5946 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-30 11:25:41.378  3582  5946 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-30 11:25:41.378  3582  5946 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-30 11:25:41.379  3582  5946 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-30 11:25:41.379  3582  5946 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-30 11:25:41.379  3582  5946 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-30 11:25:41.379  3582  5946 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-30 11:25:41.379  3582  5946 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-30 11:25:41.379  3292  5949 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-30 11:25:41.380  3292  5949 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-30 11:25:41.380  3292  5949 E AndroidRuntime: Process: android.process.acore, PID: 3292
09-30 11:25:41.380  3292  5949 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:25:41.380  3292  5949 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: Can't write: system_app_crash
09-30 11:25:41.385   929  5958 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 11,:25:41.385   929  5958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 11:25:41.385   929  5958 E DropBoxManagerService: 	... 5 more
,09-30 11:25:41.387  3292  5949 I Process : Sending signal. PID: 3292 SIG: 9
,09-30 11:25:41.408  3757  5955 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-30 11:25:41.419  3757  5955 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:25:41.419  3757  5955 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-30 11:25:41.419  3757  5955 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 11:25:41.420  3757  5955 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-30 11:25:41.439  3757  3757 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-30 11:25:41.440  3757  3757 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-30 11:25:41.452  3757  3757 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-30 11:25:41.453  3757  3757 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-30 11:25:41.475  4849  5964 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-30 11:25:41.495   929  3723 I ActivityManager: Start proc 5968:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-30 11:25:41.526  4849  5964 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-30 11:25:41.541   929  3310 I ActivityManager: Start proc 5973:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-30 11:25:41.546  3757  5963 W BaseAppContext: Using Auth Proxy for data requests.
,09-30 11:25:41.554  3757  5963 W BaseAppContext: Using Auth Proxy for data requests.
,09-30 11:25:41.560   929  3309 I ActivityManager: Process android.process.acore (pid 3292) has died
,09-30 11:25:41.561   929  3309 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-30 11:25:41.581  3757  3757 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-30 11:25:41.599  3757  5979 I GMPM-SVC: App measurement is starting up
,09-30 11:25:41.609  3757  5979 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-30 11:25:41.610  3757  5979 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-30 11:25:41.699   929  3648 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3757 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-30 11:25:41.752  3757  5961 W DriveInitializer: Awaiting to be initialized
,09-30 11:25:41.753  3757  5984 W DriveInitializer: Background init thread started

```
