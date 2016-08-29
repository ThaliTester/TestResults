#### Test 82883341eb96f76_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 09:18:45.268   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:18:45.747  5612  5612 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 09:18:45.753  5612  5612 D AndroidRuntime: CheckJNI is OFF
08-29 09:18:45.776  5612  5612 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 09:18:45.806  5612  5612 I Radio-JNI: register_android_hardware_Radio DONE
08-29 09:18:45.821  5612  5612 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 09:18:45.830   928  2878 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 09:18:45.879   928  2878 I ActivityManager: Start proc 5621:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 09:18:45.884  5612  5612 D AndroidRuntime: Shutting down VM
08-29 09:18:45.976  5621  5621 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 09:18:46.005  5621  5621 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 09:18:46.035  5621  5621 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 7778-7797)
08-29 09:18:46.035  5621  5621 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:18:46.054  5621  5621 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9692dbb}
08-29 09:18:46.055  5621  5621 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:18:46.055  5621  5621 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 09:18:46.061  5621  5621 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 09:18:46.062  5621  5621 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 09:18:46.098  5621  5621 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 09:18:46.111  5621  5621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 09:18:46.111  5621  5621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 09:18:46.111  5621  5621 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 09:18:46.111  5621  5621 I Adreno  : Build Date                       : 10/21/15
08-29 09:18:46.111  5621  5621 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 09:18:46.111  5621  5621 I Adreno  : Local Branch                     : 
08-29 09:18:46.111  5621  5621 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 09:18:46.111  5621  5621 I Adreno  : Remote Branch                    : NONE
08-29 09:18:46.111  5621  5621 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 09:18:46.171   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fff5318:true
,08-29 09:18:46.219  5621  5621 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 09:18:46.228  5621  5621 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 09:18:46.255  5621  5658 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 09:18:46.263  5621  5645 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 09:18:46.269   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:18:46.289  5621  5658 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 09:18:46.377   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +455ms (total +527ms)
,08-29 09:18:46.411  5621  5621 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5621
,08-29 09:18:46.501  5621  5621 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 09:18:46.706  5621  5661 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -560461520
,08-29 09:18:46.729  5621  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 09:18:46.729  5621  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 09:18:46.729  5621  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 09:18:46.729  5621  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 09:18:46.729  5621  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 09:18:46.729  5621  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eed5829 added. We now have 1 listener(s)
,08-29 09:18:46.734  5621  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 09:18:46.735  5621  5661 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:18:46.736  5621  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:18:46.737  5621  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 09:18:46.742  5621  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9698dc added. We now have 1 listener(s)
08-29 09:18:46.743  5621  5661 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:18:46.747   928  2917 D WifiService: New client listening to asynchronous messages
,08-29 09:18:46.748  5621  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:18:46.748  5621  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 09:18:46.748  5621  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 09:18:46.748  5621  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 09:18:46.749  5621  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 09:18:46.753  5621  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:18:46.753  5621  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 09:18:46.763  5621  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:18:46.764  5621  5661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:18:46.764  5621  5661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 09:18:46.764  5621  5661 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:18:46.765  5621  5661 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 09:18:46.768  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:18:46.772  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:18:46.793  5621  5621 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 09:18:47.271   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:18:47.345  5621  5630 I art     : Background sticky concurrent mark sweep GC freed 79495(8MB) AllocSpace objects, 19(2MB) LOS objects, 25% free, 24MB/32MB, paused 1.413ms total 327.267ms
,08-29 09:18:47.346  5621  5667 W jxcore-log: Initializing JXcore engine
08-29 09:18:47.346  5621  5667 W jxcore-log: JXcore engine is ready
,08-29 09:18:47.406  5667  5667 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1216 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 09:18:47.406  5667  5667 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[17572]" dev="sockfs" ino=17572 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 09:18:47.406  5667  5667 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 09:18:47.406  5667  5667 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[31557]" dev="sockfs" ino=31557 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 09:18:47.421  5621  5667 W jxcore-log: Starting JXcore engine
,08-29 09:18:47.502  5621  5667 W jxcore-log: Platform android
08-29 09:18:47.502  5621  5667 W jxcore-log: 
,08-29 09:18:47.502  5621  5667 W jxcore-log: Process ARCH arm
08-29 09:18:47.502  5621  5667 W jxcore-log: 
,08-29 09:18:47.597  5621  5667 I jxcore-log: JXcore Cordova bridge is ready!
08-29 09:18:47.597  5621  5667 I jxcore-log: 
,08-29 09:18:47.597  5621  5667 W jxcore-log: JXcore engine is started
,08-29 09:18:47.603  5621  5661 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 09:18:47.607  5621  5621 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 09:18:47.788   928  5190 D NetlinkSocketObserver: NeighborEvent{elapsedMs=169551, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 09:18:48.272   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:18:49.273   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:18:50.274   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:18:54.094  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 09:18:54.094  5621  5667 I jxcore-log: 
,08-29 09:18:54.096  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 09:18:54.096  5621  5667 I jxcore-log: 
,08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:18:54.100  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:18:54.101  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:18:54.103  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 09:18:54.103  5621  5667 I jxcore-log: 
,08-29 09:18:54.104  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 09:18:54.104  5621  5667 I jxcore-log: 
,08-29 09:18:54.459   928  3378 D WifiService: setWifiEnabled: true pid=5621, uid=10077
,08-29 09:18:54.459   928  3378 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 09:18:54.462  5621  5667 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 09:18:54.463  5621  5667 I jxcore-log: Unit Test app is loaded
08-29 09:18:54.463  5621  5667 I jxcore-log: 
,08-29 09:18:54.465  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:18:54.465  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f72e4e added. We now have 2 listener(s)
08-29 09:18:54.466  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:18:54.466  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:18:54.466  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:18:54.467  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:18:54.467  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@caeab6f added. We now have 2 listener(s)
,08-29 09:18:54.467  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:18:54.467  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:18:54.469  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:18:54.472  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:18:54.473  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:54.473  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:18:54.474  5621  5667 D ExecuteNativeTests: Running unit tests
,08-29 09:18:54.476  3590  3590 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 09:18:54.481  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:18:54.489  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:18:54.494  5621  5621 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 09:18:54.509  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:18:54.509  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 added. We now have 3 listener(s)
08-29 09:18:54.509  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:18:54.510  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:18:54.510  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:18:54.510  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:18:54.510  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a added. We now have 3 listener(s)
08-29 09:18:54.510  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:18:54.510  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:18:54.511  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:18:54.514  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:18:54.514  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:54.514  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:18:54.516  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:18:54.516  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 09:18:54.516  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:18:54.516  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:18:54.517  5621  5667 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 09:18:54.517  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:18:54.517  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:18:54.517  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:18:54.517  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 09:18:54.517  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:18:54.517  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:18:54.517  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:18:54.517  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:18:54.517  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:18:54.518  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:54.518  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:18:54.518  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:18:54.518  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 removed from the list
08-29 09:18:54.518  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:18:54.518  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a removed from the list
08-29 09:18:54.518  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:18:54.520  3590  3590 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
08-29 09:18:54.524  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:18:54.525  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:18:54.525  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:18:54.525   928  2914 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 09:18:54.525   928  2914 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 09:18:54.525  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:54.525  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:18:54.525   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:18:54.525   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:18:54.526  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:18:54.526  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:18:54.526  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:18:54.526  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:18:54.526  5621  5667 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 09:18:54.527  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:18:54.527  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:18:54.527  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:18:54.527  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:18:54.527  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:54.527  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:18:54.527  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:18:54.527  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:18:54.527  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:18:54.527  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:18:54.527  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:18:54.527  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:18:54.527  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:54.527  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:18:54.528  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:18:54.528  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:18:54.528  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:18:54.528  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:18:54.530  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:18:54.531  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:18:54.531  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:18:54.531  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:18:54.531  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:18:54.531  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:54.531  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:18:54.531  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:18:54.531  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:18:54.531  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:18:54.531  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:18:54.531  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:54.531  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:18:54.531  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:54.531  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:18:54.532  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:18:54.532  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:18:54.532  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:18:54.532  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:18:54.533  5621  5667 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-29 09:18:54.534  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:18:54.536  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:18:54.537  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:54.537  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:18:54.537  5621  5667 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-29 09:18:54.537  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-29 09:18:54.537  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 09:18:54.537  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 09:18:54.537  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 09:18:54.537  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:18:54.538   928  2914 E native  : do suspend true
08-29 09:18:54.538  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 09:18:54.539  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:18:54.539  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 09:18:54.539  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:18:54.539  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 09:18:54.539  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:18:54.539  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:18:54.540  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:18:54.541  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:18:54.541  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:18:54.542  5621  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:18:54.542  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:18:54.543  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 09:18:54.544  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:18:54.545  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:18:54.545  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:18:54.545  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-29 09:18:54.546  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 09:18:54.546  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:18:54.546  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
08-29 09:18:54.547  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 09:18:54.547  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 09:18:54.547  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 09:18:54.547   928  5191 D DhcpClient: Clearing IP address
08-29 09:18:54.547   506   922 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:18:54.548  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:18:54.550   506   922 D CommandListener: Setting iface cfg
08-29 09:18:54.550  4347  4361 D BtGatt.GattService: registerClient() - UUID=3fd79e9e-4686-4aad-8f46-7445d1d15833
08-29 09:18:54.551  4347  4409 D BtGatt.GattService: onClientRegistered() - UUID=3fd79e9e-4686-4aad-8f46-7445d1d15833, clientIf=5
08-29 09:18:54.552  5621  5632 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-29 09:18:54.553  4347  4420 D BtGatt.AdvertiseManager: message : 0
08-29 09:18:54.556  4347  4420 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 09:18:54.558  3538  5245 V NativeCrypto: Read error: ssl=0x7f67189d00: I/O error during system call, Connection timed out
08-29 09:18:54.558   928  5192 D DhcpClient: Receive thread stopped
08-29 09:18:54.560  3538  5245 V NativeCrypto: SSL shutdown failed: ssl=0x7f67189d00: I/O error during system call, Broken pipe
08-29 09:18:54.562   928   938 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 09:18:54.563   928  5189 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 09:18:54.566   928  2914 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 09:18:54.569   928  5189 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 09:18:54.570   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 09:18:54.570   544   544 E Parcel  : Reading a NULL string not supported here.
08-29 09:18:54.570   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 09:18:54.570   928  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 09:18:54.572   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 09:18:54.573   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:18:54.574   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 09:18:54.573   928  2914 E native  : do suspend true
08-29 09:18:54.580  4347  4409 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
08-29 09:18:54.580   928  2918 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 09:18:54.582  3424  3546 W QCNEJ   : |CORE| network lost: 100
08-29 09:18:54.582  3424  3546 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 09:18:54.590  4347  4409 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
08-29 09:18:54.591  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 09:18:54.591  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:18:54.592  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:18:54.593  5621  5667 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:18:54.593  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 09:18:54.593  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 09:18:54.594  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 09:18:54.594  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 09:18:54.594  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 09:18:54.594  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-29 09:18:54.596  5621  5621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 09:18:54.597  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 09:18:54.608   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:18:54.625   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:18:54.626   506   922 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:18:54.626   506   922 D TetherController: Setting IP forward enable = 0
08-29 09:18:54.626   928  2918 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 09:18:54.627   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:18:54.631  5081  5081 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7d1e544 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 09:18:54.631   928   945 D Tethering: MasterInitialState.processMessage what=3
,08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:18:54.635  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:18:54.638  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:18:54.642  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:18:54.642   928  2914 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 09:18:54.644  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:18:54.647  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 09:18:54.648  4814  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 09:18:54.648  4814  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 09:18:54.648  4814  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 09:18:54.648  4814  4848 E SarControlService: no key has been found,reset the power
08-29 09:18:54.649  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 09:18:54.649  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:18:54.649  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:18:54.649  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 09:18:54.649  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:18:54.649  4855  4855 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 09:18:54.650  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 09:18:54.650  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 09:18:54.650  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 09:18:54.651  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:18:54.653  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:18:54.653  4855  4855 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 09:18:54.656  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000ea03000000000000ffffffff]
08-29 09:18:54.656  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,08-29 09:18:54.656  4855  4869 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 09:18:54.656  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:18:54.657  4814  4826 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 09:18:54.657  3815  3815 D SystemUpdateService: onCreate
08-29 09:18:54.660  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000eb03000000000000ffffffff]
08-29 09:18:54.661  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:18:54.661  4855  4869 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
08-29 09:18:54.661  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:18:54.661  4814  4824 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 09:18:54.662  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:18:54.670  3815  5685 I SystemUpdateService: active receiver: enabled
,08-29 09:18:54.671  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 09:18:54.676  3815  5215 I iu.UploadsManager: num queued entries: 0
,08-29 09:18:54.676  3815  5215 I iu.UploadsManager: num updated entries: 0
,08-29 09:18:54.679  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:18:54.681  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 09:18:54.683  3815  5685 I SystemUpdateService: showing system update notification
,08-29 09:18:54.684  3815  5215 I iu.SyncManager: NEXT; no task
,08-29 09:18:54.692   928  3511 I ActivityManager: Start proc 5687:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 09:18:54.701  3815  5685 V SystemUpdateService: retry (wakeup: false) in 3599970 ms
,08-29 09:18:54.705  3815  3815 D SystemUpdateService: onDestroy
,08-29 09:18:54.722  5687  5687 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 09:18:54.725  5687  5687 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:18:54.730  5687  5687 D SprintDMHelper: simOperator: 
,08-29 09:18:54.730  5687  5687 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:18:54.744   928  2878 I ActivityManager: Start proc 5699:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 09:18:54.744   928  2878 I ActivityManager: Killing 4904:com.google.android.deskclock/u0a66 (adj 15): empty #17
,08-29 09:18:54.814  4165  5713 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 09:18:54.827   928  3377 I ActivityManager: Killing 5268:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-29 09:18:55.098  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 09:18:55.099  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 09:18:55.099  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 09:18:55.724   506   922 E Netd    : netlink response contains error (No such file or directory)
,08-29 09:18:55.725   928  2918 E NetdConnector: NDC Command {52 network destroy 100} took too long (1097ms)
08-29 09:18:55.726   928  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 09:18:55.728   928  2888 E NetdConnector: NDC Command {53 bandwidth setglobalalert 2097152} took too long (1093ms)
,08-29 09:18:55.728   506   922 D TetherController: Setting IP forward enable = 0
,08-29 09:18:58.351   928  2914 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=75.00 rxSuccessRate=77.50 delta 1000 -> 1
08-29 09:18:58.352   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
08-29 09:18:58.352   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 09:18:58.378   928  2914 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:18:58.395   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 09:18:58.397  3590  3590 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 09:18:58.968  3590  3590 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 09:18:59.023  3590  3590 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:18:59.024  3590  3590 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 09:18:59.039   928  2914 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:18:59.039   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:18:59.039   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 09:18:59.054   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:18:59.066   506   922 D CommandListener: Setting iface cfg
,08-29 09:18:59.067   928  2914 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 09:18:59.077   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 09:18:59.089   928  5723 D DhcpClient: Receive thread started
,08-29 09:18:59.173   928  2914 E native  : do suspend false
,08-29 09:18:59.185   928  5191 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 09:18:59.598  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:18:59.598  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 09:18:59.598  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:18:59.598  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 09:18:59.598  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 09:18:59.598  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 09:18:59.599  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 09:18:59.599  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:18:59.599  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:18:59.599  5621  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 09:18:59.600  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 09:18:59.600  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:18:59.600  5621  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:18:59.600  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:18:59.600  5621  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 09:18:59.600  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:18:59.601  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:18:59.602  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:18:59.603  5621  5667 D BluetoothLeScanner: could not find callback wrapper
,08-29 09:18:59.603  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:18:59.603  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 09:18:59.604  4347  4420 D BtGatt.AdvertiseManager: message : 1
08-29 09:18:59.606  4347  4420 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 09:18:59.619  4347  4409 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-29 09:18:59.620  4347  4409 D BtGatt.GattService: Client app is not null!
08-29 09:18:59.621  4347  4362 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:18:59.622  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:18:59.622  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 09:18:59.622  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-29 09:18:59.622  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 09:18:59.622  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-29 09:18:59.623  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:18:59.624  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:18:59.624  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:18:59.624  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 09:18:59.626  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:18:59.626  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:18:59.626  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:18:59.627  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:18:59.627  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 09:18:59.627  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:18:59.627  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:18:59.627  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:18:59.627  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:18:59.627  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:18:59.627  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:18:59.627  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:18:59.657   928  5723 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172663, domain null
,08-29 09:18:59.658   928  5191 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172663 seconds
,08-29 09:18:59.659   928  5191 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 09:18:59.684   928  5723 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 09:18:59.685   928  5191 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 09:18:59.688   506   922 D CommandListener: Setting iface cfg
,08-29 09:18:59.696   928  5191 D DhcpClient: Scheduling renewal in 86399s
08-29 09:18:59.696   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 09:18:59.698   928  2914 E native  : do suspend true
,08-29 09:18:59.714   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 09:18:59.716   928  2914 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 09:18:59.716   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 09:18:59.721   928  2918 D ConnectivityService: Adding iface wlan0 to network 101
08-29 09:18:59.724   928  2914 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 09:18:59.760   928  2918 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 09:18:59.760   928  2918 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 09:18:59.762   928  2918 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 09:18:59.764   928  2918 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 09:18:59.765   928  2918 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 09:18:59.770   928  2918 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 09:18:59.775   928  2918 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 09:18:59.775   928  2918 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 09:18:59.775   928  2918 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 09:18:59.775   928  2918 D ConnectivityService:    accepting network in place of null
08-29 09:18:59.775   928  2914 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 09:18:59.776   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:18:59.776   928  2918 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:18:59.797   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:18:59.798   928  5722 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181561, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:18:59.815   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:18:59.818   928  2918 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 09:18:59.818   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:18:59.818  3424  3546 W QCNEJ   : |CORE| network available: 101
08-29 09:18:59.819   928  2918 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 09:18:59.819   928   945 D Tethering: MasterInitialState.processMessage what=3
08-29 09:18:59.823  5081  5081 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7d1e544 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 09:18:59.823  3424  3546 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-29 09:18:59.825  3424  3546 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-29 09:18:59.825  3424  3546 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:18:59.828  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:18:59.830  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:18:59.834  4814  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:18:59.834  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:18:59.834  4814  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 09:18:59.834  4814  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 09:18:59.834  4814  4848 E SarControlService: no key has been found,reset the power
08-29 09:18:59.834  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 09:18:59.834  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 09:18:59.835  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 09:18:59.835  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:18:59.835  4855  4855 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,08-29 09:18:59.836  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:18:59.836  5081  5081 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-29 09:18:59.838  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 09:18:59.838  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 09:18:59.838  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 09:18:59.838  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,08-29 09:18:59.838  4855  4855 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 09:18:59.840  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 09:18:59.841  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000ec03000000000000ffffffff]
08-29 09:18:59.841  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:18:59.842  4855  4869 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
08-29 09:18:59.844  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000ed03000000000000ffffffff]
,08-29 09:18:59.844  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:18:59.844  4855  4869 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
08-29 09:18:59.846  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:18:59.846  3815  3815 D SystemUpdateService: onCreate
08-29 09:18:59.849  4814  4826 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 09:18:59.850  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:18:59.850  4814  4824 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 09:18:59.856  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:18:59.865   928  5721 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:815::200e
,08-29 09:18:59.870  3815  5734 I SystemUpdateService: active receiver: enabled
,08-29 09:18:59.888  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 09:18:59.892  3815  5215 I iu.UploadsManager: num queued entries: 0
,08-29 09:18:59.892  3815  5215 I iu.UploadsManager: num updated entries: 0
08-29 09:18:59.893  3815  5215 I iu.SyncManager: NEXT; no task
,08-29 09:18:59.898  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:18:59.899  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 09:18:59.902  5687  5687 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:18:59.904  5687  5687 D SprintDMHelper: simOperator: 
08-29 09:18:59.904  5687  5687 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:18:59.912  3815  5734 I SystemUpdateService: showing system update notification
,08-29 09:18:59.940  3815  5734 V SystemUpdateService: retry (wakeup: false) in 3599931 ms
,08-29 09:18:59.942  3815  3815 D SystemUpdateService: onDestroy
,08-29 09:18:59.950   928  5721 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 13:18:59 GMT], X-Android-Received-Millis=[1472476739949], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472476739908]}
08-29 09:18:59.951   928  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 09:18:59.951   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 09:18:59.951   928  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 09:18:59.952   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 09:19:00.022  4165  5739 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 09:19:00.127  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:19:00.819   928  2918 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 09:19:04.635  5621  5667 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-29 09:19:04.641  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:04.650  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:19:04.653  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:04.653  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:19:04.653  5621  5667 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
08-29 09:19:04.653  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
08-29 09:19:04.654  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 09:19:04.654  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 09:19:04.654  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 09:19:04.654  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:19:04.655  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 09:19:04.656  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:19:04.656  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 09:19:04.656  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:19:04.656  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 09:19:04.656  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:19:04.656  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:19:04.657  5621  5746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:19:04.659  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:04.661  5621  5746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 09:19:04.662  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 09:19:04.662  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:19:04.663  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:04.663  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 09:19:04.666  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:19:04.667  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:19:04.667  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:19:04.669  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 09:19:04.670  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:19:04.670  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
08-29 09:19:04.670  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 09:19:04.670  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 09:19:04.671  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 09:19:04.671  5621  5667 D BluetoothAdapter: STATE_ON
,08-29 09:19:04.674  4347  4614 D BtGatt.GattService: registerClient() - UUID=9093e889-c037-4dfc-bbe6-2ff2ec32c279
,08-29 09:19:04.674  4347  4409 D BtGatt.GattService: onClientRegistered() - UUID=9093e889-c037-4dfc-bbe6-2ff2ec32c279, clientIf=5
08-29 09:19:04.674  5621  5631 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 09:19:04.675  4347  4420 D BtGatt.AdvertiseManager: message : 0
,08-29 09:19:04.677  4347  4420 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 09:19:04.687  4347  4409 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 09:19:04.693  4347  4409 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 09:19:04.694  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 09:19:04.694  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 09:19:04.695  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:19:04.696  5621  5667 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:19:04.696  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 09:19:04.697  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 09:19:04.697  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 09:19:04.697  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 09:19:04.697  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 09:19:04.697  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 09:19:04.699  5621  5621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 09:19:04.700  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 09:19:05.200  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 09:19:05.201  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 09:19:05.201  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 09:19:07.783   928  2918 D ConnectivityService: handlePromptUnvalidated 101
,08-29 09:19:09.703  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:09.703  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 09:19:09.703  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 09:19:09.703  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 09:19:09.704  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 09:19:09.704  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 09:19:09.704  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 09:19:09.704  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:19:09.705  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 09:19:09.705  5621  5746 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 09:19:09.705  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:19:09.705  5621  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:19:09.705  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 09:19:09.705  5621  5746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 09:19:09.705  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:19:09.705  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:19:09.705  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:19:09.708  5621  5667 D BluetoothAdapter: STATE_ON
,08-29 09:19:09.708  5621  5667 D BluetoothLeScanner: could not find callback wrapper
08-29 09:19:09.708  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:19:09.708  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 09:19:09.710  4347  4420 D BtGatt.AdvertiseManager: message : 1
08-29 09:19:09.711  4347  4420 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 09:19:09.727  4347  4409 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-29 09:19:09.727  4347  4409 D BtGatt.GattService: Client app is not null!
08-29 09:19:09.729  4347  4614 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:19:09.729  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:19:09.730  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 09:19:09.730  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-29 09:19:09.730  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 09:19:09.730  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 09:19:09.733  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:19:09.733  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:19:09.733  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:19:09.734  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:19:09.735  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:09.736  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:09.736  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:19:09.736  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 09:19:09.736  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:09.736  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:19:09.736  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:09.736  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:19:09.736  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:09.736  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:19:09.736  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:09.736  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:09.738  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:09.738  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:09.740  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:09.740  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:19:09.740  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:09.740  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:09.741  5621  5667 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:19:09.743  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:09.748  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:19:09.750  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:19:09.750  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:19:09.751  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:19:09.751  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:19:09.751  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:19:09.751  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:19:09.751  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:19:09.754  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:09.755  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:19:09.755  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:19:09.758  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:09.760  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:19:09.761  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:19:09.761  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:19:09.763  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 09:19:09.766  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 09:19:09.766  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:19:09.766  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:19:09.767  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:19:09.768  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:19:09.771  4347  4362 D BtGatt.GattService: registerClient() - UUID=5e223c4f-c910-4ddf-8173-cb41c66076f2
,08-29 09:19:09.771  4347  4409 D BtGatt.GattService: onClientRegistered() - UUID=5e223c4f-c910-4ddf-8173-cb41c66076f2, clientIf=5
,08-29 09:19:09.772  5621  5632 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:19:09.772  4347  4361 D BtGatt.GattService: start scan with filters
08-29 09:19:09.776  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:19:09.776  4347  4424 D BtGatt.ScanManager: handling starting scan
,08-29 09:19:09.778  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:19:09.778  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:19:09.778  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:19:09.780  4347  4424 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
08-29 09:19:09.780  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:19:09.781  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:19:09.781  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:19:09.782  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:19:09.784  5621  5667 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 09:19:09.786  4347  4409 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:19:09.786  4347  4409 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:19:09.786  4347  4424 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 09:19:09.792  4347  4409 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:19:09.793  4347  4409 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:19:09.793  4347  4424 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:19:09.793  4347  4424 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 09:19:09.803  4347  4409 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 09:19:09.803  4347  4409 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:19:09.809  4347  4409 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:19:09.809  4347  4409 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:19:10.275   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:10.282  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 09:19:10.283  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:19:10.283  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 09:19:11.277   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:12.278   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:13.279   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:14.280   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:14.784  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:14.785  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:14.785  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 09:19:14.785  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:14.785  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 09:19:14.786  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:19:14.786  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 09:19:14.786  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:19:14.786  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 09:19:14.786  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 09:19:14.787  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:19:14.789  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:19:14.791  4347  4362 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:19:14.794  4347  4361 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 09:19:14.795  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 09:19:14.796  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:19:14.796  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:19:14.797  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:19:14.798  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:19:14.801  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:19:14.801  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:19:14.801  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:19:14.802  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:19:14.804  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:19:14.806  4347  4347 D BtGatt.ScanManager: awakened up at time 196569
,08-29 09:19:14.808  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:19:14.808  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:19:14.809  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:19:14.812  4347  4409 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:19:14.812  4347  4409 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:19:14.812  4347  4424 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:19:14.819  4347  4409 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 09:19:14.819  4347  4409 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:19:14.820  4347  4424 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 09:19:14.838  4347  4409 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-29 09:19:14.838  4347  4409 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:19:14.838  4347  4409 D BtGatt.GattService: current time is 196601671382
08-29 09:19:14.839  4347  4409 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -82, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -77, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 09:19:14.840  4347  4409 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 09:19:14.840  4347  4409 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 09:19:14.841  4347  4409 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 09:19:14.841  4347  4409 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-29 09:19:14.841  4347  4409 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 09:19:14.841  4347  4409 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 09:19:15.280   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:19:15.309  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:19:15.310  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:19:15.310  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 09:19:16.658   928  5722 D NetlinkSocketObserver: NeighborEvent{elapsedMs=198420, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:19:19.810  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:19.810  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.810  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.810  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.811  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.811  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 09:19:19.811  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.811  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.811  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.811  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:19:19.812  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.813  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:19.813  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.816  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.816  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:19.816  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.816  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
,08-29 09:19:19.820  5621  5667 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 09:19:19.822  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:19.822  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.822  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:19:19.822  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.823  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.823  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.823  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
,08-29 09:19:19.823  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.823  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.823  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:19:19.823  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.824  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.824  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.824  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:19.826  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.827  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:19.827  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.827  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.829  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:19:19.829  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:19:19.829  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.829  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.829  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:19:19.829  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.829  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.830  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.830  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:19.830  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.830  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.830  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.830  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.830  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.830  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.832  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.832  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:19:19.832  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.832  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.833  5621  5667 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 09:19:19.833  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:19:19.833  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.833  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.833  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:19:19.833  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.833  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.834  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.834  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.834  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
,08-29 09:19:19.834  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.834  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.834  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.834  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.834  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:19.836  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.836  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:19:19.836  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.836  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.837  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 09:19:19.837  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:19.837  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.837  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.837  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.837  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.837  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:19.838  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.838  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.838  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.838  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.838  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.838  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.838  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.838  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:19.840  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.840  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:19.840  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.840  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.841  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 09:19:19.841  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:19:19.841  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:19:19.841  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:19:19.841  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:19:19.841  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:19:19.842  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:19:19.842  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:19:19.842  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:19:19.842  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:19.842  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.842  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.842  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.842  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.843  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.843  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.843  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:19.843  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.843  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.843  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.843  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.843  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.843  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.844  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.845  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:19:19.845  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.845  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
,08-29 09:19:19.846  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:19:19.846  5621  5667 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:19:19.846  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 09:19:19.850  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:19:19.850  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 09:19:19.850  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:19:19.851  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:19:19.852  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:19:19.852  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 09:19:19.852  5621  5667 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:19:19.853  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 09:19:19.853  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 09:19:19.853  5621  5667 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:19:19.853  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 09:19:19.853  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:19:19.853  5621  5667 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:19:19.853  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 09:19:19.857  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 09:19:19.857  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 09:19:19.857  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 09:19:19.858  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 09:19:19.858  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-29 09:19:19.858  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 09:19:19.859  5621  5667 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:19:19.859  5621  5667 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 09:19:19.859  5621  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 123)
,08-29 09:19:19.860  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:19:19.860  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.860  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.860  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:19:19.860  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.860  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.860  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 09:19:19.862  5621  5747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:19:19.862  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.862  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.862  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.862  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.862  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.862  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.862  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.862  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.863  5621  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 123
08-29 09:19:19.863  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.863  5621  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 123)
08-29 09:19:19.863  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:19.863  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.863  5621  5748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 123)
08-29 09:19:19.863  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.864  5621  5667 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 09:19:19.864  5621  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 123)
08-29 09:19:19.865  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:19:19.865  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.865  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.865  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.865  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.865  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.865  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.865  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.865  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.865  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.865  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blue,toothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.865  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.865  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.865  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:19.868  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.868  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:19.868  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:19.868  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.869  5621  5667 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 09:19:19.869  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:19:19.869  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.869  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.869  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.869  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.869  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.869  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.869  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:19.869  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.869  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.869  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.869  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.869  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.869  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.870  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.870  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:19.870  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.871  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
,08-29 09:19:19.871  5621  5667 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 09:19:19.871  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 09:19:19.871  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:19:19.871  5621  5667 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 09:19:19.872  5621  5667 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:19:19.872  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 09:19:19.872  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:19:19.872  5621  5667 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 09:19:19.872  5621  5667 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:19:19.872  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:19:19.872  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:19:19.872  5621  5667 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 09:19:19.872  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:19.872  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:19.872  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:19.872  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.872  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.872  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.872  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.872  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.872  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.873  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.873  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.873  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.873  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.873  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.874  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:19.874  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:19.874  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.874  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
,08-29 09:19:19.874  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:19.874  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.874  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:19.874  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:19.875  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:19.875  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:19.875  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:19.875  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:19.875  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:24.875  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:24.876  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.876  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:24.876  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:24.876  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.877  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:24.877  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:19:24.877  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:24.877  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:19:24.878  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:24.878  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.878  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:24.878  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:24.879  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:24.879  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.879  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:19:24.879  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.879  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:24.879  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.880  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:24.883  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:24.883  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:24.883  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:24.883  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.886  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 09:19:24.886  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:19:24.888  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 09:19:24.889  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:19:24.889  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 09:19:24.890  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:19:24.890  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:19:24.890  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 09:19:24.890  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:24.891  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 09:19:24.891  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 09:19:24.891  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 09:19:24.891  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.891  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:19:24.891  5621  5749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:19:24.891  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:24.891  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:19:24.891  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:24.892  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:19:24.892  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:19:24.892  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 09:19:24.892  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.892  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.894  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:19:24.894  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.894  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:24.895  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:24.894  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:19:24.895  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:24.895  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:24.895  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:24.895  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:19:24.895  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.895  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:24.895  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:19:24.895  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:24.895  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.895  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:24.895  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.895  5621  5749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 09:19:24.896  5621  5749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:19:24.896  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.896  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.896  5621  5749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 09:19:24.896  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.896  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 09:19:24.899  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:24.899  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:19:24.899  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:24.899  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.901  5621  5667 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 09:19:24.902  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:19:24.902  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 09:19:24.902  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:19:24.902  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:19:24.902  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:19:24.903  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:24.903  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:19:24.903  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:24.903  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.903  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.903  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:24.903  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:24.903  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.903  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:24.903  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.904  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.904  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:24.904  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.907  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:24.907  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:24.907  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:24.907  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
,08-29 09:19:24.915  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:24.915  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:24.915  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:24.915  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:24.915  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:24.915  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.915  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:24.916  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:24.916  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.916  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:24.916  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.916  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:24.916  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.916  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.918  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:19:24.918  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:24.918  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:24.918  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.920  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:19:24.920  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:19:24.920  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:19:24.921  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:19:24.921  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.921  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.921  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7de6175 not in the list
08-29 09:19:24.921  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:24.921  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.921  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:24.921  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.921  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:24.921  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:24.921  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:24.922  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:19:24.923  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:19:24.923  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:24.923  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df550a not in the list
08-29 09:19:24.924  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 09:19:24.924  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:19:24.924  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 09:19:24.924  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-29 09:19:24.924  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 09:19:24.924  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:19:24.926  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:19:24.926  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 09:19:24.927  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 09:19:24.927  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:19:24.927  5621  5667 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 09:19:24.927  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:19:24.927  5621  5667 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 09:19:24.927  5621  5667 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 09:19:24.928  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-29 09:19:24.928  5621  5667 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 09:19:24.929  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 09:19:24.929  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 09:19:24.929  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-29 09:19:24.929  5621  5667 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 09:19:24.930  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:19:24.930  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2726cdc added. We now have 3 listener(s)
08-29 09:19:24.930  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:19:24.932  5621  5667 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 09:19:24.933   928  3511 D WifiService: setWifiEnabled: true pid=5621, uid=10077
08-29 09:19:24.933   928  3511 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:19:24.991  4347  4576 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-29 09:19:24.991  4347  4579 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,08-29 09:19:25.395  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:19:29.938  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:19:29.938  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60b91e5 added. We now have 4 listener(s)
08-29 09:19:29.939  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:19:29.948  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:29.948  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60b91e5 removed from the list
,08-29 09:19:29.948  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:29.949  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:29.949  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:29.950  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:19:29.951  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57f14ba added. We now have 4 listener(s)
08-29 09:19:29.951  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:19:29.954  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:29.954  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@57f14ba removed from the list
,08-29 09:19:29.954  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:29.954  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:19:29.955  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:29.957  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:19:29.958  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@148af6b added. We now have 4 listener(s)
,08-29 09:19:29.958  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:19:29.964   928  3378 D WifiService: setWifiEnabled: false pid=5621, uid=10077
08-29 09:19:29.964   928  3378 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:19:29.975   928  2914 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 09:19:29.976   928  2914 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 09:19:29.976   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:19:29.976   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:19:29.978  4347  4405 D BluetoothAdapterState: Current state: ON, message: 23
08-29 09:19:29.978  4347  4405 D BluetoothAdapterProperties: Setting state to 13
08-29 09:19:29.978  4347  4405 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 09:19:29.979  4347  4405 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 09:19:29.980  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:19:29.981  4347  4405 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:19:29.984  4347  4409 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:19:29.985  4347  4405 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 09:19:29.989  4347  4347 D BluetoothMapService: onReceive
,08-29 09:19:29.989  4347  4347 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:19:29.989  4347  4347 D BluetoothMapService: STATE_TURNING_OFF
08-29 09:19:29.992  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:29.992  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:19:29.992  4347  4347 D BluetoothMapService: MAP Service closeService in
,08-29 09:19:29.992  4347  4347 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 09:19:29.993  4347  4347 D ObexServerSockets0: shutdown(block = true)
08-29 09:19:29.994  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:29.994  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:29.994  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:19:29.995  4347  4347 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 09:19:29.995  4347  4347 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:19:29.995  4347  4620 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 09:19:29.995  4347  4579 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 09:19:29.995  4347  4621 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 09:19:29.999  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:30.002  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:30.004   928  2914 E native  : do suspend true
08-29 09:19:30.005  4347  4347 I BtOppRfcommListener: stopping Accept Thread
08-29 09:19:30.006  4347  5139 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:19:30.007  4347  5139 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:19:30.007  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:30.007  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:19:30.008  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.008  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:19:30.014  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:30.014  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:19:30.015  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.015  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:19:30.016   928   941 I ActivityManager: Start proc 5753:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 09:19:30.018  4347  4347 D HeadsetService: Received stop request...Stopping profile...
,08-29 09:19:30.019   928   928 D BluetoothHeadset: Proxy object disconnected
,08-29 09:19:30.020  3454  3475 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:30.020  3061  3642 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:30.020  3061  3061 D HeadsetProfile: Bluetooth service disconnected
08-29 09:19:30.020   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:30.020   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:30.021  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.023  4347  4347 D A2dpService: Received stop request...Stopping profile...
,08-29 09:19:30.023  4347  4604 D A2dpStateMachine: Exit Disconnected: -1
,08-29 09:19:30.026   928   928 D BluetoothA2dp: Proxy object disconnected
,08-29 09:19:30.026  3061  3061 D BluetoothA2dp: Proxy object disconnected
08-29 09:19:30.026  4347  4347 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:19:30.026  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.026  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:30.026  4347  4347 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:30.030  4347  4347 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:19:30.030  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:30.031  4347  4347 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:19:30.031  4347  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:30.031  4347  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:30.031  4347  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:30.032  4347  4347 D HidService: Received stop request...Stopping profile...
08-29 09:19:30.032  4347  4347 D HidService: Stopping Bluetooth HidService
,08-29 09:19:30.032  3061  3061 D BluetoothInputDevice: Proxy object disconnected
08-29 09:19:30.032  3061  3061 D HidProfile: Bluetooth service disconnected
08-29 09:19:30.033  4347  4409 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 09:19:30.033  4347  4409 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 09:19:30.033  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:30.033  4347  4347 D HealthService: Received stop request...Stopping profile...
08-29 09:19:30.035  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:30.036  4347  4347 D PanService: Received stop request...Stopping profile...
08-29 09:19:30.037  3061  3061 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:19:30.037  4347  4347 D BluetoothMapService: Received stop request...Stopping profile...
08-29 09:19:30.037  3061  3061 D PanProfile: Bluetooth service disconnected
08-29 09:19:30.037  4347  4347 D BluetoothMapService: stop()
08-29 09:19:30.038  4347  4347 D BluetoothMapAppObserver: deinitObservers()
08-29 09:19:30.038  4347  4347 D BluetoothMapAppObserver: removeReceiver()
,08-29 09:19:30.039  3061  3061 D BluetoothMap: Proxy object disconnected
08-29 09:19:30.039  3061  3061 D MapProfile: Bluetooth service disconnected
,08-29 09:19:30.042   928  5191 D DhcpClient: Clearing IP address
,08-29 09:19:30.043   506   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:19:30.047  4347  4347 D SapService: Received stop request...Stopping profile...
08-29 09:19:30.047  4347  4347 V SapService: stop()
,08-29 09:19:30.049  4347  4347 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:19:30.049  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.049  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:30.049  4347  4347 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:30.049   506   922 D CommandListener: Setting iface cfg
08-29 09:19:30.051   928  5723 D DhcpClient: Receive thread stopped
08-29 09:19:30.051  4347  4347 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:30.051  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.051  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:30.051  4347  4347 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:30.051  4347  4347 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:19:30.051  4347  4347 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:19:30.051  4347  4347 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:30.051  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.051  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:19:30.052  4347  4347 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:30.052  4347  4347 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:19:30.052  3538  5745 V NativeCrypto: Read error: ssl=0x7f77787300: I/O error during system call, Connection timed out
08-29 09:19:30.052  4347  4347 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:19:30.052  4347  4347 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:30.052  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.052  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:30.052  4347  4347 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:30.053  4347  4347 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:19:30.053  4347  4347 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 09:19:30.053  3538  5745 V NativeCrypto: SSL shutdown failed: ssl=0x7f77787300: I/O error during system call, Broken pipe
08-29 09:19:30.053  4347  4347 D BluetoothMapService: MAP Service closeService in
,08-29 09:19:30.053  4347  4347 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:30.053  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.054  4347  4409 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 09:19:30.054  4347  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:30.054  4347  4409 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 09:19:30.054  4347  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:30.054  4347  4409 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 09:19:30.054  4347  4576 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:19:30.054  4347  4576 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:19:30.054  4347  4576 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:19:30.054  4347  4576 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:19:30.054  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:30.054  4347  4347 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:19:30.055  4347  4347 D BluetoothMapService: cleanup()
08-29 09:19:30.055  4347  4347 D BluetoothMapService: MAP Service closeService in
08-29 09:19:30.055  4347  4347 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:30.055  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.055  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:30.055  4347  4347 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:30.055  4347  4405 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 09:19:30.055  4347  4405 D BluetoothAdapterProperties: Setting state to 15
08-29 09:19:30.055  4347  4405 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 09:19:30.056  4347  4405 I BluetoothAdapterState: Entering BleOnState
08-29 09:19:30.056  3061  3636 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:19:30.057  3061  3072 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:19:30.057   928  3491 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
08-29 09:19:30.058   928  5721 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
08-29 09:19:30.058  3061  3073 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:19:30.058  3061  3642 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:19:30.059  3061  3636 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:19:30.059   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:19:30.060   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:30.060  3454  3477 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:30.060   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:30.060  3061  3072 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:19:30.061   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:30.061   928  5721 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 09:19:30.061   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-29 09:19:30.061   928  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 09:19:30.062   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 09:19:30.062  4347  4405 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-29 09:19:30.062  4347  4405 D BluetoothAdapterProperties: Setting state to 16
08-29 09:19:30.062  4347  4405 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 09:19:30.063  4347  4405 D BluetoothAdapterProperties: onBleDisable
08-29 09:19:30.063  4347  4405 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:19:30.063  4347  4406 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 09:19:30.065  4347  4576 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 09:19:30.065  4347  4576 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:30.066   544   544 E Parcel  : Reading a NULL string not supported here.
08-29 09:19:30.066   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 09:19:30.066   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 09:19:30.068  4347  4409 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:19:30.071   928   928 D RttService: SCAN_AVAILABLE : 1
08-29 09:19:30.071   928  3025 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:19:30.074  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:30.074  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:19:30.074   928  2918 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 09:19:30.075  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:30.075  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:30.076  3424  3546 W QCNEJ   : |CORE| network lost: 101
08-29 09:19:30.078  3424  3546 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-29 09:19:30.079  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:30.079  5753  5753 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:30.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:30.080  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.080  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:30.082  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:30.082  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:30.083  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:30.083  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:30.085  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:30.085  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:30.086  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.088  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.093  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:19:30.098   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9418b52:true
,08-29 09:19:30.100  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:19:30.101   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:19:30.106   928  2914 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 09:19:30.113   928   939 I ActivityManager: Start proc 5769:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 09:19:30.119   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:19:30.120   928  2914 E native  : do suspend true
08-29 09:19:30.120  5753  5753 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 09:19:30.122  5753  5753 D BluetoothMap: Create BluetoothMap proxy object
08-29 09:19:30.125   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 09:19:30.126   928  2918 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 09:19:30.126   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:19:30.131  5081  5081 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7d1e544 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 09:19:30.133  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.134   928   945 D Tethering: MasterInitialState.processMessage what=3
,08-29 09:19:30.135  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.139  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.144  4814  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-29 09:19:30.144  4814  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 09:19:30.144  4814  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 09:19:30.144  4814  4848 E SarControlService: no key has been found,reset the power
08-29 09:19:30.144  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 09:19:30.144  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 09:19:30.144  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 09:19:30.145  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:19:30.145  4855  4855 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,08-29 09:19:30.146  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 09:19:30.146  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 09:19:30.146  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 09:19:30.146  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:19:30.146  4855  4855 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 09:19:30.148  5753  5753 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 09:19:30.149  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000ee03000000000000ffffffff]
08-29 09:19:30.149  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:19:30.149  4855  4869 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,08-29 09:19:30.149  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,08-29 09:19:30.150  4814  4824 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 09:19:30.156  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000ef03000000000000ffffffff]
08-29 09:19:30.156  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:19:30.156  4855  4869 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
08-29 09:19:30.156  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:19:30.157  4814  4826 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 09:19:30.169  5769  5769 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 09:19:30.172  5753  5753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:19:30.174   928  2878 I ActivityManager: Killing 5081:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 09:19:30.185   506   922 E Netd    : netlink response contains error (No such file or directory)
,08-29 09:19:30.186   506   922 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:19:30.186   928  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 09:19:30.201   928  2914 D DhcpClient: doQuit
,08-29 09:19:30.201   928  2914 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 09:19:30.202   928  5191 D DhcpClient: onQuitting
,08-29 09:19:30.203  3590  3590 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 09:19:30.208  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:30.208  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:30.208  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.209  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:19:30.211  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:30.211  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:19:30.212  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:30.212  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:30.215  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:30.215  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:30.216  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:30.216  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:19:30.246  3590  3590 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 09:19:30.250  3590  3590 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 09:19:30.271  4347  4409 I bt_hci  : shut_down
,08-29 09:19:30.274  4347  4441 D bt_hwcfg: hw_epilog_process
,08-29 09:19:30.275  4347  4441 I bt_vendor: low_power_mode_cb
,08-29 09:19:30.277  4347  4441 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 09:19:30.277  4347  4441 I bt_vendor: epilog_cb
08-29 09:19:30.277  4347  4441 I bt_hci  : epilog_finished_callback
,08-29 09:19:30.279  4347  4409 I bt_hci_h4: hal_close
,08-29 09:19:30.279  4347  4409 I bt_userial_vendor: device fd = 51 close
,08-29 09:19:30.349  3590  3590 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.355  5769  5769 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:19:30.355  5769  5769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:19:30.359  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 09:19:30.364  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:19:30.367  3590  3590 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 09:19:30.372  5753  5753 D DockEventReceiver: finishStartingService: stopping service
08-29 09:19:30.375   928  3133 I ActivityManager: Killing 4431:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 09:19:30.413  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 09:19:30.417  3815  3815 D SystemUpdateService: onCreate
08-29 09:19:30.420  4347  4406 D bt_stack_manager: event_shut_down_stack finished.
08-29 09:19:30.420  4347  4405 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-29 09:19:30.421  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 09:19:30.421  4347  4405 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 09:19:30.421  4347  4347 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 09:19:30.422  4347  4347 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 09:19:30.422  4347  4347 D BtGatt.GattService: stop()
08-29 09:19:30.422  4347  4347 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 09:19:30.425  4347  4347 V BluetoothAdapterState: isTurningOff()=false
08-29 09:19:30.425  4347  4347 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:30.425  4347  4347 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:30.425  4347  4347 V BluetoothAdapterState: isBleTurningOff()=true
08-29 09:19:30.425  4347  4405 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 09:19:30.425  4347  4405 D BluetoothAdapterProperties: Setting state to 10
08-29 09:19:30.426  4347  4405 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 09:19:30.426  4347  4405 I BluetoothAdapterState: Entering OffState
,08-29 09:19:30.426   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 09:19:30.432  4347  4347 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 09:19:30.432  4347  4347 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 09:19:30.432  4347  4347 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 09:19:30.433  4347  4406 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 09:19:30.434  4347  4406 D bt_stack_manager: event_clean_up_stack finished.
,08-29 09:19:30.436  4347  4347 I art     : System.exit called, status: 0
,08-29 09:19:30.437  4347  4347 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 09:19:30.439  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 09:19:30.440  3815  5215 I iu.UploadsManager: num queued entries: 0
,08-29 09:19:30.441  3815  5215 I iu.UploadsManager: num updated entries: 0
08-29 09:19:30.441  3815  5215 I iu.SyncManager: NEXT; no task
,08-29 09:19:30.458  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:19:30.460  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 09:19:30.462  5687  5687 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:19:30.466  5687  5687 D SprintDMHelper: simOperator: 
08-29 09:19:30.466  5687  5687 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:19:30.472   928  2914 D wifi    : In wifi stop Hal
,08-29 09:19:30.472   928  2914 D wifi    : halHandle = 0x7f66050880, mVM = 0x7f8160d140, mCls = 0x100b96
08-29 09:19:30.472   928  3588 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 09:19:30.472   928  3588 D WifiHAL : Got a signal to exit!!!
08-29 09:19:30.472   928  3588 I WifiHAL : Exit wifi_event_loop
08-29 09:19:30.473   928  2914 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 09:19:30.473   928  2914 E WifiHAL : Event processing terminated
08-29 09:19:30.473   928  2914 D wifi    : In wifi cleaned up handler
08-29 09:19:30.473   928  2914 I WifiHAL : Internal cleanup completed
08-29 09:19:30.474  4165  4165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:19:30.474  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:30.475  3556  3909 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:19:30.476  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.477  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:30.478  4165  5807 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 09:19:30.468  3815  5804 I SystemUpdateService: active receiver: enabled
,08-29 09:19:30.490   928  3588 D wifi    : set interface wlan0 flags (DOWN)
,08-29 09:19:30.491   928  2914 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 09:19:30.495   928   939 I ActivityManager: Start proc 5809:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 09:19:30.519  3815  5804 I SystemUpdateService: showing system update notification
,08-29 09:19:30.522   928   938 I ActivityManager: Process com.android.bluetooth (pid 4347) has died
,08-29 09:19:30.535  5809  5809 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 09:19:30.592  5809  5809 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 09:19:30.617  3815  5804 V SystemUpdateService: retry (wakeup: false) in 3599872 ms
,08-29 09:19:30.620  3815  3815 D SystemUpdateService: onDestroy
,08-29 09:19:30.624   928   939 I ActivityManager: Killing 5416:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 09:19:30.693   928   945 D Tethering: InitialState.processMessage what=4
,08-29 09:19:30.696   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 09:19:30.757  5769  5796 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 09:19:30.769   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12d414:true
,08-29 09:19:34.998   928  3358 D WifiService: setWifiEnabled: true pid=5621, uid=10077
,08-29 09:19:34.998   928  3358 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:19:35.006   506   922 D SoftapController: Softap fwReload - Ok
,08-29 09:19:35.011   506   922 D CommandListener: Setting iface cfg
,08-29 09:19:35.011   506   922 D CommandListener: Trying to bring down wlan0
,08-29 09:19:35.013   506   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:19:35.017   928  2914 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 09:19:35.594   928  2914 D wifi    : set interface wlan0 flags (UP)
,08-29 09:19:35.596   928  2914 I WifiHAL : Initializing wifi
08-29 09:19:35.596   928  2914 I WifiHAL : Creating socket
08-29 09:19:35.597   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 09:19:35.599   928  2914 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 09:19:35.599   928  2914 D wifi    : Did set static halHandle = 0x7f66050880
,08-29 09:19:35.599   928  2914 D wifi    : halHandle = 0x7f66050880, mVM = 0x7f8160d140, mCls = 0x17de
,08-29 09:19:35.600   928  2914 D wifi    : array field set
08-29 09:19:35.600   928  2914 I WifiNative-HAL: interface[0] = wlan0
08-29 09:19:35.602   928  5838 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547172452480
08-29 09:19:35.602   928  5838 D wifi    : waitForHalEvents called, vm = 0x7f8160d140, obj = 0x17de, env = 0x7f6833ef80
,08-29 09:19:35.642  5839  5839 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 09:19:35.659  5839  5839 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:19:35.670  5839  5839 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:19:35.670  5839  5839 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 09:19:35.704   928  2914 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 09:19:35.715  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:35.716  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:35.716  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:35.716  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:35.719  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:35.719  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:35.719  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:35.719  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:35.723   928  2914 D WifiConfigStore: Loading config and enabling all networks 
08-29 09:19:35.723  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:35.723  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:35.723  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:35.723  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:19:35.725  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:35.726  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:35.728  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:35.730   928  2914 D WifiConfigStore: loaded 0 passpoint configs
08-29 09:19:35.730   928  2914 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 09:19:35.731   928  2914 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 09:19:35.733   928  2914 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 09:19:35.733   928  2914 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 09:19:35.733   928  2914 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 09:19:35.740  4165  4165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:19:35.740   928  2914 D WifiNative-HAL: Setting external_sim to 1
08-29 09:19:35.741   928  2914 D wifi    : setting dfs flag to true, 0x7f685ffa20
,08-29 09:19:35.741   928  2914 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:19:35.741   928  2914 D wifi    : setting scan oui 0x7f685ffa20
08-29 09:19:35.742   928  2914 D WifiHAL : Sending mac address OUI
,08-29 09:19:35.755   928  2914 E native  : do suspend true
,08-29 09:19:35.761   928   928 D RttService: SCAN_AVAILABLE : 3
08-29 09:19:35.761   928  2914 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 09:19:35.761   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 09:19:35.761   928  3025 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:19:35.762   506   922 D CommandListener: Setting iface cfg
,08-29 09:19:35.767   928  2892 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '86 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 86 Failed to set address (No such device)'
,08-29 09:19:35.767   928  2892 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 09:19:35.773   928  2892 D WifiNative-HAL: p2pGetDeviceAddress
08-29 09:19:35.774   928  2892 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 09:19:35.792   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=217554 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,08-29 09:19:38.992  5839  5839 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 09:19:39.025   928  2914 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 09:19:39.036   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-29 09:19:39.036   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:19:39.052   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 09:19:39.108   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 09:19:39.428  5839  5839 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 09:19:39.474  5839  5839 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 09:19:39.476  5839  5839 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 09:19:39.488   928  2914 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:19:39.489   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:19:39.489   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 09:19:39.505   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:19:39.518   506   922 D CommandListener: Setting iface cfg
,08-29 09:19:39.524   928  2914 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 09:19:39.532   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 09:19:39.600   928  5845 D DhcpClient: Receive thread started
,08-29 09:19:39.686   928  2914 E native  : do suspend false
,08-29 09:19:39.703   928  5844 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 09:19:39.736   928  5845 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172760, domain null
,08-29 09:19:39.736   928  5844 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172760 seconds
,08-29 09:19:39.739   928  5844 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 09:19:39.757   928  5845 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 09:19:39.758   928  5844 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 09:19:39.760   506   922 D CommandListener: Setting iface cfg
,08-29 09:19:39.771   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 09:19:39.772   928  5844 D DhcpClient: Scheduling renewal in 86399s
,08-29 09:19:39.775   928  2914 E native  : do suspend true
,08-29 09:19:39.789   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 09:19:39.791   928  2914 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 09:19:39.792   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 09:19:39.794   928  2918 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 09:19:39.799   928  2914 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 09:19:39.845   928  2918 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 09:19:39.845   928  2918 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 09:19:39.848   928  2918 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 09:19:39.853   928  2918 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 09:19:39.855   928  2918 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 09:19:39.863   928  2918 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 09:19:39.869   928  2918 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 09:19:39.870   928  2918 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 09:19:39.870   928  2918 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 09:19:39.870   928  2914 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 09:19:39.870   928  2918 D ConnectivityService:    accepting network in place of null
,08-29 09:19:39.871   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:19:39.871   928  2918 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:19:39.886   928  5843 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221649, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:19:39.902   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:19:39.929   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:19:39.933   928  2918 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 09:19:39.933  3424  3546 W QCNEJ   : |CORE| network available: 102
08-29 09:19:39.933   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:19:39.934   928  2918 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 09:19:39.934   928   945 D Tethering: MasterInitialState.processMessage what=3
08-29 09:19:39.936  3424  3546 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-29 09:19:39.938  3424  3546 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-29 09:19:39.938  3424  3546 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-29 09:19:39.939  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:39.939  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:19:39.939  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:39.939  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:39.941  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:39.941  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:19:39.942  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:39.942  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:39.944  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:19:39.944  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:19:39.944  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:39.944  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:19:39.950  4814  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 09:19:39.950  4814  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 09:19:39.950  4814  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 09:19:39.950  4814  4848 E SarControlService: no key has been found,reset the power
08-29 09:19:39.950  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 09:19:39.951  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 09:19:39.951  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,08-29 09:19:39.951  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:19:39.951  4855  4855 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 09:19:39.952  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 09:19:39.952  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 09:19:39.953  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 09:19:39.953  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:19:39.953  4855  4855 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,08-29 09:19:39.959  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000f003000000000000ffffffff]
,08-29 09:19:39.959  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:19:39.959  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 09:19:39.959  4855  4869 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
08-29 09:19:39.961  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,08-29 09:19:39.961  4814  4824 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 09:19:39.963  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000f103000000000000ffffffff]
08-29 09:19:39.963  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:19:39.963  4855  4869 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
08-29 09:19:39.964  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:19:39.964  4814  4826 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 09:19:39.965  3815  3815 D SystemUpdateService: onCreate
08-29 09:19:39.968  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:19:39.976   928  5842 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:817::200e
,08-29 09:19:39.979  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 09:19:39.985  3815  5215 I iu.UploadsManager: num queued entries: 0
08-29 09:19:39.985  3815  5215 I iu.UploadsManager: num updated entries: 0
08-29 09:19:39.985  3815  5215 I iu.SyncManager: NEXT; no task
,08-29 09:19:39.987  3815  5855 I SystemUpdateService: active receiver: enabled
,08-29 09:19:39.988  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:19:39.989  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
08-29 09:19:39.991  5687  5687 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 09:19:39.994  5687  5687 D SprintDMHelper: simOperator: 
08-29 09:19:39.994  5687  5687 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:19:40.002   928  3133 D WifiService: setWifiEnabled: false pid=5621, uid=10077
08-29 09:19:40.003   928  3133 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:19:40.006   928  2914 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 09:19:40.006   928  2914 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 09:19:40.006   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:19:40.006   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:19:40.012   928  2914 E native  : do suspend true
,08-29 09:19:40.018   928  5844 D DhcpClient: Clearing IP address
08-29 09:19:40.018   506   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:19:40.020   506   922 D CommandListener: Setting iface cfg
,08-29 09:19:40.022   928  5845 D DhcpClient: Receive thread stopped
08-29 09:19:40.023   928  5842 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-29 09:19:40.023   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation failed
,08-29 09:19:40.036   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 09:19:40.036   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
08-29 09:19:40.036  3815  5855 I SystemUpdateService: showing system update notification
08-29 09:19:40.038   544   544 E Parcel  : Reading a NULL string not supported here.
08-29 09:19:40.040   928   928 D RttService: SCAN_AVAILABLE : 1
,08-29 09:19:40.040   928  2918 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,08-29 09:19:40.040   928  3025 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:19:40.042  3424  3546 W QCNEJ   : |CORE| network lost: 102
08-29 09:19:40.042  3424  3546 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-29 09:19:40.046   928  2914 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 09:19:40.049  3815  5855 V SystemUpdateService: retry (wakeup: false) in 3599938 ms
,08-29 09:19:40.051   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:19:40.051   928  2914 E native  : do suspend true
08-29 09:19:40.052  3815  3815 D SystemUpdateService: onDestroy
,08-29 09:19:40.065   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:19:40.083   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 09:19:40.083   506   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:19:40.084   928  2918 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 09:19:40.084   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:19:40.085   928   945 D Tethering: MasterInitialState.processMessage what=3
,08-29 09:19:40.087  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:40.087  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:40.087  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.087  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:40.088  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:40.089  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:40.089  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:40.089   928  2914 D DhcpClient: doQuit
08-29 09:19:40.089  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.089   928  2914 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:40.089  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:40.089  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.090  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:40.090   928  5844 D DhcpClient: onQuitting
08-29 09:19:40.090  5839  5839 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 09:19:40.093  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:40.093  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:40.093  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.093  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:40.094  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 09:19:40.094  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:40.094  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:19:40.094  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.094  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:19:40.094  4814  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 09:19:40.095  4814  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 09:19:40.095  4814  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 09:19:40.095  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.095  4814  4848 E SarControlService: no key has been found,reset the power
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:40.095  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:40.095  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:40.095  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:40.095  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 09:19:40.095  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 09:19:40.095  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 09:19:40.096  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:19:40.096  4855  4855 D QcrilMsgTunnelSocket: [1010] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 09:19:40.098  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,08-29 09:19:40.098  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 09:19:40.098  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 09:19:40.098  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:19:40.098  4855  4855 D QcrilMsgTunnelSocket: [1011] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 09:19:40.101  3815  3815 D SystemUpdateService: onCreate
08-29 09:19:40.102  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000f203000000000000ffffffff]
08-29 09:19:40.102  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:19:40.102  4855  4869 D QcrilMsgTunnelSocket: [1010] < OEM_HOOK_RAW [null]
08-29 09:19:40.102  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:19:40.102  4814  4826 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 09:19:40.103  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000f303000000000000ffffffff]
08-29 09:19:40.103  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:19:40.103  4855  4869 D QcrilMsgTunnelSocket: [1011] < OEM_HOOK_RAW [null]
,08-29 09:19:40.104  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:19:40.104  4814  4824 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 09:19:40.106  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:19:40.113  3815  5872 I SystemUpdateService: active receiver: enabled
,08-29 09:19:40.115  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 09:19:40.119  3815  5215 I iu.UploadsManager: num queued entries: 0
,08-29 09:19:40.120  3815  5215 I iu.UploadsManager: num updated entries: 0
,08-29 09:19:40.120  3815  5215 I iu.SyncManager: NEXT; no task
,08-29 09:19:40.122  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:19:40.124  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 09:19:40.125  5687  5687 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:19:40.129  5687  5687 D SprintDMHelper: simOperator: 
08-29 09:19:40.129  5687  5687 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:19:40.138   506   922 E Netd    : netlink response contains error (No such file or directory)
08-29 09:19:40.138  5839  5839 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
08-29 09:19:40.139  3815  5872 I SystemUpdateService: showing system update notification
,08-29 09:19:40.139   928  2918 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 09:19:40.139   928  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 09:19:40.141  5839  5839 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 09:19:40.156  3815  5872 V SystemUpdateService: retry (wakeup: false) in 3599958 ms
,08-29 09:19:40.158  3815  3815 D SystemUpdateService: onDestroy
,08-29 09:19:40.177  5839  5839 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 09:19:40.178  5839  5839 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 09:19:40.183   928  2914 D wifi    : In wifi stop Hal
,08-29 09:19:40.183   928  2914 D wifi    : halHandle = 0x7f66050880, mVM = 0x7f8160d140, mCls = 0x17de
08-29 09:19:40.184   928  5838 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 09:19:40.184   928  5838 D WifiHAL : Got a signal to exit!!!
08-29 09:19:40.184   928  5838 I WifiHAL : Exit wifi_event_loop
08-29 09:19:40.184   928  2914 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 09:19:40.184   928  2914 E WifiHAL : Event processing terminated
,08-29 09:19:40.184   928  2914 D wifi    : In wifi cleaned up handler
08-29 09:19:40.184   928  2914 I WifiHAL : Internal cleanup completed
08-29 09:19:40.185  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:40.186  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:40.187  4165  4165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:19:40.187  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:40.189  3556  3909 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:19:40.199   928  5838 D wifi    : set interface wlan0 flags (DOWN)
,08-29 09:19:40.200   928  2914 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 09:19:40.281   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:19:40.281   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:19:40.407   928   945 D Tethering: InitialState.processMessage what=4
,08-29 09:19:40.413   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 09:19:40.934   928  2918 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 09:19:45.028  4165  5859 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-29 09:19:45.029  4165  5859 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 09:19:45.044   928   945 I ActivityManager: Start proc 5879:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 09:19:45.046  4165  5859 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 09:19:45.127  5879  5879 D AdapterServiceConfig: Adding HeadsetService
,08-29 09:19:45.127  5879  5879 D AdapterServiceConfig: Adding A2dpService
08-29 09:19:45.127  5879  5879 D AdapterServiceConfig: Adding HidService
,08-29 09:19:45.127  5879  5879 D AdapterServiceConfig: Adding HealthService
08-29 09:19:45.128  5879  5879 D AdapterServiceConfig: Adding PanService
08-29 09:19:45.128  5879  5879 D AdapterServiceConfig: Adding GattService
08-29 09:19:45.128  5879  5879 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 09:19:45.128  5879  5879 D AdapterServiceConfig: Adding SapService
,08-29 09:19:45.139   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e784835:true
,08-29 09:19:45.139  5879  5879 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 09:19:45.142  5879  5879 I bt_bluedroid: init
,08-29 09:19:45.142  5879  5891 I BluetoothAdapterState: Entering OffState
,08-29 09:19:45.144  5879  5892 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 09:19:45.144  5879  5892 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 09:19:45.144  5879  5892 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 09:19:45.144  5879  5892 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 09:19:45.145  5879  5879 I bt_bluedroid: get_profile_interface socket
,08-29 09:19:45.146  5879  5895 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 09:19:45.146  5879  5879 I bt_bluedroid: get_profile_interface sdp
08-29 09:19:45.148  5879  5895 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 09:19:45.150  5879  5890 I bt_bluedroid: config_hci_snoop_log
,08-29 09:19:45.151   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-29 09:19:45.154  5879  5891 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 09:19:45.154  5879  5891 D BluetoothAdapterProperties: Setting state to 14
08-29 09:19:45.154  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 09:19:45.156  5879  5891 D BluetoothBondStateMachine: make
,08-29 09:19:45.158  5879  5896 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 09:19:45.161  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:19:45.162  5879  5879 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 09:19:45.164  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:19:45.164  5879  5879 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:19:45.165  5879  5879 D BtGatt.GattService: Received start request. Starting profile...
08-29 09:19:45.165  5879  5879 D BtGatt.GattService: start()
08-29 09:19:45.165  5879  5879 I bt_bluedroid: get_profile_interface gatt
,08-29 09:19:45.166  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:19:45.166  5879  5879 D BtGatt.AdvertiseManager: advertise manager created
,08-29 09:19:45.172  5879  5879 V BluetoothAdapterState: isTurningOff()=false
08-29 09:19:45.172  5879  5879 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:45.172  5879  5879 V BluetoothAdapterState: isBleTurningOn()=true
08-29 09:19:45.172  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:45.172  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 09:19:45.172  5879  5891 I bt_bluedroid: enable
,08-29 09:19:45.172  5879  5892 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 09:19:45.173  5879  5892 I bt_hci  : start_up
,08-29 09:19:45.180  5879  5892 I bt_vendor: alloc value 0xf3ff304d
,08-29 09:19:45.180  5879  5892 I bt_vendor: init
08-29 09:19:45.180  5879  5892 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 09:19:45.180  5879  5892 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 09:19:45.299  5879  5892 D bt_hci  : start_up starting async portion
,08-29 09:19:45.299  5879  5899 I bt_hci  : event_finish_startup
08-29 09:19:45.299  5879  5899 I bt_hci_h4: hal_open
,08-29 09:19:45.299  5879  5899 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 09:19:45.296  5900  5900 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 09:19:45.303  5879  5899 I bt_userial_vendor: device fd = 51 open
,08-29 09:19:45.318  5879  5899 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:19:45.320  5879  5899 D bt_hwcfg: Chipset BCM4358A3
08-29 09:19:45.321  5879  5899 D bt_hwcfg: Target name = [BCM4358A3]
08-29 09:19:45.321  5879  5899 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 09:19:45.708  5879  5899 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 09:19:45.709  5879  5899 D bt_hwcfg: Settlement delay -- 100 ms
08-29 09:19:45.709  5879  5899 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 09:19:45.844  5879  5899 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 09:19:45.844  5879  5899 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 09:19:45.846  5879  5899 I bt_hwcfg: vendor lib fwcfg completed
,08-29 09:19:45.846  5879  5899 I bt_vendor: firmware callback
08-29 09:19:45.847  5879  5899 I bt_hci  : firmware_config_callback
,08-29 09:19:45.855  5879  5902 I bt_btu  : btu_task pending for preload complete event
,08-29 09:19:45.855  5879  5902 I bt_btu_task: Bluetooth chip preload is complete
,08-29 09:19:45.856  5879  5902 I bt_btu  : btu_task received preload complete event
,08-29 09:19:45.864  5879  5902 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 09:19:45.864  5879  5902 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 09:19:45.864  5879  5902 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 09:19:45.864  5879  5902 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 09:19:45.865  5879  5902 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 09:19:45.866  5879  5902 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 09:19:45.866  5879  5902 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 09:19:45.866  5879  5902 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 09:19:45.947  5879  5902 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f70c99
,08-29 09:19:45.947  5879  5902 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f70c99 
,08-29 09:19:45.973  5879  5895 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 09:19:45.974  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 09:19:45.975  5879  5895 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 09:19:45.977  5879  5895 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 09:19:45.979  5879  5895 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:19:45.979  5879  5895 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:19:45.979  5879  5895 D bt_hci  : do_postload posting postload work item
08-29 09:19:45.980  5879  5899 I bt_hci  : event_postload
,08-29 09:19:45.980  5879  5899 I bt_vendor: sco_config_cb
,08-29 09:19:45.980  5879  5899 I bt_hci  : sco_config_callback postload finished.
08-29 09:19:45.983  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:45.985  5879  5895 D bt_bte_conf: Device ID record 1 : primary
,08-29 09:19:45.985  5879  5895 D bt_bte_conf:   vendorId            = 000f
08-29 09:19:45.985  5879  5895 D bt_bte_conf:   vendorIdSource      = 0001
08-29 09:19:45.985  5879  5895 D bt_bte_conf:   product             = 1200
08-29 09:19:45.985  5879  5895 D bt_bte_conf:   version             = 1436
08-29 09:19:45.985  5879  5895 D bt_bte_conf:   clientExecutableURL = 
08-29 09:19:45.985  5879  5895 D bt_bte_conf:   serviceDescription  = 
08-29 09:19:45.985  5879  5895 D bt_bte_conf:   documentationURL    = 
08-29 09:19:45.985  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:45.985  5879  5895 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 09:19:45.986  5879  5892 D bt_stack_manager: event_start_up_stack finished
08-29 09:19:45.986  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 09:19:45.987  5879  5891 D BluetoothAdapterProperties: Setting state to 15
08-29 09:19:45.987  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 09:19:45.987  5879  5891 I BluetoothAdapterState: Entering BleOnState
08-29 09:19:45.988  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:45.989  5879  5899 I bt_vendor: low_power_mode_cb
08-29 09:19:45.991  5879  5891 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 09:19:45.991  5879  5891 D BluetoothAdapterProperties: Setting state to 11
08-29 09:19:45.991  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 09:19:45.995  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:19:45.996  5879  5879 D HeadsetService: Received start request. Starting profile...
08-29 09:19:45.999  5879  5879 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 09:19:45.999  5879  5879 D HeadsetStateMachine: make
08-29 09:19:46.000  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:46.002  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:46.004  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:46.010  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:19:46.013  5879  5879 D HeadsetStateMachine: max_hf_connections = 1
,08-29 09:19:46.013  5879  5879 I bt_bluedroid: get_profile_interface handsfree
08-29 09:19:46.014  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 09:19:46.014  5879  5895 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 09:19:46.016  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:19:46.017  5879  5879 D A2dpService: Received start request. Starting profile...
,08-29 09:19:46.017  5879  5879 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 09:19:46.018  5879  5879 I bt_bluedroid: get_profile_interface avrcp
,08-29 09:19:46.023  5879  5879 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:19:46.023  5879  5879 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:19:46.023  5879  5879 D A2dpStateMachine: make
08-29 09:19:46.024  5879  5879 I bt_bluedroid: get_profile_interface a2dp
,08-29 09:19:46.026  5879  5911 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:19:46.026  5879  5879 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 09:19:46.027  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
08-29 09:19:46.027  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 09:19:46.028  5879  5879 D HidService: Received start request. Starting profile...
08-29 09:19:46.028  5753  5753 D BluetoothInputDevice: Proxy object connected
08-29 09:19:46.028  5879  5879 I bt_bluedroid: get_profile_interface hidhost
08-29 09:19:46.028  5879  5895 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f522d9
08-29 09:19:46.028  5879  5879 D HidService: setHidService(): set to: null
08-29 09:19:46.029  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 09:19:46.029  5753  5753 D HidProfile: Bluetooth service connected
08-29 09:19:46.030  5879  5879 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 09:19:46.031  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:19:46.031  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:19:46.031  5879  5879 D HealthService: Received start request. Starting profile...
,08-29 09:19:46.033  5879  5879 I bt_bluedroid: get_profile_interface health
08-29 09:19:46.034  5879  5879 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 09:19:46.034  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
08-29 09:19:46.035  5753  5753 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:19:46.035  5879  5879 D PanService: Received start request. Starting profile...
08-29 09:19:46.036  5879  5879 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 09:19:46.036  5879  5879 I bt_bluedroid: get_profile_interface pan
08-29 09:19:46.036  5753  5753 D PanProfile: Bluetooth service connected
08-29 09:19:46.036  5879  5895 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 09:19:46.038  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:19:46.040  5879  5879 D BluetoothMapService: Received start request. Starting profile...
,08-29 09:19:46.040  5879  5879 D BluetoothMapService: start()
08-29 09:19:46.042  5879  5879 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 09:19:46.043  5879  5879 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 09:19:46.043  5879  5879 D BluetoothMapAppObserver: createReceiver()
08-29 09:19:46.044  5879  5879 D BluetoothMapAppObserver: initObservers()
08-29 09:19:46.044  5879  5879 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 09:19:46.049  5879  5879 V SapService: SapBinder()
08-29 09:19:46.049  5879  5879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:19:46.050  5879  5879 D SapService: Received start request. Starting profile...
,08-29 09:19:46.050  5879  5879 V SapService: start()
08-29 09:19:46.051  5753  5753 D BluetoothMap: Proxy object connected
,08-29 09:19:46.052  5753  5753 D MapProfile: Bluetooth service connected
08-29 09:19:46.052  5753  5753 D BluetoothMap: getConnectedDevices()
08-29 09:19:46.053  5753  5753 D BluetoothMap: Bluetooth is Not enabled
,08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isTurningOn()=true
,08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:46.054  5879  5908 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isTurningOff()=false
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isTurningOn()=true
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isTurningOff()=false
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isTurningOn()=true
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:46.054  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isTurningOff()=false
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isTurningOn()=true
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isTurningOn()=true
,08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isTurningOff()=false
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isTurningOn()=true
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:46.055  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:46.056  5879  5879 V BluetoothAdapterState: isTurningOff()=false
08-29 09:19:46.056  5879  5879 V BluetoothAdapterState: isTurningOn()=true
08-29 09:19:46.056  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:46.056  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:46.056  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 09:19:46.056  5879  5891 D BluetoothAdapterProperties: ScanMode =  20
08-29 09:19:46.056  5879  5891 D BluetoothAdapterProperties: State =  11
08-29 09:19:46.057  5879  5891 D BluetoothAdapterProperties: Setting state to 12
08-29 09:19:46.057  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 09:19:46.057  5879  5891 I BluetoothAdapterState: Entering OnState
08-29 09:19:46.057  3061  3072 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:19:46.058  5879  5895 D BluetoothAdapterProperties: Scan Mode:21
08-29 09:19:46.058  5879  5895 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:19:46.061  3061  3061 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:19:46.061  3061  3061 D PanProfile: Bluetooth service connected
08-29 09:19:46.061  3061  3636 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:19:46.062  3061  3073 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:46.063  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:19:46.063  5753  5764 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 09:19:46.064  3061  3642 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:19:46.065  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:46.066  3061  3061 D BluetoothInputDevice: Proxy object connected
08-29 09:19:46.066  3061  3636 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:19:46.066  3061  3061 D HidProfile: Bluetooth service connected
08-29 09:19:46.068   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:19:46.068  5753  5763 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:19:46.069   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:19:46.069  5879  5879 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:19:46.069  3454  3686 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:19:46.069   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:19:46.069  3061  3073 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:19:46.069  5879  5879 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:46.070  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:46.071  3061  3061 D BluetoothMap: Proxy object connected
08-29 09:19:46.071  3061  3061 D MapProfile: Bluetooth service connected
08-29 09:19:46.071  5753  5764 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:19:46.071  3061  3061 D BluetoothMap: getConnectedDevices()
08-29 09:19:46.071  5879  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:19:46.071  5753  5763 D BluetoothPan: onBluetoothStateChange on: true
,08-29 09:19:46.071   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:19:46.072   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 09:19:46.073  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:46.075  5753  5753 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 09:19:46.075  5879  5879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:19:46.078  5879  5879 D ObexServerSockets: Succeed to create listening sockets 
,08-29 09:19:46.078  5879  5879 D ObexServerSockets0: startAccept()
08-29 09:19:46.078  5879  5879 D ObexServerSockets0: prepareForNewConnect()
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:46.079  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:46.079  5753  5753 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 09:19:46.081  5879  5879 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 09:19:46.081  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:46.081  5879  5879 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 09:19:46.082  5879  5918 D ObexServerSockets0: Accepting socket connection...
,08-29 09:19:46.083  5879  5919 D ObexServerSockets0: Accepting socket connection...
,08-29 09:19:46.083  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:46.084   928   928 D BluetoothA2dp: Proxy object connected
08-29 09:19:46.084  5879  5879 D BluetoothMapService: onReceive
08-29 09:19:46.084  5879  5879 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:19:46.085  5879  5879 D BluetoothMapService: STATE_ON
08-29 09:19:46.085  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:46.086  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 09:19:46.087  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:46.088  5879  5920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:19:46.088  5753  5753 D BluetoothA2dp: Proxy object connected
,08-29 09:19:46.090  5879  5920 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 09:19:46.090  5879  5920 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 09:19:46.093  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:19:46.095  5753  5753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:19:46.100  5753  5753 D BluetoothPbap: Proxy object connected
,08-29 09:19:46.100  5753  5753 D PbapServerProfile: Bluetooth service connected
,08-29 09:19:46.103  3061  3061 D BluetoothA2dp: Proxy object connected
,08-29 09:19:46.105  3061  3061 D BluetoothPbap: Proxy object connected
08-29 09:19:46.105  3061  3061 D PbapServerProfile: Bluetooth service connected
,08-29 09:19:46.106  5879  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:19:46.116  5879  5879 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 09:19:46.116  5879  5879 D ObexServerSockets0: prepareForNewConnect()
,08-29 09:19:46.120  5879  5928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:19:46.122  5879  5928 I BtOppRfcommListener: Accept thread started.
,08-29 09:19:46.162   928   928 D BluetoothHeadset: Proxy object connected
,08-29 09:19:46.163  3454  3475 D BluetoothHeadset: Proxy object connected
08-29 09:19:46.163  3061  3072 D BluetoothHeadset: Proxy object connected
08-29 09:19:46.163  3061  3061 D HeadsetProfile: Bluetooth service connected
08-29 09:19:46.163   928   928 D BluetoothHeadset: Proxy object connected
08-29 09:19:46.163   928   928 D BluetoothHeadset: Proxy object connected
,08-29 09:19:46.169   928   945 D BluetoothHeadset: Proxy object connected
,08-29 09:19:46.169  3454  3477 D BluetoothHeadset: Proxy object connected
08-29 09:19:46.169   928   945 D BluetoothHeadset: Proxy object connected
,08-29 09:19:46.171   928   945 D BluetoothHeadset: Proxy object connected
,08-29 09:19:46.183  5753  5763 D BluetoothHeadset: Proxy object connected
,08-29 09:19:46.184  5753  5753 D HeadsetProfile: Bluetooth service connected
,08-29 09:19:47.877   928  2918 D ConnectivityService: handlePromptUnvalidated 102
,08-29 09:19:50.019  5879  5891 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 09:19:50.019  5879  5891 D BluetoothAdapterProperties: Setting state to 13
08-29 09:19:50.019  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 09:19:50.021  5879  5891 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 09:19:50.023  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:19:50.032  5879  5879 D BluetoothMapService: onReceive
,08-29 09:19:50.032  5879  5879 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:19:50.032  5879  5879 D BluetoothMapService: STATE_TURNING_OFF
,08-29 09:19:50.032  5879  5895 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:19:50.032  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 09:19:50.032  5879  5879 D BluetoothMapService: MAP Service closeService in
,08-29 09:19:50.033  5879  5879 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 09:19:50.033  5879  5879 D ObexServerSockets0: shutdown(block = true)
08-29 09:19:50.033  5879  5879 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:19:50.034  5879  5879 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:19:50.034  5879  5919 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 09:19:50.035  5879  5918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 09:19:50.035  5879  5904 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 09:19:50.035  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 09:19:50.039  5879  5879 I BtOppRfcommListener: stopping Accept Thread
08-29 09:19:50.039  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:50.039  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:50.039  5879  5928 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:19:50.039  5879  5928 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:19:50.040  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:50.040  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:19:50.043  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:50.043  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:19:50.044  5753  5753 D DockEventReceiver: finishStartingService: stopping service
08-29 09:19:50.045  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:50.045  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:19:50.048  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:19:50.048  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:19:50.050  5621  5621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:19:50.050  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:19:50.050  5879  5879 D HeadsetService: Received stop request...Stopping profile...
08-29 09:19:50.052  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:50.052   928   928 D BluetoothHeadset: Proxy object disconnected
,08-29 09:19:50.053  5753  5764 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:50.053  5879  5879 D A2dpService: Received stop request...Stopping profile...
08-29 09:19:50.053  5879  5911 D A2dpStateMachine: Exit Disconnected: -1
08-29 09:19:50.053  3454  3686 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:50.054  3061  3636 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:50.054   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:50.055   928   928 D BluetoothHeadset: Proxy object disconnected
08-29 09:19:50.055   928   928 D BluetoothA2dp: Proxy object disconnected
08-29 09:19:50.055  5879  5879 D HidService: Received stop request...Stopping profile...
08-29 09:19:50.055  5879  5879 D HidService: Stopping Bluetooth HidService
08-29 09:19:50.056  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:50.057  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:50.058  5753  5753 D HeadsetProfile: Bluetooth service disconnected
08-29 09:19:50.058  5753  5753 D BluetoothA2dp: Proxy object disconnected
08-29 09:19:50.058  5753  5753 D BluetoothInputDevice: Proxy object disconnected
08-29 09:19:50.058  5753  5753 D HidProfile: Bluetooth service disconnected
08-29 09:19:50.059  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:19:50.061  3061  3061 D HeadsetProfile: Bluetooth service disconnected
,08-29 09:19:50.061  3061  3061 D BluetoothA2dp: Proxy object disconnected
08-29 09:19:50.061  3061  3061 D BluetoothInputDevice: Proxy object disconnected
08-29 09:19:50.061  3061  3061 D HidProfile: Bluetooth service disconnected
08-29 09:19:50.062  5879  5879 D HealthService: Received stop request...Stopping profile...
,08-29 09:19:50.063  5879  5879 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:50.064  5879  5879 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:50.064  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.064  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:19:50.064  5879  5879 D PanService: Received stop request...Stopping profile...
,08-29 09:19:50.066  3061  3061 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:19:50.066  3061  3061 D PanProfile: Bluetooth service disconnected
08-29 09:19:50.066  5753  5753 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 09:19:50.066  5753  5753 D PanProfile: Bluetooth service disconnected
,08-29 09:19:50.068  5879  5879 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:19:50.068  5879  5879 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:19:50.068  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:50.068  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:50.068  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:50.068  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 09:19:50.068  5879  5895 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 09:19:50.069  5879  5879 D BluetoothMapService: Received stop request...Stopping profile...
08-29 09:19:50.069  5879  5879 D BluetoothMapService: stop()
,08-29 09:19:50.070  5879  5879 D BluetoothMapAppObserver: deinitObservers()
,08-29 09:19:50.078  5879  5879 D BluetoothMapAppObserver: removeReceiver()
,08-29 09:19:50.079  3061  3061 D BluetoothMap: Proxy object disconnected
08-29 09:19:50.079  5753  5753 D BluetoothMap: Proxy object disconnected
08-29 09:19:50.079  3061  3061 D MapProfile: Bluetooth service disconnected
08-29 09:19:50.079  5879  5879 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:50.079  5753  5753 D MapProfile: Bluetooth service disconnected
08-29 09:19:50.079  5879  5879 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:50.079  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.079  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:19:50.080  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 09:19:50.081  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:50.081  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 09:19:50.081  5879  5879 D SapService: Received stop request...Stopping profile...
08-29 09:19:50.081  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:19:50.081  5879  5879 V SapService: stop()
08-29 09:19:50.081  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:19:50.081  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:19:50.081  5879  5902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 09:19:50.083  5879  5879 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:50.083  5879  5879 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:19:50.083  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.083  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:50.083  5879  5879 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:19:50.083  5879  5879 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:19:50.083  5879  5895 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 09:19:50.086  3061  3061 D BluetoothPbap: Proxy object disconnected
08-29 09:19:50.086  3061  3061 D PbapServerProfile: Bluetooth service disconnected
08-29 09:19:50.086  5753  5753 D BluetoothPbap: Proxy object disconnected
08-29 09:19:50.086  5753  5753 D PbapServerProfile: Bluetooth service disconnected
,08-29 09:19:50.086  5879  5879 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:50.086  5879  5879 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:50.087  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.087  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:50.087  5879  5879 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:19:50.087  5879  5895 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 09:19:50.087  5879  5879 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 09:19:50.087  5879  5879 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:19:50.088  5879  5879 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:50.088  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.088  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:50.088  5879  5879 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:19:50.088  5879  5879 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 09:19:50.090  5879  5879 D BluetoothMapService: MAP Service closeService in
,08-29 09:19:50.090  5879  5879 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:50.091  5879  5879 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:50.091  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.091  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:50.091  5879  5879 D BluetoothMapService: cleanup()
08-29 09:19:50.091  5879  5879 D BluetoothMapService: MAP Service closeService in
08-29 09:19:50.091  5879  5879 V BluetoothAdapterState: isTurningOff()=true
08-29 09:19:50.091  5879  5879 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:19:50.091  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.091  5879  5879 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:19:50.091  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 09:19:50.091  5879  5891 D BluetoothAdapterProperties: Setting state to 15
08-29 09:19:50.091  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 09:19:50.092  3061  3072 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:19:50.093  5879  5891 I BluetoothAdapterState: Entering BleOnState
08-29 09:19:50.093  5753  5763 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:19:50.094  3061  3073 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:50.094  3061  3636 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 09:19:50.095  5753  5764 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:19:50.095  3061  3072 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:19:50.096  3061  3073 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:19:50.096   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:19:50.097  5753  5763 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:19:50.098  5753  5764 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:50.098   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:50.099  3454  3475 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:50.099   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:50.099  3061  3642 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:19:50.100  5753  5764 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:19:50.101  5753  5763 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:19:50.101   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:19:50.102  5879  5891 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 09:19:50.102  5879  5891 D BluetoothAdapterProperties: Setting state to 16
08-29 09:19:50.102  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 09:19:50.102  5879  5891 D BluetoothAdapterProperties: onBleDisable
08-29 09:19:50.102  5879  5891 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:19:50.103  5879  5892 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 09:19:50.103  5879  5902 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 09:19:50.104  5879  5902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:19:50.105  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:50.105  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:19:50.106  5879  5895 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:19:50.107  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:50.109  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:50.109  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:19:50.110  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:50.112  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:19:50.113  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:19:50.115  5753  5753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:19:50.281   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:50.310  5879  5895 I bt_hci  : shut_down
,08-29 09:19:50.315  5879  5899 D bt_hwcfg: hw_epilog_process
08-29 09:19:50.315  5879  5899 I bt_vendor: low_power_mode_cb
,08-29 09:19:50.318  5879  5899 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 09:19:50.318  5879  5899 I bt_vendor: epilog_cb
08-29 09:19:50.318  5879  5899 I bt_hci  : epilog_finished_callback
,08-29 09:19:50.321  5879  5895 I bt_hci_h4: hal_close
,08-29 09:19:50.322  5879  5895 I bt_userial_vendor: device fd = 51 close
,08-29 09:19:50.443  5879  5892 D bt_stack_manager: event_shut_down_stack finished.
,08-29 09:19:50.444  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 09:19:50.448  5879  5879 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:19:50.449  5879  5879 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 09:19:50.449  5879  5891 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 09:19:50.449  5879  5879 D BtGatt.GattService: stop()
08-29 09:19:50.449  5879  5879 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 09:19:50.453  5879  5879 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:19:50.453  5879  5879 V BluetoothAdapterState: isTurningOn()=false
08-29 09:19:50.453  5879  5879 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:19:50.453  5879  5879 V BluetoothAdapterState: isBleTurningOff()=true
08-29 09:19:50.454  5879  5891 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 09:19:50.454  5879  5891 D BluetoothAdapterProperties: Setting state to 10
08-29 09:19:50.454  5879  5891 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 09:19:50.455  5879  5891 I BluetoothAdapterState: Entering OffState
,08-29 09:19:50.457   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 09:19:50.471  5879  5879 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 09:19:50.471  5879  5879 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 09:19:50.471  5879  5879 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 09:19:50.474  5879  5892 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 09:19:50.478  5879  5892 D bt_stack_manager: event_clean_up_stack finished.
,08-29 09:19:50.480  5879  5879 I art     : System.exit called, status: 0
08-29 09:19:50.480  5879  5879 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 09:19:50.514   928  3133 I ActivityManager: Process com.android.bluetooth (pid 5879) has died
,08-29 09:19:51.282   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:52.283   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:53.284   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:54.284   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:19:55.016  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:19:55.016  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:19:55.020  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:19:55.021  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@148af6b removed from the list
,08-29 09:19:55.021  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:19:55.021  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:55.021  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:55.023  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:19:55.024  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be86761 added. We now have 4 listener(s)
08-29 09:19:55.024  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:19:55.025  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:19:55.025  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be86761 removed from the list
08-29 09:19:55.026  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:19:55.026  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:19:55.026  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:19:55.028  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:19:55.028  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@779c286 added. We now have 4 listener(s)
08-29 09:19:55.028  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:19:55.285   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:20:00.036  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:00.071   928   945 I ActivityManager: Start proc 5936:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 09:20:00.161  5936  5936 D AdapterServiceConfig: Adding HeadsetService
,08-29 09:20:00.161  5936  5936 D AdapterServiceConfig: Adding A2dpService
08-29 09:20:00.161  5936  5936 D AdapterServiceConfig: Adding HidService
08-29 09:20:00.161  5936  5936 D AdapterServiceConfig: Adding HealthService
08-29 09:20:00.162  5936  5936 D AdapterServiceConfig: Adding PanService
,08-29 09:20:00.162  5936  5936 D AdapterServiceConfig: Adding GattService
08-29 09:20:00.162  5936  5936 D AdapterServiceConfig: Adding BluetoothMapService
08-29 09:20:00.162  5936  5936 D AdapterServiceConfig: Adding SapService
,08-29 09:20:00.179   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ff75fb:true
,08-29 09:20:00.179  5936  5936 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 09:20:00.184  5936  5936 I bt_bluedroid: init
,08-29 09:20:00.185  5936  5948 I BluetoothAdapterState: Entering OffState
,08-29 09:20:00.189  5936  5949 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 09:20:00.189  5936  5949 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 09:20:00.189  5936  5949 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 09:20:00.189  5936  5949 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 09:20:00.190  5936  5936 I bt_bluedroid: get_profile_interface socket
,08-29 09:20:00.193  5936  5936 I bt_bluedroid: get_profile_interface sdp
,08-29 09:20:00.193  5936  5952 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 09:20:00.194  5936  5952 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 09:20:00.195  5936  5947 I bt_bluedroid: config_hci_snoop_log
08-29 09:20:00.197   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 09:20:00.201  5936  5948 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 09:20:00.201  5936  5948 D BluetoothAdapterProperties: Setting state to 14
08-29 09:20:00.202  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 09:20:00.203  5936  5948 D BluetoothBondStateMachine: make
,08-29 09:20:00.205  5936  5953 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 09:20:00.208  5936  5948 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:20:00.209  5936  5936 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 09:20:00.212  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
08-29 09:20:00.212  5936  5936 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 09:20:00.213  5936  5936 D BtGatt.GattService: Received start request. Starting profile...
08-29 09:20:00.213  5936  5936 D BtGatt.GattService: start()
08-29 09:20:00.213  5936  5936 I bt_bluedroid: get_profile_interface gatt
08-29 09:20:00.214  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
08-29 09:20:00.214  5936  5936 D BtGatt.AdvertiseManager: advertise manager created
,08-29 09:20:00.221  5936  5936 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:20:00.221  5936  5936 V BluetoothAdapterState: isTurningOn()=false
08-29 09:20:00.221  5936  5936 V BluetoothAdapterState: isBleTurningOn()=true
08-29 09:20:00.221  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:20:00.221  5936  5948 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 09:20:00.222  5936  5948 I bt_bluedroid: enable
,08-29 09:20:00.222  5936  5949 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 09:20:00.222  5936  5949 I bt_hci  : start_up
,08-29 09:20:00.228  5936  5949 I bt_vendor: alloc value 0xf3ff304d
08-29 09:20:00.228  5936  5949 I bt_vendor: init
08-29 09:20:00.228  5936  5949 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 09:20:00.228  5936  5949 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 09:20:00.286   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:00.348  5936  5949 D bt_hci  : start_up starting async portion
08-29 09:20:00.348  5936  5956 I bt_hci  : event_finish_startup
,08-29 09:20:00.348  5936  5956 I bt_hci_h4: hal_open
,08-29 09:20:00.349  5936  5956 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-29 09:20:00.346  5957  5957 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 09:20:00.352  5936  5956 I bt_userial_vendor: device fd = 51 open
,08-29 09:20:00.369  5936  5956 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:20:00.372  5936  5956 D bt_hwcfg: Chipset BCM4358A3
08-29 09:20:00.373  5936  5956 D bt_hwcfg: Target name = [BCM4358A3]
,08-29 09:20:00.373  5936  5956 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 09:20:00.854  5936  5956 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 09:20:00.855  5936  5956 D bt_hwcfg: Settlement delay -- 100 ms
08-29 09:20:00.855  5936  5956 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 09:20:00.989  5936  5956 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-29 09:20:00.990  5936  5956 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
08-29 09:20:00.991  5936  5956 I bt_hwcfg: vendor lib fwcfg completed
08-29 09:20:00.991  5936  5956 I bt_vendor: firmware callback
08-29 09:20:00.992  5936  5956 I bt_hci  : firmware_config_callback
,08-29 09:20:01.001  5936  5959 I bt_btu  : btu_task pending for preload complete event
,08-29 09:20:01.001  5936  5959 I bt_btu_task: Bluetooth chip preload is complete
,08-29 09:20:01.001  5936  5959 I bt_btu  : btu_task received preload complete event
,08-29 09:20:01.008  5936  5959 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 09:20:01.009  5936  5959 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 09:20:01.009  5936  5959 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 09:20:01.009  5936  5959 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 09:20:01.009  5936  5959 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 09:20:01.009  5936  5959 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 09:20:01.010  5936  5959 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 09:20:01.010  5936  5959 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:20:01.010  5936  5959 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 09:20:01.010  5936  5959 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 09:20:01.010  5936  5959 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 09:20:01.010  5936  5959 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 09:20:01.010  5936  5959 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 09:20:01.011  5936  5959 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 09:20:01.011  5936  5959 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 09:20:01.090  5936  5959 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f70c99
,08-29 09:20:01.091  5936  5959 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f70c99 
,08-29 09:20:01.113  5936  5952 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 09:20:01.114  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 09:20:01.115  5936  5952 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 09:20:01.117  5936  5952 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 09:20:01.120  5936  5952 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:20:01.121  5936  5952 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:20:01.121  5936  5952 D bt_hci  : do_postload posting postload work item
08-29 09:20:01.121  5936  5956 I bt_hci  : event_postload
08-29 09:20:01.121  5936  5956 I bt_vendor: sco_config_cb
08-29 09:20:01.121  5936  5956 I bt_hci  : sco_config_callback postload finished.
08-29 09:20:01.124  5936  5952 D bt_bte_conf: Device ID record 1 : primary
08-29 09:20:01.124  5936  5952 D bt_bte_conf:   vendorId            = 000f
08-29 09:20:01.124  5936  5952 D bt_bte_conf:   vendorIdSource      = 0001
08-29 09:20:01.124  5936  5952 D bt_bte_conf:   product             = 1200
,08-29 09:20:01.124  5936  5952 D bt_bte_conf:   version             = 1436
08-29 09:20:01.124  5936  5952 D bt_bte_conf:   clientExecutableURL = 
08-29 09:20:01.124  5936  5952 D bt_bte_conf:   serviceDescription  = 
08-29 09:20:01.124  5936  5952 D bt_bte_conf:   documentationURL    = 
08-29 09:20:01.124  5936  5952 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 09:20:01.125  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:01.125  5936  5949 D bt_stack_manager: event_start_up_stack finished
08-29 09:20:01.125  5936  5948 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 09:20:01.126  5936  5948 D BluetoothAdapterProperties: Setting state to 15
,08-29 09:20:01.126  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 09:20:01.130  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:01.131  5936  5948 I BluetoothAdapterState: Entering BleOnState
08-29 09:20:01.131  5936  5956 I bt_vendor: low_power_mode_cb
,08-29 09:20:01.134  5936  5948 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 09:20:01.134  5936  5948 D BluetoothAdapterProperties: Setting state to 11
08-29 09:20:01.134  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 09:20:01.139  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:20:01.140  5936  5936 D HeadsetService: Received start request. Starting profile...
08-29 09:20:01.140  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:01.142  5936  5936 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:20:01.142  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:01.142  5936  5936 D HeadsetStateMachine: make
,08-29 09:20:01.152  5936  5936 D HeadsetStateMachine: max_hf_connections = 1
,08-29 09:20:01.152  5936  5936 I bt_bluedroid: get_profile_interface handsfree
08-29 09:20:01.152  5936  5948 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:20:01.153  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 09:20:01.153  5936  5952 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 09:20:01.157  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:20:01.157  5936  5936 D A2dpService: Received start request. Starting profile...
08-29 09:20:01.158  5936  5936 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 09:20:01.158  5936  5936 I bt_bluedroid: get_profile_interface avrcp
,08-29 09:20:01.164  5936  5936 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:20:01.164  5936  5936 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:20:01.164  5936  5936 D A2dpStateMachine: make
,08-29 09:20:01.165  5936  5936 I bt_bluedroid: get_profile_interface a2dp
,08-29 09:20:01.165  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 09:20:01.167  5936  5967 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:20:01.168  5936  5936 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 09:20:01.169  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
08-29 09:20:01.169  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:20:01.170  5936  5936 D HidService: Received start request. Starting profile...
08-29 09:20:01.170  5936  5936 I bt_bluedroid: get_profile_interface hidhost
08-29 09:20:01.170  5936  5936 D HidService: setHidService(): set to: null
08-29 09:20:01.170  5936  5952 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f522d9
08-29 09:20:01.170  5936  5952 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 09:20:01.170  5936  5936 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 09:20:01.171  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:20:01.172  5936  5936 D HealthService: Received start request. Starting profile...
,08-29 09:20:01.173  5936  5936 I bt_bluedroid: get_profile_interface health
,08-29 09:20:01.175  5936  5936 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 09:20:01.175  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
08-29 09:20:01.175  5936  5936 D PanService: Received start request. Starting profile...
08-29 09:20:01.176  5936  5936 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:20:01.176  5936  5936 I bt_bluedroid: get_profile_interface pan
08-29 09:20:01.176  5936  5952 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 09:20:01.178  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:20:01.178  5936  5936 D BluetoothMapService: Received start request. Starting profile...
,08-29 09:20:01.178  5936  5936 D BluetoothMapService: start()
08-29 09:20:01.180  5936  5936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 09:20:01.181  5936  5936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 09:20:01.181  5936  5936 D BluetoothMapAppObserver: createReceiver()
08-29 09:20:01.182  5936  5936 D BluetoothMapAppObserver: initObservers()
08-29 09:20:01.182  5936  5936 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 09:20:01.188  5936  5936 V SapService: SapBinder()
08-29 09:20:01.188  5936  5936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:20:01.189  5936  5936 D SapService: Received start request. Starting profile...
08-29 09:20:01.189  5936  5936 V SapService: start()
,08-29 09:20:01.190  5936  5936 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:20:01.190  5936  5936 V BluetoothAdapterState: isTurningOn()=true
08-29 09:20:01.190  5936  5965 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:20:01.190  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:20:01.190  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:20:01.190  5936  5936 V BluetoothAdapterState: isTurningOff()=false
08-29 09:20:01.191  5936  5936 V BluetoothAdapterState: isTurningOn()=true
08-29 09:20:01.191  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:20:01.191  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:20:01.191  5936  5936 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:20:01.191  5936  5936 V BluetoothAdapterState: isTurningOn()=true
08-29 09:20:01.191  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:20:01.191  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isTurningOff()=false
08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isTurningOn()=true
08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isTurningOn()=true
08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:20:01.192  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:20:01.193  5936  5936 V BluetoothAdapterState: isTurningOff()=false
08-29 09:20:01.193  5936  5936 V BluetoothAdapterState: isTurningOn()=true
08-29 09:20:01.193  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:20:01.193  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:20:01.193  5936  5936 V BluetoothAdapterState: isTurningOff()=false
08-29 09:20:01.194  5936  5936 V BluetoothAdapterState: isTurningOn()=true
08-29 09:20:01.194  5936  5936 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:20:01.194  5936  5936 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:20:01.194  5936  5948 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 09:20:01.194  5936  5948 D BluetoothAdapterProperties: ScanMode =  20
08-29 09:20:01.194  5936  5948 D BluetoothAdapterProperties: State =  11
08-29 09:20:01.194  5936  5948 D BluetoothAdapterProperties: Setting state to 12
08-29 09:20:01.194  5936  5948 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 09:20:01.195  5936  5948 I BluetoothAdapterState: Entering OnState
,08-29 09:20:01.196  3061  3072 D BluetoothPan: onBluetoothStateChange on: true
,08-29 09:20:01.198  5936  5952 D BluetoothAdapterProperties: Scan Mode:21
08-29 09:20:01.198  5936  5952 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:20:01.198  5753  5764 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:20:01.199  3061  3061 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:20:01.200  3061  3061 D PanProfile: Bluetooth service connected
08-29 09:20:01.201  3061  3636 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:20:01.201  3061  3642 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:20:01.202  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:20:01.203  5753  5764 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:20:01.204  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:20:01.204  3061  3072 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:20:01.206  3061  3073 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:20:01.207  3061  3061 D BluetoothInputDevice: Proxy object connected
08-29 09:20:01.207  3061  3061 D HidProfile: Bluetooth service connected
08-29 09:20:01.207  5936  5936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:20:01.207   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:20:01.207  5936  5936 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 09:20:01.208   928   928 D BluetoothA2dp: Proxy object connected
08-29 09:20:01.208  5753  5763 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 09:20:01.209  5936  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:20:01.209  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:20:01.210  3061  3061 D BluetoothA2dp: Proxy object connected
08-29 09:20:01.210  5753  5753 D BluetoothA2dp: Proxy object connected
08-29 09:20:01.210  5753  5764 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:20:01.211   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:20:01.211  3454  3686 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:20:01.211  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:20:01.211  5936  5936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:20:01.211   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:20:01.212  3061  3642 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:20:01.212  5936  5936 D ObexServerSockets: Succeed to create listening sockets 
08-29 09:20:01.213  5936  5936 D ObexServerSockets0: startAccept()
08-29 09:20:01.213  5936  5936 D ObexServerSockets0: prepareForNewConnect()
,08-29 09:20:01.213  5753  5763 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:20:01.214  5936  5936 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 09:20:01.214  5936  5936 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 09:20:01.215  5753  5764 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:20:01.215  5936  5976 D ObexServerSockets0: Accepting socket connection...
08-29 09:20:01.215  5936  5977 D ObexServerSockets0: Accepting socket connection...
08-29 09:20:01.216  3061  3061 D BluetoothMap: Proxy object connected
08-29 09:20:01.216  3061  3061 D MapProfile: Bluetooth service connected
08-29 09:20:01.216  3061  3061 D BluetoothMap: getConnectedDevices()
08-29 09:20:01.218   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:20:01.218  5753  5753 D BluetoothInputDevice: Proxy object connected
08-29 09:20:01.218  5753  5753 D HidProfile: Bluetooth service connected
08-29 09:20:01.218   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 09:20:01.219  5936  5936 D BluetoothMapService: onReceive
08-29 09:20:01.219  5936  5936 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:20:01.219  5936  5936 D BluetoothMapService: STATE_ON
08-29 09:20:01.220  5753  5753 D BluetoothMap: Proxy object connected
08-29 09:20:01.220  5753  5753 D MapProfile: Bluetooth service connected
08-29 09:20:01.220  5753  5753 D BluetoothMap: getConnectedDevices()
08-29 09:20:01.221  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:01.222  5753  5753 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:20:01.222  5753  5753 D PanProfile: Bluetooth service connected
08-29 09:20:01.222  5936  5978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:20:01.222  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:01.224  5936  5978 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 09:20:01.224  5936  5978 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 09:20:01.225  5753  5753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:20:01.232  3538  3538 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:20:01.232  5753  5753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:20:01.238  5753  5753 D BluetoothPbap: Proxy object connected
,08-29 09:20:01.238  5753  5753 D PbapServerProfile: Bluetooth service connected
,08-29 09:20:01.244  5936  5936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:20:01.244  5936  5936 D ObexServerSockets0: prepareForNewConnect()
08-29 09:20:01.244  5936  5982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:20:01.246  3061  3061 D BluetoothPbap: Proxy object connected
08-29 09:20:01.246  3061  3061 D PbapServerProfile: Bluetooth service connected
,08-29 09:20:01.258  5936  5986 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:20:01.259  5936  5986 I BtOppRfcommListener: Accept thread started.
,08-29 09:20:01.286   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:01.303   928   928 D BluetoothHeadset: Proxy object connected
,08-29 09:20:01.303  5753  5763 D BluetoothHeadset: Proxy object connected
08-29 09:20:01.303  3454  3475 D BluetoothHeadset: Proxy object connected
,08-29 09:20:01.304  3061  3636 D BluetoothHeadset: Proxy object connected
08-29 09:20:01.304  3061  3061 D HeadsetProfile: Bluetooth service connected
,08-29 09:20:01.304   928   928 D BluetoothHeadset: Proxy object connected
08-29 09:20:01.304   928   928 D BluetoothHeadset: Proxy object connected
08-29 09:20:01.306  5753  5753 D HeadsetProfile: Bluetooth service connected
,08-29 09:20:01.310  5753  5764 D BluetoothHeadset: Proxy object connected
08-29 09:20:01.310  5753  5753 D HeadsetProfile: Bluetooth service connected
08-29 09:20:01.311   928   945 D BluetoothHeadset: Proxy object connected
,08-29 09:20:01.312  3454  3477 D BluetoothHeadset: Proxy object connected
,08-29 09:20:01.312   928   945 D BluetoothHeadset: Proxy object connected
,08-29 09:20:01.317   928   945 D BluetoothHeadset: Proxy object connected
,08-29 09:20:02.287   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:03.288   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:04.288   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:20:05.050  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:20:05.054  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:20:05.055  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:20:05.055  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@779c286 removed from the list
,08-29 09:20:05.055  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:20:05.056  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:05.056  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:20:05.059  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:20:05.059  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c0d747 added. We now have 4 listener(s)
08-29 09:20:05.060  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:20:05.062   928  3377 D WifiService: setWifiEnabled: false pid=5621, uid=10077
,08-29 09:20:05.062   928  3377 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:20:05.289   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:20:10.070  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:10.072   928   938 D WifiService: setWifiEnabled: true pid=5621, uid=10077
,08-29 09:20:10.072   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:20:10.080   506   922 D SoftapController: Softap fwReload - Ok
,08-29 09:20:10.085   506   922 D CommandListener: Setting iface cfg
08-29 09:20:10.086   506   922 D CommandListener: Trying to bring down wlan0
,08-29 09:20:10.088   506   922 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:20:10.093   928  2914 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 09:20:10.703   928  2914 D wifi    : set interface wlan0 flags (UP)
,08-29 09:20:10.706   928  2914 I WifiHAL : Initializing wifi
08-29 09:20:10.706   928  2914 I WifiHAL : Creating socket
08-29 09:20:10.711   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 09:20:10.712   928  2914 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 09:20:10.712   928  2914 D wifi    : Did set static halHandle = 0x7f66050880
08-29 09:20:10.713   928  2914 D wifi    : halHandle = 0x7f66050880, mVM = 0x7f8160d140, mCls = 0x2010ea
08-29 09:20:10.713   928  2914 D wifi    : array field set
,08-29 09:20:10.713   928  2914 I WifiNative-HAL: interface[0] = wlan0
08-29 09:20:10.715   928  5991 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547172452480
08-29 09:20:10.715   928  5991 D wifi    : waitForHalEvents called, vm = 0x7f8160d140, obj = 0x2010ea, env = 0x7f63382fc0
,08-29 09:20:10.760  5992  5992 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 09:20:10.780  5992  5992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:20:10.790  5992  5992 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:20:10.790  5992  5992 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 09:20:10.816   928  2914 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 09:20:10.824  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:10.832   928  2914 D WifiConfigStore: Loading config and enabling all networks 
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:20:10.833  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:20:10.836  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:20:10.838   928  2914 D WifiConfigStore: loaded 0 passpoint configs
08-29 09:20:10.838   928  2914 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 09:20:10.839   928  2914 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 09:20:10.840   928  2914 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 09:20:10.840   928  2914 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 09:20:10.840   928  2914 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:20:10.841  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:20:10.843  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:20:10.843   928  2914 D WifiNative-HAL: Setting external_sim to 1
08-29 09:20:10.844   928  2914 D wifi    : setting dfs flag to true, 0x7f685ff160
08-29 09:20:10.844   928  2914 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:20:10.844  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:10.845   928  2914 D wifi    : setting scan oui 0x7f685ff160
08-29 09:20:10.845   928  2914 D WifiHAL : Sending mac address OUI
08-29 09:20:10.845  4165  4165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:20:10.865   928  2914 E native  : do suspend true
,08-29 09:20:10.873   928  2914 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 09:20:10.873   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 09:20:10.873   928   928 D RttService: SCAN_AVAILABLE : 3
08-29 09:20:10.874   928  3025 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:20:10.874   506   922 D CommandListener: Setting iface cfg
,08-29 09:20:10.880   928  2892 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
08-29 09:20:10.880   928  2892 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 09:20:10.883   928  2892 D WifiNative-HAL: p2pGetDeviceAddress
08-29 09:20:10.883   928  2892 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 09:20:10.914   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=252677 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=22 mControllerEnergyUsed=83 }
,08-29 09:20:14.106  5992  5992 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 09:20:14.147   928  2914 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 09:20:14.155   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
08-29 09:20:14.156   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:20:14.176   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 09:20:14.225   928  2914 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 09:20:14.572  5992  5992 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 09:20:14.624  5992  5992 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 09:20:14.625  5992  5992 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 09:20:14.640   928  2914 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 09:20:14.641   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:20:14.641   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 09:20:14.660   928  2914 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:20:14.675   506   922 D CommandListener: Setting iface cfg
,08-29 09:20:14.681   928  2914 D WifiStateMachine: Start Dhcp Watchdog 4
,08-29 09:20:14.688   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 09:20:14.699   928  5997 D DhcpClient: Receive thread started
,08-29 09:20:14.793   928  2914 E native  : do suspend false
,08-29 09:20:14.820   928  5996 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 09:20:14.833   928  5997 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-29 09:20:14.834   928  5996 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-29 09:20:14.836   928  5996 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 09:20:14.864   928  5997 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 09:20:14.865   928  5996 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 09:20:14.869   506   922 D CommandListener: Setting iface cfg
,08-29 09:20:14.878   928  5996 D DhcpClient: Scheduling renewal in 86399s
,08-29 09:20:14.880   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 09:20:14.881   928  2914 E native  : do suspend true
,08-29 09:20:14.897   928  2914 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 09:20:14.898   928  2914 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 09:20:14.899   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 09:20:14.900   928  2918 D ConnectivityService: Adding iface wlan0 to network 103
08-29 09:20:14.900   928  2914 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 09:20:14.933   928  2918 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 09:20:14.933   928  2918 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,08-29 09:20:14.935   928  2918 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,08-29 09:20:14.937   928  2918 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,08-29 09:20:14.939   928  2918 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,08-29 09:20:14.946   928  2918 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-29 09:20:14.950   928  2918 D ConnectivityService: scheduleUnvalidatedPrompt 103
,08-29 09:20:14.950   928  2918 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
08-29 09:20:14.951   928  2918 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
08-29 09:20:14.951   928  2918 D ConnectivityService:    accepting network in place of null
08-29 09:20:14.951   928  2914 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 09:20:14.951   928  2918 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 09:20:14.951   928  2914 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:20:14.974   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:20:14.976   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=256738, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:20:14.996   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 09:20:15.000   928  2918 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,08-29 09:20:15.000   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:20:15.000  3424  3546 W QCNEJ   : |CORE| network available: 103
08-29 09:20:15.001   928  2918 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
08-29 09:20:15.001  3424  3546 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-29 09:20:15.003  3424  3546 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,08-29 09:20:15.003  3424  3546 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
08-29 09:20:15.004   928   945 D Tethering: MasterInitialState.processMessage what=3
,08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:15.013  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:20:15.015  4814  4848 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,08-29 09:20:15.015  4814  4848 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 09:20:15.015  4814  4848 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 09:20:15.016  4814  4848 E SarControlService: no key has been found,reset the power
08-29 09:20:15.016  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:15.016  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 09:20:15.016  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 09:20:15.016  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 09:20:15.017  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:20:15.017  4855  4855 D QcrilMsgTunnelSocket: [1012] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 09:20:15.018  4814  4865 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 09:20:15.019  4814  4865 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 09:20:15.019  4814  4865 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 09:20:15.020  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:15.020  5621  5621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:20:15.021  3815  3815 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 09:20:15.022  5621  5621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:15.023  4855  4855 D QcrilMsgTunnelSocket: [1013] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 09:20:15.024  3815  3815 D SystemUpdateService: onCreate
,08-29 09:20:15.027  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000f403000000000000ffffffff]
,08-29 09:20:15.028  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:20:15.028  4855  4869 D QcrilMsgTunnelSocket: [1012] < OEM_HOOK_RAW [null]
,08-29 09:20:15.028  4855  4869 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6145a4a HexData = [00000000f503000000000000ffffffff]
08-29 09:20:15.028  4855  4869 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:20:15.028  4855  4869 D QcrilMsgTunnelSocket: [1013] < OEM_HOOK_RAW [null]
08-29 09:20:15.028  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:20:15.029  4814  4826 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 09:20:15.029  4855  4855 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:20:15.029  4814  4824 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 09:20:15.030  3815  3815 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:20:15.039  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 09:20:15.043  3815  5215 I iu.UploadsManager: num queued entries: 0
,08-29 09:20:15.044  3815  5215 I iu.UploadsManager: num updated entries: 0
08-29 09:20:15.045  3815  5215 I iu.SyncManager: NEXT; no task
,08-29 09:20:15.047   928  5994 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:805::200e
,08-29 09:20:15.048  3815  6007 I SystemUpdateService: active receiver: enabled
,08-29 09:20:15.050  3815  3815 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:20:15.052  3815  3815 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 09:20:15.054  5687  5687 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:20:15.058  5687  5687 D SprintDMHelper: simOperator: 
08-29 09:20:15.058  5687  5687 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:15.084  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:20:15.085  3815  6007 I SystemUpdateService: showing system update notification
,08-29 09:20:15.086  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:20:15.087  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:15.087  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c0d747 removed from the list
08-29 09:20:15.087  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:20:15.087  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:15.087  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:20:15.090  5621  6016 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-29 09:20:15.090  5621  6016 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 09:20:15.096  3815  6007 V SystemUpdateService: retry (wakeup: false) in 3599953 ms
,08-29 09:20:15.098  3815  3815 D SystemUpdateService: onDestroy
,08-29 09:20:15.135   928  5994 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 13:20:15 GMT], X-Android-Received-Millis=[1472476815135], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472476815088]}
,08-29 09:20:15.136   928  2918 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 09:20:15.136   928  2918 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
,08-29 09:20:15.136   928  2918 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
08-29 09:20:15.137   928  2918 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 09:20:15.208  4165  6012 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 09:20:15.290   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:16.291   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:17.292   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:18.101  5621  6016 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-29 09:20:18.102  5621  6016 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 09:20:18.103  5621  6016 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 09:20:18.104  5621  6020 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-29 09:20:18.104  5621  6020 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-29 09:20:18.105  5621  6016 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 09:20:18.105  5621  6020 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 09:20:18.107  5621  6016 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 09:20:18.108  5621  6022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Sender)
,08-29 09:20:18.110  5621  6020 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 09:20:18.112  5621  6023 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: OutgoingSocketThread/Receiver)
,08-29 09:20:18.113  5621  6024 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Sender)
,08-29 09:20:18.114  5621  6023 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: OutgoingSocketThread/Receiver)
08-29 09:20:18.114  5621  6023 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 09:20:18.114  5621  6020 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-29 09:20:18.114  5621  6023 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 09:20:18.115  5621  6025 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Receiver)
08-29 09:20:18.116  5621  6025 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: IncomingSocketThread/Receiver)
08-29 09:20:18.117  5621  6025 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 09:20:18.117  5621  6025 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 09:20:18.293   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:19.294   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:20.294   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:20:21.099  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 09:20:21.100  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 09:20:21.108  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e629a69 Bundle[{}]
08-29 09:20:21.109  5621  5667 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 09:20:21.109  5621  5667 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 09:20:21.109  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 09:20:21.110  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 09:20:21.110  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 09:20:21.112  5621  5667 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 09:20:21.116  5621  5667 I System.out: Running OutgoingSocketThread
,08-29 09:20:21.120  5621  6026 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-29 09:20:21.120  5621  6026 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 09:20:22.959   928  2918 D ConnectivityService: handlePromptUnvalidated 103
,08-29 09:20:24.130  5621  6027 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-29 09:20:24.130  5621  6027 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 09:20:24.130  5621  6027 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 09:20:24.131  5621  6027 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 09:20:24.134  5621  6026 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-29 09:20:24.134  5621  6026 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 09:20:24.134  5621  6027 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-29 09:20:24.134  5621  6026 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 09:20:24.136  5621  6029 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
,08-29 09:20:24.137  5621  6026 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 09:20:24.141  5621  6031 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Sender)
,08-29 09:20:24.143  5621  6026 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-29 09:20:24.146  5621  6030 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,08-29 09:20:24.147  5621  6032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Receiver)
,08-29 09:20:24.147  5621  6030 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
08-29 09:20:24.147  5621  6030 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-29 09:20:24.147  5621  6030 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 09:20:24.149  5621  6032 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: OutgoingSocketThread/Receiver)
08-29 09:20:24.149  5621  6032 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-29 09:20:24.149  5621  6032 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 09:20:27.129  5621  5667 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,08-29 09:20:27.130  5621  5667 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 09:20:27.130  5621  5667 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 179)
08-29 09:20:27.135  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:20:27.135  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89d7b74 added. We now have 3 listener(s)
,08-29 09:20:27.140  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 09:20:27.140  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:20:27.141  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:20:27.141  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:20:27.141  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@663189d added. We now have 4 listener(s)
08-29 09:20:27.141  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:20:27.142  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:20:27.147  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:27.154  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:20:27.157  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:27.158  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:20:27.159  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:20:27.159  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:20:27.159  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:20:27.159  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:27.159  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:27.159  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:20:27.159  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:20:27.159  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89d7b74 removed from the list
,08-29 09:20:27.159  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:27.159  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@663189d removed from the list
08-29 09:20:27.161  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:27.162  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:20:27.162  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:20:27.163  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:27.163  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:20:27.166  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:27.166  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:20:27.167  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:27.167  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:27.167  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@663189d not in the list
08-29 09:20:27.167  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:27.167  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:20:27.168  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:27.168  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:20:27.168  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:27.169  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@663189d not in the list
08-29 09:20:27.169  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:27.169  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:27.169  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:27.169  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89d7b74 not in the list
08-29 09:20:27.170  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:20:27.170  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca9a0e3 added. We now have 3 listener(s)
,08-29 09:20:27.171  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:20:27.172  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:20:27.172  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:20:27.172  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:20:27.172  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0dae0 added. We now have 4 listener(s)
08-29 09:20:27.172  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:20:27.173  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:20:27.178  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:27.182  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:20:27.184  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:27.185  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:20:27.185  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:20:27.185  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 09:20:27.185  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:20:27.185  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:20:27.185  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:20:27.188  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:27.190  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:20:27.190  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:20:27.192  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:27.195  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:20:27.196  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 09:20:27.196  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:20:27.200  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:20:27.200  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:20:27.200  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:20:27.201  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:20:27.203  5936  5972 D BtGatt.GattService: registerClient() - UUID=8b228a10-56f3-46c8-9fd4-303e2d92de4b
08-29 09:20:27.204  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=8b228a10-56f3-46c8-9fd4-303e2d92de4b, clientIf=5
08-29 09:20:27.205  5621  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 09:20:27.206  5936  5975 D BtGatt.GattService: start scan with filters
,08-29 09:20:27.209  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:20:27.209  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:20:27.209  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:20:27.209  5936  5955 D BtGatt.ScanManager: handling starting scan
08-29 09:20:27.209  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:20:27.212  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:20:27.212  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:20:27.212  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:20:27.213  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:20:27.213  5936  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5ab246d
,08-29 09:20:27.216  5621  5667 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 09:20:27.217  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:20:27.217  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:20:27.217  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:27.217  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 09:20:27.217  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:20:27.217  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:20:27.217  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:20:27.218  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:20:27.218  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:20:27.218  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:20:27.220  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:20:27.221  5936  5946 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:20:27.221  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:20:27.221  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:20:27.221  5936  5972 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 09:20:27.222  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:20:27.222  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:20:27.222  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:20:27.222  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:20:27.222  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:20:27.222  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:20:27.223  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:20:27.223  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:20:27.223  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:20:27.223  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:20:27.224  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:20:27.225  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:20:27.225  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:20:27.225  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:20:27.229  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:20:27.229  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:20:27.229  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:20:27.229  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 09:20:27.241  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:20:27.241  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:20:27.246  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:20:27.247  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:20:27.253  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:20:27.253  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:20:27.253  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:20:27.260  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:20:27.260  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:20:27.261  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 09:20:27.266  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:20:27.266  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:20:27.727  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:20:27.727  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:20:27.727  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 09:20:30.226  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:20:30.226  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:20:30.226  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:20:30.226  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:30.227  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:20:30.227  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:20:30.227  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:20:30.227  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca9a0e3 removed from the list
08-29 09:20:30.227  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:20:30.228  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0dae0 removed from the list
08-29 09:20:30.228  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:20:30.228  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:30.229  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:30.230  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:20:30.233  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:20:30.233  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:30.233  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:30.233  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0dae0 not in the list
08-29 09:20:30.233  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:30.233  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:30.236  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:30.236  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:20:30.237  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:30.237  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d0dae0 not in the list
08-29 09:20:30.238  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:30.238  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:30.238  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:30.239  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca9a0e3 not in the list
08-29 09:20:30.239  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:20:30.239  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ddbe55 added. We now have 3 listener(s)
,08-29 09:20:30.241  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:20:30.241  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:20:30.241  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:20:30.242  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:20:30.242  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d26206a added. We now have 4 listener(s)
08-29 09:20:30.242  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:20:30.242  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:20:30.245  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:30.250  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:20:30.252  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:30.252  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:20:30.253  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 09:20:30.253  5621  5667 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
08-29 09:20:30.254  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-29 09:20:30.254  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 09:20:30.254  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 09:20:30.254  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 09:20:30.254  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:20:30.255  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 09:20:30.256  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:20:30.256  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:30.256  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 09:20:30.256  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:20:30.256  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 09:20:30.256  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:20:30.256  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:20:30.257  5621  6033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:20:30.261  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:30.261  5621  6033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-29 09:20:30.261  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 09:20:30.262  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 09:20:30.262  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:20:30.266  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:20:30.267  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:20:30.267  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:20:30.269  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 09:20:30.269  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:20:30.270  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
08-29 09:20:30.270  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 09:20:30.270  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 09:20:30.270  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 09:20:30.270  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:20:30.272  5936  5973 D BtGatt.GattService: registerClient() - UUID=14395d00-8cf9-44d6-bb53-b13cf8cceefb
08-29 09:20:30.273  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=14395d00-8cf9-44d6-bb53-b13cf8cceefb, clientIf=5
,08-29 09:20:30.273  5621  5631 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-29 09:20:30.275  5936  5954 D BtGatt.AdvertiseManager: message : 0
,08-29 09:20:30.277  5936  5954 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 09:20:30.287  5936  5952 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 09:20:30.292  5936  5952 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 09:20:30.293  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 09:20:30.293  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:20:30.294  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:20:30.295  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 09:20:30.296  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 09:20:30.296  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 09:20:30.296  5621  5621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 09:20:30.296  5621  5621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 09:20:30.296  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-29 09:20:30.297  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 09:20:30.298  5621  5621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 09:20:30.299  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 09:20:30.800  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 09:20:30.800  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 09:20:30.800  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 09:20:31.818   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273580, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:20:33.299  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:20:33.299  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 09:20:33.300  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 09:20:33.300  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 09:20:33.300  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 09:20:33.300  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 09:20:33.301  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 09:20:33.301  5621  5667 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:20:33.301  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:20:33.301  5621  6033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 09:20:33.301  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:20:33.301  5621  6033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:20:33.301  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 09:20:33.301  5621  6033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 09:20:33.301  5621  5621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:20:33.302  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 09:20:33.302  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:20:33.304  5621  5667 D BluetoothAdapter: STATE_ON
,08-29 09:20:33.304  5621  5667 D BluetoothLeScanner: could not find callback wrapper
08-29 09:20:33.304  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:20:33.305  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-29 09:20:33.307  5936  5954 D BtGatt.AdvertiseManager: message : 1
08-29 09:20:33.309  5936  5954 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 09:20:33.321  5936  5952 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 09:20:33.321  5936  5952 D BtGatt.GattService: Client app is not null!
,08-29 09:20:33.322  5936  5947 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:20:33.322  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:20:33.322  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 09:20:33.322  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 09:20:33.323  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 09:20:33.323  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 09:20:33.324  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:20:33.324  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:20:33.325  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:20:33.325  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:20:33.327  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:20:33.327  5621  5621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 09:20:33.327  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:33.327  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:20:33.327  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:20:33.327  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:20:33.327  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ddbe55 removed from the list
08-29 09:20:33.327  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:20:33.327  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:20:33.327  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d26206a removed from the list
08-29 09:20:33.327  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:20:33.327  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:20:33.327  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:33.328  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:33.328  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:33.329  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:20:33.329  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:20:33.329  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:33.329  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d26206a not in the list
08-29 09:20:33.330  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:33.330  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:33.331  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:33.331  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:20:33.331  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:33.331  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d26206a not in the list
08-29 09:20:33.331  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:33.331  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:33.331  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:20:33.331  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ddbe55 not in the list
08-29 09:20:33.332  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:20:33.332  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9882037 added. We now have 3 listener(s)
08-29 09:20:33.334  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:20:33.334  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:20:33.334  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:20:33.334  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:20:33.334  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a50a9a4 added. We now have 4 listener(s)
08-29 09:20:33.335  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:20:33.337  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:20:33.340  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:33.346  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:20:33.348  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:33.348  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:20:33.348  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:20:33.348  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:20:33.349  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:20:33.349  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:20:33.349  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:20:33.352  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:33.353  5621  5667 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:20:33.353  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:20:33.355  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:33.357  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:20:33.358  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 09:20:33.358  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:20:33.360  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:20:33.360  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:20:33.360  5621  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:20:33.361  5621  5667 D BluetoothAdapter: STATE_ON
08-29 09:20:33.362  5936  5947 D BtGatt.GattService: registerClient() - UUID=78504ef6-6ba2-46fc-8c22-b14f8d2854fc
08-29 09:20:33.363  5936  5952 D BtGatt.GattService: onClientRegistered() - UUID=78504ef6-6ba2-46fc-8c22-b14f8d2854fc, clientIf=5
,08-29 09:20:33.363  5621  5631 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:20:33.364  5936  5973 D BtGatt.GattService: start scan with filters
08-29 09:20:33.366  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:20:33.366  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:20:33.366  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:20:33.366  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:20:33.366  5936  5955 D BtGatt.ScanManager: handling starting scan
,08-29 09:20:33.368  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:20:33.369  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:20:33.369  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:20:33.370  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:20:33.372  5936  5952 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:20:33.372  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:20:33.372  5936  5955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 09:20:33.378  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:20:33.378  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:20:33.378  5936  5955 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:20:33.378  5936  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 09:20:33.389  5936  5952 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 09:20:33.389  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:20:33.394  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 09:20:33.394  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:20:33.828  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:20:33.870  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 09:20:33.870  5621  5621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:20:33.870  5621  5621 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 09:20:35.295   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:36.296   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:36.380  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:20:36.380  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:20:36.380  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:20:36.381  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.381  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 09:20:36.381  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 09:20:36.381  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 09:20:36.381  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 09:20:36.381  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:20:36.382  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 09:20:36.382  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:20:36.384  5621  5667 D BluetoothAdapter: STATE_ON
,08-29 09:20:36.386  5936  5975 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:20:36.389  5936  5963 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:20:36.389  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:20:36.390  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:20:36.390  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:20:36.390  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:20:36.390  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:20:36.392  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:20:36.393  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:20:36.393  5621  5667 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:20:36.393  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:20:36.395  5936  5936 D BtGatt.ScanManager: awakened up at time 278157
08-29 09:20:36.396  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 09:20:36.400  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:36.400  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.400  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 09:20:36.400  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:20:36.400  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9882037 removed from the list
08-29 09:20:36.401  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:36.401  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a50a9a4 removed from the list
08-29 09:20:36.401  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 09:20:36.401  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:20:36.401  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.401  5621  5621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:20:36.401  5621  5621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:20:36.403  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.403  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.403  5936  5952 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:20:36.404  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:20:36.404  5936  5955 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:20:36.405  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:20:36.405  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:36.405  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:20:36.406  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a50a9a4 not in the list
08-29 09:20:36.406  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.406  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.408  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:36.408  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:20:36.408  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:36.408  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a50a9a4 not in the list
08-29 09:20:36.408  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:36.409  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.409  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.409  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9882037 not in the list
08-29 09:20:36.409  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:20:36.410  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebd2309 added. We now have 3 listener(s)
08-29 09:20:36.412  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:20:36.412  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:20:36.412  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:20:36.413  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:20:36.413  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92ad90e added. We now have 4 listener(s)
08-29 09:20:36.413  5621  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:20:36.413  5936  5952 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:20:36.414  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:20:36.414  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:20:36.414  5936  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 09:20:36.418  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:20:36.423  5621  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:20:36.426  5621  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:20:36.426  5621  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:20:36.426  5621  5667 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:20:36.426  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:20:36.426  5621  5667 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:20:36.426  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:36.426  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.427  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:20:36.427  5621  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:20:36.427  5621  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebd2309 removed from the list
08-29 09:20:36.427  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:36.427  5621  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92ad90e removed from the list
,08-29 09:20:36.429  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:20:36.429  5621  5667 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:20:36.429  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.430  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.430  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.432  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:20:36.432  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:36.432  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:36.432  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92ad90e not in the list
08-29 09:20:36.432  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.432  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.434  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:20:36.434  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:20:36.434  5621  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:20:36.434  5621  5667 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92ad90e not in the list
08-29 09:20:36.434  5621  5667 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:20:36.434  5621  5667 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:20:36.434  5621  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:20:36.434  5621  5667 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebd2309 not in the list
08-29 09:20:36.435  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 09:20:36.435  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 09:20:36.436  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 09:20:36.436  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:20:36.436  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-29 09:20:36.436  5621  5667 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:20:36.436  5936  5952 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-29 09:20:36.436  5936  5952 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:20:36.437  5936  5952 D BtGatt.GattService: current time is 278199889371
08-29 09:20:36.437  5621  5621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:20:36.439  5936  5952 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -77, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -76, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 09:20:36.440  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 09:20:36.441  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 09:20:36.441  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 09:20:36.442  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 09:20:36.442  5936  5952 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 09:20:36.902  5621  5621 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:20:37.297   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:38.298   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:38.449  5621  6034 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name)
,08-29 09:20:39.299   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:20:40.300   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:20:40.448  5621  5667 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 188
,08-29 09:20:40.448  5621  5667 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 188, name: My test thread name)
,08-29 09:20:40.452  5621  6035 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name)
,08-29 09:20:40.452  5621  6035 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 189, thread name: My test thread name)
08-29 09:20:40.453  5621  6035 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-29 09:20:40.458  5621  5667 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 09:20:40.465  5621  6036 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name)
,08-29 09:20:40.465  5621  6036 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 193, thread name: My test thread name): Test exception.
08-29 09:20:40.466  5621  6036 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-29 09:20:40.471  5621  5667 I jxcore-log: Total number of executed tests:  82
08-29 09:20:40.471  5621  5667 I jxcore-log: 
,08-29 09:20:40.472  5621  5667 I jxcore-log: Number of passed tests:  82
08-29 09:20:40.472  5621  5667 I jxcore-log: 
08-29 09:20:40.472  5621  5667 I jxcore-log: Number of failed tests:  0
08-29 09:20:40.472  5621  5667 I jxcore-log: 
08-29 09:20:40.472  5621  5667 I jxcore-log: Number of ignored tests:  0
08-29 09:20:40.472  5621  5667 I jxcore-log: 
08-29 09:20:40.473  5621  5667 I jxcore-log: Total duration:  105959
08-29 09:20:40.473  5621  5667 I jxcore-log: 
,08-29 09:20:40.484  5621  6034 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-29 09:20:40.488  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.488  5621  5667 I jxcore-log: 
,08-29 09:20:40.494  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.494  5621  5667 I jxcore-log: 
08-29 09:20:40.497  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.497  5621  5667 I jxcore-log: 
,08-29 09:20:40.500  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.500  5621  5667 I jxcore-log: 
,08-29 09:20:40.502  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.502  5621  5667 I jxcore-log: 
,08-29 09:20:40.504  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.504  5621  5667 I jxcore-log: 
,08-29 09:20:40.508  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.508  5621  5667 I jxcore-log: 
,08-29 09:20:40.511  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 09:20:40.511  5621  5667 I jxcore-log: 
,08-29 09:20:40.512  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.512  5621  5667 I jxcore-log: 
08-29 09:20:40.512  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.512  5621  5667 I jxcore-log: 
08-29 09:20:40.513  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:20:40.513  5621  5667 I jxcore-log: 
08-29 09:20:40.514  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.514  5621  5667 I jxcore-log: 
08-29 09:20:40.514  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 09:20:40.514  5621  5667 I jxcore-log: 
08-29 09:20:40.515  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.515  5621  5667 I jxcore-log: 
08-29 09:20:40.516  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 09:20:40.516  5621  5667 I jxcore-log: 
08-29 09:20:40.517  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:20:40.517  5621  5667 I jxcore-log: 
,08-29 09:20:40.518  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:20:40.518  5621  5667 I jxcore-log: 
08-29 09:20:40.519  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.519  5621  5667 I jxcore-log: 
,08-29 09:20:40.520  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.520  5621  5667 I jxcore-log: 
,08-29 09:20:40.521  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.521  5621  5667 I jxcore-log: 
,08-29 09:20:40.522  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.522  5621  5667 I jxcore-log: 
,08-29 09:20:40.523  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.523  5621  5667 I jxcore-log: 
08-29 09:20:40.524  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.524  5621  5667 I jxcore-log: 
08-29 09:20:40.524  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.524  5621  5667 I jxcore-log: 
08-29 09:20:40.525  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.525  5621  5667 I jxcore-log: 
08-29 09:20:40.525  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.525  5621  5667 I jxcore-log: 
08-29 09:20:40.526  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.526  5621  5667 I jxcore-log: 
08-29 09:20:40.527  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.527  5621  5667 I jxcore-log: 
08-29 09:20:40.527  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.527  5621  5667 I jxcore-log: 
08-29 09:20:40.528  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.528  5621  5667 I jxcore-log: 
,08-29 09:20:40.529  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.529  5621  5667 I jxcore-log: 
,08-29 09:20:40.530  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.530  5621  5667 I jxcore-log: 
,08-29 09:20:40.531  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.531  5621  5667 I jxcore-log: 
08-29 09:20:40.532  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.532  5621  5667 I jxcore-log: 
,08-29 09:20:40.533  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.533  5621  5667 I jxcore-log: 
,08-29 09:20:40.534  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.534  5621  5667 I jxcore-log: 
,08-29 09:20:40.535  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.535  5621  5667 I jxcore-log: 
08-29 09:20:40.535  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.535  5621  5667 I jxcore-log: 
08-29 09:20:40.536  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.536  5621  5667 I jxcore-log: 
08-29 09:20:40.537  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.537  5621  5667 I jxcore-log: 
08-29 09:20:40.537  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.537  5621  5667 I jxcore-log: 
,08-29 09:20:40.538  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.538  5621  5667 I jxcore-log: 
,08-29 09:20:40.539  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.539  5621  5667 I jxcore-log: 
08-29 09:20:40.540  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.540  5621  5667 I jxcore-log: 
,08-29 09:20:40.541  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.541  5621  5667 I jxcore-log: 
,08-29 09:20:40.542  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.542  5621  5667 I jxcore-log: 
,08-29 09:20:40.543  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:20:40.543  5621  5667 I jxcore-log: 
,08-29 09:20:40.543  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.543  5621  5667 I jxcore-log: 
08-29 09:20:40.544  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:20:40.544  5621  5667 I jxcore-log: 
08-29 09:20:40.545  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.545  5621  5667 I jxcore-log: 
08-29 09:20:40.545  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.545  5621  5667 I jxcore-log: 
08-29 09:20:40.546  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.546  5621  5667 I jxcore-log: 
08-29 09:20:40.546  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.546  5621  5667 I jxcore-log: 
08-29 09:20:40.547  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.547  5621  5667 I jxcore-log: 
08-29 09:20:40.548  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:20:40.548  5621  5667 I jxcore-log: 
,08-29 09:20:40.549  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.549  5621  5667 I jxcore-log: 
,08-29 09:20:40.549  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 09:20:40.549  5621  5667 I jxcore-log: 
08-29 09:20:40.550  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.550  5621  5667 I jxcore-log: 
,08-29 09:20:40.551  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:20:40.551  5621  5667 I jxcore-log: 
08-29 09:20:40.551  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 09:20:40.551  5621  5667 I jxcore-log: 
,08-29 09:20:40.552  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:20:40.552  5621  5667 I jxcore-log: 
,08-29 09:20:40.553  5621  5667 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:20:40.553  5621  5667 I jxcore-log: 
,08-29 09:20:40.556  5621  5667 I jxcore-log: My device name is: Huawei-Nexus 6P
08-29 09:20:40.556  5621  5667 I jxcore-log: 
,08-29 09:20:43.290  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-29 09:20:43.290  5621  5667 I jxcore-log: 
,08-29 09:20:43.908  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-29 09:20:43.908  5621  5667 I jxcore-log: 
,08-29 09:20:43.926  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-29 09:20:43.926  5621  5667 I jxcore-log: 
,08-29 09:20:43.930  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-29 09:20:43.930  5621  5667 I jxcore-log: 
,08-29 09:20:43.934  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-29 09:20:43.934  5621  5667 I jxcore-log: 
,08-29 09:20:43.944  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-29 09:20:43.944  5621  5667 I jxcore-log: 
,08-29 09:20:43.947  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-29 09:20:43.947  5621  5667 I jxcore-log: 
,08-29 09:20:46.102  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-29 09:20:46.102  5621  5667 I jxcore-log: 
,08-29 09:20:46.113  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-29 09:20:46.113  5621  5667 I jxcore-log: 
,08-29 09:20:46.121  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-29 09:20:46.121  5621  5667 I jxcore-log: 
,08-29 09:20:46.225  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-29 09:20:46.225  5621  5667 I jxcore-log: 
,08-29 09:20:46.776  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-29 09:20:46.776  5621  5667 I jxcore-log: 
,08-29 09:20:46.959  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-29 09:20:46.959  5621  5667 I jxcore-log: 
,08-29 09:20:46.963  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-29 09:20:46.963  5621  5667 I jxcore-log: 
,08-29 09:20:47.090  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-29 09:20:47.090  5621  5667 I jxcore-log: 
,08-29 09:20:47.104  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-29 09:20:47.104  5621  5667 I jxcore-log: 
,08-29 09:20:47.107  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-29 09:20:47.107  5621  5667 I jxcore-log: 
,08-29 09:20:47.111  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-29 09:20:47.111  5621  5667 I jxcore-log: 
,08-29 09:20:47.121  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-29 09:20:47.121  5621  5667 I jxcore-log: 
,08-29 09:20:47.133  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-29 09:20:47.133  5621  5667 I jxcore-log: 
,08-29 09:20:47.187  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-29 09:20:47.187  5621  5667 I jxcore-log: 
,08-29 09:20:47.191  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-29 09:20:47.191  5621  5667 I jxcore-log: 
,08-29 09:20:47.209  5621  5667 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-29 09:20:47.209  5621  5667 I jxcore-log: 
,08-29 09:20:47.217  5621  5667 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-29 09:20:47.218  5621  5667 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-29 09:20:47.218  5621  5667 I jxcore-log: 
,08-29 09:20:48.168   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=289931, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 09:21:00.301   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:01.302   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:02.303   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:03.304   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:04.305   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:04.519   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306281, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:21:05.305   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:21:30.306   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:21:30.307   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:21:34.858   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=336621, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 09:21:45.308   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:46.309   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:47.311   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:48.312   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:49.313   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:50.314   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:21:51.198   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=352961, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:21:55.316   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:56.317   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:57.318   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:58.320   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:21:59.321   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:00.322   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:22:10.323   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:11.325   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:12.326   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:13.328   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:14.329   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:15.330   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:22:30.331   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:31.332   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:32.334   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:33.335   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:34.337   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:35.337   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:22:55.339   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:56.340   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:57.341   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:58.343   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:22:59.344   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:00.344   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:23:04.979   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=426741, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 09:23:21.359   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443121, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:23:25.345   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:23:25.345   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:23:45.346   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:46.348   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:47.349   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:48.350   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:49.351   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:50.351   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:23:55.353   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:56.354   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:57.355   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:58.357   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:23:59.358   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:00.359   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:24:10.360   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:11.362   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:12.363   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:13.365   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:14.366   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:15.367   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:24:20.378   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=502141, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 09:24:30.368   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:31.369   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:32.371   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:33.372   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:34.373   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:35.374   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:24:47.358   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=529120, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:24:55.375   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:56.376   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:57.378   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:58.379   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:24:59.381   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:25:00.382   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:25:20.138   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=561900, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 09:25:25.382   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:25:25.383   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:25:31.558   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=573320, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:25:49.728   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=591490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 09:25:50.393   546  1139 E QC-QMI  : qmi_client [546] 8: failed to locate client data
,08-29 09:25:50.395   518   518 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,08-29 09:25:50.396   518   518 E QC-QMI  : QMUX qmux_client_id=8 not found in qmux client list, unable to remove
08-29 09:25:50.401   546   546 I Atfwd_Daemon: Stop the daemon....
,08-29 09:25:50.454  6050  6050 I libmdmdetect: ESOC framework not supported
,08-29 09:25:50.455  6050  6050 I libmdmdetect: Found internal modem: modem
08-29 09:25:50.446  6050  6050 W ATFWD-daemon: type=1400 audit(0.0:73): avc: denied { read write } for name="diag" dev="tmpfs" ino=1155 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
08-29 09:25:50.456  6050  6050 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 09:25:50.465  6050  6050 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 09:25:50.465  6050  6050 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,08-29 09:25:50.466  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:25:51.470  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:25:52.471  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:25:53.472  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:25:54.473  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:25:55.473  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:26:00.475  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:01.476  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:02.478  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:03.479  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:04.481  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:05.482  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:26:06.079   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=607841, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:26:15.483  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:16.485  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:17.486  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:18.488  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:19.248   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=621010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 09:26:19.489  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:20.490  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:26:35.491  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:35.598   928  5995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=637360, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 09:26:36.493  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:37.494  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:38.496  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:39.497  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:26:40.498  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:27:00.500  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:01.501  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:02.503  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:03.504  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:04.505  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:05.506  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:27:30.507  6050  6050 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:27:30.507  6050  6050 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:27:35.508  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:36.509  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:37.510  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:38.511  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:39.512  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:40.513  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:27:45.514  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:46.516  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:47.517  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:48.518  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:49.519  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:27:50.520  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:28:00.521  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:01.523  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:02.524  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:03.525  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:04.527  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:05.528  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:28:20.529  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:21.530  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:22.531  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:23.532  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:24.534  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:25.535  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:28:45.536  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:46.538  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:47.539  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:48.541  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:49.542  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:28:50.542  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:29:15.543  6050  6050 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:29:15.544  6050  6050 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:29:25.545  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:26.546  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:27.547  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:28.548  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:29.549  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:30.550  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:29:35.551  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:36.552  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:37.554  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:38.555  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:39.556  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:40.557  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:29:50.558  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:51.559  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:52.561  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:53.562  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:54.563  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:29:55.564  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:30:10.565  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:11.566  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:12.568  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:13.569  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:14.570  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:15.571  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:30:35.572  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:36.573  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:37.575  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:38.576  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:39.578  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:30:40.578  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:31:05.579  6050  6050 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:31:05.579  6050  6050 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:31:20.581  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:21.582  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:22.583  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:23.585  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:24.586  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:25.587  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:31:30.589  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:31.590  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:32.591  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:33.592  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:34.594  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:35.595  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:31:45.596  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:46.598  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:47.599  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:48.601  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:49.602  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:31:50.603  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:32:05.605  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:06.606  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:07.607  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:08.609  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:09.610  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:10.611  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:32:30.612  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:31.614  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:32.615  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:33.616  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:34.618  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:32:35.618  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:33:00.183   928  3511 I ActivityManager: Start proc 6062:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-29 09:33:00.223  6062  6062 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,08-29 09:33:00.243  6062  6062 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 09:33:00.243  6062  6062 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 09:33:00.243  6062  6062 I GAv4    :   adb logcat -s GAv4
,08-29 09:33:00.260  6062  6062 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,08-29 09:33:00.266  6062  6062 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 09:33:00.283  6062  6077 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 09:33:00.289   928   938 I ActivityManager: Killing 5339:android.process.acore/u0a2 (adj 15): empty #17
,08-29 09:33:00.619  6050  6050 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:33:00.619  6050  6050 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:33:20.620  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:21.622  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:22.623  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:23.624  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:24.625  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:25.626  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:33:30.628  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:31.629  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:32.630  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:33.632  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:34.633  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:35.633  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:33:45.634  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:46.636  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:47.637  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:48.638  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:49.639  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:33:50.640  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:34:05.641  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:06.643  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:07.644  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:08.646  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:09.648  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:10.648  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:34:30.649  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:31.650  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:32.651  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:33.652  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:34.653  6050  6050 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:34:35.654  6050  6050 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:35:00.654  6050  6050 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:35:00.655  6050  6050 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:35:25.664  6050  6052 E QC-QMI  : qmi_client [6050] 1d: failed to locate client data
,08-29 09:35:25.667   518   518 E QC-QMI  : qmuxd: RX on fd=16 returned error=0 errno[2:No such file or directory]
,08-29 09:35:25.669   518   518 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
08-29 09:35:25.672  6050  6050 I Atfwd_Daemon: Stop the daemon....
,08-29 09:35:25.718  6081  6081 I libmdmdetect: ESOC framework not supported
08-29 09:35:25.719  6081  6081 I libmdmdetect: Found internal modem: modem
08-29 09:35:25.720  6081  6081 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 09:35:25.716  6081  6081 W ATFWD-daemon: type=1400 audit(0.0:74): avc: denied { read write } for name="diag" dev="tmpfs" ino=1155 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,08-29 09:35:25.729  6081  6081 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 09:35:25.729  6081  6081 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,08-29 09:35:25.730  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:26.733  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:27.735  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:28.736  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:29.738  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:30.739  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:35:35.740  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:36.741  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:37.743  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:38.744  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:39.745  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:40.746  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:35:50.748  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:51.750  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:52.751  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:53.752  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:54.754  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:35:55.755  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:36:10.756  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:11.758  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:12.759  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:13.760  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:14.761  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:15.762  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:36:20.645   928   940 I UsageStatsService: User[0] Flushing usage stats to disk
,08-29 09:36:35.763  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:36.764  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:37.766  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:38.767  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:39.768  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:36:40.768  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:37:05.769  6081  6081 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:37:05.769  6081  6081 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:37:10.770  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:11.771  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:12.772  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:13.774  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:14.775  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:15.776  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:37:20.777  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:21.779  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:22.780  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:23.781  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:24.783  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:25.783  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:37:35.785  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:36.786  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:37.787  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:38.788  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:39.789  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:40.790  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:37:55.791  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:56.793  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:57.794  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:58.795  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:37:59.796  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:38:00.797  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:38:20.799  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:38:21.800  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:38:22.801  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:38:23.802  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:38:24.803  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:38:25.804  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:38:50.804  6081  6081 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:38:50.805  6081  6081 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:39:00.806  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:01.807  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:02.808  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:03.809  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:04.810  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:05.811  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:39:10.812  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:11.813  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:12.815  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:13.816  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:14.818  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:15.819  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:39:25.820  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:26.822  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:27.823  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:28.824  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:29.825  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:30.826  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:39:45.827  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:46.829  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:47.830  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:48.831  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:49.832  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:39:50.832  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:40:10.833  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:11.835  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:12.836  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:13.838  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:14.839  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:15.839  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 09:40:40.840  6081  6081 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 09:40:40.840  6081  6081 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:40:55.842  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:56.843  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:57.844  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:58.846  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:40:59.847  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:00.848  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:41:05.850  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:06.851  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:07.853  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:08.854  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:09.856  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:10.856  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 09:41:20.858  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:21.859  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:22.861  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:23.862  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:24.864  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:25.864  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 09:41:40.866  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:41.868  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:42.869  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:43.871  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:44.872  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:41:45.873  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:42:05.874  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:42:06.876  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:42:07.877  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:42:08.879  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:42:09.880  6081  6081 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:42:10.880  6081  6081 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,TIME-OUT KILL (timeout was 1400000ms)
```
