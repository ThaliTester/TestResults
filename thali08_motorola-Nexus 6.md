#### Test 797510150d7f48d_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-04 12:00:49.445   873  1995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=375037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-04 12:00:50.095  3693  3693 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 12:00:50.100  3693  3693 D AndroidRuntime: CheckJNI is OFF
08-04 12:00:50.142  3693  3693 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 12:00:50.192  3693  3693 I Radio-JNI: register_android_hardware_Radio DONE
08-04 12:00:50.213  3693  3693 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-04 12:00:50.218   873  1796 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 12:00:50.281   873  1796 I ActivityManager: Start proc 3703:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-04 12:00:50.284  3693  3693 D AndroidRuntime: Shutting down VM
08-04 12:00:50.386  3703  3703 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-04 12:00:50.412  3703  3703 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-04 12:00:50.419  3703  3703 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6008-6010)
08-04 12:00:50.419  3703  3703 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 12:00:50.434  3703  3703 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8530f26}
08-04 12:00:50.434  3703  3703 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 12:00:50.435  3703  3703 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 12:00:50.440  3703  3703 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 12:00:50.441  3703  3703 E SysUtils: ApplicationContext is null in ApplicationStatus
08-04 12:00:50.459  3703  3703 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-04 12:00:50.469  3703  3703 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 12:00:50.469  3703  3703 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 12:00:50.469  3703  3703 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 12:00:50.469  3703  3703 I Adreno  : Build Date                       : 10/20/15
08-04 12:00:50.469  3703  3703 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 12:00:50.469  3703  3703 I Adreno  : Local Branch                     : M14
08-04 12:00:50.469  3703  3703 I Adreno  : Remote Branch                    : 
08-04 12:00:50.469  3703  3703 I Adreno  : Remote Branch                    : 
08-04 12:00:50.469  3703  3703 I Adreno  : Reconstruct Branch               : 
,08-04 12:00:50.532   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8a0a25:true
,08-04 12:00:50.561  3703  3703 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-04 12:00:50.575  3703  3703 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-04 12:00:50.643  3703  3740 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-04 12:00:50.656  3703  3727 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-04 12:00:50.695  3703  3740 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 12:00:50.712  1668  1668 I Keyboard.Facilitator: onFinishInput()
,08-04 12:00:50.771   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +432ms (total +512ms)
,08-04 12:00:50.820  3703  3703 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3703
,08-04 12:00:50.994  3703  3703 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-04 12:00:51.220  3703  3741 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1658848976
08-04 12:00:51.228  3703  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 12:00:51.228  3703  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 12:00:51.228  3703  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 12:00:51.228  3703  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 12:00:51.228  3703  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 12:00:51.228  3703  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d79935 added. We now have 1 listener(s)
08-04 12:00:51.232  3703  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-04 12:00:51.233  3703  3741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:00:51.234  3703  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:00:51.234  3703  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 12:00:51.238  3703  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d76658 added. We now have 1 listener(s)
08-04 12:00:51.238  3703  3741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:00:51.244   873  1316 D WifiService: New client listening to asynchronous messages
08-04 12:00:51.247  3703  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:00:51.247  3703  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 12:00:51.247  3703  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 12:00:51.248  3703  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 12:00:51.248  3703  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 12:00:51.256  3703  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:00:51.257  3703  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-04 12:00:51.268  3703  3741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:00:51.269  3703  3741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:00:51.269  3703  3741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 12:00:51.269  3703  3741 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:00:51.271  3703  3741 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 12:00:51.272  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:00:51.275  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:00:51.303  3703  3703 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 12:00:52.340  3703  3748 W jxcore-log: Initializing JXcore engine
,08-04 12:00:52.341  3703  3748 W jxcore-log: JXcore engine is ready
,08-04 12:00:52.376  3748  3748 W Thread-324: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-04 12:00:52.376  3748  3748 W Thread-324: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12737]" dev="sockfs" ino=12737 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-04 12:00:52.389  3703  3748 W jxcore-log: Starting JXcore engine
,08-04 12:00:52.376  3748  3748 W Thread-324: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-04 12:00:52.376  3748  3748 W Thread-324: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23458]" dev="sockfs" ino=23458 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-04 12:00:52.468  3703  3748 W jxcore-log: Platform android
08-04 12:00:52.468  3703  3748 W jxcore-log: 
,08-04 12:00:52.468  3703  3748 W jxcore-log: Process ARCH arm
08-04 12:00:52.468  3703  3748 W jxcore-log: 
,08-04 12:00:52.682  3703  3748 I jxcore-log: JXcore Cordova bridge is ready!
08-04 12:00:52.682  3703  3748 I jxcore-log: 
,08-04 12:00:52.683  3703  3748 W jxcore-log: JXcore engine is started
,08-04 12:00:52.695  3703  3741 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 12:00:52.703  3703  3703 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 12:01:05.499   873  1995 D NetlinkSocketObserver: NeighborEvent{elapsedMs=391090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-04 12:01:08.398  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 12:01:08.398  3703  3748 I jxcore-log: 
,08-04 12:01:08.401  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 12:01:08.401  3703  3748 I jxcore-log: 
,08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:08.413  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:01:08.417  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:01:08.419  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 12:01:08.419  3703  3748 I jxcore-log: 
,08-04 12:01:08.421  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 12:01:08.421  3703  3748 I jxcore-log: 
,08-04 12:01:08.759  3703  3748 D ExecuteNativeTests: Running unit tests
,08-04 12:01:08.816  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:08.817  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 added. We now have 2 listener(s)
08-04 12:01:08.818  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:01:08.818  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:01:08.818  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:01:08.818  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:08.818  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a added. We now have 2 listener(s)
08-04 12:01:08.818  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:08.819  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:01:08.823  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:08.835  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:01:08.837  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:01:08.837  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:08.842  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:08.845  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 12:01:08.850  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 12:01:08.850  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 12:01:08.852  3703  3748 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-04 12:01:08.853  3703  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-04 12:01:08.853  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:01:08.853  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:01:08.853  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:01:08.853  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:08.853  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:08.854  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:08.854  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:01:08.854  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:01:08.854  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:08.854  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:01:08.854  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:08.854  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 removed from the list
08-04 12:01:08.855  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:08.855  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a removed from the list
08-04 12:01:08.855  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:08.855  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.855  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:08.855  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.857  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:08.857  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:08.857  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:08.857  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:08.859  3703  3748 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 12:01:08.860  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:08.860  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:08.860  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:08.860  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:08.860  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.860  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.860  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:08.860  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:08.860  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:08.860  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:08.860  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.860  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:08.861  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.861  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.862  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:08.862  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:08.862  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:08.862  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 12:01:08.867  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 12:01:08.868  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 12:01:08.869  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 12:01:08.869  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:08.869  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:08.869  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:08.870  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:08.870  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.870  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.870  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
,08-04 12:01:08.870  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:08.870  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:08.870  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:08.870  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.870  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.870  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.870  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.872  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:08.872  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:08.872  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:08.872  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:08.873  3703  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 12:01:08.874  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:08.878  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:01:08.880  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:01:08.880  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:01:08.880  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:01:08.880  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:01:08.880  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:01:08.880  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:08.880  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:01:08.883  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:08.885  3703  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:01:08.885  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 12:01:08.885  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:08.889  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:01:08.890  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:01:08.890  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:01:08.892  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-04 12:01:08.896  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-04 12:01:08.896  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:01:08.896  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-04 12:01:08.897  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:01:08.898  3703  3748 D BluetoothAdapter: STATE_ON
,08-04 12:01:08.903  2560  2574 D BtGatt.GattService: registerClient() - UUID=06eca87f-2d84-4786-881b-e03ccd51e92c
,08-04 12:01:08.905  2560  2616 D BtGatt.GattService: onClientRegistered() - UUID=06eca87f-2d84-4786-881b-e03ccd51e92c, clientIf=5
,08-04 12:01:08.905  3703  3713 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 12:01:08.906  2560  2762 D BtGatt.GattService: start scan with filters
,08-04 12:01:08.909  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:01:08.909  2560  2621 D BtGatt.ScanManager: handling starting scan
08-04 12:01:08.909  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:01:08.909  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:01:08.909  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:01:08.910  2560  2621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:08.911  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:01:08.911  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:01:08.911  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:01:08.912  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:01:08.914  3703  3748 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 12:01:08.918  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:08.918  3703  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:01:08.918  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:08.919  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:01:08.919  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:08.919  2560  2616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:01:08.919  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:01:08.919  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:01:08.919  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:08.919  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:01:08.919  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:01:08.919  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:01:08.919  2560  2621 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 12:01:08.919  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:01:08.919  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:01:08.920  3703  3748 D BluetoothAdapter: STATE_ON
08-04 12:01:08.921  2560  2574 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:01:08.922  2560  2762 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:01:08.922  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:01:08.922  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:01:08.922  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 12:01:08.922  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-04 12:01:08.922  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:01:08.923  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:08.924  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:01:08.924  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:01:08.924  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:01:08.924  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:08.925  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:08.925  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.925  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:08.925  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:08.925  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:08.925  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:08.925  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:08.925  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:08.925  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:08.925  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.925  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:08.925  3703  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 12:01:08.926  2560  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:01:08.926  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:08.927  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:08.927  2560  2621 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 12:01:08.927  2560  2621 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:08.935  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:01:08.941  2560  2616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:01:08.941  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:01:08.941  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:01:08.942  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:08.943  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:01:08.943  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:01:08.943  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-04 12:01:08.943  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:08.944  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 12:01:08.946  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:08.946  2560  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:01:08.946  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:08.950  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:08.954  3703  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 12:01:08.954  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:01:08.955  2560  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:01:08.956  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:08.956  2560  2621 D BtGatt.ScanManager: stopping BLe Batch
,08-04 12:01:08.963  2560  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 12:01:08.963  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:08.963  2560  2621 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:01:08.964  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:01:08.964  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:01:08.964  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:01:08.967  2560  2616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:01:08.967  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:01:08.970  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 12:01:08.970  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:01:08.970  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:01:08.972  3703  3748 D BluetoothAdapter: STATE_ON
,08-04 12:01:08.974  2560  2773 D BtGatt.GattService: registerClient() - UUID=e2c9ea9a-ce78-4e73-ab04-aceb0b3579ac
,08-04 12:01:08.974  2560  2616 D BtGatt.GattService: onClientRegistered() - UUID=e2c9ea9a-ce78-4e73-ab04-aceb0b3579ac, clientIf=5
08-04 12:01:08.975  3703  3713 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:01:08.975  2560  2762 D BtGatt.GattService: start scan with filters
,08-04 12:01:08.979  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:01:08.979  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:01:08.979  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:01:08.979  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 12:01:08.980  2560  2621 D BtGatt.ScanManager: handling starting scan
,08-04 12:01:08.982  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:01:08.982  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:01:08.982  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:01:08.984  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:01:08.986  2560  2616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:01:08.986  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:08.986  3703  3748 I io.jxcore.node.ConnectionHelper: start: OK
08-04 12:01:08.986  2560  2621 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:01:08.988  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:08.988  3703  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 12:01:08.988  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:08.988  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-04 12:01:08.988  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:08.989  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-04 12:01:08.989  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 12:01:08.989  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:01:08.989  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:01:08.989  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-04 12:01:08.989  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:01:08.989  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:01:08.990  3703  3748 D BluetoothAdapter: STATE_ON
08-04 12:01:08.990  2560  2762 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:01:08.990  2560  2573 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 12:01:08.990  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:01:08.990  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 12:01:08.991  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:01:08.991  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:01:08.991  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:01:08.992  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:01:08.992  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:01:08.992  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:01:08.992  2560  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 12:01:08.992  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:01:08.992  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:08.992  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:08.992  2560  2621 D BtGatt.ScanManager: Starting BLE batch scan
,08-04 12:01:08.992  2560  2621 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:01:08.994  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:08.994  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.994  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:08.994  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 12:01:08.994  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:08.994  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:08.994  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:08.994  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:08.994  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:08.994  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.994  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:08.994  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:08.994  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:08.995  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:08.995  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:08.995  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:08.995  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
,08-04 12:01:08.996  3703  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 12:01:08.997  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:09.000  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:01:09.001  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:09.001  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 12:01:09.001  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:01:09.001  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:01:09.001  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:01:09.001  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:09.001  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:01:09.002  2560  2616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:01:09.003  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.004  3703  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:01:09.004  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 12:01:09.005  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:09.007  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:01:09.008  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:09.008  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 12:01:09.008  2560  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:01:09.008  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 12:01:09.008  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.012  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:01:09.012  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:01:09.012  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-04 12:01:09.013  3703  3748 D BluetoothAdapter: STATE_ON
,08-04 12:01:09.015  2560  2574 D BtGatt.GattService: registerClient() - UUID=7da2a732-cabb-41a4-b6f1-642458289c83
08-04 12:01:09.015  2560  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:01:09.015  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.015  2560  2616 D BtGatt.GattService: onClientRegistered() - UUID=7da2a732-cabb-41a4-b6f1-642458289c83, clientIf=5
08-04 12:01:09.015  2560  2621 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:01:09.016  3703  3714 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:01:09.016  2560  2762 D BtGatt.GattService: start scan with filters
,08-04 12:01:09.018  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 12:01:09.018  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:01:09.018  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-04 12:01:09.018  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:01:09.020  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:01:09.020  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 12:01:09.021  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:01:09.021  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:01:09.022  2560  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:01:09.022  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.022  2560  2621 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 12:01:09.023  3703  3748 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 12:01:09.023  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-04 12:01:09.023  3703  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:01:09.023  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:09.023  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-04 12:01:09.023  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.023  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:01:09.023  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:01:09.023  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-04 12:01:09.023  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:01:09.023  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:01:09.023  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:01:09.023  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:01:09.024  3703  3748 D BluetoothAdapter: STATE_ON
08-04 12:01:09.024  2560  2762 D BtGatt.GattService: stopScan() - queue size =0
08-04 12:01:09.026  2560  2573 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-04 12:01:09.026  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:01:09.026  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:01:09.026  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:01:09.026  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:01:09.026  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 12:01:09.027  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:09.027  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:01:09.027  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:01:09.027  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:01:09.027  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:09.028  2560  2616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:01:09.028  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.029  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:09.029  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:01:09.029  3703  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-04 12:01:09.029  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.029  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.029  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.029  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.029  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:09.029  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:01:09.029  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
,08-04 12:01:09.029  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.029  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.029  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.029  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:09.029  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.029  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.029  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.030  2560  2621 D BtGatt.ScanManager: handling starting scan
08-04 12:01:09.030  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:09.030  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.030  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.031  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.032  3703  3748 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 12:01:09.032  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.032  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.033  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:01:09.033  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.033  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.033  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.033  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.033  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.033  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.033  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.033  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.033  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.033  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.033  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.034  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.035  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.035  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.035  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.036  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 12:01:09.036  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:01:09.036  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.036  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.036  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.036  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.036  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.036  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.035  2560  2616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:01:09.036  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.036  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
,08-04 12:01:09.036  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.036  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.036  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.036  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.037  2560  2621 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 12:01:09.036  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.037  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.038  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.038  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:09.038  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:09.038  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.039  3703  3748 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-04 12:01:09.039  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:01:09.039  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:09.039  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:01:09.039  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.039  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.039  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.039  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.039  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.039  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.039  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:01:09.039  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.039  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.040  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.040  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.041  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:09.041  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.041  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:09.041  2560  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:01:09.041  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.041  3703  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-04 12:01:09.041  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.041  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.042  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:09.042  2560  2621 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:01:09.042  2560  2621 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:01:09.042  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.042  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.042  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.042  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.042  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.042  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:09.042  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.042  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.042  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.043  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.043  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.043  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.044  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:09.044  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:09.044  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.044  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.044  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 12:01:09.046  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 12:01:09.046  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:01:09.046  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:01:09.046  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 12:01:09.046  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 12:01:09.046  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.046  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.046  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:01:09.047  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.047  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.047  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.047  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.047  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.047  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.048  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.048  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.048  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.048  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.049  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.051  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.051  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.051  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.051  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
,08-04 12:01:09.052  2560  2616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:01:09.052  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.052  3703  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:01:09.052  3703  3748 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-04 12:01:09.052  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 12:01:09.057  3703  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:01:09.058  2560  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:01:09.058  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.058  3703  3748 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 12:01:09.058  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 12:01:09.058  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-04 12:01:09.058  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 12:01:09.058  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 12:01:09.058  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-04 12:01:09.058  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 12:01:09.059  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510],
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 12:01:09.060  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-04 12:01:09.061  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 12:01:09.061  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 12:01:09.061  3703  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-04 12:01:09.062  3703  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 12:01:09.062  3703  3748 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 12:01:09.063  2560  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:01:09.063  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.063  2560  2621 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:01:09.062  3703  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:01:09.063  3703  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 12:01:09.063  3703  3748 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-04 12:01:09.063  3703  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:01:09.063  3703  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 12:01:09.063  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-04 12:01:09.068  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 12:01:09.068  2560  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-04 12:01:09.068  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.069  2560  2621 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:01:09.069  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 12:01:09.069  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-04 12:01:09.070  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 12:01:09.070  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-04 12:01:09.070  3703  3748 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 12:01:09.070  3703  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 12:01:09.071  3703  3748 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 12:01:09.071  3703  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 388)
08-04 12:01:09.072  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:01:09.072  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.072  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.072  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:01:09.072  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.072  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.072  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 12:01:09.073  3703  3749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:01:09.073  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.073  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:09.073  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.073  2560  2616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:01:09.073  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.073  2560  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:09.073  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.073  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.073  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.073  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.074  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:09.074  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.074  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.074  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.075  3703  3748 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-04 12:01:09.076  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.076  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.076  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.076  3703  3750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 388
,08-04 12:01:09.076  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.076  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.076  3703  3750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 388)
08-04 12:01:09.076  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.076  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
,08-04 12:01:09.076  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.076  3703  3749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 388)
08-04 12:01:09.076  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
,08-04 12:01:09.076  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.076  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.077  2560  2757 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-04 12:01:09.076  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.077  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.077  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.077  3703  3750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 388)
08-04 12:01:09.078  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.078  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:09.078  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.078  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.079  3703  3748 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 12:01:09.079  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-04 12:01:09.079  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.079  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.079  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:01:09.079  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.079  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.080  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.080  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.080  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.080  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.080  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.080  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.080  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.080  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.082  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:09.082  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.082  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.082  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.082  3703  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 12:01:09.082  3703  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 12:01:09.082  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:01:09.083  3703  3748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 12:01:09.083  3703  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 12:01:09.083  3703  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 12:01:09.083  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:01:09.083  3703  3748 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 12:01:09.083  3703  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 12:01:09.083  3703  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-04 12:01:09.083  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 12:01:09.083  3703  3748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 12:01:09.083  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.083  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.083  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.083  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.084  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.084  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.084  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.084  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.084  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.084  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.084  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.084  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.084  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.084  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.085  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.085  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.085  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.085  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.086  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.086  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.086  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.086  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.086  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.086  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.086  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.086  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.086  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.086  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.087  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.087  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.087  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.087  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.087  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.087  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.087  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.087  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.087  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.087  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.087  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.087  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.087  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.087  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.087  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:01:09.087  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.087  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.088  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.088  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.089  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.089  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.089  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.089  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.090  3703  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 12:01:09.090  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:09.091  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 12:01:09.092  3703  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 12:01:09.092  3703  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 12:01:09.092  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 12:01:09.092  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 12:01:09.092  3703  3703 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 12:01:09.092  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.092  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 12:01:09.092  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 12:01:09.093  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 12:01:09.093  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.093  3703  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 12:01:09.093  3703  3751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:01:09.093  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.093  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:09.093  3703  3703 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 12:01:09.093  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:01:09.093  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:01:09.093  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:01:09.093  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.093  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.094  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:09.094  3703  3751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-04 12:01:09.094  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.094  3703  3751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 12:01:09.095  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.095  3703  3751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 12:01:09.095  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:09.095  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:09.095  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.095  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:09.095  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:09.095  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.095  3703  3703 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 12:01:09.095  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.095  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.095  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.095  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.095  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.096  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:01:09.096  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.096  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.096  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.096  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.097  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.097  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.097  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.097  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.098  3703  3748 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 12:01:09.099  3703  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 12:01:09.099  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 12:01:09.100  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 12:01:09.100  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.100  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.100  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:01:09.101  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.101  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.101  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.101  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.101  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.101  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.101  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.101  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.101  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.101  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.101  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.102  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.102  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:09.102  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.103  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.106  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.106  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.106  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.106  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.106  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.106  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.107  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.107  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.107  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.107  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.107  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.107  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:09.107  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.107  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.108  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.108  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:09.108  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.108  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.109  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:09.109  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:09.109  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:09.110  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:09.110  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:09.110  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.110  3703  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f809f5 not in the list
08-04 12:01:09.110  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.110  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.110  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:09.110  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.110  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.110  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:09.110  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:09.111  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:09.112  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:09.112  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:09.112  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323138a not in the list
08-04 12:01:09.113  3703  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 12:01:09.113  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:01:09.113  3703  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 12:01:09.113  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 12:01:09.113  3703  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 12:01:09.113  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-04 12:01:09.116  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 12:01:09.116  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 12:01:09.116  3703  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 12:01:09.117  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 12:01:09.117  3703  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 12:01:09.117  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-04 12:01:09.117  3703  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 12:01:09.117  3703  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 12:01:09.118  3703  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 12:01:09.118  3703  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-04 12:01:09.119  3703  3748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 12:01:09.119  3703  3748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 12:01:09.119  3703  3748 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 12:01:09.119  3703  3748 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-04 12:01:09.120  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:09.120  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@633075c added. We now have 2 listener(s)
08-04 12:01:09.120  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:09.123  3703  3748 D BluetoothAdapter: enable(): BT is already enabled..!
,08-04 12:01:09.123   873  1796 D WifiService: setWifiEnabled: true pid=3703, uid=10000
08-04 12:01:09.123   873  1796 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:01:09.124  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:09.124  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d205a65 added. We now have 3 listener(s)
08-04 12:01:09.124  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:09.134  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:01:09.135  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16f733a added. We now have 4 listener(s)
,08-04 12:01:09.135  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:09.137  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-04 12:01:09.137  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a6bebeb added. We now have 5 listener(s)
,08-04 12:01:09.137  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:09.141   873   883 D WifiService: setWifiEnabled: false pid=3703, uid=10000
,08-04 12:01:09.141   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 12:01:09.144  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:09.148  2560  2610 D BluetoothAdapterState: Current state: ON, message: 23
08-04 12:01:09.148  2560  2610 D BluetoothAdapterProperties: Setting state to 13
08-04 12:01:09.148  2560  2610 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 12:01:09.148  2560  2610 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:09.149  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:01:09.149  2560  2610 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:01:09.151  2560  2616 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:01:09.152  2560  2610 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 12:01:09.155  2560  2560 D HeadsetService: Received stop request...Stopping profile...
08-04 12:01:09.159  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:09.159  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:01:09.160  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:09.165  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:09.165  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:01:09.165  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:09.166  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:01:09.166  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 12:01:09.169  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:09.171   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-04 12:01:09.171   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-04 12:01:09.172   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:01:09.172   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:01:09.172   873   886 I ActivityManager: Start proc 3754:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-04 12:01:09.172  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:09.172  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:01:09.173  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:09.173  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:09.173   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:09.174   873   873 D BluetoothHeadset: Proxy object disconnected
,08-04 12:01:09.174  2560  2560 D BluetoothMapService: onReceive
08-04 12:01:09.174  2560  2560 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:01:09.174  2560  2560 D BluetoothMapService: STATE_TURNING_OFF
08-04 12:01:09.174  1744  1758 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:09.174  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:09.174  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:09.174  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:01:09.174  1360  2386 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:09.174   873   873 D BluetoothHeadset: Proxy object disconnected
,08-04 12:01:09.176  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:09.178  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-04 12:01:09.174  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:09.180  2560  2560 D A2dpService: Received stop request...Stopping profile...
08-04 12:01:09.180  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:09.181  2560  2767 D A2dpStateMachine: Exit Disconnected: -1
,08-04 12:01:09.183   873   873 D BluetoothA2dp: Proxy object disconnected
,08-04 12:01:09.184  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:09.185  2560  2560 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-04 12:01:09.185  2560  2560 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-04 12:01:09.186  2560  2560 D BluetoothMapService: MAP Service closeService in
,08-04 12:01:09.186  2560  2560 D BluetoothMapMasInstance0: MAP Service shutdown
08-04 12:01:09.186  2560  2560 D ObexServerSockets0: shutdown(block = true)
,08-04 12:01:09.186  2560  2560 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-04 12:01:09.186  2560  2560 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-04 12:01:09.186  2560  2616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 12:01:09.186  2560  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:09.187  2560  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:09.187  2560  2783 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-04 12:01:09.187  2560  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:09.187  2560  2757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 12:01:09.187  2560  2785 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 12:01:09.187  2560  2616 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-04 12:01:09.188  2560  2560 I BtOppRfcommListener: stopping Accept Thread
08-04 12:01:09.188  2560  3268 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 12:01:09.188  2560  3268 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 12:01:09.189   873  1315 E native  : do suspend true
,08-04 12:01:09.190  2560  2560 D HidService: Received stop request...Stopping profile...
08-04 12:01:09.190  2560  2560 D HidService: Stopping Bluetooth HidService
08-04 12:01:09.191  2560  2560 D HealthService: Received stop request...Stopping profile...
08-04 12:01:09.192  2560  2560 D PanService: Received stop request...Stopping profile...
,08-04 12:01:09.194  2560  2560 D BluetoothMapService: Received stop request...Stopping profile...
08-04 12:01:09.194  2560  2560 D BluetoothMapService: stop()
08-04 12:01:09.196  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-04 12:01:09.196  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-04 12:01:09.196  1360  1360 D HidProfile: Bluetooth service disconnected
08-04 12:01:09.197  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 12:01:09.197  1360  1360 D PanProfile: Bluetooth service disconnected
08-04 12:01:09.197  2560  2560 D BluetoothMapAppObserver: deinitObservers()
08-04 12:01:09.197  2560  2560 D BluetoothMapAppObserver: removeReceiver()
08-04 12:01:09.198  1360  1360 D BluetoothMap: Proxy object disconnected
08-04 12:01:09.198  2560  2560 V BluetoothAdapterState: isTurningOff()=true
,08-04 12:01:09.198  1360  1360 D MapProfile: Bluetooth service disconnected
08-04 12:01:09.198  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:09.198  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:09.198  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:09.199  2560  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:09.199  2560  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:09.199  2560  2736 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:01:09.199  2560  2736 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:01:09.199  2560  2736 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:01:09.199  2560  2736 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-04 12:01:09.199  2560  2616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-04 12:01:09.201  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:09.201  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:09.202   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-04 12:01:09.202   873  1997 D DhcpClient: Clearing IP address
08-04 12:01:09.201  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:09.203  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:09.204  2560  2560 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-04 12:01:09.204  2560  2616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 12:01:09.204  2560  2560 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 12:01:09.205   371   871 D CommandListener: Setting iface cfg
08-04 12:01:09.211   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 12:01:09.212   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-04 12:01:09.212   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
08-04 12:01:09.213   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 12:01:09.213   873  1315 E native  : do suspend true
08-04 12:01:09.215  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:09.215  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:09.215  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:09.215  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:09.215   455   455 E Parcel  : Reading a NULL string not supported here.
08-04 12:01:09.215  2560  2560 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-04 12:01:09.216  2560  2616 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-04 12:01:09.217  2560  2560 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 12:01:09.217  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:09.217  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:09.217  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:01:09.217  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:09.217  2560  2560 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-04 12:01:09.218  2560  2560 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 12:01:09.220  2560  2560 D BluetoothMapService: MAP Service closeService in
08-04 12:01:09.220  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:09.220  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:09.221  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:09.221  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:09.222  1523  2317 V NativeCrypto: Read error: ssl=0xaebea200: I/O error during system call, Connection timed out
08-04 12:01:09.222  2560  2610 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 12:01:09.222  2560  2610 D BluetoothAdapterProperties: Setting state to 15
08-04 12:01:09.222  2560  2610 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-04 12:01:09.222   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:09.222   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:01:09.223  1360  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 12:01:09.223  2560  2610 I BluetoothAdapterState: Entering BleOnState
08-04 12:01:09.223   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-04 12:01:09.224   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:09.224  2560  2560 D BluetoothMapService: cleanup()
08-04 12:01:09.224  2560  2560 D BluetoothMapService: MAP Service closeService in
08-04 12:01:09.225  1360  2386 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:01:09.225  1360  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-04 12:01:09.226  1360  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:01:09.227  1744  1758 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:09.227  1360  2386 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:01:09.228   873  1999 D DhcpClient: Receive thread stopped
08-04 12:01:09.229  1360  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:09.230   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:09.231  2560  2610 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-04 12:01:09.231  2560  2610 D BluetoothAdapterProperties: Setting state to 16
08-04 12:01:09.232  2560  2610 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-04 12:01:09.233  2560  2610 D BluetoothAdapterProperties: onBleDisable
08-04 12:01:09.233  2560  2610 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:01:09.233  2560  2611 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-04 12:01:09.234  2560  2616 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:01:09.234  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:09.234  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:09.235  2560  2736 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 12:01:09.235  2560  2736 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:09.235  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:09.235  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:09.236  1523  2317 V NativeCrypto: SSL shutdown failed: ssl=0xaebea200: I/O error during system call, Broken pipe
,08-04 12:01:09.237  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:09.237  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:09.237  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:09.237  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:09.240  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:09.241  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:09.257   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:01:09.264  3754  3754 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-04 12:01:09.275  3754  3754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:01:09.275   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:01:09.275   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-04 12:01:09.276   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 12:01:09.276   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:09.277   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:01:09.282  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:09.283  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:09.286   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:01:09.289  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:01:09.291   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cdbc1d6:true
,08-04 12:01:09.303   873   884 I ActivityManager: Start proc 3773:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-04 12:01:09.304   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:01:09.307  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:09.307  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:09.308  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:09.308  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:09.309   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 12:01:09.309  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:09.309  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:09.310  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:09.310  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:09.311  1900  2102 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:01:09.340   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-04 12:01:09.346  3754  3754 D LocalBluetoothProfileManager: Adding local MAP profile
,08-04 12:01:09.347  3754  3754 D BluetoothMap: Create BluetoothMap proxy object
,08-04 12:01:09.351  3773  3773 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-04 12:01:09.355  3754  3754 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-04 12:01:09.371  3754  3754 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:01:09.380   873  1389 I ActivityManager: Killing 2372:com.google.android.talk/u0a61 (adj 15): empty #17
,08-04 12:01:09.438  2560  2616 I bt_hci  : shut_down
,08-04 12:01:09.438  2560  2622 D bt_hwcfg: hw_epilog_process
,08-04 12:01:09.447  2560  2622 I bt_vendor: low_power_mode_cb
,08-04 12:01:09.473  2560  2622 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-04 12:01:09.473  2560  2622 I bt_vendor: epilog_cb
08-04 12:01:09.473  2560  2622 I bt_hci  : epilog_finished_callback
,08-04 12:01:09.480  2560  2616 I bt_hci_h4: hal_close
08-04 12:01:09.480  2560  2616 I bt_userial_vendor: device fd = 51 close
,08-04 12:01:09.518  3773  3773 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.518  3773  3773 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.518  3773  3773 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.518  3773  3773 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.518  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.519  3773  3773 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.r.k.d(PG:583)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.519  3773  3773 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.519  3773  3773 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.File.exists(File.java:361)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.519  3773  3773 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:09.519  3773  3773 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:09.528  3754  3754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:01:09.548  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:01:09.567  3754  3754 D DockEventReceiver: finishStartingService: stopping service
08-04 12:01:09.596  3703  3703 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:01:09.628   873  1389 I ActivityManager: Start proc 3806:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-04 12:01:09.631   873  1389 I ActivityManager: Killing 3090:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-04 12:01:09.729  2560  2611 D bt_stack_manager: event_shut_down_stack finished.
08-04 12:01:09.730  2560  2610 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 12:01:09.736  3806  3806 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-04 12:01:09.744  2560  2610 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-04 12:01:09.745  2560  2560 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:01:09.746  2560  2560 D BtGatt.GattService: Received stop request...Stopping profile...
,08-04 12:01:09.746  2560  2560 D BtGatt.GattService: stop()
08-04 12:01:09.746  2560  2560 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 12:01:09.748  2560  2560 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:09.748  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:09.748  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:09.748  2560  2560 V BluetoothAdapterState: isBleTurningOff()=true
08-04 12:01:09.748  2560  2610 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-04 12:01:09.749  2560  2610 D BluetoothAdapterProperties: Setting state to 10
08-04 12:01:09.749  2560  2610 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-04 12:01:09.749  2560  2610 I BluetoothAdapterState: Entering OffState
,08-04 12:01:09.750   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-04 12:01:09.766  2560  2560 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-04 12:01:09.766  2560  2560 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-04 12:01:09.767  2560  2560 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 12:01:09.767  2560  2611 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-04 12:01:09.771  2560  2611 D bt_stack_manager: event_clean_up_stack finished.
,08-04 12:01:09.785  2560  2560 I art     : System.exit called, status: 0
08-04 12:01:09.785  2560  2560 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 12:01:09.852   873  2060 I ActivityManager: Process com.android.bluetooth (pid 2560) has died
,08-04 12:01:09.999  3806  3827 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-04 12:01:09.999  3806  3827 I Babel_SMS: MmsConfig.loadMmsSettings
,08-04 12:01:10.010  3806  3827 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-04 12:01:10.010  3806  3827 I Babel_SMS: MmsConfig.loadFromDatabase
,08-04 12:01:10.041  3806  3827 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-04 12:01:10.041  3806  3827 I Babel_SMS: MmsConfig.loadFromResources
,08-04 12:01:10.043  3806  3827 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-04 12:01:10.044  3806  3827 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-04 12:01:10.070  3806  3806 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:01:10.073  3806  3806 I Babel_Crash: startup - clean
,08-04 12:01:10.102  3806  3806 I Babel_telephony: TeleModule.launchCompleted
,08-04 12:01:10.113  3773  3799 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-04 12:01:10.114   873  2060 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 12:01:10.126  3806  3806 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-04 12:01:10.133  3806  3806 W Babel   : BAM#gBA: invalid account id: -1
,08-04 12:01:10.134  3806  3806 W Babel   : BAM#gBA: invalid account id: -1
08-04 12:01:10.134  3806  3806 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-04 12:01:10.138  3806  3833 I Babel   : deleted: false for 0
,08-04 12:01:10.146   873  1806 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-04 12:01:10.168  1880  1880 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:01:10.174  1880  1880 D SystemUpdateService: onCreate
,08-04 12:01:10.202  1880  1880 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:01:10.217  1880  3835 I SystemUpdateService: active receiver: enabled
,08-04 12:01:10.221  1880  3835 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:01:10.222  1880  1880 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 12:01:10.223  1880  3835 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 12:01:10.223  1880  3835 I SystemUpdateService: now status is 0 (complete)
08-04 12:01:10.223  1880  3835 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:01:10.223  1880  3835 I SystemUpdateService: file has been verified
08-04 12:01:10.223  1880  3835 I SystemUpdateService: OTA package size = 12249756
,08-04 12:01:10.225  1880  2346 I iu.UploadsManager: num queued entries: 0
,08-04 12:01:10.225  1880  2346 I iu.UploadsManager: num updated entries: 0
,08-04 12:01:10.229  1880  3835 I SystemUpdateService: showing system update notification
,08-04 12:01:10.229  1880  2346 I iu.SyncManager: NEXT; no task
,08-04 12:01:10.239  1880  1880 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:01:10.240  1880  1880 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:01:10.254   873  1807 I ActivityManager: Start proc 3837:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-04 12:01:10.255  3806  3806 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:01:10.257  1880  1880 D SystemUpdateService: onDestroy
,08-04 12:01:10.304  3837  3837 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-04 12:01:10.312  3837  3837 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:10.324  3806  3806 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 12:01:10.325  3837  3837 D SprintDMHelper: simOperator: 
,08-04 12:01:10.325  3837  3837 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:01:10.335  3806  3806 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:01:10.340  3806  3806 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-04 12:01:10.346  3806  3806 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 12:01:10.349   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b4621a:true
,08-04 12:01:10.354   873  1389 I ActivityManager: Start proc 3849:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-04 12:01:10.362  3806  3806 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-04 12:01:10.365   873  1764 I ActivityManager: Killing 3414:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-04 12:01:10.434  3806  3806 I vclib   : onServiceConnected
,08-04 12:01:10.538   873  1806 I ActivityManager: Start proc 3864:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-04 12:01:10.540  3806  3863 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-04 12:01:10.545   873  3003 I ActivityManager: Killing 2640:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-04 12:01:10.600  3864  3864 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-04 12:01:10.655  3864  3864 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-04 12:01:10.655  3864  3864 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-04 12:01:10.655  3864  3864 I GAv4    :   adb logcat -s GAv4
,08-04 12:01:10.670  3864  3864 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:01:10.676  3864  3864 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:01:10.699  3864  3881 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-04 12:01:10.811  3864  3864 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-04 12:01:10.848  3864  3864 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-04 12:01:10.857  3864  3864 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6446-6449)
,08-04 12:01:10.857  3864  3864 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 12:01:10.869  3864  3864 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {741017a}
,08-04 12:01:10.870  3864  3864 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 12:01:10.870  3864  3864 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 12:01:10.879  3864  3864 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 12:01:10.880  3864  3864 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 12:01:10.898  3864  3864 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-04 12:01:10.914  3864  3864 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-04 12:01:10.914  3864  3864 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 12:01:10.914  3864  3864 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 12:01:10.914  3864  3864 I Adreno  : Build Date                       : 10/20/15
08-04 12:01:10.914  3864  3864 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 12:01:10.914  3864  3864 I Adreno  : Local Branch                     : M14
08-04 12:01:10.914  3864  3864 I Adreno  : Remote Branch                    : 
08-04 12:01:10.914  3864  3864 I Adreno  : Remote Branch                    : 
08-04 12:01:10.914  3864  3864 I Adreno  : Reconstruct Branch               : 
,08-04 12:01:10.973  3864  3864 I NSApplication: Starting up...
,08-04 12:01:10.981  3864  3910 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 12:01:11.009   873  1807 I ActivityManager: Start proc 3915:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-04 12:01:11.010   873  1807 I ActivityManager: Killing 3334:android.process.acore/u0a5 (adj 15): empty #17
,08-04 12:01:11.102  3915  3915 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-04 12:01:11.273   873  1807 I ActivityManager: Killing 3528:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-04 12:01:11.364   873  1764 I ActivityManager: Start proc 3929:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-04 12:01:11.403  3929  3929 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-04 12:01:11.444  3929  3929 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-04 12:01:11.457   873  1796 I ActivityManager: Killing 3545:com.android.musicfx/u0a18 (adj 15): empty #17
,08-04 12:01:12.162   873  1389 D WifiService: setWifiEnabled: true pid=3703, uid=10000
,08-04 12:01:12.163   873  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:01:12.174   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-04 12:01:12.182  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:12.182  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:12.182  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:12.183  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:12.186  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:12.186  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:12.186  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:12.187  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:12.223   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-04 12:01:12.224   873  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 12:01:12.224   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-04 12:01:12.225   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-04 12:01:12.226   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-04 12:01:12.226   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-04 12:01:12.226   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-04 12:01:12.227   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 12:01:12.241   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 12:01:12.241   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:01:12.243   371   871 D CommandListener: Setting iface cfg
,08-04 12:01:12.251   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-04 12:01:12.251   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 12:01:12.253   873  1315 E native  : do suspend true
,08-04 12:01:12.262   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 12:01:12.267   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 12:01:12.271   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:01:13.658   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:01:13.734   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.88 rxSuccessRate=11.81 delta 1000 -> 994
,08-04 12:01:13.736   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-04 12:01:13.736   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:01:13.753   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 12:01:13.805   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 12:01:13.807  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 12:01:14.235  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 12:01:14.279  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 12:01:14.281  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-04 12:01:14.292  3754  3763 W art     : Suspending all threads took: 9.896ms
08-04 12:01:14.292   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:01:14.307   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:01:14.307   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:01:14.308   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-04 12:01:14.325   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:01:14.338   371   871 D CommandListener: Setting iface cfg
,08-04 12:01:14.340   873  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,08-04 12:01:14.347   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 12:01:14.395   873  3964 D DhcpClient: Receive thread started
,08-04 12:01:14.475   873  1315 E native  : do suspend false
,08-04 12:01:14.485   873  1997 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 12:01:14.497   873  3964 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172423, domain null
,08-04 12:01:14.497   873  1997 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172423 seconds
08-04 12:01:14.498   873  1997 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 12:01:14.508   873  3964 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-04 12:01:14.509   873  1997 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 12:01:14.510   371   871 D CommandListener: Setting iface cfg
,08-04 12:01:14.514   873  1997 D DhcpClient: Scheduling renewal in 86399s
,08-04 12:01:14.519   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 12:01:14.522   873  1315 E native  : do suspend true
,08-04 12:01:14.541   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 12:01:14.545   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 12:01:14.546   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-04 12:01:14.548   873  1317 D ConnectivityService: Adding iface wlan0 to network 101
,08-04 12:01:14.560   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 12:01:14.611   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 12:01:14.612   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-04 12:01:14.614   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-04 12:01:14.617   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-04 12:01:14.622   873  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-04 12:01:14.635   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 12:01:14.640   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-04 12:01:14.641   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-04 12:01:14.641   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-04 12:01:14.642   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 12:01:14.642   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-04 12:01:14.642   873  1317 D ConnectivityService:    accepting network in place of null
,08-04 12:01:14.644   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:01:14.656   873  3963 D NetlinkSocketObserver: NeighborEvent{elapsedMs=400247, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 12:01:14.684   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:01:14.728   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:01:14.737   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-04 12:01:14.738   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:14.746   873  3962 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 12:01:14.747   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-04 12:01:14.758   873   890 D Tethering: MasterInitialState.processMessage what=3
08-04 12:01:14.771  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:14.771  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:01:14.771  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:14.771  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:14.773  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:14.773  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 12:01:14.773  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:14.773  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:14.776  1880  1880 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:01:14.778  1880  1880 D SystemUpdateService: onCreate
,08-04 12:01:14.780  1880  1880 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:01:14.784  1880  3974 I SystemUpdateService: active receiver: enabled
,08-04 12:01:14.789  1880  3974 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:01:14.791  1880  3974 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-04 12:01:14.791  1880  3974 I SystemUpdateService: now status is 0 (complete)
,08-04 12:01:14.791  1880  3974 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-04 12:01:14.791  1880  3974 I SystemUpdateService: file has been verified
08-04 12:01:14.792  1880  3974 I SystemUpdateService: OTA package size = 12249756
,08-04 12:01:14.794  1880  3974 I SystemUpdateService: showing system update notification
,08-04 12:01:14.801  1880  1880 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 12:01:14.808  1880  3977 I MDM     : [214] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 12:01:14.808  1880  3977 W BaseAppContext: Using Auth Proxy for data requests.
08-04 12:01:14.808  1880  2346 I iu.UploadsManager: num queued entries: 0
08-04 12:01:14.809  1880  3977 V GoogleAuthProtoRequest: [214] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 12:01:14.812  1880  1880 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-04 12:01:14.813  1880  1880 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:01:14.813  1880  1880 D SystemUpdateService: onDestroy
08-04 12:01:14.815  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:01:14.817  1880  2346 I iu.UploadsManager: num updated entries: 0
,08-04 12:01:14.817  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-04 12:01:14.818  1880  2346 I iu.SyncManager: NEXT; no task
,08-04 12:01:14.819  3837  3837 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:14.823  3837  3837 D SprintDMHelper: simOperator: 
,08-04 12:01:14.823  3837  3837 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:01:14.842  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-04 12:01:14.842  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 12:01:14.843  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-04 12:01:14.843  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:01:14.847   873  3962 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 10:01:15 GMT], X-Android-Received-Millis=[1470304874847], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470304874807]}
,08-04 12:01:14.848   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-04 12:01:14.848   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-04 12:01:14.848   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 12:01:14.850   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 12:01:14.856  1880  3977 E MDM     : [214] SitrepService.a: Error sending sitrep.
,08-04 12:01:14.856  3806  3806 I art     : Waiting for a blocking GC DisableMovingGc
,08-04 12:01:14.859  3806  3806 I art     : Starting a blocking GC DisableMovingGc
,08-04 12:01:15.005  3806  3982 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 12:01:15.013   873  1806 I ActivityManager: Killing 2072:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-04 12:01:15.169   873  2061 D WifiService: setWifiEnabled: false pid=3703, uid=10000
,08-04 12:01:15.169   873  2061 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:01:15.196  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-04 12:01:15.199   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-04 12:01:15.199   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-04 12:01:15.200   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-04 12:01:15.200   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:01:15.217   873  1315 E native  : do suspend true
,08-04 12:01:15.224   873  1997 D DhcpClient: Clearing IP address
,08-04 12:01:15.225   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-04 12:01:15.230  1523  3987 V NativeCrypto: Read error: ssl=0x9ad69200: I/O error during system call, Connection timed out
,08-04 12:01:15.232  1523  3987 V NativeCrypto: SSL shutdown failed: ssl=0x9ad69200: I/O error during system call, Broken pipe
,08-04 12:01:15.233   873  1389 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-04 12:01:15.234   873  3962 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-04 12:01:15.234   873  3962 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 12:01:15.238   873  3962 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:800::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-04 12:01:15.239   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-04 12:01:15.240   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-04 12:01:15.242   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 12:01:15.244   371   871 D CommandListener: Setting iface cfg
,08-04 12:01:15.250   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-04 12:01:15.252   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:01:15.252   873  1315 E native  : do suspend true
,08-04 12:01:15.250   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-04 12:01:15.254   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-04 12:01:15.256   455   455 E Parcel  : Reading a NULL string not supported here.
,08-04 12:01:15.262   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-04 12:01:15.271   873  3964 D DhcpClient: Receive thread stopped
,08-04 12:01:15.295   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:01:15.320   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-04 12:01:15.321   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-04 12:01:15.322   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-04 12:01:15.323   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:15.325   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:01:15.325   873   890 D Tethering: MasterInitialState.processMessage what=3
08-04 12:01:15.329  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:15.329  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:15.329  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.329  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:15.331  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:15.331  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:15.331  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.331  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:15.338  1880  1880 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:01:15.342  1880  1880 D SystemUpdateService: onCreate
,08-04 12:01:15.343   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:01:15.345  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:15.345  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:15.345  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.345  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:15.346  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:15.346  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:15.346  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:15.346  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:15.347  1880  1880 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-04 12:01:15.348   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-04 12:01:15.353  1900  2102 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 12:01:15.367  1880  1880 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 12:01:15.369  1880  2346 I iu.UploadsManager: num queued entries: 0
,08-04 12:01:15.369  1880  2346 I iu.UploadsManager: num updated entries: 0
08-04 12:01:15.370  1880  2346 I iu.SyncManager: NEXT; no task
,08-04 12:01:15.379  1880  1880 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-04 12:01:15.380  1880  1880 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:01:15.382  1880  3995 I SystemUpdateService: active receiver: enabled
,08-04 12:01:15.388  3837  3837 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:15.392  1880  3995 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-04 12:01:15.393  1880  3995 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-04 12:01:15.395  1880  3995 I SystemUpdateService: now status is 0 (complete)
,08-04 12:01:15.395  1880  3995 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-04 12:01:15.395  1880  3995 I SystemUpdateService: file has been verified
,08-04 12:01:15.395  1880  3995 I SystemUpdateService: OTA package size = 12249756
,08-04 12:01:15.396  3837  3837 D SprintDMHelper: simOperator: 
,08-04 12:01:15.396  3837  3837 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:01:15.403   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-04 12:01:15.406   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-04 12:01:15.418  3806  4000 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-04 12:01:15.454  1880  3995 I SystemUpdateService: showing system update notification
,08-04 12:01:15.468  1880  1880 D SystemUpdateService: onDestroy
,08-04 12:01:15.735   873  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-04 12:01:18.226   873   890 I ActivityManager: Start proc 4003:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 12:01:18.373  4003  4003 D AdapterServiceConfig: Adding HeadsetService
08-04 12:01:18.373  4003  4003 D AdapterServiceConfig: Adding A2dpService
08-04 12:01:18.374  4003  4003 D AdapterServiceConfig: Adding HidService
08-04 12:01:18.374  4003  4003 D AdapterServiceConfig: Adding HealthService
08-04 12:01:18.374  4003  4003 D AdapterServiceConfig: Adding PanService
08-04 12:01:18.374  4003  4003 D AdapterServiceConfig: Adding GattService
08-04 12:01:18.374  4003  4003 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 12:01:18.390   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1eef6cf:true
08-04 12:01:18.390  4003  4003 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 12:01:18.394  4003  4003 I bt_bluedroid: init
,08-04 12:01:18.395  4003  4015 I BluetoothAdapterState: Entering OffState
,08-04 12:01:18.401  4003  4016 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 12:01:18.401  4003  4016 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-04 12:01:18.402  4003  4016 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 12:01:18.402  4003  4016 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 12:01:18.404  4003  4003 I bt_bluedroid: get_profile_interface socket
,08-04 12:01:18.409  4003  4003 I bt_bluedroid: get_profile_interface sdp
,08-04 12:01:18.409  4003  4019 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:01:18.412  4003  4019 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:01:18.417  4003  4013 I bt_bluedroid: config_hci_snoop_log
,08-04 12:01:18.420   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 12:01:18.431  4003  4015 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 12:01:18.431  4003  4015 D BluetoothAdapterProperties: Setting state to 14
,08-04 12:01:18.432  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-04 12:01:18.436  4003  4015 D BluetoothBondStateMachine: make
,08-04 12:01:18.443  4003  4020 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 12:01:18.453  4003  4015 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:01:18.456  4003  4003 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 12:01:18.466  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:18.468  4003  4003 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:01:18.470  4003  4003 D BtGatt.GattService: Received start request. Starting profile...
,08-04 12:01:18.471  4003  4003 D BtGatt.GattService: start()
08-04 12:01:18.471  4003  4003 I bt_bluedroid: get_profile_interface gatt
,08-04 12:01:18.474  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:18.475  4003  4003 D BtGatt.AdvertiseManager: advertise manager created
,08-04 12:01:18.485  4003  4003 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:18.486  4003  4003 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:18.486  4003  4003 V BluetoothAdapterState: isBleTurningOn()=true
08-04 12:01:18.486  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:18.486  4003  4015 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-04 12:01:18.487  4003  4015 I bt_bluedroid: enable
,08-04 12:01:18.488  4003  4016 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-04 12:01:18.489  4003  4016 I bt_hci  : start_up
,08-04 12:01:18.509  4003  4016 I bt_vendor: alloc value 0xb39dc189
,08-04 12:01:18.509  4003  4016 I bt_vendor: init
08-04 12:01:18.509  4003  4016 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 12:01:18.509  4003  4016 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 12:01:18.617  4003  4016 D bt_hci  : start_up starting async portion
,08-04 12:01:18.618  4003  4023 I bt_hci  : event_finish_startup
08-04 12:01:18.618  4003  4023 I bt_hci_h4: hal_open
,08-04 12:01:18.618  4003  4023 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 12:01:18.628  4003  4023 I bt_userial_vendor: device fd = 51 open
,08-04 12:01:18.658  4003  4023 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:01:18.690  4003  4023 D bt_hwcfg: Chipset BCM4354A2
,08-04 12:01:18.691  4003  4023 D bt_hwcfg: Target name = [BCM4354A2]
08-04 12:01:18.691  4003  4023 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 12:01:19.344  4003  4023 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 12:01:19.345  4003  4023 D bt_hwcfg: Settlement delay -- 100 ms
08-04 12:01:19.345  4003  4023 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 12:01:19.462  4003  4023 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:01:19.463  4003  4023 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 12:01:19.493  4003  4023 I bt_hwcfg: vendor lib fwcfg completed
,08-04 12:01:19.493  4003  4023 I bt_vendor: firmware callback
08-04 12:01:19.493  4003  4023 I bt_hci  : firmware_config_callback
,08-04 12:01:19.504  4003  4025 I bt_btu  : btu_task pending for preload complete event
,08-04 12:01:19.504  4003  4025 I bt_btu_task: Bluetooth chip preload is complete
,08-04 12:01:19.504  4003  4025 I bt_btu  : btu_task received preload complete event
,08-04 12:01:19.516  4003  4025 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 12:01:19.516  4003  4025 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 12:01:19.516  4003  4025 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 12:01:19.517  4003  4025 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 12:01:19.517  4003  4025 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-04 12:01:19.517  4003  4025 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 12:01:19.517  4003  4025 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 12:01:19.518  4003  4025 I         : BTE_InitTraceLevels -- TRC_BTM
,08-04 12:01:19.518  4003  4025 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 12:01:19.518  4003  4025 I         : BTE_InitTraceLevels -- TRC_PAN
,08-04 12:01:19.519  4003  4025 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 12:01:19.519  4003  4025 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 12:01:19.519  4003  4025 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 12:01:19.519  4003  4025 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 12:01:19.520  4003  4025 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 12:01:19.644  4003  4025 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3959d9d
,08-04 12:01:19.644  4003  4025 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3959d9d 
,08-04 12:01:19.654  4003  4019 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-04 12:01:19.656  4003  4019 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-04 12:01:19.657  4003  4019 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:01:19.659  4003  4019 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:01:19.665  4003  4019 D BluetoothAdapterProperties: Scan Mode:20
,08-04 12:01:19.665  4003  4019 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:01:19.665  4003  4019 D bt_hci  : do_postload posting postload work item
08-04 12:01:19.666  4003  4023 I bt_hci  : event_postload
08-04 12:01:19.666  4003  4023 I bt_vendor: sco_config_cb
08-04 12:01:19.666  4003  4023 I bt_hci  : sco_config_callback postload finished.
08-04 12:01:19.668  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:19.668  4003  4019 D bt_bte_conf: Device ID record 1 : primary
,08-04 12:01:19.669  4003  4019 D bt_bte_conf:   vendorId            = 000f
08-04 12:01:19.669  4003  4019 D bt_bte_conf:   vendorIdSource      = 0001
08-04 12:01:19.669  4003  4019 D bt_bte_conf:   product             = 1200
08-04 12:01:19.669  4003  4019 D bt_bte_conf:   version             = 1436
08-04 12:01:19.669  4003  4019 D bt_bte_conf:   clientExecutableURL = 
08-04 12:01:19.670  4003  4019 D bt_bte_conf:   serviceDescription  = 
,08-04 12:01:19.670  4003  4019 D bt_bte_conf:   documentationURL    = 
08-04 12:01:19.670  4003  4019 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 12:01:19.671  4003  4016 D bt_stack_manager: event_start_up_stack finished
08-04 12:01:19.671  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:19.673  4003  4015 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-04 12:01:19.673  4003  4015 D BluetoothAdapterProperties: Setting state to 15
08-04 12:01:19.674  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-04 12:01:19.676  4003  4015 I BluetoothAdapterState: Entering BleOnState
08-04 12:01:19.677  4003  4023 I bt_vendor: low_power_mode_cb
,08-04 12:01:19.680  4003  4015 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-04 12:01:19.680  4003  4015 D BluetoothAdapterProperties: Setting state to 11
08-04 12:01:19.680  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 12:01:19.687  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:19.690  4003  4003 D HeadsetService: Received start request. Starting profile...
,08-04 12:01:19.700  4003  4003 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 12:01:19.700  4003  4003 D HeadsetStateMachine: make
,08-04 12:01:19.704  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:19.706  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:19.713  4003  4015 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:01:19.715  4003  4003 D HeadsetStateMachine: max_hf_connections = 1
,08-04 12:01:19.715  4003  4003 I bt_bluedroid: get_profile_interface handsfree
08-04 12:01:19.716  4003  4019 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 12:01:19.716  4003  4019 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-04 12:01:19.721  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:19.721  4003  4003 D A2dpService: Received start request. Starting profile...
08-04 12:01:19.722  4003  4003 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 12:01:19.722  4003  4003 I bt_bluedroid: get_profile_interface avrcp
,08-04 12:01:19.727  4003  4003 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 12:01:19.728  4003  4003 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 12:01:19.728  4003  4003 D A2dpStateMachine: make
08-04 12:01:19.729  4003  4003 I bt_bluedroid: get_profile_interface a2dp
,08-04 12:01:19.729  4003  4019 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 12:01:19.732  4003  4034 D A2dpStateMachine: Enter Disconnected: -2
,08-04 12:01:19.733  4003  4003 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 12:01:19.734  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:19.735  4003  4003 D HidService: Received start request. Starting profile...
,08-04 12:01:19.735  3754  3754 D BluetoothInputDevice: Proxy object connected
08-04 12:01:19.735  4003  4003 I bt_bluedroid: get_profile_interface hidhost
08-04 12:01:19.735  4003  4003 D HidService: setHidService(): set to: null
08-04 12:01:19.735  4003  4019 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393b3e5
,08-04 12:01:19.735  4003  4019 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 12:01:19.736  3754  3754 D HidProfile: Bluetooth service connected
08-04 12:01:19.736  4003  4003 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 12:01:19.737  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:19.738  4003  4003 D HealthService: Received start request. Starting profile...
,08-04 12:01:19.739  4003  4003 I bt_bluedroid: get_profile_interface health
,08-04 12:01:19.740  4003  4003 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 12:01:19.740  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:19.742  4003  4003 D PanService: Received start request. Starting profile...
08-04 12:01:19.742  3754  3754 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 12:01:19.742  4003  4003 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 12:01:19.742  4003  4003 I bt_bluedroid: get_profile_interface pan
08-04 12:01:19.742  3754  3754 D PanProfile: Bluetooth service connected
08-04 12:01:19.743  4003  4019 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 12:01:19.748  4003  4003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
08-04 12:01:19.750  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:01:19.751  4003  4003 D BluetoothMapService: Received start request. Starting profile...
08-04 12:01:19.751  4003  4003 D BluetoothMapService: start()
,08-04 12:01:19.752  3754  3754 D BluetoothMap: Proxy object connected
,08-04 12:01:19.753  3754  3754 D MapProfile: Bluetooth service connected
,08-04 12:01:19.753  3754  3754 D BluetoothMap: getConnectedDevices()
08-04 12:01:19.754  4003  4003 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 12:01:19.754  3754  3754 D BluetoothMap: Bluetooth is Not enabled
08-04 12:01:19.755  4003  4003 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-04 12:01:19.755  4003  4003 D BluetoothMapAppObserver: createReceiver()
,08-04 12:01:19.756  4003  4003 D BluetoothMapAppObserver: initObservers()
08-04 12:01:19.756  4003  4003 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 12:01:19.766  4003  4003 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:19.766  4003  4003 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:19.766  4003  4031 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 12:01:19.766  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:19.766  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:19.767  4003  4003 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:19.767  4003  4003 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false,
08-04 12:01:19.768  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:19.769  4003  4003 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:19.769  4003  4003 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:19.769  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:19.769  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:19.771  4003  4003 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:19.771  4003  4003 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:19.771  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:19.771  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:19.771  4003  4015 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-04 12:01:19.772  4003  4015 D BluetoothAdapterProperties: ScanMode =  20
,08-04 12:01:19.772  4003  4015 D BluetoothAdapterProperties: State =  11
,08-04 12:01:19.772  4003  4015 D BluetoothAdapterProperties: Setting state to 12
08-04 12:01:19.772  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-04 12:01:19.773  4003  4019 D BluetoothAdapterProperties: Scan Mode:21
,08-04 12:01:19.773  4003  4019 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:01:19.773   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:01:19.773   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 12:01:19.773  4003  4015 I BluetoothAdapterState: Entering OnState
08-04 12:01:19.775  3754  3765 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 12:01:19.776   873   873 D BluetoothA2dp: Proxy object connected
08-04 12:01:19.777  3754  3764 D BluetoothPan: onBluetoothStateChange on: true
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:19.777  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:19.778  1360  2386 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 12:01:19.780  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:19.780  1360  1360 D BluetoothInputDevice: Proxy object connected
,08-04 12:01:19.780  1360  1360 D HidProfile: Bluetooth service connected
08-04 12:01:19.781   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:01:19.781  1360  1373 D BluetoothPan: onBluetoothStateChange on: true
08-04 12:01:19.783  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:01:19.783  1360  1360 D PanProfile: Bluetooth service connected
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:19.784  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:19.784  1360  2386 D BluetoothMap: onBluetoothStateChange: up=true
08-04 12:01:19.786  4003  4003 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 12:01:19.786  4003  4003 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-04 12:01:19.786  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:19.787  1360  1360 D BluetoothMap: Proxy object connected
08-04 12:01:19.787  1360  1360 D MapProfile: Bluetooth service connected
08-04 12:01:19.787  1360  1360 D BluetoothMap: getConnectedDevices()
,08-04 12:01:19.788  4003  4003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:01:19.788  3754  3765 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 12:01:19.789  3754  3764 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 12:01:19.789  1360  1373 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:01:19.790  4003  4003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:01:19.792  4003  4003 D ObexServerSockets: Succeed to create listening sockets 
,08-04 12:01:19.792  1360  1360 D BluetoothA2dp: Proxy object connected
,08-04 12:01:19.792  4003  4003 D ObexServerSockets0: startAccept()
08-04 12:01:19.792  4003  4003 D ObexServerSockets0: prepareForNewConnect()
08-04 12:01:19.792  1744  1949 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:01:19.793  1360  2386 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 12:01:19.796  1360  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:01:19.796   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:01:19.796  4003  4003 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-04 12:01:19.796  4003  4003 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-04 12:01:19.797  4003  4040 D ObexServerSockets0: Accepting socket connection...
08-04 12:01:19.797  4003  4041 D ObexServerSockets0: Accepting socket connection...
08-04 12:01:19.799  4003  4003 D BluetoothMapService: onReceive
,08-04 12:01:19.800  4003  4003 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:01:19.800  4003  4003 D BluetoothMapService: STATE_ON
08-04 12:01:19.800   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-04 12:01:19.802  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:19.803  3754  3754 D LocalBluetoothProfileManager: Adding local A2DP profile
08-04 12:01:19.803  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:19.808  3754  3754 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-04 12:01:19.814  3754  3754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:01:19.817  3754  3754 D BluetoothA2dp: Proxy object connected
,08-04 12:01:19.821  4003  4003 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 12:01:19.821  4003  4003 D ObexServerSockets0: prepareForNewConnect()
,08-04 12:01:19.824  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:01:19.831  3754  3754 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:01:19.834  3754  3754 D BluetoothPbap: Proxy object connected
,08-04 12:01:19.833  1360  1360 D BluetoothPbap: Proxy object connected
08-04 12:01:19.834  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-04 12:01:19.834  3754  3754 D PbapServerProfile: Bluetooth service connected
,08-04 12:01:19.846  4003  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:01:19.864  4003  4049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:01:19.866  4003  4049 I BtOppRfcommListener: Accept thread started.
,08-04 12:01:19.875   873   873 D BluetoothHeadset: Proxy object connected
08-04 12:01:19.875   873   873 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.876  1744  1755 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.876  1360  1373 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.877  1360  1360 D HeadsetProfile: Bluetooth service connected
08-04 12:01:19.877   873   873 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.881   873   890 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.893  1744  1915 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.897  1360  2386 D BluetoothHeadset: Proxy object connected
08-04 12:01:19.897  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-04 12:01:19.897   873   890 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.911  3754  3765 D BluetoothHeadset: Proxy object connected
,08-04 12:01:19.911  3754  3754 D HeadsetProfile: Bluetooth service connected
,08-04 12:01:21.189  4003  4015 D BluetoothAdapterState: Current state: ON, message: 23
,08-04 12:01:21.189  4003  4015 D BluetoothAdapterProperties: Setting state to 13
,08-04 12:01:21.190  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 12:01:21.192  4003  4015 D BluetoothAdapterProperties: onBluetoothDisable()
,08-04 12:01:21.195  4003  4015 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:01:21.202  4003  4003 D BluetoothMapService: onReceive
08-04 12:01:21.203  4003  4003 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 12:01:21.203  4003  4003 D BluetoothMapService: STATE_TURNING_OFF
,08-04 12:01:21.204  4003  4003 D BluetoothMapService: MAP Service closeService in
,08-04 12:01:21.205  4003  4003 D BluetoothMapMasInstance0: MAP Service shutdown
08-04 12:01:21.205  4003  4003 D ObexServerSockets0: shutdown(block = true)
08-04 12:01:21.206  4003  4040 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-04 12:01:21.208  4003  4019 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:01:21.209  4003  4015 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-04 12:01:21.210  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:21.210  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:21.213  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:21.213  4003  4003 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:01:21.213  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:21.214  4003  4027 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-04 12:01:21.214  4003  4041 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-04 12:01:21.214  4003  4003 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-04 12:01:21.215  4003  4003 I BtOppRfcommListener: stopping Accept Thread
08-04 12:01:21.217  4003  4049 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 12:01:21.218  3754  3754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:01:21.217  4003  4049 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 12:01:21.219  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:21.219  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 12:01:21.221  3703  3703 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 12:01:21.221  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:21.222  4003  4003 D HeadsetService: Received stop request...Stopping profile...
08-04 12:01:21.223  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:21.224   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:21.225   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:21.225  1744  1758 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:21.225  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:21.225  4003  4003 D A2dpService: Received stop request...Stopping profile...
08-04 12:01:21.226  4003  4034 D A2dpStateMachine: Exit Disconnected: -1
08-04 12:01:21.227  3754  3765 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:21.227  1360  2386 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:21.228  4003  4003 D HidService: Received stop request...Stopping profile...
08-04 12:01:21.228  4003  4003 D HidService: Stopping Bluetooth HidService
,08-04 12:01:21.228   873   873 D BluetoothHeadset: Proxy object disconnected
08-04 12:01:21.228   873   873 D BluetoothA2dp: Proxy object disconnected
08-04 12:01:21.230  4003  4003 D HealthService: Received stop request...Stopping profile...
08-04 12:01:21.230  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-04 12:01:21.230  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-04 12:01:21.230  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-04 12:01:21.231  1360  1360 D HidProfile: Bluetooth service disconnected
08-04 12:01:21.232  4003  4003 D PanService: Received stop request...Stopping profile...
08-04 12:01:21.233  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-04 12:01:21.233  1360  1360 D PanProfile: Bluetooth service disconnected
08-04 12:01:21.234  3754  3754 D DockEventReceiver: finishStartingService: stopping service
08-04 12:01:21.235  4003  4003 D BluetoothMapService: Received stop request...Stopping profile...
08-04 12:01:21.235  3754  3754 D HeadsetProfile: Bluetooth service disconnected
08-04 12:01:21.235  4003  4003 D BluetoothMapService: stop()
,08-04 12:01:21.235  3754  3754 D BluetoothA2dp: Proxy object disconnected
08-04 12:01:21.237  4003  4003 D BluetoothMapAppObserver: deinitObservers()
,08-04 12:01:21.237  4003  4003 D BluetoothMapAppObserver: removeReceiver()
08-04 12:01:21.237  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 12:01:21.238  1360  1360 D BluetoothMap: Proxy object disconnected
08-04 12:01:21.238  1360  1360 D MapProfile: Bluetooth service disconnected
08-04 12:01:21.238  4003  4003 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:21.238  4003  4003 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:21.238  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:21.238  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:21.239  3754  3754 D BluetoothInputDevice: Proxy object disconnected
,08-04 12:01:21.239  3754  3754 D HidProfile: Bluetooth service disconnected
08-04 12:01:21.240  4003  4003 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-04 12:01:21.240  3754  3754 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 12:01:21.240  3754  3754 D PanProfile: Bluetooth service disconnected
08-04 12:01:21.240  4003  4003 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-04 12:01:21.240  4003  4019 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-04 12:01:21.240  4003  4025 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:21.240  4003  4025 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:21.240  4003  4025 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:21.240  4003  4019 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-04 12:01:21.241  4003  4003 V BluetoothAdapterState: isTurningOff()=true
,08-04 12:01:21.241  4003  4003 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:21.242  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:21.242  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:21.243  4003  4019 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-04 12:01:21.243  4003  4025 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:21.243  3754  3754 D BluetoothMap: Proxy object disconnected
08-04 12:01:21.243  4003  4025 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:21.243  3754  3754 D MapProfile: Bluetooth service disconnected
08-04 12:01:21.243  4003  4025 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:01:21.243  4003  4025 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:01:21.243  4003  4025 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 12:01:21.243  4003  4025 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 12:01:21.243  4003  4003 V BluetoothAdapterState: isTurningOff()=true
,08-04 12:01:21.244  4003  4003 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:21.244  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:21.244  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:21.244  4003  4003 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 12:01:21.244  4003  4019 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-04 12:01:21.244  4003  4003 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 12:01:21.245  4003  4003 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:21.245  4003  4003 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:21.245  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:21.245  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:21.245  4003  4003 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 12:01:21.245  4003  4019 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-04 12:01:21.245  4003  4003 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 12:01:21.246  4003  4003 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:21.246  4003  4003 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:21.246  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:21.246  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:21.246  4003  4003 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 12:01:21.246  4003  4003 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 12:01:21.248  1360  1360 D BluetoothPbap: Proxy object disconnected
08-04 12:01:21.248  1360  1360 D PbapServerProfile: Bluetooth service disconnected
,08-04 12:01:21.249  4003  4003 D BluetoothMapService: MAP Service closeService in
08-04 12:01:21.249  4003  4003 V BluetoothAdapterState: isTurningOff()=true
08-04 12:01:21.249  4003  4003 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:21.249  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:21.249  3754  3754 D BluetoothPbap: Proxy object disconnected
08-04 12:01:21.249  3754  3754 D PbapServerProfile: Bluetooth service disconnected
08-04 12:01:21.249  4003  4003 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:21.250  4003  4015 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-04 12:01:21.250  4003  4015 D BluetoothAdapterProperties: Setting state to 15
08-04 12:01:21.250  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-04 12:01:21.251  4003  4015 I BluetoothAdapterState: Entering BleOnState
08-04 12:01:21.251   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:21.251   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:01:21.251  3754  3764 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:01:21.252  4003  4003 D BluetoothMapService: cleanup()
08-04 12:01:21.252  4003  4003 D BluetoothMapService: MAP Service closeService in
08-04 12:01:21.252  3754  4053 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:01:21.253  1360  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 12:01:21.256   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-04 12:01:21.256  1360  2386 D BluetoothPan: onBluetoothStateChange on: false
08-04 12:01:21.257  1360  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-04 12:01:21.257  3754  3765 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 12:01:21.258  3754  3764 D BluetoothMap: onBluetoothStateChange: up=false
,08-04 12:01:21.258  1360  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:01:21.259  3754  4053 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:21.259  1744  1949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:21.259  1360  2386 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 12:01:21.260  1360  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:21.260   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 12:01:21.260  3754  3765 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 12:01:21.261  4003  4015 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-04 12:01:21.261  4003  4015 D BluetoothAdapterProperties: Setting state to 16
,08-04 12:01:21.261  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-04 12:01:21.262  4003  4015 D BluetoothAdapterProperties: onBleDisable
08-04 12:01:21.263  4003  4015 I BluetoothAdapterState: Entering PendingCommandState
08-04 12:01:21.263  4003  4016 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-04 12:01:21.264  4003  4025 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 12:01:21.264  4003  4025 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-04 12:01:21.265  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:21.266  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:21.267  4003  4019 D BluetoothAdapterProperties: Scan Mode:20
08-04 12:01:21.268  3754  3754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 12:01:21.269  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:21.270  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:21.273  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:01:21.278  3754  3754 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:01:21.465  4003  4019 I bt_hci  : shut_down
,08-04 12:01:21.465  4003  4023 D bt_hwcfg: hw_epilog_process
,08-04 12:01:21.466  4003  4023 I bt_vendor: low_power_mode_cb
,08-04 12:01:21.485  4003  4023 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-04 12:01:21.486  4003  4023 I bt_vendor: epilog_cb
08-04 12:01:21.486  4003  4023 I bt_hci  : epilog_finished_callback
,08-04 12:01:21.487  4003  4019 I bt_hci_h4: hal_close
,08-04 12:01:21.489  4003  4019 I bt_userial_vendor: device fd = 51 close
,08-04 12:01:21.623  4003  4016 D bt_stack_manager: event_shut_down_stack finished.
,08-04 12:01:21.625  4003  4015 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-04 12:01:21.631  4003  4015 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-04 12:01:21.632  4003  4003 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:01:21.634  4003  4003 D BtGatt.GattService: Received stop request...Stopping profile...
,08-04 12:01:21.634  4003  4003 D BtGatt.GattService: stop()
08-04 12:01:21.634  4003  4003 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 12:01:21.639  4003  4003 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:21.640  4003  4003 V BluetoothAdapterState: isTurningOn()=false
,08-04 12:01:21.640  4003  4003 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:21.640  4003  4003 V BluetoothAdapterState: isBleTurningOff()=true
08-04 12:01:21.641  4003  4015 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-04 12:01:21.642  4003  4015 D BluetoothAdapterProperties: Setting state to 10
08-04 12:01:21.642  4003  4015 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-04 12:01:21.644  4003  4015 I BluetoothAdapterState: Entering OffState
08-04 12:01:21.646   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-04 12:01:21.668  4003  4003 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-04 12:01:21.668  4003  4003 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-04 12:01:21.669  4003  4016 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-04 12:01:21.671  4003  4016 D bt_stack_manager: event_clean_up_stack finished.
08-04 12:01:21.672  4003  4003 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 12:01:21.674  4003  4003 I art     : System.exit called, status: 0
,08-04 12:01:21.674  4003  4003 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 12:01:21.715   873  1807 I ActivityManager: Process com.android.bluetooth (pid 4003) has died
,08-04 12:01:22.647   873  1317 D ConnectivityService: handlePromptUnvalidated 101
,08-04 12:01:24.186  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:01:24.186  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:27.194  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:01:27.195  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c137e1 added. We now have 6 listener(s)
08-04 12:01:27.195  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:27.199  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:01:27.200  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8518906 added. We now have 7 listener(s)
,08-04 12:01:27.200  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:27.202  3703  3748 I System.out: IsBluetoothEnabled
,08-04 12:01:27.212  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:27.240   873   890 I ActivityManager: Start proc 4060:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-04 12:01:27.382  4060  4060 D AdapterServiceConfig: Adding HeadsetService
,08-04 12:01:27.383  4060  4060 D AdapterServiceConfig: Adding A2dpService
08-04 12:01:27.383  4060  4060 D AdapterServiceConfig: Adding HidService
,08-04 12:01:27.383  4060  4060 D AdapterServiceConfig: Adding HealthService
,08-04 12:01:27.383  4060  4060 D AdapterServiceConfig: Adding PanService
,08-04 12:01:27.384  4060  4060 D AdapterServiceConfig: Adding GattService
,08-04 12:01:27.384  4060  4060 D AdapterServiceConfig: Adding BluetoothMapService
,08-04 12:01:27.402  4060  4060 D BluetoothAdapterState: make() - Creating AdapterState
,08-04 12:01:27.402   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6535f0:true
,08-04 12:01:27.411  4060  4060 I bt_bluedroid: init
,08-04 12:01:27.411  4060  4072 I BluetoothAdapterState: Entering OffState
,08-04 12:01:27.416  4060  4073 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 12:01:27.417  4060  4073 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-04 12:01:27.417  4060  4073 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 12:01:27.417  4060  4073 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 12:01:27.419  4060  4060 I bt_bluedroid: get_profile_interface socket
08-04 12:01:27.423  4060  4076 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-04 12:01:27.423  4060  4060 I bt_bluedroid: get_profile_interface sdp
,08-04 12:01:27.426  4060  4076 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:01:27.431  4060  4071 I bt_bluedroid: config_hci_snoop_log
,08-04 12:01:27.434   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-04 12:01:27.443  4060  4072 D BluetoothAdapterState: Current state: OFF, message: 0
,08-04 12:01:27.444  4060  4072 D BluetoothAdapterProperties: Setting state to 14
08-04 12:01:27.445  4060  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-04 12:01:27.449  4060  4072 D BluetoothBondStateMachine: make
,08-04 12:01:27.455  4060  4077 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 12:01:27.462  4060  4072 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:01:27.466  4060  4060 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-04 12:01:27.475  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:27.477  4060  4060 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 12:01:27.479  4060  4060 D BtGatt.GattService: Received start request. Starting profile...
,08-04 12:01:27.479  4060  4060 D BtGatt.GattService: start()
08-04 12:01:27.480  4060  4060 I bt_bluedroid: get_profile_interface gatt
,08-04 12:01:27.482  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:27.483  4060  4060 D BtGatt.AdvertiseManager: advertise manager created
,08-04 12:01:27.494  4060  4060 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:27.494  4060  4060 V BluetoothAdapterState: isTurningOn()=false
08-04 12:01:27.494  4060  4060 V BluetoothAdapterState: isBleTurningOn()=true
,08-04 12:01:27.494  4060  4060 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:27.495  4060  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-04 12:01:27.495  4060  4072 I bt_bluedroid: enable
08-04 12:01:27.496  4060  4073 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-04 12:01:27.497  4060  4073 I bt_hci  : start_up
,08-04 12:01:27.518  4060  4073 I bt_vendor: alloc value 0xb3a20189
,08-04 12:01:27.518  4060  4073 I bt_vendor: init
08-04 12:01:27.519  4060  4073 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-04 12:01:27.519  4060  4073 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-04 12:01:27.631  4060  4073 D bt_hci  : start_up starting async portion
,08-04 12:01:27.631  4060  4080 I bt_hci  : event_finish_startup
08-04 12:01:27.632  4060  4080 I bt_hci_h4: hal_open
08-04 12:01:27.632  4060  4080 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 12:01:27.641  4060  4080 I bt_userial_vendor: device fd = 51 open
,08-04 12:01:27.672  4060  4080 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:01:27.704  4060  4080 D bt_hwcfg: Chipset BCM4354A2
,08-04 12:01:27.704  4060  4080 D bt_hwcfg: Target name = [BCM4354A2]
,08-04 12:01:27.705  4060  4080 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-04 12:01:28.358  4060  4080 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 12:01:28.360  4060  4080 D bt_hwcfg: Settlement delay -- 100 ms
,08-04 12:01:28.361  4060  4080 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 12:01:28.477  4060  4080 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 12:01:28.478  4060  4080 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-04 12:01:28.507  4060  4080 I bt_hwcfg: vendor lib fwcfg completed
08-04 12:01:28.508  4060  4080 I bt_vendor: firmware callback
,08-04 12:01:28.508  4060  4080 I bt_hci  : firmware_config_callback
,08-04 12:01:28.520  4060  4082 I bt_btu  : btu_task pending for preload complete event
08-04 12:01:28.520  4060  4082 I bt_btu_task: Bluetooth chip preload is complete
08-04 12:01:28.520  4060  4082 I bt_btu  : btu_task received preload complete event
,08-04 12:01:28.530  4060  4082 I         : BTE_InitTraceLevels -- TRC_HCI,
08-04 12:01:28.530  4060  4082 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-04 12:01:28.531  4060  4082 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-04 12:01:28.531  4060  4082 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 12:01:28.531  4060  4082 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 12:01:28.532  4060  4082 I         : BTE_InitTraceLevels -- TRC_A2D
,08-04 12:01:28.532  4060  4082 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 12:01:28.532  4060  4082 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 12:01:28.532  4060  4082 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 12:01:28.533  4060  4082 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 12:01:28.533  4060  4082 I         : BTE_InitTraceLevels -- TRC_SDP
,08-04 12:01:28.533  4060  4082 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 12:01:28.533  4060  4082 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 12:01:28.534  4060  4082 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 12:01:28.534  4060  4082 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 12:01:28.666  4060  4082 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399dd9d,
08-04 12:01:28.666  4060  4082 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399dd9d 
,08-04 12:01:28.678  4060  4076 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-04 12:01:28.680  4060  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-04 12:01:28.682  4060  4076 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-04 12:01:28.686  4060  4076 D BluetoothAdapterProperties: Name is: Nexus 6
,08-04 12:01:28.690  4060  4076 D BluetoothAdapterProperties: Scan Mode:20
,08-04 12:01:28.691  4060  4076 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 12:01:28.691  4060  4076 D bt_hci  : do_postload posting postload work item
,08-04 12:01:28.692  4060  4080 I bt_hci  : event_postload
08-04 12:01:28.692  4060  4080 I bt_vendor: sco_config_cb
,08-04 12:01:28.692  4060  4080 I bt_hci  : sco_config_callback postload finished.
,08-04 12:01:28.696  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:28.697  4060  4076 D bt_bte_conf: Device ID record 1 : primary
08-04 12:01:28.698  4060  4080 I bt_vendor: low_power_mode_cb
,08-04 12:01:28.698  4060  4076 D bt_bte_conf:   vendorId            = 000f
,08-04 12:01:28.699  4060  4076 D bt_bte_conf:   vendorIdSource      = 0001
08-04 12:01:28.699  4060  4076 D bt_bte_conf:   product             = 1200
08-04 12:01:28.700  4060  4076 D bt_bte_conf:   version             = 1436
,08-04 12:01:28.700  4060  4076 D bt_bte_conf:   clientExecutableURL = 
08-04 12:01:28.700  4060  4076 D bt_bte_conf:   serviceDescription  = 
08-04 12:01:28.701  4060  4076 D bt_bte_conf:   documentationURL    = 
08-04 12:01:28.702  4060  4076 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-04 12:01:28.702  4060  4073 D bt_stack_manager: event_start_up_stack finished
08-04 12:01:28.705  4060  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-04 12:01:28.706  4060  4072 D BluetoothAdapterProperties: Setting state to 15
08-04 12:01:28.706  4060  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-04 12:01:28.708  4060  4072 I BluetoothAdapterState: Entering BleOnState
,08-04 12:01:28.712  4060  4072 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-04 12:01:28.712  4060  4072 D BluetoothAdapterProperties: Setting state to 11
08-04 12:01:28.712  4060  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-04 12:01:28.720  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:28.722  4060  4060 D HeadsetService: Received start request. Starting profile...
08-04 12:01:28.723  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:28.727  4060  4060 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 12:01:28.728  4060  4060 D HeadsetStateMachine: make
08-04 12:01:28.729  4060  4072 I BluetoothAdapterState: Entering PendingCommandState
,08-04 12:01:28.738  4060  4060 D HeadsetStateMachine: max_hf_connections = 1
,08-04 12:01:28.738  4060  4060 I bt_bluedroid: get_profile_interface handsfree
08-04 12:01:28.738  4060  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-04 12:01:28.739  4060  4076 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-04 12:01:28.744  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:28.745  4060  4060 D A2dpService: Received start request. Starting profile...
,08-04 12:01:28.745  4060  4060 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 12:01:28.745  4060  4060 I bt_bluedroid: get_profile_interface avrcp
,08-04 12:01:28.753  4060  4060 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 12:01:28.753  4060  4060 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 12:01:28.753  4060  4060 D A2dpStateMachine: make
,08-04 12:01:28.755  4060  4060 I bt_bluedroid: get_profile_interface a2dp
,08-04 12:01:28.756  4060  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-04 12:01:28.759  4060  4091 D A2dpStateMachine: Enter Disconnected: -2
,08-04 12:01:28.760  4060  4060 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 12:01:28.762  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:28.763  4060  4060 D HidService: Received start request. Starting profile...
,08-04 12:01:28.764  4060  4060 I bt_bluedroid: get_profile_interface hidhost
,08-04 12:01:28.764  4060  4076 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397f3e5
08-04 12:01:28.764  4060  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-04 12:01:28.764  4060  4060 D HidService: setHidService(): set to: null
08-04 12:01:28.765  4060  4060 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 12:01:28.765  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:28.766  4060  4060 D HealthService: Received start request. Starting profile...
,08-04 12:01:28.769  4060  4060 I bt_bluedroid: get_profile_interface health
,08-04 12:01:28.770  4060  4060 I BluetoothPanServiceJni: classInitNative(L105): succeeds,
,08-04 12:01:28.772  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:28.773  4060  4060 D PanService: Received start request. Starting profile...
,08-04 12:01:28.773  4060  4060 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-04 12:01:28.773  4060  4060 I bt_bluedroid: get_profile_interface pan
08-04 12:01:28.774  4060  4076 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 12:01:28.783  4060  4060 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:28.785  4060  4060 D BluetoothMapService: Received start request. Starting profile...
,08-04 12:01:28.785  4060  4060 D BluetoothMapService: start()
,08-04 12:01:28.791  4060  4060 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-04 12:01:28.793  4060  4060 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-04 12:01:28.793  4060  4060 D BluetoothMapAppObserver: createReceiver()
,08-04 12:01:28.795  4060  4060 D BluetoothMapAppObserver: initObservers()
,08-04 12:01:28.795  4060  4060 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-04 12:01:28.810  4060  4060 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:28.810  4060  4060 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:28.810  4060  4060 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:01:28.810  4060  4060 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:28.810  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 12:01:28.810  4060  4089 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 12:01:28.818  4060  4060 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:28.818  4060  4060 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:28.818  4060  4060 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:28.818  4060  4060 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:28.819  4060  4060 V BluetoothAdapterState: isTurningOff()=false
,08-04 12:01:28.819  4060  4060 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:28.819  4060  4060 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:28.820  4060  4060 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:28.820  4060  4060 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:28.820  4060  4060 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:28.821  4060  4060 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:28.821  4060  4060 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:28.822  4060  4060 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:28.822  4060  4060 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:28.822  4060  4060 V BluetoothAdapterState: isBleTurningOn()=false
08-04 12:01:28.822  4060  4060 V BluetoothAdapterState: isBleTurningOff()=false
,08-04 12:01:28.823  4060  4060 V BluetoothAdapterState: isTurningOff()=false
08-04 12:01:28.823  4060  4060 V BluetoothAdapterState: isTurningOn()=true
08-04 12:01:28.824  4060  4060 V BluetoothAdapterState: isBleTurningOn()=false
,08-04 12:01:28.824  4060  4060 V BluetoothAdapterState: isBleTurningOff()=false
08-04 12:01:28.825  4060  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-04 12:01:28.825  4060  4072 D BluetoothAdapterProperties: ScanMode =  20
08-04 12:01:28.825  4060  4072 D BluetoothAdapterProperties: State =  11
,08-04 12:01:28.826  4060  4072 D BluetoothAdapterProperties: Setting state to 12
,08-04 12:01:28.829  4060  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 12:01:28.830  4060  4072 I BluetoothAdapterState: Entering OnState
08-04 12:01:28.830   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:01:28.830  4060  4060 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-04 12:01:28.830   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:01:28.830  4060  4076 D BluetoothAdapterProperties: Scan Mode:21
08-04 12:01:28.830  4060  4076 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 12:01:28.831  4060  4060 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-04 12:01:28.833  3754  3765 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:28.836  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:28.839  3754  3764 D BluetoothPan: onBluetoothStateChange on: true
,08-04 12:01:28.839  4060  4060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 12:01:28.839  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:28.842  1360  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 12:01:28.843  4060  4060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:01:28.845  4060  4060 D ObexServerSockets: Succeed to create listening sockets 
08-04 12:01:28.845  4060  4060 D ObexServerSockets0: startAccept()
08-04 12:01:28.845  4060  4060 D ObexServerSockets0: prepareForNewConnect()
,08-04 12:01:28.846   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:01:28.847  1360  1384 D BluetoothPan: onBluetoothStateChange on: true
,08-04 12:01:28.850  4060  4060 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-04 12:01:28.850  4060  4060 D BluetoothSdpJni: SDP Create record success - handle: 0
08-04 12:01:28.850  1360  2386 D BluetoothMap: onBluetoothStateChange: up=true
08-04 12:01:28.853   873   873 D BluetoothA2dp: Proxy object connected
,08-04 12:01:28.853  3754  4053 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 12:01:28.853  4060  4097 D ObexServerSockets0: Accepting socket connection...
08-04 12:01:28.854  4060  4098 D ObexServerSockets0: Accepting socket connection...
08-04 12:01:28.855  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:01:28.856  1360  1360 D PanProfile: Bluetooth service connected
08-04 12:01:28.856  1360  1360 D BluetoothInputDevice: Proxy object connected
,08-04 12:01:28.856  1360  1360 D HidProfile: Bluetooth service connected
,08-04 12:01:28.857  3754  3765 D BluetoothMap: onBluetoothStateChange: up=true
08-04 12:01:28.858  1360  1360 D BluetoothMap: Proxy object connected
08-04 12:01:28.858  1360  1360 D MapProfile: Bluetooth service connected
,08-04 12:01:28.858  1360  1360 D BluetoothMap: getConnectedDevices()
,08-04 12:01:28.859  3754  3754 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 12:01:28.859  3754  3754 D PanProfile: Bluetooth service connected
08-04 12:01:28.859  3754  3754 D BluetoothInputDevice: Proxy object connected
,08-04 12:01:28.859  3754  3754 D HidProfile: Bluetooth service connected
08-04 12:01:28.861  1360  2386 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 12:01:28.862  3754  3754 D BluetoothMap: Proxy object connected
08-04 12:01:28.862  3754  3754 D MapProfile: Bluetooth service connected
,08-04 12:01:28.862  3754  3754 D BluetoothMap: getConnectedDevices()
08-04 12:01:28.863  1360  1360 D BluetoothA2dp: Proxy object connected
,08-04 12:01:28.863  3754  4053 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:01:28.865  1744  1949 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:01:28.865  1360  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 12:01:28.867  1360  2386 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 12:01:28.867   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 12:01:28.867  3754  3765 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 12:01:28.869  3754  3754 D BluetoothA2dp: Proxy object connected
08-04 12:01:28.871   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-04 12:01:28.872  4060  4060 D BluetoothMapService: onReceive
,08-04 12:01:28.872  4060  4060 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 12:01:28.872  4060  4060 D BluetoothMapService: STATE_ON
08-04 12:01:28.873  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:28.878  3754  3754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 12:01:28.885  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 12:01:28.885  3754  3754 D DockEventReceiver: finishStartingService: stopping service
,08-04 12:01:28.893  3754  3754 D BluetoothPbap: Proxy object connected
,08-04 12:01:28.893  3754  3754 D PbapServerProfile: Bluetooth service connected
,08-04 12:01:28.896  1360  1360 D BluetoothPbap: Proxy object connected
,08-04 12:01:28.896  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-04 12:01:28.901  4060  4060 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-04 12:01:28.901  4060  4060 D ObexServerSockets0: prepareForNewConnect()
,08-04 12:01:28.905  4060  4103 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:01:28.922  4060  4107 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 12:01:28.923  4060  4107 I BtOppRfcommListener: Accept thread started.
,08-04 12:01:28.932   873   873 D BluetoothHeadset: Proxy object connected
08-04 12:01:28.932   873   873 D BluetoothHeadset: Proxy object connected
,08-04 12:01:28.932  1744  1755 D BluetoothHeadset: Proxy object connected
,08-04 12:01:28.933  3754  3764 D BluetoothHeadset: Proxy object connected
08-04 12:01:28.933  3754  3754 D HeadsetProfile: Bluetooth service connected
08-04 12:01:28.933  1360  1373 D BluetoothHeadset: Proxy object connected
08-04 12:01:28.933  1360  1360 D HeadsetProfile: Bluetooth service connected
08-04 12:01:28.934   873   873 D BluetoothHeadset: Proxy object connected
,08-04 12:01:28.947   873   890 D BluetoothHeadset: Proxy object connected
,08-04 12:01:28.964  3754  3765 D BluetoothHeadset: Proxy object connected
,08-04 12:01:28.964  3754  3754 D HeadsetProfile: Bluetooth service connected
,08-04 12:01:28.966  1744  1915 D BluetoothHeadset: Proxy object connected
,08-04 12:01:28.970  1360  1384 D BluetoothHeadset: Proxy object connected
,08-04 12:01:28.971  1360  1360 D HeadsetProfile: Bluetooth service connected
08-04 12:01:28.971   873   890 D BluetoothHeadset: Proxy object connected
,08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:29.232  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:29.238  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:29.241  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:01:29.242  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31b5bc7 added. We now have 8 listener(s)
08-04 12:01:29.242  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:29.249   873  2061 D WifiService: setWifiEnabled: false pid=3703, uid=10000
,08-04 12:01:29.250   873  2061 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:01:29.259  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:29.260   873  1764 D WifiService: setWifiEnabled: true pid=3703, uid=10000
08-04 12:01:29.260   873  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 12:01:29.279   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:29.293  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:29.301  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:29.311   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-04 12:01:29.311   873  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 12:01:29.312   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-04 12:01:29.312   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-04 12:01:29.313   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 12:01:29.313   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-04 12:01:29.314   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-04 12:01:29.314   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-04 12:01:29.327   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-04 12:01:29.328   371   871 D CommandListener: Setting iface cfg
,08-04 12:01:29.328   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:01:29.329   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-04 12:01:29.329   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 12:01:29.388   873  1315 E native  : do suspend true
08-04 12:01:29.388   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 12:01:29.402   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-04 12:01:29.415   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:30.282  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:30.289  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:30.302  3703  3748 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-04 12:01:30.304  3703  3748 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 12:01:30.309  3703  3748 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@70586ac Bundle[{}]
,08-04 12:01:30.310  3703  3748 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 12:01:30.310  3703  3748 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 12:01:30.311  3703  3748 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-04 12:01:30.312  3703  3748 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-04 12:01:30.312  3703  3748 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 12:01:30.313  3703  3748 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-04 12:01:30.317  3703  3748 I System.out: Running OutgoingSocketThread
08-04 12:01:30.320  3703  4113 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 418)
08-04 12:01:30.322  3703  4113 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48368
08-04 12:01:30.322  3703  4113 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 12:01:30.815   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-04 12:01:30.963   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.50 rxSuccessRate=13.25 delta 1000 -> 994
,08-04 12:01:30.967   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-04 12:01:30.967   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:01:30.988   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-04 12:01:31.057   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-04 12:01:31.061  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-04 12:01:31.320  3703  3748 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 419)
,08-04 12:01:31.321  3703  3748 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 419)
,08-04 12:01:31.331  3703  3748 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 424)
,08-04 12:01:31.334  3703  3748 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-04 12:01:31.335  3703  3748 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 425)
,08-04 12:01:31.340  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.340  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b86e5f4 added. We now have 2 listener(s)
,08-04 12:01:31.342  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:01:31.343  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:01:31.343  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:01:31.343  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:31.343  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@138711d added. We now have 9 listener(s)
08-04 12:01:31.343  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.344  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 12:01:31.347  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:31.352  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:31.355  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:31.355  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:31.355  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.355  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667ed63 added. We now have 3 listener(s)
,08-04 12:01:31.357  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:01:31.357  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:01:31.357  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:01:31.357  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:31.358  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2266d60 added. We now have 10 listener(s)
,08-04 12:01:31.358  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.358  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:31.358  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:31.358  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:31.358  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:31.358  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.358  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:31.358  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.359  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b86e5f4 removed from the list
08-04 12:01:31.359  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.359  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@138711d removed from the list
08-04 12:01:31.359  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:31.359  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:31.359  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.360  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.360  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.361  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.362  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.362  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.362  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@138711d not in the list
08-04 12:01:31.362  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:31.363  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.363  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.364  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.364  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.364  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.364  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2266d60 removed from the list
08-04 12:01:31.364  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:31.364  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not e,xist in the list - probably already removed
08-04 12:01:31.365  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.365  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.365  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667ed63 removed from the list
08-04 12:01:31.366  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.366  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f00219 added. We now have 2 listener(s)
08-04 12:01:31.368  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:01:31.368  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:01:31.368  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:01:31.368  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:01:31.368  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2ab2de added. We now have 9 listener(s)
08-04 12:01:31.369  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.370  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:01:31.376  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:31.383  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:31.387  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:31.387  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:31.388  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.388  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b74ff8c added. We now have 3 listener(s)
08-04 12:01:31.390  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:01:31.390  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:01:31.390  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:01:31.391  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:31.391  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f5a6d5 added. We now have 10 listener(s)
08-04 12:01:31.391  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.391  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:31.391  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:01:31.391  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:01:31.392  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:01:31.392  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:31.392  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 12:01:31.394  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:31.395  3703  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-04 12:01:31.395  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:01:31.401  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:01:31.402  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:01:31.402  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:01:31.406  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 12:01:31.406  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:01:31.406  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-04 12:01:31.407  3703  3748 D BluetoothAdapter: STATE_ON
,08-04 12:01:31.412  4060  4099 D BtGatt.GattService: registerClient() - UUID=45b1135d-0c1b-4b00-b8a4-d9a03fa60a3a
08-04 12:01:31.413  4060  4076 D BtGatt.GattService: onClientRegistered() - UUID=45b1135d-0c1b-4b00-b8a4-d9a03fa60a3a, clientIf=5
,08-04 12:01:31.413  3703  3713 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-04 12:01:31.415  4060  4096 D BtGatt.GattService: start scan with filters
,08-04 12:01:31.420  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:01:31.420  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-04 12:01:31.421  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-04 12:01:31.421  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 12:01:31.421  4060  4079 D BtGatt.ScanManager: handling starting scan
,08-04 12:01:31.423  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:01:31.424  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:01:31.424  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:01:31.425  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-04 12:01:31.426  4060  4079 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bb6c280
,08-04 12:01:31.428  3703  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-04 12:01:31.428  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:31.428  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-04 12:01:31.428  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-04 12:01:31.428  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:01:31.428  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-04 12:01:31.428  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-04 12:01:31.429  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:01:31.429  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:01:31.429  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 12:01:31.429  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:01:31.431  3703  3748 D BluetoothAdapter: STATE_ON
08-04 12:01:31.432  4060  4099 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:01:31.433  4060  4096 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:01:31.433  4060  4076 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:01:31.433  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.434  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:01:31.434  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:01:31.434  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:01:31.435  4060  4079 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 12:01:31.435  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:01:31.435  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:01:31.437  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:31.437  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:01:31.437  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:01:31.438  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:01:31.439  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:01:31.441  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:31.441  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:31.441  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:01:31.446  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:01:31.447  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:31.447  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:31.448  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:31.448  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:31.448  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 12:01:31.448  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.449  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f00219 removed from the list
08-04 12:01:31.449  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.449  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2ab2de removed from the list
08-04 12:01:31.449  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:01:31.450  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.450  4060  4076 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:01:31.451  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:01:31.451  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:31.451  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.451  4060  4079 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:01:31.452  4060  4079 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-04 12:01:31.455  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:31.455  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.455  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.455  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2ab2de not in the list
08-04 12:01:31.455  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.455  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.457  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:31.457  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.458  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:31.458  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f5a6d5 removed from the list
08-04 12:01:31.458  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:31.458  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.459  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.459  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.459  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b74ff8c removed from the list
,08-04 12:01:31.461  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.461  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b76db51 added. We now have 2 listener(s)
,08-04 12:01:31.467  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:01:31.468  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:01:31.468  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:01:31.469  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-04 12:01:31.469  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a143fb6 added. We now have 9 listener(s)
,08-04 12:01:31.469  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:31.470  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:01:31.473  4060  4076 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 12:01:31.474  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:01:31.476  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:31.484  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:31.486  4060  4076 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 12:01:31.486  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:01:31.486  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 12:01:31.490  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:31.492  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:31.492  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.492  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9b424 added. We now have 3 listener(s)
,08-04 12:01:31.495  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 12:01:31.496  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:31.503  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:01:31.503  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 12:01:31.504  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:01:31.504  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:01:31.504  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fcdb8d added. We now have 10 listener(s)
08-04 12:01:31.504  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.505  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:01:31.505  4060  4076 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:01:31.505  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.505  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:01:31.506  4060  4079 D BtGatt.ScanManager: stopping BLe Batch
,08-04 12:01:31.506  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 12:01:31.506  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:01:31.506  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:31.506  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:01:31.509  3703  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 12:01:31.509  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 12:01:31.513  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 12:01:31.515  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-04 12:01:31.515  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 12:01:31.516  4060  4076 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:01:31.516  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:01:31.516  4060  4079 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-04 12:01:31.522  4060  4076 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:01:31.522  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.522  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-04 12:01:31.522  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:01:31.523  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-04 12:01:31.524  3703  3748 D BluetoothAdapter: STATE_ON
,08-04 12:01:31.527  4060  4099 D BtGatt.GattService: registerClient() - UUID=f77995b9-4499-4494-99cb-8f976f8f37dc
,08-04 12:01:31.528  4060  4076 D BtGatt.GattService: onClientRegistered() - UUID=f77995b9-4499-4494-99cb-8f976f8f37dc, clientIf=5
08-04 12:01:31.528  3703  3714 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 12:01:31.529  4060  4096 D BtGatt.GattService: start scan with filters
,08-04 12:01:31.534  4060  4079 D BtGatt.ScanManager: handling starting scan
,08-04 12:01:31.534  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-04 12:01:31.534  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 12:01:31.534  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-04 12:01:31.534  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-04 12:01:31.538  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 12:01:31.538  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-04 12:01:31.539  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:01:31.539  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-04 12:01:31.539  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:01:31.541  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-04 12:01:31.541   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-04 12:01:31.545  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 12:01:31.545  3703  3748 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-04 12:01:31.546  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:01:31.546  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:31.546  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 12:01:31.546  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:01:31.546  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.546  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:01:31.546  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.546  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b76db51 removed from the list
,08-04 12:01:31.546  4060  4076 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-04 12:01:31.546  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.546  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a143fb6 removed from the list
08-04 12:01:31.546  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-04 12:01:31.546  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:31.547  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:31.547  4060  4079 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-04 12:01:31.547  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.547  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 12:01:31.547  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:31.547  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:31.548  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.548  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.548  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.548  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a143fb6 not in the list
,08-04 12:01:31.549  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 12:01:31.549  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:01:31.549  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:01:31.549  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 12:01:31.549  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-04 12:01:31.550  3703  3748 D BluetoothAdapter: STATE_ON
08-04 12:01:31.551  4060  4070 D BtGatt.GattService: stopScan() - queue size =1
08-04 12:01:31.552  4060  4071 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:01:31.553  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:01:31.553  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-04 12:01:31.553  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-04 12:01:31.553  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-04 12:01:31.553  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-04 12:01:31.554  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:31.554  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:01:31.554  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:01:31.555  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 12:01:31.555  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.556   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:01:31.556   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 12:01:31.556   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 12:01:31.556  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.556  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.556  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.556  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:31.557  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fcdb8d removed from the list
08-04 12:01:31.557  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:31.557  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-04 12:01:31.557  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.557  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 12:01:31.557  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.557  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.557  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9b424 removed from the list
08-04 12:01:31.558  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 12:01:31.558  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@468a389 added. We now have 2 listener(s)
,08-04 12:01:31.559  4060  4076 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-04 12:01:31.559  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.560  4060  4079 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:01:31.560  4060  4079 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:01:31.560  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:01:31.560  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:01:31.560  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:01:31.560  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:31.561  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7578f8e added. We now have 9 listener(s)
08-04 12:01:31.561  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.561  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:01:31.564  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:31.569  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:31.574  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 12:01:31.576  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:31.578   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 12:01:31.579  4060  4076 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-04 12:01:31.579  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.580  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:31.581  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.581  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:31.582  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd63bc added. We now have 3 listener(s)
,08-04 12:01:31.584  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 12:01:31.585  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:01:31.585  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:01:31.585  4060  4076 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-04 12:01:31.585  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:31.585  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.585  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daeef45 added. We now have 10 listener(s)
08-04 12:01:31.585  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.586   371   871 D CommandListener: Setting iface cfg
,08-04 12:01:31.586  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:01:31.586  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-04 12:01:31.586  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 12:01:31.586  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 12:01:31.586   873  1315 D WifiStateMachine: Start Dhcp Watchdog 3
08-04 12:01:31.586  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 12:01:31.589  3703  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-04 12:01:31.589  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 12:01:31.592  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 12:01:31.592   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-04 12:01:31.593  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-04 12:01:31.593  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 12:01:31.594  4060  4076 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-04 12:01:31.594  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.594  4060  4079 D BtGatt.ScanManager: stopping BLe Batch
,08-04 12:01:31.597  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-04 12:01:31.597  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-04 12:01:31.598  3703  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-04 12:01:31.598  3703  3748 D BluetoothAdapter: STATE_ON
08-04 12:01:31.600  4060  4076 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-04 12:01:31.600  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.601  4060  4079 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:01:31.601  4060  4096 D BtGatt.GattService: registerClient() - UUID=fe2b97ed-f5f1-447c-827d-5ab5809f391f
,08-04 12:01:31.602  4060  4076 D BtGatt.GattService: onClientRegistered() - UUID=fe2b97ed-f5f1-447c-827d-5ab5809f391f, clientIf=5
08-04 12:01:31.602  3703  3714 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-04 12:01:31.602  4060  4070 D BtGatt.GattService: start scan with filters
08-04 12:01:31.604  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-04 12:01:31.604  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-04 12:01:31.604  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-04 12:01:31.604  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-04 12:01:31.605  4060  4076 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-04 12:01:31.606  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.606  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-04 12:01:31.606  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-04 12:01:31.606  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-04 12:01:31.607  4060  4079 D BtGatt.ScanManager: handling starting scan
,08-04 12:01:31.607  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-04 12:01:31.608   873  4116 D DhcpClient: Receive thread started
08-04 12:01:31.611  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 12:01:31.611  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:31.611  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:31.611  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:01:31.611  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.611  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-04 12:01:31.611  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:01:31.611  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@468a389 removed from the list
08-04 12:01:31.611  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:31.611  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7578f8e removed from the list
08-04 12:01:31.611  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 12:01:31.611  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:31.611  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.611  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-04 12:01:31.612  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:31.612  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:31.612  4060  4076 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-04 12:01:31.612  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.612  4060  4079 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-04 12:01:31.612  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.612  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 12:01:31.612  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:31.612  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7578f8e not in the list
08-04 12:01:31.612  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-04 12:01:31.612  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 12:01:31.612  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 12:01:31.613  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-04 12:01:31.613  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-04 12:01:31.613  3703  3748 D BluetoothAdapter: STATE_ON
08-04 12:01:31.613  4060  4070 D BtGatt.GattService: stopScan() - queue size =1,
08-04 12:01:31.614  4060  4071 D BtGatt.GattService: unregisterClient() - clientIf=5
08-04 12:01:31.614  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 12:01:31.614  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-04 12:01:31.614  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-04 12:01:31.614  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-04 12:01:31.614  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-04 12:01:31.615  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:01:31.615  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-04 12:01:31.615  3703  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 12:01:31.615  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 12:01:31.615  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.616  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.616  4060  4076 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-04 12:01:31.617  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.617  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.617  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:31.617  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daeef45 removed from the list
08-04 12:01:31.617  4060  4079 D BtGatt.ScanManager: Starting BLE batch scan
08-04 12:01:31.617  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-04 12:01:31.617  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:31.617  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:31.617  4060  4079 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-04 12:01:31.617  3703  3703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 12:01:31.617  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:31.617  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.617  3703  3703 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-04 12:01:31.617  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fd63bc removed from the list
08-04 12:01:31.617  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.617  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9543ac1 added. We now have 2 listener(s)
08-04 12:01:31.619  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:01:31.619  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:01:31.619  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 12:01:31.619  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 12:01:31.619  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50a0266 added. We now have 9 listener(s)
08-04 12:01:31.619  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 12:01:31.619  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 12:01:31.621  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 12:01:31.624  3703  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 12:01:31.625  3703  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 12:01:31.626  3703  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 12:01:31.626  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 12:01:31.626  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af46e54 added. We now have 3 listener(s)
08-04 12:01:31.627  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-04 12:01:31.627  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 12:01:31.627  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 12:01:31.627  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 12:01:31.627  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca8c1fd added. We now have 10 listener(s)
,08-04 12:01:31.627  3703  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 12:01:31.627  3703  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 12:01:31.627  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 12:01:31.627  3703  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 12:01:31.627  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 12:01:31.627  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.627  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 12:01:31.627  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 12:01:31.627  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9543ac1 removed from the list
,08-04 12:01:31.628  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 12:01:31.628  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50a0266 removed from the list
08-04 12:01:31.628  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 12:01:31.628  4060  4076 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-04 12:01:31.629  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.629  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-04 12:01:31.629  3703  3748 D io.jxcore.node.ConnectivityMonitor: stop
08-04 12:01:31.630  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:31.630  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 12:01:31.630  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:31.631  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 12:01:31.631  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.631  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:31.631  3703  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50a0266 not in the list
08-04 12:01:31.631  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.631  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 12:01:31.631  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 12:01:31.632  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 12:01:31.632  3703  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 12:01:31.632  3703  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca8c1fd removed from the list
,08-04 12:01:31.632  3703  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 12:01:31.632  3703  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 12:01:31.632  3703  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 12:01:31.632  3703  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 12:01:31.632  3703  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af46e54 removed from the list
08-04 12:01:31.632  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-04 12:01:31.632  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 12:01:31.633  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 12:01:31.633  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:01:31.633  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-04 12:01:31.633  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:31.634  4060  4076 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-04 12:01:31.634  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.637  3703  4117 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
08-04 12:01:31.637  3703  4117 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
,08-04 12:01:31.637  3703  4117 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 12:01:31.638  3703  4118 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
08-04 12:01:31.638  3703  4118 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
08-04 12:01:31.638  3703  4118 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 12:01:31.639  3703  3748 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-04 12:01:31.639  3703  3748 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-04 12:01:31.639  3703  3748 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 12:01:31.639  4060  4076 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-04 12:01:31.639  3703  3748 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 12:01:31.639  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-04 12:01:31.639  3703  3748 D com.test.thalitest.ThaliTestRunner: Total duration: 22824 ms
08-04 12:01:31.640  4060  4079 D BtGatt.ScanManager: stopping BLe Batch
08-04 12:01:31.641  3703  3748 I jxcore-log: Total number of executed tests:  80
08-04 12:01:31.641  3703  3748 I jxcore-log: 
08-04 12:01:31.641  3703  3748 I jxcore-log: Number of passed tests:  80
08-04 12:01:31.641  3703  3748 I jxcore-log: 
,08-04 12:01:31.641  3703  3748 I jxcore-log: Number of failed tests:  0
08-04 12:01:31.641  3703  3748 I jxcore-log: 
08-04 12:01:31.641  3703  3748 I jxcore-log: Number of ignored tests:  0
08-04 12:01:31.641  3703  3748 I jxcore-log: 
08-04 12:01:31.641  3703  3748 I jxcore-log: Total duration:  22824
08-04 12:01:31.641  3703  3748 I jxcore-log: 
,08-04 12:01:31.643  3703  3748 I jxcore-log: Unit Test app is loaded
08-04 12:01:31.643  3703  3748 I jxcore-log: 
08-04 12:01:31.645  4060  4076 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-04 12:01:31.645  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.646  4060  4079 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-04 12:01:31.649  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.649  3703  3748 I jxcore-log: 
,08-04 12:01:31.650  4060  4076 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-04 12:01:31.651  4060  4076 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-04 12:01:31.652  3703  3703 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-04 12:01:31.653  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.653  3703  3748 I jxcore-log: 
,08-04 12:01:31.654  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.654  3703  3748 I jxcore-log: 
08-04 12:01:31.655  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.655  3703  3748 I jxcore-log: 
08-04 12:01:31.655  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.655  3703  3748 I jxcore-log: 
08-04 12:01:31.656  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.656  3703  3748 I jxcore-log: 
08-04 12:01:31.657  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.657  3703  3748 I jxcore-log: 
08-04 12:01:31.658  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.658  3703  3748 I jxcore-log: 
,08-04 12:01:31.659  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.659  3703  3748 I jxcore-log: 
,08-04 12:01:31.659  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.659  3703  3748 I jxcore-log: 
08-04 12:01:31.660  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.660  3703  3748 I jxcore-log: 
,08-04 12:01:31.660  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.660  3703  3748 I jxcore-log: 
,08-04 12:01:31.661  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:01:31.661  3703  3748 I jxcore-log: 
,08-04 12:01:31.661  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.661  3703  3748 I jxcore-log: 
08-04 12:01:31.662  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.662  3703  3748 I jxcore-log: 
,08-04 12:01:31.662  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.662  3703  3748 I jxcore-log: 
,08-04 12:01:31.663  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:31.663  3703  3748 I jxcore-log: 
08-04 12:01:31.663  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.663  3703  3748 I jxcore-log: 
,08-04 12:01:31.664  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.664  3703  3748 I jxcore-log: 
,08-04 12:01:31.664  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.664  3703  3748 I jxcore-log: 
08-04 12:01:31.665  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.665  3703  3748 I jxcore-log: 
,08-04 12:01:31.665  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.665  3703  3748 I jxcore-log: 
,08-04 12:01:31.666  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.666  3703  3748 I jxcore-log: 
08-04 12:01:31.666  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.666  3703  3748 I jxcore-log: 
,08-04 12:01:31.666  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.666  3703  3748 I jxcore-log: 
08-04 12:01:31.667  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.667  3703  3748 I jxcore-log: 
,08-04 12:01:31.667  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 12:01:31.667  3703  3748 I jxcore-log: 
,08-04 12:01:31.668  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.668  3703  3748 I jxcore-log: 
08-04 12:01:31.668  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.668  3703  3748 I jxcore-log: 
,08-04 12:01:31.668  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.668  3703  3748 I jxcore-log: 
08-04 12:01:31.669  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.669  3703  3748 I jxcore-log: 
,08-04 12:01:31.669  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.669  3703  3748 I jxcore-log: 
,08-04 12:01:31.670  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.670  3703  3748 I jxcore-log: 
08-04 12:01:31.670  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 12:01:31.670  3703  3748 I jxcore-log: 
,08-04 12:01:31.672  3703  3748 I jxcore-log: My device name is: motorola-Nexus 6
08-04 12:01:31.672  3703  3748 I jxcore-log: 
,08-04 12:01:31.688   873  1315 E native  : do suspend false
,08-04 12:01:31.696   873  1997 D DhcpClient: Broadcasting DHCPDISCOVER
,08-04 12:01:31.724   873  4116 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-04 12:01:31.724   873  1997 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
08-04 12:01:31.725   873  1997 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-04 12:01:31.735   873  4116 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-04 12:01:31.736   873  1997 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-04 12:01:31.737   371   871 D CommandListener: Setting iface cfg
,08-04 12:01:31.739   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-04 12:01:31.740   873  1997 D DhcpClient: Scheduling renewal in 86399s
,08-04 12:01:31.740   873  1315 E native  : do suspend true
,08-04 12:01:31.750   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-04 12:01:31.751   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-04 12:01:31.751   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-04 12:01:31.753   873  1317 D ConnectivityService: Adding iface wlan0 to network 102
,08-04 12:01:31.754   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 12:01:31.804   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 12:01:31.804   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-04 12:01:31.805   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-04 12:01:31.805   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-04 12:01:31.806   873  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-04 12:01:31.812   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-04 12:01:31.816   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-04 12:01:31.816   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-04 12:01:31.816   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-04 12:01:31.816   873  1317 D ConnectivityService:    accepting network in place of null
08-04 12:01:31.816   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-04 12:01:31.817   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-04 12:01:31.817   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-04 12:01:31.825   873  4115 D NetlinkSocketObserver: NeighborEvent{elapsedMs=417417, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-04 12:01:31.841   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:01:31.859   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-04 12:01:31.861   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-04 12:01:31.861   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:31.863   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-04 12:01:31.863   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 12:01:31.873  3703  3703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 12:01:31.874  3703  3703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 12:01:31.877  1880  1880 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-04 12:01:31.881  1880  1880 D SystemUpdateService: onCreate
,08-04 12:01:31.884  1880  1880 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-04 12:01:31.900  1880  1880 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 12:01:31.903   873  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.46,2a00:1450:401b:800::200e
,08-04 12:01:31.914  1880  4128 I SystemUpdateService: active receiver: enabled
,08-04 12:01:31.904  1880  2346 I iu.UploadsManager: num queued entries: 0
,08-04 12:01:31.916  1880  1880 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-04 12:01:31.916  1880  2346 I iu.UploadsManager: num updated entries: 0
,08-04 12:01:31.917  1880  1880 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-04 12:01:31.919  3837  3837 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-04 12:01:31.925  3837  3837 D SprintDMHelper: simOperator: 
,08-04 12:01:31.925  3837  3837 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-04 12:01:31.929  1880  4130 I MDM     : [219] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-04 12:01:31.929  1880  4130 W BaseAppContext: Using Auth Proxy for data requests.
08-04 12:01:31.930  1880  4130 V GoogleAuthProtoRequest: [219] a.<init>: mAccountName set to: thalitester@gmail.com
,08-04 12:01:31.942  3703  3703 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:01:31.961  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:01:31.969  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 12:01:31.978  1880  2346 I iu.SyncManager: NEXT; no task
,08-04 12:01:31.984  1880  4128 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-04 12:01:32.000   873  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 10:01:32 GMT], X-Android-Received-Millis=[1470304891999], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470304891959]}
08-04 12:01:32.003  1880  4128 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-04 12:01:32.003  1880  4128 I SystemUpdateService: now status is 0 (complete)
,08-04 12:01:32.003  1880  4128 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-04 12:01:32.003   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-04 12:01:32.004   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-04 12:01:32.004   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-04 12:01:32.007   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 12:01:32.009  1880  4128 I SystemUpdateService: file has been verified
,08-04 12:01:32.011  1880  4128 I SystemUpdateService: OTA package size = 12249756
,08-04 12:01:32.019  1880  4128 I SystemUpdateService: showing system update notification
,08-04 12:01:32.028  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-04 12:01:32.028  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-04 12:01:32.029  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 12:01:32.029  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-04 12:01:32.046  1880  4130 E MDM     : [219] SitrepService.a: Error sending sitrep.
,08-04 12:01:32.050  1880  1880 D SystemUpdateService: onDestroy
,08-04 12:01:32.058  3703  3703 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:01:32.113  3806  4133 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-04 12:01:32.118  3703  3703 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 12:01:33.996  3703  3748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-04 12:01:33.996  3703  3748 I jxcore-log: 
,08-04 12:01:34.611  3703  3748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-04 12:01:34.611  3703  3748 I jxcore-log: 
,08-04 12:01:34.635  3703  3748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-04 12:01:34.635  3703  3748 I jxcore-log: 
,08-04 12:01:35.992  3703  3748 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-04 12:01:35.992  3703  3748 I jxcore-log: 
,08-04 12:01:36.222  3703  3748 I jxcore-log: ERROR runTests: 
08-04 12:01:36.222  3703  3748 I jxcore-log: 
,08-04 12:01:36.225  3703  3748 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-04 12:01:36.225  3703  3748 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-04 12:01:36.225  3703  3748 I jxcore-log: WARN testUtils: logCallback not set!
08-04 12:01:36.225  3703  3748 I jxcore-log: 
,08-04 12:01:36.237  3703  3748 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _functionName: 'loadFile',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _lineNumber: '26',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _columnNumber: '11',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-04 12:01:36.237  3703  3748 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _functionName: '',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _lineNumber: '39',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _columnNumber: '7',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-04 12:01:36.237  3703  3748 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _functionName: '',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _lineNumber: '35',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _columnNumber: '3',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-04 12:01:36.237  3703  3748 I jxcore-log:   { _fileName: 'module.js',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _functionName: '$w.prototype._compile',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _lineNumber: '621',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _columnNumber: '8',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-04 12:01:36.237  3703  3748 I jxcore-log:   { _fileName: 'module.js',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _lineNumber: '651',
08-04 12:01:36.237  3703  3748 I jxcore-log:     _columnNumber: '1',
08-04 12:01:36.237  3703  3748 I jxcore-log:    
,08-04 12:01:36.237  3703  3748 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-04 12:01:36.237  3703  3748 I jxcore-log: 
,08-04 12:01:36.245  3703  3748 E jxcore-log: Error: 
08-04 12:01:36.245  3703  3748 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-04 12:01:36.245  3703  3748 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-04 12:01:36.246  3703  3748 E jxcore-log: 
08-04 12:01:36.247  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 12:01:36.247  3703  3748 I jxcore-log: 
08-04 12:01:36.248  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:01:36.248  3703  3748 I jxcore-log: 
08-04 12:01:36.248  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:01:36.248  3703  3748 I jxcore-log: 
08-04 12:01:36.249  3703  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 12:01:36.249  3703  3748 I jxcore-log: 
08-04 12:01:36.249  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 12:01:36.249  3703  3748 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-04 12:01:36.249  3703  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 12:01:36.249  3703  3748 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-04 12:01:36.933  4140  4140 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 12:01:36.938  4140  4140 D AndroidRuntime: CheckJNI is OFF
,08-04 12:01:36.979  4140  4140 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 12:01:37.026  4140  4140 I Radio-JNI: register_android_hardware_Radio DONE
,08-04 12:01:37.048  4140  4140 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 12:01:37.059   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-04 12:01:37.060   873   886 I ActivityManager: Killing 3703:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-04 12:01:37.175   873  1389 D GraphicsStats: Buffer count: 2
,08-04 12:01:37.179   873  1316 D WifiService: Client connection lost with reason: 4
,08-04 12:01:37.179   873  1389 I WindowState: WIN DEATH: Window{50ac695 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 12:01:37.193   873   897 W PackageSettings: Skipping PackageSetting{e6b8dcd com.example.hello/10273} due to missing metadata
,08-04 12:01:37.226   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-04 12:01:37.226   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-04 12:01:37.227   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-04 12:01:37.227   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
,08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-04 12:01:37.227   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.227   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.227   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:01:37.227   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 12:01:37.227   873   886 I ActivityManager:   Force finishing activity ActivityRecord{3760f16 u0 com.test.thalitest/.MainActivity t2}
08-04 12:01:37.228   873   897 I art     : Starting a blocking GC Explicit
,08-04 12:01:37.248   873  1806 W ActivityManager: Spurious death for ProcessRecord{2340435 0:com.test.thalitest/u0a0}, curProc for 3703: null
,08-04 12:01:37.274   873   897 I art     : Explicit concurrent mark sweep GC freed 29076(1840KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 725us total 45.082ms
,08-04 12:01:37.295   873   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-04 12:01:37.297  4140  4140 I art     : System.exit called, status: 0
,08-04 12:01:37.297  4140  4140 I AndroidRuntime: VM exiting with result code 0.
,08-04 12:01:37.299   873   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-04 12:01:37.315   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-04 12:01:37.320  4060  4060 D BluetoothMapAppObserver: onReceive
,08-04 12:01:37.320  4060  4060 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-04 12:01:37.322  1900  2050 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-04 12:01:37.324  3514  3514 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-04 12:01:37.324  1668  1668 I Keyboard.Facilitator: resetDictionaries() : en_US
08-04 12:01:37.329   873  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 12:01:37.369  1744  1744 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-04 12:01:37.364  1668  4151 I Keyboard.Facilitator.DecoderInitializer: run()
,08-04 12:01:37.375   873   884 I ActivityManager: Start proc 4154:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-04 12:01:37.413  1668  4151 I Decoder : createOrResetDecoder
,08-04 12:01:37.422   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 12:01:37.429  4154  4154 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-04 12:01:37.432  1523  1523 I ConfigService: onCreate
,08-04 12:01:37.437   873  2060 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3703 uid 10000
,08-04 12:01:37.438  1668  1668 I Keyboard.Facilitator: onFinishInput()
,08-04 12:01:37.444  1756  1838 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-04 12:01:37.445  1523  4167 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 12:01:37.445  1523  4167 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-04 12:01:37.445   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-04 12:01:37.445   873   885 E PackageManager: Failed to write settings, restoring backup
,08-04 12:01:37.445   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-04 12:01:37.445   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-04 12:01:37.445   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-04 12:01:37.445   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-04 12:01:37.445   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-04 12:01:37.445   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.445   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.445   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-04 12:01:37.446  1523  4167 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-04 12:01:37.449   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-04 12:01:37.449   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 12:01:37.449   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:01:37.449   873   886 E DropBoxManagerService: 	... 13 more
08-04 12:01:37.450  1523  4167 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-04 12:01:37.457   873  3003 I ActivityManager: Start proc 4168:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-04 12:01:37.457  1756  1838 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-04 12:01:37.457  1756  1838 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1756
08-04 12:01:37.457  1756  1838 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.457  1756  1838 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 12:01:37.460   873  1796 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-04 12:01:37.462   873  4174 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:01:37.462   873  4174 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:01:37.462   873  4174 E DropBoxManagerService: 	... 5 more
,08-04 12:01:37.464  1756  1838 I Process : Sending signal. PID: 1756 SIG: 9
,08-04 12:01:37.480  1668  4151 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-04 12:01:37.513  1668  4151 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-04 12:01:37.514  1668  4151 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-04 12:01:37.514  1668  4151 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-04 12:01:37.518  1668  4151 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-04 12:01:37.518  1668  4151 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-04 12:01:37.519  1668  4151 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-04 12:01:37.519  1668  4151 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-04 12:01:37.519  1668  4151 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-04 12:01:37.519  1668  4151 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-04 12:01:37.519  1668  4151 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-04 12:01:37.519  1668  4151 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-04 12:01:37.519  1668  4151 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-04 12:01:37.520  1668  4151 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-04 12:01:37.527  4154  4154 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-04 12:01:37.536   278   278 E lowmemorykiller: Error writing /proc/1756/oom_score_adj; errno=22
,08-04 12:01:37.549   873  3003 I ActivityManager: Start proc 4187:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-04 12:01:37.549   278   278 E lowmemorykiller: Error writing /proc/1756/oom_score_adj; errno=22
,08-04 12:01:37.550   873  2061 D GraphicsStats: Buffer count: 1
,08-04 12:01:37.550   873  1796 I WindowState: WIN DEATH: Window{1a4b925 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-04 12:01:37.561   873  2061 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1756) has died
,08-04 12:01:37.561   873  2061 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-04 12:01:37.563   873  2061 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-04 12:01:37.572  4154  4189 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-04 12:01:37.579   873   886 I ActivityManager: Start proc 4200:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 12:01:37.617  4187  4187 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-04 12:01:37.622  4200  4200 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:37.622  4200  4200 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-04 12:01:37.623  4200  4200 D AndroidRuntime: Shutting down VM
,08-04 12:01:37.627  4154  4182 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.627  4154  4182 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:01:37.630  4200  4200 E AndroidRuntime: FATAL EXCEPTION: main
08-04 12:01:37.630  4200  4200 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4200
08-04 12:01:37.630  4200  4200 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 12:01:37.630  4200  4200 E AndroidRuntime: 	... 10 more
,08-04 12:01:37.632   873  1764 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-04 12:01:37.632  4200  4200 I Process : Sending signal. PID: 4200 SIG: 9
08-04 12:01:37.633   873  4214 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:01:37.633   873  4214 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:01:37.633   873  4214 E DropBoxManagerService: 	... 5 more
,08-04 12:01:37.649  1880  4212 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-04 12:01:37.650  1880  4212 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-04 12:01:37.652   873  2060 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4200) has died
,08-04 12:01:37.653   873  2060 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.655  4154  4182 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:01:37.660  1523  1523 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-04 12:01:37.661  1880  4212 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-04 12:01:37.665  1880  4212 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-04 12:01:37.666  1523  1523 D AndroidRuntime: Shutting down VM
,08-04 12:01:37.666   873   886 I ActivityManager: Start proc 4217:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-04 12:01:37.670  1523  1523 E AndroidRuntime: FATAL EXCEPTION: main
08-04 12:01:37.670  1523  1523 E AndroidRuntime: Process: com.google.process.gapps, PID: 1523
08-04 12:01:37.670  1523  1523 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-04 12:01:37.670  1523  1523 E AndroidRuntime: 	... 8 more
,08-04 12:01:37.674  1523  1523 I Process : Sending signal. PID: 1523 SIG: 9
08-04 12:01:37.676   873  1391 I ActivityManager: Killing 3566:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-04 12:01:37.678   873  4228 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:01:37.678   873  4228 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:01:37.678   873  4228 E DropBoxManagerService: 	... 5 more
,08-04 12:01:37.717  4154  4182 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-04 12:01:37.721  4154  4189 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.721  4154  4189 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:01:37.722  4154  4189 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-04 12:01:37.722  4154  4189 E AndroidRuntime: Process: android.process.acore, PID: 4154
08-04 12:01:37.722  4154  4189 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269),
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 12:01:37.722  4154  4189 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 12:01:37.725   873  1316 D WifiService: Client connection lost with reason: 4
,08-04 12:01:37.728  4154  4182 I Process : Sending signal. PID: 4154 SIG: 9
,08-04 12:01:37.752   873   884 I ActivityManager: Process com.google.process.gapps (pid 1523) has died
,08-04 12:01:37.753   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-04 12:01:37.753   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-04 12:01:37.753   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-04 12:01:37.757   873  4230 E DropBoxManagerService: Can't write: system_app_crash
08-04 12:01:37.757   873  4230 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 12:01:37.757   873  4230 E DropBoxManagerService: 	... 5 more
,08-04 12:01:37.760  1880  1880 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-04 12:01:37.775   873   884 I ActivityManager: Start proc 4231:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-04 12:01:37.780   873  1764 I ActivityManager: Process android.process.acore (pid 4154) has died
,08-04 12:01:37.781   873  1764 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30972ms

```
