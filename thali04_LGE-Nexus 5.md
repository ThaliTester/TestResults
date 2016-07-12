#### Test 757892685a40176_thali04_LGE-Nexus 5 Logs


```
--------- beginning of system
07-12 17:45:04.219   791  1303 I ActivityManager: Killing 2721:com.android.chrome/u0a34 (adj 15): empty #17
,--------- beginning of main
07-12 17:45:04.804  3442  3442 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 17:45:04.808  3442  3442 D AndroidRuntime: CheckJNI is OFF
07-12 17:45:04.842  3442  3442 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 17:45:04.877  3442  3442 I Radio-JNI: register_android_hardware_Radio DONE
07-12 17:45:04.895  3442  3442 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 17:45:04.898   791  2609 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 17:45:04.927   791  2609 I ActivityManager: Start proc 3458:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 17:45:04.930  3442  3442 D AndroidRuntime: Shutting down VM
07-12 17:45:04.999  3458  3458 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-12 17:45:05.046  3458  3458 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 343-345)
07-12 17:45:05.046  3458  3458 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:05.068  3458  3458 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a04a51}
07-12 17:45:05.068  3458  3458 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:05.068  3458  3458 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:45:05.074  3458  3458 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-12 17:45:05.075  3458  3458 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 17:45:05.085  3458  3458 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-12 17:45:05.089  3458  3458 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:05.089  3458  3458 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:05.089  3458  3458 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-12 17:45:05.129   791   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@add22b7:true
,07-12 17:45:05.244  3458  3458 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 17:45:05.254  3458  3458 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-12 17:45:05.305  3458  3495 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-12 17:45:05.326  3458  3482 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-12 17:45:05.349  3458  3495 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 17:45:05.376  1240  1240 I Keyboard.Facilitator: onFinishInput()
,07-12 17:45:05.394   791   812 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +441ms (total +480ms)
,07-12 17:45:05.474  3458  3458 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3458
,07-12 17:45:05.554  3458  3458 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 17:45:05.706  3458  3498 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1654458064
,07-12 17:45:05.711  3458  3498 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:45:05.711  3458  3498 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:45:05.711  3458  3498 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:45:05.711  3458  3498 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:45:05.711  3458  3498 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-12 17:45:05.711  3458  3498 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d2077c added. We now have 1 listener(s)
,07-12 17:45:05.713  3458  3498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
,07-12 17:45:05.714  3458  3498 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:05.715  3458  3498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:05.715  3458  3498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-12 17:45:05.717  3458  3498 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8e828b added. We now have 1 listener(s)
07-12 17:45:05.717  3458  3498 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:05.719   791   897 D WifiService: New client listening to asynchronous messages
,07-12 17:45:05.721  3458  3498 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-12 17:45:05.723  3458  3498 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-12 17:45:05.723  3458  3498 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-12 17:45:05.724  3458  3498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:05.724  3458  3498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:05.728  3458  3498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:05.728  3458  3498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:45:05.728  3458  3498 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:05.728  3458  3498 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:45:05.737  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:05.738  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:05.749  3458  3458 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 17:45:06.469  3458  3505 W jxcore-log: Initializing JXcore engine
,07-12 17:45:06.469  3458  3505 W jxcore-log: JXcore engine is ready
,07-12 17:45:06.504  3505  3505 W Thread-273: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8467]" dev="sockfs" ino=8467 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-12 17:45:06.504  3505  3505 W Thread-273: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 17:45:06.504  3505  3505 W Thread-273: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21927]" dev="sockfs" ino=21927 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 17:45:06.531  3458  3505 W jxcore-log: Starting JXcore engine
,07-12 17:45:06.628  3458  3505 W jxcore-log: Platform android
07-12 17:45:06.628  3458  3505 W jxcore-log: 
07-12 17:45:06.628  3458  3505 W jxcore-log: Process ARCH arm
07-12 17:45:06.628  3458  3505 W jxcore-log: 
,07-12 17:45:06.843  3458  3505 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:45:06.843  3458  3505 I jxcore-log: 
07-12 17:45:06.843  3458  3505 W jxcore-log: JXcore engine is started
,07-12 17:45:06.848  3458  3498 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:45:06.849  3458  3458 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:45:14.726  2450  2482 I Finsky  : [214] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-12 17:45:14.804  2450  2482 I Finsky  : [214] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-12 17:45:14.804  2450  2450 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-12 17:45:16.641  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 17:45:16.641  3458  3505 I jxcore-log: 
07-12 17:45:16.643  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 17:45:16.643  3458  3505 I jxcore-log: 
,07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:16.647  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:16.648  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:16.650  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 17:45:16.650  3458  3505 I jxcore-log: 
07-12 17:45:16.651  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 17:45:16.651  3458  3505 I jxcore-log: 
,07-12 17:45:16.986  3458  3505 I jxcore-log: Unit Test app is loadeded
07-12 17:45:16.986  3458  3505 I jxcore-log: 
,07-12 17:45:16.992  3458  3458 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 17:45:16.993  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:16.993  3458  3505 I jxcore-log: 
07-12 17:45:16.996  3458  3505 I jxcore-log: runUTtestsBefore
07-12 17:45:16.996  3458  3505 I jxcore-log: 
07-12 17:45:16.997  3458  3505 D JXMOBILE: Running tests
,07-12 17:45:17.074  3458  3505 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-12 17:45:17.074  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-12 17:45:17.074  3458  3505 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,07-12 17:45:17.074  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-12 17:45:17.074  3458  3505 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,07-12 17:45:17.074  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-12 17:45:17.075  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-12 17:45:17.075  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-12 17:45:17.076  3458  3505 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-12 17:45:17.076  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:17.076  3458  3505 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-12 17:45:17.076  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-12 17:45:17.076  3458  3505 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-12 17:45:17.076  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:17.076  3458  3505 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-12 17:45:17.076  3458  3505 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-12 17:45:17.077  3458  3505 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-12 17:45:17.077  3458  3505 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-12 17:45:17.077  3458  3505 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-12 17:45:17.077  3458  3505 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-12 17:45:17.077  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:17.077  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f6a8e9 added. We now have 2 listener(s)
07-12 17:45:17.077  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:17.079  3458  3505 D BluetoothAdapter: enable(): BT is already enabled..!
07-12 17:45:17.079   791  1306 D WifiService: setWifiEnabled: true pid=3458, uid=10000
07-12 17:45:17.079   791  1306 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:17.080  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:17.080  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b3196e added. We now have 3 listener(s)
07-12 17:45:17.080  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:17.083  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:17.083  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@415880f added. We now have 4 listener(s)
07-12 17:45:17.083  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:17.084  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:17.084  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@739b09c added. We now have 5 listener(s)
07-12 17:45:17.084  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:17.085   791   801 D WifiService: setWifiEnabled: false pid=3458, uid=10000
,07-12 17:45:17.085   791   801 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:17.087   791   896 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-12 17:45:17.087   791   896 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-12 17:45:17.087   791   896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:17.087   791   896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:17.089  1954  2037 D BluetoothAdapterState: Current state: ON, message: 23
07-12 17:45:17.089  1954  2037 D BluetoothAdapterProperties: Setting state to 13
07-12 17:45:17.089  1954  2037 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-12 17:45:17.090  1954  2037 D BluetoothAdapterProperties: onBluetoothDisable()
07-12 17:45:17.090  1954  2037 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:17.093  1954  1954 D BluetoothMapService: onReceive
07-12 17:45:17.093  1954  1954 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:17.093  1954  1954 D BluetoothMapService: STATE_TURNING_OFF
07-12 17:45:17.093  1954  1954 D BluetoothMapService: MAP Service closeService in
07-12 17:45:17.093  1954  1954 D BluetoothMapMasInstance0: MAP Service shutdown
07-12 17:45:17.093  1954  1954 D ObexServerSockets0: shutdown(block = true)
07-12 17:45:17.094  1954  1954 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:17.094  1954  1954 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:17.094  1954  2210 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-12 17:45:17.094  1954  2211 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-12 17:45:17.094  1954  2199 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-12 17:45:17.095  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:17.100  1954  1954 I BtOppRfcommListener: stopping Accept Thread
07-12 17:45:17.101  1954  2630 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-12 17:45:17.101  1954  2630 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:17.102  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:17.103  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:17.103  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:17.104   791   807 I ActivityManager: Start proc 3509:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-12 17:45:17.104  1954  2041 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:17.105  1954  2037 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-12 17:45:17.107  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:17.107   791   896 E native  : do suspend true
07-12 17:45:17.108  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:17.111  1954  1954 D HeadsetService: Received stop request...Stopping profile...
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Blu,etooth enabled: false
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:17.111  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:17.112  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:17.113   946   964 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:17.115  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:17.119  1954  1954 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:17.120  1954  2203 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:17.121  1954  1954 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:17.121  1954  1954 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.121  1954  1954 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:17.121  1954  1954 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:17.123  1954  1954 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-12 17:45:17.123  1954  1954 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-12 17:45:17.123  1954  2136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:17.123  1954  2136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:17.123  1954  1954 D HidService: Received stop request...Stopping profile...
07-12 17:45:17.123  1954  1954 D HidService: Stopping Bluetooth HidService
07-12 17:45:17.124  1954  2041 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-12 17:45:17.124  1954  2041 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-12 17:45:17.124  1954  1954 D HealthService: Received stop request...Stopping profile...
07-12 17:45:17.125  1954  1954 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:17.125  1954  1954 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.125  1954  1954 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:17.125  1954  1954 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:17.126  1954  1954 D PanService: Received stop request...Stopping profile...
07-12 17:45:17.127  1954  2136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:17.127  1954  2136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:17.127  1954  2136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:17.127  1954  2136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:17.127  1954  2136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:17.127  1954  2136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:17.127  1954  2041 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-12 17:45:17.128  1954  1954 D BluetoothMapService: Received stop request...Stopping profile...
07-12 17:45:17.128  1954  1954 D BluetoothMapService: stop()
07-12 17:45:17.128  1954  1954 D BluetoothMapAppObserver: deinitObservers()
07-12 17:45:17.128  1954  1954 D BluetoothMapAppObserver: removeReceiver()
07-12 17:45:17.129  1954  1954 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:17.129  1954  1954 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.129  1954  1954 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:17.129  1954  1954 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:17.129  1954  1954 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-12 17:45:17.129  1954  2041 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-12 17:45:17.12,9  1954  1954 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-12 17:45:17.130  1954  1954 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:17.130  1954  1954 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.130  1954  1954 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:17.130  1954  1954 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:17.130  1954  1954 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-12 17:45:17.130  1954  2041 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-12 17:45:17.130  1954  1954 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-12 17:45:17.131  1954  1954 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:17.131  1954  1954 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.131  1954  1954 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:17.131  1954  1954 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:17.131  1954  1954 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-12 17:45:17.131  1954  1954 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-12 17:45:17.132  1954  1954 D BluetoothMapService: MAP Service closeService in
,07-12 17:45:17.132  1954  1954 V BluetoothAdapterState: isTurningOff()=true
,07-12 17:45:17.132  1954  1954 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.132  1954  1954 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:17.132  1954  1954 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:17.132  1954  2037 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-12 17:45:17.132  1954  2037 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:17.132  1954  2037 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:17.133  1954  2037 I BluetoothAdapterState: Entering BleOnState
,07-12 17:45:17.133  1954  1954 D BluetoothMapService: cleanup()
07-12 17:45:17.133  1954  1954 D BluetoothMapService: MAP Service closeService in
07-12 17:45:17.143   791   791 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:17.143   946   964 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-12 17:45:17.144  1286  1302 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:17.144   791   791 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:17.144   791   791 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:17.144   791   791 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:17.146   791  2688 D DhcpClient: Clearing IP address
,07-12 17:45:17.146   193   684 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:17.149   193   684 D CommandListener: Setting iface cfg
07-12 17:45:17.149   946   946 D HeadsetProfile: Bluetooth service disconnected
,07-12 17:45:17.149   946   946 D BluetoothInputDevice: Proxy object disconnected
07-12 17:45:17.149   946   946 D HidProfile: Bluetooth service disconnected
07-12 17:45:17.149   946   946 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:17.149   946   946 D PanProfile: Bluetooth service disconnected
07-12 17:45:17.149   946   946 D BluetoothMap: Proxy object disconnected
07-12 17:45:17.149   946   946 D MapProfile: Bluetooth service disconnected
07-12 17:45:17.154  1286  1299 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:17.156   946  1416 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:17.159   946   959 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:17.159   946  3520 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:17.160   791   811 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-12 17:45:17.169   946  1641 D BluetoothMap: onBluetoothStateChange: up=false
,07-12 17:45:17.169   791   811 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:17.170   946   964 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:17.171   791   811 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:17.171   791   811 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:17.171  1954  2037 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-12 17:45:17.171  1954  2037 D BluetoothAdapterProperties: Setting state to 16
,07-12 17:45:17.171  1954  2037 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-12 17:45:17.172  1954  2037 D BluetoothAdapterProperties: onBleDisable
,07-12 17:45:17.172  1954  2037 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:17.172  1954  2038 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:17.174  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:17.176  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:17.176  1954  2041 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:17.181  1954  2136 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-12 17:45:17.181  1954  2136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:17.194  1743  2853 V NativeCrypto: Read error: ssl=0x9a486600: I/O error during system call, Connection timed out
07-12 17:45:17.195  1743  2853 V NativeCrypto: SSL shutdown failed: ssl=0x9a486600: I/O error during system call, Broken pipe
07-12 17:45:17.197  1743  2853 E GCM     : Wifi connection closed with errorCode 20
07-12 17:45:17.197   791  1301 D ConnectivityService: reportNetworkConnectivity(100, false) by 10008
07-12 17:45:17.197   791  2686 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10008
,07-12 17:45:17.206   791  2686 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-12 17:45:17.206   791   898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-12 17:45:17.207   791   898 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 17:45:17.207   791   898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-12 17:45:17.245  2797  2957 V NativeCrypto: Read error: ssl=0xa08bc600: I/O error during system call, Connection timed out
07-12 17:45:17.245  2797  2957 V NativeCrypto: Write error: ssl=0xa08bc600: I/O error during system call, Broken pipe
07-12 17:45:17.245  2797  2957 V NativeCrypto: Write error: ssl=0xa08bc600: I/O error during system call, Broken pipe
07-12 17:45:17.246  2797  2957 V NativeCrypto: SSL shutdown failed: ssl=0xa08bc600: I/O error during system call, Broken pipe
07-12 17:45:17.254  3509  3509 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-12 17:45:17.269  3509  3509 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:17.274   791   896 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:17.275   791   898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-12 17:45:17.275   791   898 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-12 17:45:17.281   791   898 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-12 17:45:17.284  1954  2041 I bt_hci  : shut_down
07-12 17:45:17.284  1954  2046 D bt_hwcfg: hw_epilog_process
07-12 17:45:17.286   791   791 D RttService: SCAN_AVAILABLE : 1
07-12 17:45:17.287   791   910 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-12 17:45:17.290   791   896 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-12 17:45:17.293   791   896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:17.293   791   896 E native  : do suspend true
07-12 17:45:17.294  1954  2046 I bt_vendor: low_power_mode_cb
07-12 17:45:17.314   193   684 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-12 17:45:17.315  1954  2046 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-12 17:45:17.315  1954  2046 I bt_vendor: epilog_cb
07-12 17:45:17.315  1954  2046 I bt_hci  : epilog_finished_callback
07-12 17:45:17.318  2797  2922 V NativeCrypto: Read error: ssl=0xa08bc000: I/O error during system call, Connection timed out
07-12 17:45:17.318  2797  2922 V NativeCrypto: Write error: ssl=0xa08bc000: I/O error during system call, Broken pipe
07-12 17:45:17.318  2797  2922 V NativeCrypto: Write error: ssl=0xa08bc000: I/O error during system call, Broken pipe
07-12 17:45:17.318  2797  2922 V NativeCrypto: SSL shutdown failed: ssl=0xa08bc000: I/O error during system call, Broken pipe
07-12 17:45:17.320  1954  2041 I bt_hci_h4: hal_close
07-12 17:45:17.320  1954  2041 I bt_userial_vendor: device fd = 49 close
07-12 17:45:17.322   791  2691 D DhcpClient: Receive thread stopped
07-12 17:45:17.325  1954  2038 D bt_stack_manager: event_shut_down_stack finished.
07-12 17:45:17.325  1954  2037 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-12 17:45:17.326  1954  2037 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-12 17,:45:17.326  1954  1954 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:17.327  1954  1954 D BtGatt.GattService: Received stop request...Stopping profile...
07-12 17:45:17.327  1954  1954 D BtGatt.GattService: stop()
07-12 17:45:17.327  1954  1954 D BtGatt.AdvertiseManager: advertise clients cleared
07-12 17:45:17.327  1954  1954 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:17.328  1954  1954 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:17.328  1954  1954 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:17.328  1954  1954 V BluetoothAdapterState: isBleTurningOff()=true
07-12 17:45:17.328  1954  2037 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-12 17:45:17.328  1954  2037 D BluetoothAdapterProperties: Setting state to 10
07-12 17:45:17.328  1954  2037 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-12 17:45:17.328   791   811 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 7 receivers.
07-12 17:45:17.329  1954  2037 I BluetoothAdapterState: Entering OffState
07-12 17:45:17.331   193   684 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-12 17:45:17.331   193   684 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:17.332   791   898 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-12 17:45:17.332   791   898 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-12 17:45:17.333  1954  1954 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-12 17:45:17.333  1954  1954 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-12 17:45:17.333  1954  1954 I BluetoothServiceJni: cleanupNative: return from cleanup
07-12 17:45:17.335   791   811 D Tethering: MasterInitialState.processMessage what=3
07-12 17:45:17.336  1954  2038 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-12 17:45:17.336  1397  1397 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-12 17:45:17.338   791   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f9b5ea2:true
07-12 17:45:17.340   791   896 D DhcpClient: doQuit
07-12 17:45:17.340   791   896 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-12 17:45:17.341   791  2688 D DhcpClient: onQuitting
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:17.342  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:17.342  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:17.343  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:17.343  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:17.344  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:17.344  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:17.354  1954  1954 I art     : System.exit called, status: 0
07-12 17:45:17.354  1954  1954 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-12 17:45:17.355  3509  3509 D LocalBluetoothProfileManager: Adding local MAP profile
07-12 17:45:17.357  3509  3509 D BluetoothMap: Create BluetoothMap proxy object
07-12 17:45:17.366  3509  3509 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-12 17:45:17.383   193   684 E Netd    : netlink response contains error (No such file or directory)
07-12 17:45:17.383   791   898 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-12 17:45:17.390   791  1173 I ActivityManager: Process com.android.bluetooth (pid 1954) has died
07-12 17:45:17.390  1389  1389 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-12 17:45:17.392  3509  3509 D DockEventReceiver: finishStartingService: stopping service
07-12 17:45:17.397   791   897 D WifiService: New client listening to asynchronous messages
07-12 17:45:17.402  1389  1389 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-12 17:45:17.414  1389  1389 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-12 17:45:17.415   791  1303 I ActivityManager: Start proc 3555:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
07-12 17:45:17.416   791  1303 I ActivityManager: Killing 2822:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,07-12 17:45:17.461  1389  1389 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-12 17:45:17.471  1389  1389 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-12 17:45:17.522  3555  3555 D AdapterServiceConfig: Adding HeadsetService
07-12 17:45:17.522  3555  3555 D AdapterServiceConfig: Adding A2dpService
,07-12 17:45:17.522  3555  3555 D AdapterServiceConfig: Adding HidService
07-12 17:45:17.522  3555  3555 D AdapterServiceConfig: Adding HealthService
07-12 17:45:17.522  3555  3555 D AdapterServiceConfig: Adding PanService
07-12 17:45:17.522  3555  3555 D AdapterServiceConfig: Adding GattService
07-12 17:45:17.522  3555  3555 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 17:45:17.534   791  1184 I ActivityManager: Start proc 3567:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-12 17:45:17.535   791  1184 I ActivityManager: Killing 2769:com.google.android.apps.photos/u0a65 (adj 15): empty #17
,07-12 17:45:17.916   791   896 D wifi    : In wifi stop Hal
07-12 17:45:17.916   791   896 D wifi    : halHandle = 0x9f33b800, mVM = 0xb4d7c000, mCls = 0x100b7e
,07-12 17:45:17.916   791  1383 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-12 17:45:17.916   791  1383 D WifiHAL : Got a signal to exit!!!
07-12 17:45:17.916   791  1383 I WifiHAL : Exit wifi_event_loop
07-12 17:45:17.917   791   896 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
07-12 17:45:17.917   791   896 E WifiHAL : Event processing terminated
07-12 17:45:17.917  1743  1816 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:17.918   791   896 D wifi    : In wifi cleaned up handler
07-12 17:45:17.918   791   896 I WifiHAL : Internal cleanup completed
07-12 17:45:17.918  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:17.918  2241  2241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:17.918  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:18.027   791  1383 D wifi    : set interface wlan0 flags (DOWN)
07-12 17:45:18.028   791   896 D WifiNative-HAL: HAL event thread stopped successfully
,07-12 17:45:18.089  3567  3567 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-12 17:45:18.089  3567  3567 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:18.089  3567  3567 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:18.089  3567  3567 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:18.089  3567  3567 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.k.d(PG:583)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCal,ler.run(ZygoteInit.java:726)
07-12 17:45:18.089  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:18.090  3567  3567 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:18.090  3567  3567 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:226,5)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:18.090  3567  3567 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:18.090  3567  3567 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:18.094   791   973 I ActivityManager: Killing 2052:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-12 17:45:18.125  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:18.127  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:18.129  3509  3509 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:18.135  3509  3509 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:18.148  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:18.152  1743  3614 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 17:45:18.155  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:18.173  1743  3614 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-12 17:45:18.176  3567  3597 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 17:45:18.184   791   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bd42ae4:true
,07-12 17:45:18.188   791   802 I ActivityManager: Start proc 3616:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-12 17:45:18.230   791   811 D Tethering: InitialState.processMessage what=4
,07-12 17:45:18.232   791   811 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-12 17:45:18.254  2241  3632 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-12 17:45:18.263   791   802 I ActivityManager: Start proc 3633:com.google.android.apps.photos/u0a65 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 17:45:18.302  3633  3633 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 17:45:18.435   791  2610 I ActivityManager: Killing 3121:com.google.android.gms:car/u0a8 (adj 15): empty #17
,07-12 17:45:18.475  1622  1622 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-12 17:45:18.481  1622  2821 I iu.UploadsManager: num queued entries: 0
,07-12 17:45:18.483  1622  2821 I iu.UploadsManager: num updated entries: 0
,07-12 17:45:18.486  1622  2821 I iu.SyncManager: NEXT; no task
,07-12 17:45:18.502   791   801 I ActivityManager: Start proc 3651:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 17:45:18.553  3651  3651 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-12 17:45:18.628  3651  3651 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-12 17:45:18.628  3651  3651 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 17:45:18.628  3651  3651 I GAv4    :   adb logcat -s GAv4
,07-12 17:45:18.644  3651  3651 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:18.650  3651  3651 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:18.658  3651  3669 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:18.796  3651  3651 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-12 17:45:18.828  3651  3651 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4125-4127)
,07-12 17:45:18.828  3651  3651 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:45:18.834  3651  3651 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3911c75}
07-12 17:45:18.835  3651  3651 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:18.835  3651  3651 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:45:18.840  3651  3651 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 17:45:18.841  3651  3651 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 17:45:18.851  3651  3651 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-12 17:45:18.855  3651  3651 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:18.855  3651  3651 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:18.855  3651  3651 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 17:45:18.900  3651  3651 I NSApplication: Starting up...
,07-12 17:45:18.902  3651  3697 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 17:45:18.908   791  1336 I ActivityManager: Killing 3252:com.google.android.gms.unstable/u0a8 (adj 15): empty #17
,07-12 17:45:18.951   791  2608 I ActivityManager: Start proc 3702:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-12 17:45:18.977  3702  3702 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-12 17:45:19.011  3702  3702 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-12 17:45:19.014   791  2234 I ActivityManager: Killing 3350:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-12 17:45:22.103   791  2234 D WifiService: setWifiEnabled: true pid=3458, uid=10000
,07-12 17:45:22.103   791  2234 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:22.105   193   684 D SoftapController: Softap fwReload - Ok
07-12 17:45:22.106   193   684 D CommandListener: Setting iface cfg
07-12 17:45:22.106   193   684 D CommandListener: Trying to bring down wlan0
07-12 17:45:22.107   193   684 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:22.108   791   896 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 17:45:22.886   791   896 D wifi    : set interface wlan0 flags (UP)
,07-12 17:45:22.886   791   896 I WifiHAL : Initializing wifi
07-12 17:45:22.886   791   896 I WifiHAL : Creating socket
07-12 17:45:22.887   791   811 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 17:45:22.887   791   896 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-12 17:45:22.888   791   896 D wifi    : Did set static halHandle = 0x9f33b800
,07-12 17:45:22.888   791   896 D wifi    : halHandle = 0x9f33b800, mVM = 0xb4d7c000, mCls = 0x18ae
,07-12 17:45:22.888   791   896 D wifi    : array field set
07-12 17:45:22.888   791   896 I WifiNative-HAL: interface[0] = p2p0
07-12 17:45:22.888   791   896 I WifiNative-HAL: interface[1] = wlan0
07-12 17:45:22.889   791   896 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-12 17:45:22.891   791   896 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-12 17:45:22.891  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:22.892  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:22.892   791  3749 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1624000512
07-12 17:45:22.892   791  3749 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x18ae, env = 0x959eff40
,07-12 17:45:22.947  3750  3750 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 17:45:22.990  3750  3750 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:23.001  3750  3750 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:23.178   791  1173 I ActivityManager: Killing 3372:com.android.musicfx/u0a15 (adj 15): empty #17
,07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:23.897  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:23.897  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:23.898  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:23.898  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:23.899   791   896 D WifiConfigStore: Loading config and enabling all networks 
,07-12 17:45:23.936   791   896 D WifiConfigStore: loaded 0 passpoint configs
,07-12 17:45:23.936   791   896 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:23.937   791   896 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-12 17:45:23.939   791   896 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 17:45:23.941   791   896 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:23.942   791   896 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-12 17:45:23.942   791   896 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 17:45:23.942   791   896 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-12 17:45:23.954   791   896 D WifiNative-HAL: Setting external_sim to 1
,07-12 17:45:23.954   791   896 D wifi    : setting dfs flag to true, 0x99a2a7f0
,07-12 17:45:23.954   791   896 D WifiStateMachine: Setting OUI to DA-A1-19
,07-12 17:45:23.955   791   896 D wifi    : setting scan oui 0x99a2a7f0
07-12 17:45:23.955   791   896 D WifiHAL : Sending mac address OUI
07-12 17:45:23.956  2241  2241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:23.975   791   896 E native  : do suspend true
,07-12 17:45:23.979   791   896 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-12 17:45:23.979   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-12 17:45:23.979   791   791 D RttService: SCAN_AVAILABLE : 3
07-12 17:45:23.980   791   910 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 17:45:23.980   193   684 D CommandListener: Setting iface cfg
07-12 17:45:23.980   193   684 D CommandListener: Trying to bring up p2p0
07-12 17:45:23.980   791   895 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 17:45:23.988   791   895 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 17:45:23.988   791   895 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-12 17:45:27.105   791  1184 D WifiService: setWifiEnabled: false pid=3458, uid=10000
,07-12 17:45:27.105   791  1184 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:27.107   791   896 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:27.122   791   791 D RttService: SCAN_AVAILABLE : 1
,07-12 17:45:27.122   791   910 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 17:45:27.136   791   896 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:27.137   193   684 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:27.159   791   896 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:27.166  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:27.166  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:27.167  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:27.167  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:27.177  3750  3750 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-12 17:45:28.180  3750  3750 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-12 17:45:28.184  3750  3750 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-12 17:45:28.192  3750  3750 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-12 17:45:28.213  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:28.214  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:28.215  1743  1816 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:28.218   791   896 D wifi    : In wifi stop Hal
,07-12 17:45:28.218   791   896 D wifi    : halHandle = 0x9f33b800, mVM = 0xb4d7c000, mCls = 0x18ae
07-12 17:45:28.218   791  3749 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-12 17:45:28.218   791  3749 D WifiHAL : Got a signal to exit!!!
07-12 17:45:28.218   791  3749 I WifiHAL : Exit wifi_event_loop
07-12 17:45:28.222   791   896 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-12 17:45:28.222   791   896 E WifiHAL : Event processing terminated
07-12 17:45:28.223   791   896 D wifi    : In wifi cleaned up handler
07-12 17:45:28.224   791   896 I WifiHAL : Internal cleanup completed
07-12 17:45:28.225  2241  2241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 17:45:28.357   791  3749 D wifi    : set interface wlan0 flags (DOWN)
,07-12 17:45:28.358   791   896 D WifiNative-HAL: HAL event thread stopped successfully
,07-12 17:45:28.559   791   811 D Tethering: InitialState.processMessage what=4
,07-12 17:45:28.561   791   811 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-12 17:45:32.170   791   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1598b99:true
,07-12 17:45:32.170  3555  3555 D BluetoothAdapterState: make() - Creating AdapterState
07-12 17:45:32.172  3555  3555 I bt_bluedroid: init
07-12 17:45:32.172  3555  3815 I BluetoothAdapterState: Entering OffState
07-12 17:45:32.173  3555  3816 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-12 17:45:32.173  3555  3816 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:32.173  3555  3816 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:32.173  3555  3816 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-12 17:45:32.173  3555  3555 I bt_bluedroid: get_profile_interface socket
07-12 17:45:32.174  3555  3555 I bt_bluedroid: get_profile_interface sdp
,07-12 17:45:32.176  3555  3565 I bt_bluedroid: config_hci_snoop_log
07-12 17:45:32.176   791   811 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
07-12 17:45:32.178  3555  3815 D BluetoothAdapterState: Current state: OFF, message: 0
07-12 17:45:32.178  3555  3815 D BluetoothAdapterProperties: Setting state to 14
07-12 17:45:32.178  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-12 17:45:32.179  3555  3815 D BluetoothBondStateMachine: make
07-12 17:45:32.181  3555  3819 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-12 17:45:32.182  3555  3819 D BluetoothAdapterProperties: Name is: Nexus 5
07-12 17:45:32.185  3555  3555 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-12 17:45:32.186  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
,07-12 17:45:32.186  3555  3815 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:32.187  3555  3555 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:32.187  3555  3555 D BtGatt.GattService: Received start request. Starting profile...
07-12 17:45:32.187  3555  3555 D BtGatt.GattService: start()
07-12 17:45:32.187  3555  3555 I bt_bluedroid: get_profile_interface gatt
07-12 17:45:32.187  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:32.187  3555  3555 D BtGatt.AdvertiseManager: advertise manager created
07-12 17:45:32.188  3555  3820 I BluetoothBondStateMachine: StableState(): Entering Off State
07-12 17:45:32.191  3555  3555 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:32.191  3555  3555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:32.191  3555  3555 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:32.191  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:32.191  3555  3815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 17:45:32.191  3555  3815 I bt_bluedroid: enable
07-12 17:45:32.191  3555  3816 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-12 17:45:32.191  3555  3816 I bt_hci  : start_up
07-12 17:45:32.195  3555  3816 I bt_vendor: alloc value 0xb3a2d631
07-12 17:45:32.195  3555  3816 I bt_vendor: init
,07-12 17:45:32.195  3555  3816 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 17:45:32.195  3555  3816 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 17:45:32.230  3555  3816 D bt_hci  : start_up starting async portion
,07-12 17:45:32.231  3555  3823 I bt_hci  : event_finish_startup
07-12 17:45:32.231  3555  3823 I bt_hci_h4: hal_open
07-12 17:45:32.231  3555  3823 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-12 17:45:32.234  3555  3823 I bt_userial_vendor: device fd = 49 open
,07-12 17:45:32.320  3555  3823 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 17:45:32.347  3555  3823 D bt_hwcfg: Chipset BCM4335C0
,07-12 17:45:32.347  3555  3823 D bt_hwcfg: Target name = [BCM4335C0]
,07-12 17:45:32.347  3555  3823 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-12 17:45:32.713  3555  3823 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 17:45:32.714  3555  3823 D bt_hwcfg: Settlement delay -- 100 ms
07-12 17:45:32.714  3555  3823 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:32.831  3555  3823 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 17:45:32.832  3555  3823 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-12 17:45:32.863  3555  3823 I bt_hwcfg: vendor lib fwcfg completed
,07-12 17:45:32.863  3555  3823 I bt_vendor: firmware callback
,07-12 17:45:32.863  3555  3823 I bt_hci  : firmware_config_callback
,07-12 17:45:32.876  3555  3825 I bt_btu  : btu_task pending for preload complete event
,07-12 17:45:32.876  3555  3825 I bt_btu_task: Bluetooth chip preload is complete
,07-12 17:45:32.876  3555  3825 I bt_btu  : btu_task received preload complete event
,07-12 17:45:32.885  3555  3825 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 17:45:32.885  3555  3825 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-12 17:45:32.885  3555  3825 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-12 17:45:32.885  3555  3825 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-12 17:45:32.885  3555  3825 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-12 17:45:32.885  3555  3825 I         : BTE_InitTraceLevels -- TRC_A2D
,07-12 17:45:32.885  3555  3825 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_BTM
,07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_GAP
,07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_PAN
,07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_SDP
,07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_GATT
,07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 17:45:32.886  3555  3825 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:33.110  3555  3825 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ab9b5
,07-12 17:45:33.110  3555  3825 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ab9b5 
,07-12 17:45:33.192  3555  3819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-12 17:45:33.192  3555  3819 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-12 17:45:33.212  3555  3819 D BluetoothAdapterProperties: Name is: Nexus 5
,07-12 17:45:33.217  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:33.220  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:33.220  3555  3819 D BluetoothAdapterProperties: Scan Mode:20
,07-12 17:45:33.221  3555  3819 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:33.221  3555  3819 D bt_hci  : do_postload posting postload work item
07-12 17:45:33.221  3555  3823 I bt_hci  : event_postload
07-12 17:45:33.221  3555  3823 I bt_vendor: sco_config_cb
07-12 17:45:33.221  3555  3823 I bt_hci  : sco_config_callback postload finished.
,07-12 17:45:33.224  3555  3819 D bt_bte_conf: Device ID record 1 : primary
07-12 17:45:33.224  3555  3819 D bt_bte_conf:   vendorId            = 000f
,07-12 17:45:33.224  3555  3819 D bt_bte_conf:   vendorIdSource      = 0001
07-12 17:45:33.224  3555  3819 D bt_bte_conf:   product             = 1200
07-12 17:45:33.224  3555  3819 D bt_bte_conf:   version             = 1436
07-12 17:45:33.224  3555  3819 D bt_bte_conf:   clientExecutableURL = 
07-12 17:45:33.224  3555  3819 D bt_bte_conf:   serviceDescription  = 
07-12 17:45:33.224  3555  3819 D bt_bte_conf:   documentationURL    = 
,07-12 17:45:33.224  3555  3819 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 17:45:33.225  3555  3816 D bt_stack_manager: event_start_up_stack finished
07-12 17:45:33.226  3555  3815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 17:45:33.226  3555  3815 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:33.226  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 17:45:33.232  3555  3815 I BluetoothAdapterState: Entering BleOnState
,07-12 17:45:33.233  3555  3815 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 17:45:33.233  3555  3815 D BluetoothAdapterProperties: Setting state to 11
07-12 17:45:33.233  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 17:45:33.242  3555  3823 I bt_vendor: low_power_mode_cb
07-12 17:45:33.248  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:33.249  3555  3555 D HeadsetService: Received start request. Starting profile...
07-12 17:45:33.250  3555  3555 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 17:45:33.250  3555  3555 D HeadsetStateMachine: make
07-12 17:45:33.260  3555  3815 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:33.261  3555  3555 D HeadsetStateMachine: max_hf_connections = 1
07-12 17:45:33.261  3555  3555 I bt_bluedroid: get_profile_interface handsfree
07-12 17:45:33.261  3555  3819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 17:45:33.261  3555  3819 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-12 17:45:33.262  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
,07-12 17:45:33.263  3555  3555 D A2dpService: Received start request. Starting profile...
,07-12 17:45:33.263  3555  3555 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 17:45:33.263  3555  3555 I bt_bluedroid: get_profile_interface avrcp
07-12 17:45:33.267  3555  3555 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-12 17:45:33.267  3555  3555 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-12 17:45:33.267  3555  3555 D A2dpStateMachine: make
07-12 17:45:33.268  3555  3555 I bt_bluedroid: get_profile_interface a2dp
07-12 17:45:33.269  3555  3819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-12 17:45:33.270  3555  3846 D A2dpStateMachine: Enter Disconnected: -2
07-12 17:45:33.270  3555  3555 I BluetoothHidServiceJni: classInitNative: succeeds
07-12 17:45:33.271  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
,07-12 17:45:33.272  3555  3555 D HidService: Received start request. Starting profile...
07-12 17:45:33.272  3555  3555 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:33.272  3555  3819 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb398d099
07-12 17:45:33.272  3555  3819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 17:45:33.272  3555  3555 D HidService: setHidService(): set to: null
,07-12 17:45:33.273  3555  3555 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 17:45:33.273  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:33.274  3555  3555 D HealthService: Received start request. Starting profile...
07-12 17:45:33.275  3509  3509 D BluetoothInputDevice: Proxy object connected
07-12 17:45:33.275  3509  3509 D HidProfile: Bluetooth service connected
,07-12 17:45:33.276  3555  3555 I bt_bluedroid: get_profile_interface health
07-12 17:45:33.276  3555  3555 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 17:45:33.277  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
,07-12 17:45:33.278  3509  3509 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:33.278  3555  3555 D PanService: Received start request. Starting profile...
07-12 17:45:33.278  3555  3555 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 17:45:33.278  3555  3555 I bt_bluedroid: get_profile_interface pan
07-12 17:45:33.278  3555  3819 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 17:45:33.278  3509  3509 D PanProfile: Bluetooth service connected
07-12 17:45:33.279  3555  3555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:33.280  3555  3555 D BluetoothMapService: Received start request. Starting profile...
,07-12 17:45:33.280  3555  3555 D BluetoothMapService: start()
07-12 17:45:33.282  3555  3555 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-12 17:45:33.282  3555  3555 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-12 17:45:33.282  3555  3555 D BluetoothMapAppObserver: createReceiver()
07-12 17:45:33.283  3555  3555 D BluetoothMapAppObserver: initObservers()
,07-12 17:45:33.283  3555  3555 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-12 17:45:33.287  3555  3555 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:33.287  3555  3555 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:33.287  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:33.287  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:33.288  3555  3842 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:33.288  3555  3555 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:33.289  3555  3555 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:33.289  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:33.289  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:33.289  3555  3815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-12 17:45:33.289  3555  3815 D BluetoothAdapterProperties: ScanMode =  20
07-12 17:45:33.289  3555  3815 D BluetoothAdapterProperties: State =  11
,07-12 17:45:33.289  3555  3815 D BluetoothAdapterProperties: Setting state to 12
07-12 17:45:33.289  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 17:45:33.289   946  1416 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:33.289  3555  3819 D BluetoothAdapterProperties: Scan Mode:21
07-12 17:45:33.289  3555  3819 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 17:45:33.290  3555  3815 I BluetoothAdapterState: Entering OnState
07-12 17:45:33.291  3509  3522 D BluetoothPbap: onBluetoothStateChange: up=true
,07-12 17:45:33.293  3509  3519 D BluetoothMap: onBluetoothStateChange: up=true
,07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:33.294  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:33.294  1286  1302 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:33.295  3509  3522 D BluetoothPan: onBluetoothStateChange on: true
,07-12 17:45:33.295   946   946 D BluetoothA2dp: Proxy object connected
07-12 17:45:33.296  3509  3519 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:33.296   946   959 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:33.298  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:33.298   946  1641 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:33.299   946  3520 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:33.301  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:33.301   946   946 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 17:45:33.301   946   946 D PanProfile: Bluetooth service connected
07-12 17:45:33.301   791   811 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:33.302   791   791 D BluetoothA2dp: Proxy object connected
,07-12 17:45:33.302   946   964 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:33.303  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:33.305   791   811 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:33.305   946   946 D BluetoothMap: Proxy object connected
,07-12 17:45:33.305   946   946 D MapProfile: Bluetooth service connected
,07-12 17:45:33.305   946   946 D BluetoothMap: getConnectedDevices()
,07-12 17:45:33.305   946  1641 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:33.307   946   946 D BluetoothInputDevice: Proxy object connected
,07-12 17:45:33.307   946   946 D HidProfile: Bluetooth service connected
07-12 17:45:33.307  3555  3555 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 17:45:33.308  3555  3555 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-12 17:45:33.308   791   811 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:33.308   791   811 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:33.310   791   791 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 17:45:33.311  3555  3555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:33.313  3555  3555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:33.313  3555  3555 D ObexServerSockets: Succeed to create listening sockets 
07-12 17:45:33.313  3555  3555 D ObexServerSockets0: startAccept()
07-12 17:45:33.313  3555  3555 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:33.315  3555  3555 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-12 17:45:33.315  3555  3555 D BluetoothSdpJni: SDP Create record success - handle: 0
07-12 17:45:33.315  3555  3555 D BluetoothMapService: onReceive
07-12 17:45:33.315  3555  3555 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:33.315  3555  3555 D BluetoothMapService: STATE_ON
,07-12 17:45:33.316  3555  3859 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:33.316  3555  3860 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:33.319  3509  3509 D BluetoothMap: Proxy object connected
07-12 17:45:33.320  3509  3509 D MapProfile: Bluetooth service connected
07-12 17:45:33.320  3509  3509 D BluetoothMap: getConnectedDevices()
,07-12 17:45:33.329  3509  3509 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 17:45:33.333  3509  3509 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 17:45:33.336  3555  3555 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 17:45:33.336  3555  3555 D ObexServerSockets0: prepareForNewConnect()
,07-12 17:45:33.337  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:33.338  3509  3509 D BluetoothA2dp: Proxy object connected
,07-12 17:45:33.342  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:33.344  3509  3509 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:33.351  3509  3509 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:33.355   946   946 D BluetoothPbap: Proxy object connected
,07-12 17:45:33.356   946   946 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:33.357  3555  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:33.359  3509  3509 D BluetoothPbap: Proxy object connected
,07-12 17:45:33.360  3509  3509 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:33.384  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:33.388  1743  3872 D EasyUnlockInitService: Handling intent for initializer IntentService.
07-12 17:45:33.389  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:33.400   946   959 D BluetoothHeadset: Proxy object connected
,07-12 17:45:33.400   946   946 D HeadsetProfile: Bluetooth service connected
07-12 17:45:33.401   791   791 D BluetoothHeadset: Proxy object connected
07-12 17:45:33.401  1286  1299 D BluetoothHeadset: Proxy object connected
,07-12 17:45:33.401  3555  3877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:33.401   791   791 D BluetoothHeadset: Proxy object connected
,07-12 17:45:33.401   791   791 D BluetoothHeadset: Proxy object connected
,07-12 17:45:33.402  3555  3877 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:33.406   791   811 D BluetoothHeadset: Proxy object connected
,07-12 17:45:33.408   791   811 D BluetoothHeadset: Proxy object connected
,07-12 17:45:33.408   791   811 D BluetoothHeadset: Proxy object connected
,07-12 17:45:33.413  1743  3872 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 17:45:33.436  3509  3522 D BluetoothHeadset: Proxy object connected
07-12 17:45:33.436  3509  3509 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:37.128  3555  3815 D BluetoothAdapterState: Current state: ON, message: 23
,07-12 17:45:37.128  3555  3815 D BluetoothAdapterProperties: Setting state to 13
,07-12 17:45:37.128  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-12 17:45:37.129  3555  3815 D BluetoothAdapterProperties: onBluetoothDisable()
07-12 17:45:37.161  3555  3815 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:37.176  3555  3555 D BluetoothMapService: onReceive
07-12 17:45:37.176  3555  3555 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:37.176  3555  3555 D BluetoothMapService: STATE_TURNING_OFF
,07-12 17:45:37.176  3555  3555 D BluetoothMapService: MAP Service closeService in
07-12 17:45:37.176  3555  3555 D BluetoothMapMasInstance0: MAP Service shutdown
07-12 17:45:37.176  3555  3555 D ObexServerSockets0: shutdown(block = true)
07-12 17:45:37.177  3555  3555 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:37.177  3555  3555 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-12 17:45:37.177  3555  3859 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,07-12 17:45:37.177  3555  3833 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-12 17:45:37.177  3555  3860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-12 17:45:37.178  3555  3555 I BtOppRfcommListener: stopping Accept Thread
07-12 17:45:37.178  3555  3877 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-12 17:45:37.178  3555  3877 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:37.179  3555  3819 D BluetoothAdapterProperties: Scan Mode:20
,07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:37.179  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:37.179  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:37.181  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:37.181  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:37.181  3555  3815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-12 17:45:37.187  3555  3555 D HeadsetService: Received stop request...Stopping profile...
07-12 17:45:37.188  3555  3555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:37.188  3555  3555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:37.188  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.188  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.189   946   964 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:37.189   946   946 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:37.189   791   791 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:37.189  3509  3522 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:37.190  1286  1302 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:37.190   791   791 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:37.190   791   791 D BluetoothHeadset: Proxy object disconnected
,07-12 17:45:37.190  3555  3555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-12 17:45:37.190  3555  3555 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-12 17:45:37.190  3555  3825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:37.190  3555  3825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:37.191  3555  3819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-12 17:45:37.191  3555  3819 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-12 17:45:37.228  3555  3555 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:37.228  3555  3846 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:37.230   791   791 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:37.231  3509  3509 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:37.235   946   946 D BluetoothA2dp: Proxy object disconnected
,07-12 17:45:37.235  3555  3555 D HidService: Received stop request...Stopping profile...
,07-12 17:45:37.235  3555  3555 D HidService: Stopping Bluetooth HidService
07-12 17:45:37.237  3555  3555 D HealthService: Received stop request...Stopping profile...
07-12 17:45:37.237  3509  3509 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:37.237  3509  3509 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:37.238  3555  3555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:37.238  3555  3555 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:37.238  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.238  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.239  3555  3555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:37.239  3555  3555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:37.239  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.239  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.239  3555  3819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-12 17:45:37.239  3555  3825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:37.239  3555  3825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:37.239  3555  3825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:37.239  3555  3825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:37.239  3555  3825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:37.239  3555  3825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-12 17:45:37.240  3555  3555 D PanService: Received stop request...Stopping profile...
07-12 17:45:37.241  3555  3555 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-12 17:45:37.241  3555  3555 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-12 17:45:37.241  3555  3819 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:37.242  3555  3555 D BluetoothMapService: Received stop request...Stopping profile...
,07-12 17:45:37.242  3555  3555 D BluetoothMapService: stop()
,07-12 17:45:37.243  3555  3555 D BluetoothMapAppObserver: deinitObservers()
,07-12 17:45:37.243  3555  3555 D BluetoothMapAppObserver: removeReceiver()
07-12 17:45:37.244  3509  3509 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:37.245  3509  3509 D BluetoothInputDevice: Proxy object disconnected
,07-12 17:45:37.245  3509  3509 D HidProfile: Bluetooth service disconnected
07-12 17:45:37.245  3555  3555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:37.245  3555  3555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:37.245  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:37.245  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.246  3509  3509 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:37.246  3509  3509 D PanProfile: Bluetooth service disconnected
07-12 17:45:37.246  3555  3555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-12 17:45:37.246  3555  3819 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-12 17:45:37.246  3555  3555 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-12 17:45:37.247  3555  3555 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:37.247  3555  3555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:37.247  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.247  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.247  3555  3555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-12 17:45:37.247  3555  3555 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-12 17:45:37.248  3509  3509 D BluetoothMap: Proxy object disconnected
,07-12 17:45:37.248  3509  3509 D MapProfile: Bluetooth service disconnected
07-12 17:45:37.248  3555  3555 D BluetoothMapService: MAP Service closeService in
07-12 17:45:37.248  3555  3555 V BluetoothAdapterState: isTurningOff()=true
,07-12 17:45:37.248  3555  3555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:37.248  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.248  3555  3555 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.248  3555  3815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-12 17:45:37.248  3555  3815 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:37.248  3555  3555 D BluetoothMapService: cleanup()
07-12 17:45:37.248  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:37.248  3555  3555 D BluetoothMapService: MAP Service closeService in
,07-12 17:45:37.248  3555  3815 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:37.248  3509  3522 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:37.249   946   964 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:37.249  3509  3519 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:37.251  3509  3522 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:37.251  1286  1299 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:37.251  3509  3853 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:37.252  3509  3519 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:37.252  3509  3522 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:37.252   946   959 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:37.253   946  1641 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:37.253   946  3520 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:37.253   946   946 D BluetoothInputDevice: Proxy object disconnected
07-12 17:45:37.253   946   946 D HidProfile: Bluetooth service disconnected
,07-12 17:45:37.253   791   811 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:37.253   946   946 D BluetoothMap: Proxy object disconnected
07-12 17:45:37.253   946   946 D MapProfile: Bluetooth service disconnected
07-12 17:45:37.253   946  1416 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:37.254   791   811 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:37.254   946  1641 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-12 17:45:37.254   791   811 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:37.254   791   811 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:37.254  3555  3815 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-12 17:45:37.254  3555  3815 D BluetoothAdapterProperties: Setting state to 16
07-12 17:45:37.254  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-12 17:45:37.254  3555  3815 D BluetoothAdapterProperties: onBleDisable
,07-12 17:45:37.255  3555  3815 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:37.255  3555  3816 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:37.255  3555  3825 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-12 17:45:37.255  3555  3825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:37.256  3555  3819 D BluetoothAdapterProperties: Scan Mode:20
,07-12 17:45:37.257  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:37.259  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:37.318  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:37.324  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:37.325  3509  3509 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:37.332  3509  3509 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:37.345  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:37.351  1743  3917 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 17:45:37.352  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:37.355  3555  3819 I bt_hci  : shut_down
,07-12 17:45:37.355  3555  3823 D bt_hwcfg: hw_epilog_process
,07-12 17:45:37.361  1743  3917 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-12 17:45:37.361  3555  3823 I bt_vendor: low_power_mode_cb
,07-12 17:45:37.380  3555  3823 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-12 17:45:37.380  3555  3823 I bt_vendor: epilog_cb
07-12 17:45:37.380  3555  3823 I bt_hci  : epilog_finished_callback
,07-12 17:45:37.382  3555  3819 I bt_hci_h4: hal_close
,07-12 17:45:37.383  3555  3819 I bt_userial_vendor: device fd = 49 close
,07-12 17:45:37.387  3555  3816 D bt_stack_manager: event_shut_down_stack finished.
,07-12 17:45:37.387  3555  3815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-12 17:45:37.389  3555  3815 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-12 17:45:37.389  3555  3555 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:37.389  3555  3555 D BtGatt.GattService: Received stop request...Stopping profile...
07-12 17:45:37.389  3555  3555 D BtGatt.GattService: stop()
,07-12 17:45:37.389  3555  3555 D BtGatt.AdvertiseManager: advertise clients cleared
07-12 17:45:37.390  3555  3555 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:37.390  3555  3555 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:37.390  3555  3555 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:37.390  3555  3555 V BluetoothAdapterState: isBleTurningOff()=true
07-12 17:45:37.390  3555  3815 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-12 17:45:37.390  3555  3815 D BluetoothAdapterProperties: Setting state to 10
07-12 17:45:37.390  3555  3815 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-12 17:45:37.391  3555  3815 I BluetoothAdapterState: Entering OffState
,07-12 17:45:37.391   791   811 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-12 17:45:37.396  3555  3555 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-12 17:45:37.396  3555  3555 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-12 17:45:37.396  3555  3555 I BluetoothServiceJni: cleanupNative: return from cleanup
07-12 17:45:37.396  3555  3816 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-12 17:45:37.397  3555  3555 I art     : System.exit called, status: 0
,07-12 17:45:37.397  3555  3555 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-12 17:45:37.420   791   801 I ActivityManager: Process com.android.bluetooth (pid 3555) has died
,07-12 17:45:42.127  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:42.127  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:42.135  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:42.135  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@97b5e7a added. We now have 6 listener(s)
07-12 17:45:42.135  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:42.139  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:42.139  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cac962b added. We now have 7 listener(s)
,07-12 17:45:42.139  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:42.140  3458  3505 I System.out: IsBluetoothEnabled
07-12 17:45:42.150  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:42.190   791   811 I ActivityManager: Start proc 3932:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 17:45:42.236  3932  3932 D AdapterServiceConfig: Adding HeadsetService
,07-12 17:45:42.236  3932  3932 D AdapterServiceConfig: Adding A2dpService
07-12 17:45:42.236  3932  3932 D AdapterServiceConfig: Adding HidService
07-12 17:45:42.236  3932  3932 D AdapterServiceConfig: Adding HealthService
07-12 17:45:42.236  3932  3932 D AdapterServiceConfig: Adding PanService
07-12 17:45:42.236  3932  3932 D AdapterServiceConfig: Adding GattService
07-12 17:45:42.236  3932  3932 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 17:45:42.245   791   811 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8071cb8:true
,07-12 17:45:42.245  3932  3932 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 17:45:42.248  3932  3932 I bt_bluedroid: init
,07-12 17:45:42.248  3932  3944 I BluetoothAdapterState: Entering OffState
,07-12 17:45:42.249  3932  3945 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 17:45:42.250  3932  3945 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:42.250  3932  3945 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:42.250  3932  3945 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 17:45:42.250  3932  3932 I bt_bluedroid: get_profile_interface socket
,07-12 17:45:42.251  3932  3932 I bt_bluedroid: get_profile_interface sdp
07-12 17:45:42.253  3932  3943 I bt_bluedroid: config_hci_snoop_log
07-12 17:45:42.254   791   811 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
07-12 17:45:42.256  3932  3944 D BluetoothAdapterState: Current state: OFF, message: 0
07-12 17:45:42.256  3932  3944 D BluetoothAdapterProperties: Setting state to 14
07-12 17:45:42.256  3932  3944 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-12 17:45:42.257  3932  3944 D BluetoothBondStateMachine: make
,07-12 17:45:42.258  3932  3948 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-12 17:45:42.259  3932  3948 D BluetoothAdapterProperties: Name is: Nexus 5
,07-12 17:45:42.263  3932  3932 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-12 17:45:42.264  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:42.265  3932  3944 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:42.265  3932  3932 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:42.265  3932  3932 D BtGatt.GattService: Received start request. Starting profile...
07-12 17:45:42.265  3932  3932 D BtGatt.GattService: start()
07-12 17:45:42.265  3932  3932 I bt_bluedroid: get_profile_interface gatt
07-12 17:45:42.266  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
,07-12 17:45:42.266  3932  3932 D BtGatt.AdvertiseManager: advertise manager created
07-12 17:45:42.266  3932  3949 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 17:45:42.270  3932  3932 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:42.270  3932  3932 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:42.270  3932  3932 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:42.270  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:42.271  3932  3944 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 17:45:42.271  3932  3944 I bt_bluedroid: enable
07-12 17:45:42.271  3932  3945 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 17:45:42.271  3932  3945 I bt_hci  : start_up
07-12 17:45:42.276  3932  3945 I bt_vendor: alloc value 0xb3a39631
07-12 17:45:42.276  3932  3945 I bt_vendor: init
07-12 17:45:42.276  3932  3945 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 17:45:42.276  3932  3945 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 17:45:42.310  3932  3945 D bt_hci  : start_up starting async portion
,07-12 17:45:42.311  3932  3952 I bt_hci  : event_finish_startup
07-12 17:45:42.311  3932  3952 I bt_hci_h4: hal_open
,07-12 17:45:42.311  3932  3952 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-12 17:45:42.314  3932  3952 I bt_userial_vendor: device fd = 49 open
,07-12 17:45:42.400  3932  3952 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 17:45:42.427  3932  3952 D bt_hwcfg: Chipset BCM4335C0
,07-12 17:45:42.427  3932  3952 D bt_hwcfg: Target name = [BCM4335C0]
07-12 17:45:42.427  3932  3952 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-12 17:45:42.996  3932  3952 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 17:45:42.996  3932  3952 D bt_hwcfg: Settlement delay -- 100 ms
,07-12 17:45:42.996  3932  3952 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:43.114  3932  3952 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 17:45:43.115  3932  3952 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-12 17:45:43.142  3932  3952 I bt_hwcfg: vendor lib fwcfg completed
,07-12 17:45:43.142  3932  3952 I bt_vendor: firmware callback
,07-12 17:45:43.142  3932  3952 I bt_hci  : firmware_config_callback
,07-12 17:45:43.155  3932  3954 I bt_btu  : btu_task pending for preload complete event
,07-12 17:45:43.155  3932  3954 I bt_btu_task: Bluetooth chip preload is complete
,07-12 17:45:43.155  3932  3954 I bt_btu  : btu_task received preload complete event
,07-12 17:45:43.163  3932  3954 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_A2D
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_BTM
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_GAP
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_PAN
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_SDP
,07-12 17:45:43.164  3932  3954 I         : BTE_InitTraceLevels -- TRC_GATT
,07-12 17:45:43.165  3932  3954 I         : BTE_InitTraceLevels -- TRC_SMP
,07-12 17:45:43.165  3932  3954 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-12 17:45:43.165  3932  3954 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:43.384  3932  3954 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b79b5
,07-12 17:45:43.384  3932  3954 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b79b5 
,07-12 17:45:43.454  3932  3948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-12 17:45:43.454  3932  3948 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-12 17:45:43.490  3932  3948 D BluetoothAdapterProperties: Name is: Nexus 5
07-12 17:45:43.492  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:43.492  3932  3948 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:43.492  3932  3948 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:43.492  3932  3948 D bt_hci  : do_postload posting postload work item
07-12 17:45:43.492  3932  3952 I bt_hci  : event_postload
07-12 17:45:43.492  3932  3952 I bt_vendor: sco_config_cb
07-12 17:45:43.492  3932  3952 I bt_hci  : sco_config_callback postload finished.
07-12 17:45:43.510  3932  3952 I bt_vendor: low_power_mode_cb
,07-12 17:45:43.511  3932  3948 D bt_bte_conf: Device ID record 1 : primary
07-12 17:45:43.511  3932  3948 D bt_bte_conf:   vendorId            = 000f
07-12 17:45:43.511  3932  3948 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 17:45:43.511  3932  3948 D bt_bte_conf:   product             = 1200
07-12 17:45:43.511  3932  3948 D bt_bte_conf:   version             = 1436
07-12 17:45:43.511  3932  3948 D bt_bte_conf:   clientExecutableURL = 
07-12 17:45:43.511  3932  3948 D bt_bte_conf:   serviceDescription  = 
07-12 17:45:43.511  3932  3948 D bt_bte_conf:   documentationURL    = 
07-12 17:45:43.530  3932  3948 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 17:45:43.530  3932  3945 D bt_stack_manager: event_start_up_stack finished
07-12 17:45:43.530  3932  3944 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 17:45:43.531  3932  3944 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:43.531  3932  3944 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 17:45:43.532  3932  3944 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:43.532  3932  3944 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-12 17:45:43.532  3932  3944 D BluetoothAdapterProperties: Setting state to 11
07-12 17:45:43.532  3932  3944 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 17:45:43.535  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:43.549  3932  3932 D HeadsetService: Received start request. Starting profile...
07-12 17:45:43.551  3932  3932 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-12 17:45:43.551  3932  3932 D HeadsetStateMachine: make
,07-12 17:45:43.566  3932  3932 D HeadsetStateMachine: max_hf_connections = 1
,07-12 17:45:43.566  3932  3932 I bt_bluedroid: get_profile_interface handsfree
,07-12 17:45:43.568  3932  3948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-12 17:45:43.568  3932  3948 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
,07-12 17:45:43.573  3932  3944 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:43.574  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
,07-12 17:45:43.575  3932  3932 D A2dpService: Received start request. Starting profile...
07-12 17:45:43.575  3932  3932 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 17:45:43.575  3932  3932 I bt_bluedroid: get_profile_interface avrcp
,07-12 17:45:43.581  3932  3932 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 17:45:43.582  3932  3932 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 17:45:43.582  3932  3932 D A2dpStateMachine: make
07-12 17:45:43.584  3932  3932 I bt_bluedroid: get_profile_interface a2dp
,07-12 17:45:43.585  3932  3948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-12 17:45:43.586  3932  3977 D A2dpStateMachine: Enter Disconnected: -2
,07-12 17:45:43.586  3932  3932 I BluetoothHidServiceJni: classInitNative: succeeds
07-12 17:45:43.587  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:43.587  3932  3932 D HidService: Received start request. Starting profile...
07-12 17:45:43.587  3932  3932 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:43.587  3932  3948 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3999099
,07-12 17:45:43.587  3932  3948 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 17:45:43.587  3932  3932 D HidService: setHidService(): set to: null
07-12 17:45:43.588  3932  3932 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 17:45:43.589  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:43.589  3932  3932 D HealthService: Received start request. Starting profile...
,07-12 17:45:43.591  3932  3932 I bt_bluedroid: get_profile_interface health
,07-12 17:45:43.592  3932  3932 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 17:45:43.593  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
,07-12 17:45:43.593  3932  3932 D PanService: Received start request. Starting profile...
,07-12 17:45:43.593  3932  3932 D BluetoothPanServiceJni: initializeNative(L110): pan
,07-12 17:45:43.593  3932  3932 I bt_bluedroid: get_profile_interface pan
07-12 17:45:43.594  3932  3948 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 17:45:43.596  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7e4ec53
07-12 17:45:43.597  3932  3932 D BluetoothMapService: Received start request. Starting profile...
07-12 17:45:43.597  3932  3932 D BluetoothMapService: start()
07-12 17:45:43.599  3932  3932 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-12 17:45:43.600  3932  3932 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-12 17:45:43.600  3932  3932 D BluetoothMapAppObserver: createReceiver()
07-12 17:45:43.601  3932  3932 D BluetoothMapAppObserver: initObservers()
07-12 17:45:43.601  3932  3932 D BluetoothMapAppObserver: getEnabledAccountItems()
07-12 17:45:43.608  3932  3932 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:43.608  3932  3932 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:43.608  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:43.608  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:43.608  3932  3973 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-12 17:45:43.609  3932  3932 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:43.609  3932  3932 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:43.610  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:43.611  3932  3932 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:43.611  3932  3932 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:43.611  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:43.611  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:43.611  3932  3944 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 17:45:43.611  3932  3944 D BluetoothAdapterProperties: ScanMode =  20
07-12 17:45:43.611  3932  3944 D BluetoothAdapterProperties: State =  11
,07-12 17:45:43.612  3932  3944 D BluetoothAdapterProperties: Setting state to 12
,07-12 17:45:43.612  3932  3944 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 17:45:43.612  3932  3944 I BluetoothAdapterState: Entering OnState
,07-12 17:45:43.613  3509  3522 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:43.614  3932  3948 D BluetoothAdapterProperties: Scan Mode:21
07-12 17:45:43.614  3932  3948 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 17:45:43.617   946  1416 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:43.619  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:43.622  3509  3853 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:43.623  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:43.623   946   946 D BluetoothA2dp: Proxy object connected
07-12 17:45:43.625  3509  3519 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:43.626  1286  1500 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:43.627  3509  3509 D BluetoothMap: Proxy object connected
07-12 17:45:43.627  3509  3509 D MapProfile: Bluetooth service connected
07-12 17:45:43.627  3509  3509 D BluetoothMap: getConnectedDevices()
07-12 17:45:43.627  3509  3853 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:43.629  3932  3932 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-12 17:45:43.629  3509  3519 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:43.629  3932  3932 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-12 17:45:43.630  3932  3932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:43.631  3509  3522 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:43.632  3932  3932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:43.633   946   959 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:43.634  3932  3932 D ObexServerSockets: Succeed to create listening sockets 
07-12 17:45:43.634  3932  3932 D ObexServerSockets0: startAccept()
,07-12 17:45:43.634  3932  3932 D ObexServerSockets0: prepareForNewConnect()
07-12 17:45:43.636  3932  3932 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-12 17:45:43.637  3932  3932 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-12 17:45:43.637   946  1641 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:43.637  3509  3509 D BluetoothA2dp: Proxy object connected
07-12 17:45:43.639   946   964 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:43.640   946   946 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:43.640   946   946 D PanProfile: Bluetooth service connected
07-12 17:45:43.640   791   811 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:43.640  3932  3988 D ObexServerSockets0: Accepting socket connection...
07-12 17:45:43.640  3932  3989 D ObexServerSockets0: Accepting socket connection...
,07-12 17:45:43.641   946  3520 D BluetoothMap: onBluetoothStateChange: up=true
,07-12 17:45:43.642   791   791 D BluetoothA2dp: Proxy object connected
,07-12 17:45:43.643   946   946 D BluetoothMap: Proxy object connected
,07-12 17:45:43.643   946   946 D MapProfile: Bluetooth service connected
07-12 17:45:43.643   946   946 D BluetoothMap: getConnectedDevices()
07-12 17:45:43.643   791   811 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:43.643  3509  3509 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:43.643  3509  3509 D PanProfile: Bluetooth service connected
07-12 17:45:43.643  3509  3509 D BluetoothInputDevice: Proxy object connected
07-12 17:45:43.643  3509  3509 D HidProfile: Bluetooth service connected
07-12 17:45:43.644   946  1641 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:43.645  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:43.648   946   946 D BluetoothInputDevice: Proxy object connected
07-12 17:45:43.648   946   946 D HidProfile: Bluetooth service connected
07-12 17:45:43.649   791   811 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:43.649   791   811 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:43.649  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-12 17:45:43.650   791   791 I Telecom : BluetoothPhoneService: queryPhoneState
,07-12 17:45:43.654  3932  3932 D BluetoothMapService: onReceive
,07-12 17:45:43.654  3932  3932 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 17:45:43.654  3932  3932 D BluetoothMapService: STATE_ON
,07-12 17:45:43.659  3509  3509 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:43.664  3509  3509 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:43.670  3509  3509 D BluetoothPbap: Proxy object connected
,07-12 17:45:43.670  3509  3509 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:43.672  3932  3997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:43.682   946   946 D BluetoothPbap: Proxy object connected
,07-12 17:45:43.682   946   946 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:43.686  3932  3932 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 17:45:43.686  3932  3932 D ObexServerSockets0: prepareForNewConnect()
,07-12 17:45:43.691  3932  4003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:43.692  3932  4003 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:43.715   946  1416 D BluetoothHeadset: Proxy object connected
07-12 17:45:43.715   946   946 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:43.715   791   791 D BluetoothHeadset: Proxy object connected
07-12 17:45:43.715  3509  3522 D BluetoothHeadset: Proxy object connected
07-12 17:45:43.716  3509  3509 D HeadsetProfile: Bluetooth service connected
07-12 17:45:43.716  1286  1302 D BluetoothHeadset: Proxy object connected
,07-12 17:45:43.716   791   791 D BluetoothHeadset: Proxy object connected
07-12 17:45:43.716   791   791 D BluetoothHeadset: Proxy object connected
,07-12 17:45:43.726  1286  1299 D BluetoothHeadset: Proxy object connected
,07-12 17:45:43.733  1743  1743 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:43.738   946  1641 D BluetoothHeadset: Proxy object connected
,07-12 17:45:43.738   946   946 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:43.741  1743  4006 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 17:45:43.742  1743  1743 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 17:45:43.744   791   811 D BluetoothHeadset: Proxy object connected
,07-12 17:45:43.749   791   811 D BluetoothHeadset: Proxy object connected
,07-12 17:45:43.749   791   811 D BluetoothHeadset: Proxy object connected
,07-12 17:45:43.755  1743  4006 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:44.199  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:44.205  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:44.209  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:44.209  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7f3a88 added. We now have 8 listener(s)
,07-12 17:45:44.209  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:44.215   791  1303 D WifiService: setWifiEnabled: false pid=3458, uid=10000
07-12 17:45:44.215   791  1303 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:44.225  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:44.226   791  2609 D WifiService: setWifiEnabled: true pid=3458, uid=10000
07-12 17:45:44.226   791  2609 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 17:45:44.236   193   684 D SoftapController: Softap fwReload - Ok
07-12 17:45:44.237   193   684 D CommandListener: Setting iface cfg
07-12 17:45:44.237   193   684 D CommandListener: Trying to bring down wlan0
07-12 17:45:44.237   193   684 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:44.238   791   896 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 17:45:44.997   791   896 D wifi    : set interface wlan0 flags (UP)
,07-12 17:45:44.997   791   896 I WifiHAL : Initializing wifi
07-12 17:45:44.997   791   896 I WifiHAL : Creating socket
,07-12 17:45:45.005   791   811 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-12 17:45:45.008   791   896 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-12 17:45:45.008   791   896 D wifi    : Did set static halHandle = 0x9f33b800
07-12 17:45:45.008   791   896 D wifi    : halHandle = 0x9f33b800, mVM = 0xb4d7c000, mCls = 0x100eaa
07-12 17:45:45.008   791   896 D wifi    : array field set
07-12 17:45:45.009   791   896 I WifiNative-HAL: interface[0] = p2p0
07-12 17:45:45.009   791   896 I WifiNative-HAL: interface[1] = wlan0
07-12 17:45:45.019   791   896 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-12 17:45:45.029  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:45.035   791  4046 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1624000512
,07-12 17:45:45.036   791  4046 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x100eaa, env = 0x959ee4a0
,07-12 17:45:45.071  4047  4047 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 17:45:45.111  4047  4047 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:45.121  4047  4047 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:45.137   791   896 D WifiConfigStore: Loading config and enabling all networks 
,07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:45.139  3458  3458 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:45.141  3458  3458 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:45.148   791   896 D WifiConfigStore: loaded 0 passpoint configs
,07-12 17:45:45.148   791   896 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-12 17:45:45.148   791   896 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-12 17:45:45.149   791   896 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 17:45:45.150   791   896 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:45.150   791   896 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-12 17:45:45.150   791   896 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-12 17:45:45.150   791   896 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-12 17:45:45.153   791   896 D WifiNative-HAL: Setting external_sim to 1
,07-12 17:45:45.153  2241  2241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:45.153   791   896 D wifi    : setting dfs flag to true, 0x97f31328
07-12 17:45:45.153   791   896 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 17:45:45.153   791   896 D wifi    : setting scan oui 0x97f31328
07-12 17:45:45.153   791   896 D WifiHAL : Sending mac address OUI
,07-12 17:45:45.164   791   896 E native  : do suspend true
,07-12 17:45:45.167   791   896 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-12 17:45:45.167   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-12 17:45:45.168   791   791 D RttService: SCAN_AVAILABLE : 3
07-12 17:45:45.168   791   910 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 17:45:45.168   193   684 D CommandListener: Setting iface cfg
07-12 17:45:45.168   193   684 D CommandListener: Trying to bring up p2p0
07-12 17:45:45.169   791   895 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 17:45:45.175   791   895 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 17:45:45.176   791   895 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-12 17:45:45.743  1743  1908 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.266  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:46.272  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:46.279  3458  3505 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
07-12 17:45:46.281  3458  3505 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-12 17:45:46.295  3458  3505 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c7faaf Bundle[{}]
07-12 17:45:46.297  3458  3505 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:45:46.298  3458  3505 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-12 17:45:46.299  3458  3505 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-12 17:45:46.301  3458  3505 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 17:45:46.303  3458  3505 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 17:45:46.305  3458  3505 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 17:45:46.320  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-12 17:45:46.320  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:46.320  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:46.320  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-12 17:45:46.320  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-12 17:45:46.320  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.323  3458  3505 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 300)
07-12 17:45:46.323  3458  3505 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 300)
07-12 17:45:46.323  3458  3505 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 300)
07-12 17:45:46.323  3458  3505 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 300)
,07-12 17:45:46.325  3458  3505 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 306)
07-12 17:45:46.325  3458  3505 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 306)
07-12 17:45:46.325  3458  3505 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 306)
07-12 17:45:46.325  3458  3505 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 307)
07-12 17:45:46.326  3458  3505 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 309)
07-12 17:45:46.327  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.327  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6318c21 added. We now have 2 listener(s)
07-12 17:45:46.328  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.328  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:46.328  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.328  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:46.328  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e50e846 added. We now have 9 listener(s)
,07-12 17:45:46.328  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:46.331  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-12 17:45:46.331  3458  3505 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-12 17:45:46.334  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.336  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:46.336  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:46.337  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:46.337  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.338  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.338  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-12 17:45:46.338  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7117734 added. We now have 3 listener(s)
,07-12 17:45:46.339  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-12 17:45:46.339  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:46.339  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:45:46.339  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:46.339  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af9c95d added. We now have 10 listener(s)
07-12 17:45:46.339  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:46.339  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:46.339  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:46.339  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:46.340  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:46.340  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:46.340  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.340  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.340  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6318c21 removed from the list
07-12 17:45:46.340  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:46.340  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e50e846 removed from the list
,07-12 17:45:46.340  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:46.340  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.340  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.340  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.340  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:46.340  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e50e846 not in the list
,07-12 17:45:46.340  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:46.340  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.341  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:46.341  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af9c95d removed from the list
,07-12 17:45:46.341  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:46.341  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:46.341  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.341  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:46.341  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7117734 removed from the list
07-12 17:45:46.341  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-12 17:45:46.341  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a342d2 added. We now have 2 listener(s)
07-12 17:45:46.343  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.343  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:46.343  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.343  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:46.343  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4b9fa3 added. We now have 9 listener(s)
07-12 17:45:46.343  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.344  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:46.344  3458  3505 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-12 17:45:46.346  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.347  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:46.348  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:46.348  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:46.349  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.350  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:46.350  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.350  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0e9e59 added. We now have 3 listener(s)
,07-12 17:45:46.351  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.351  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:46.351  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.351  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.351  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4eba1e added. We now have 10 listener(s)
,07-12 17:45:46.351  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.351  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:46.351  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:46.351  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.351  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:46.354  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:46.354  3458  3505 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:46.354  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:46.354  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.355  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.355  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.355  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.355  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:46.355  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.355  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:46.355  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.355  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a342d2 removed from the list
07-12 17:45:46.355  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.355  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4b9fa3 removed from the list
07-12 17:45:46.355  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.355  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.356  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.356  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:46.356  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.356  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.356  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.356  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4b9fa3 not in the list
07-12 17:45:46.356  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:46.356  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.356  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.356  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4eba1e removed from the list
07-12 17:45:46.356  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.356  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.356  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.356  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.356  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0e9e59 removed from the list
07-12 17:45:46.356  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.357  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11878cc added. We now have 2 listener(s)
07-12 17:45:46.357  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-12 17:45:46.357  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:46.357  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.358  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.358  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@601c715 added. We now have 9 listener(s)
07-12 17:45:46.358  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.359  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-12 17:45:46.359  3458  3505 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:46.361  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.362  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:46.363  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:46.363  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:46.364  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.364  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.364  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.365  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3601b added. We now have 3 listener(s)
07-12 17:45:46.365  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-12 17:45:46.366  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:46.366  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.366  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.366  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ba55b8 added. We now have 10 listener(s)
07-12 17:45:46.366  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.366  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-12 17:45:46.366  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:46.366  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:46.366  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.366  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:46.369  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:46.369  3458  3505 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:46.369  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.369  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.369  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.369  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.369  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.369  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:46.369  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.369  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11878cc removed from the list
07-12 17:45:46.369  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.369  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@601c715 removed from the list
07-12 17:45:46.369  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.369  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:46.369  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.369  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:46.369  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.369  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:46.369  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.369  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@601c715 not in the list
07-12 17:45:46.369  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:46.370  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.370  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:46.370  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ba55b8 removed from the list
07-12 17:45:46.370  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.370  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.370  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.370  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.370  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3601b removed from the list
,07-12 17:45:46.370  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.370  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@749eef6 added. We now have 2 listener(s)
07-12 17:45:46.371  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.371  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:46.371  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 17:45:46.371  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.371  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98de2f7 added. We now have 9 listener(s)
07-12 17:45:46.371  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.372  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:46.372  3458  3505 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:46.374  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.376  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:46.377  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:46.377  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:46.378  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.378  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.378  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.378  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e4c3cd added. We now have 3 listener(s)
07-12 17:45:46.379  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.379  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:46.379  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.379  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.379  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9e0482 added. We now have 10 listener(s)
07-12 17:45:46.379  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.379  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:46.379  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-12 17:45:46.379  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.379  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:46.383  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-12 17:45:46.383  3458  3505 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:46.384  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.384  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.384  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.384  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.384  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.384  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:46.384  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.384  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@749eef6 removed from the list
07-12 17:45:46.384  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.384  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98de2f7 removed from the list
07-12 17:45:46.384  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.384  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:46.385  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.385  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:46.385  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.385  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.385  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.385  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98de2f7 not in the list
07-12 17:45:46.385  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-12 17:45:46.385  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.385  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.385  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9e0482 removed from the list
07-12 17:45:46.385  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.385  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.385  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.385  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.385  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e4c3cd removed from the list
07-12 17:45:46.386  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.386  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a623d0 added. We now have 2 listener(s)
07-12 17:45:46.387  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.387  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:46.387  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.387  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.387  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@686cfc9 added. We now have 9 listener(s)
07-12 17:45:46.388  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.389  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-12 17:45:46.389  3458  3505 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:46.391  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.393  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:46.394  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:46.394  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:46.395  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.395  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:46.395  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.395  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95839ef added. We now have 3 listener(s)
07-12 17:45:46.396  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.396  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:46.396  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.396  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.396  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a11acfc added. We now have 10 listener(s)
07-12 17:45:46.396  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:46.397  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.397  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.397  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.397  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.397  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.397  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.397  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:46.397  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a623d0 removed from the list
07-12 17:45:46.397  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.397  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@686cfc9 removed from the list
07-12 17:45:46.397  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.397  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.398  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.398  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.398  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.398  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@686cfc9 not in the list
07-12 17:45:46.398  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.398  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.398  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.398  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a11acfc removed from the list
07-12 17:45:46.398  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.398  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.398  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.398  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:46.398  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95839ef removed from the list
,07-12 17:45:46.398  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:46.398  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 added. We now have 2 listener(s)
07-12 17:45:46.400  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-12 17:45:46.400  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:46.400  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:46.400  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:46.400  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da added. We now have 9 listener(s)
07-12 17:45:46.400  3458  3505 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:46.402  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-12 17:45:46.402  3458  3505 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-12 17:45:46.404  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.406  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:46.418  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-12 17:45:46.419  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:46.419  3458  3505 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-12 17:45:46.420  3458  3505 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-12 17:45:46.420  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:46.425  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:46.425  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:46.425  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.425  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:46.425  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.426  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.426  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.426  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.426  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:46.426  3458  3505 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 removed from the list
,07-12 17:45:46.426  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.426  3458  3505 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da removed from the list
07-12 17:45:46.426  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.426  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.427  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.427  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.427  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.427  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
,07-12 17:45:46.428  3458  3505 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-12 17:45:46.428  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.428  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.428  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.429  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:46.429  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:46.429  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.429  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.429  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.429  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.429  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.429  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.429  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.429  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.429  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.429  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.429  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.430  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:46.430  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-12 17:45:46.431  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.431  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.431  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.431  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.431  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.431  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.431  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.431  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.431  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.431  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.431  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.431  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.431  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.431  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.431  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.432  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.432  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.432  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.432  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.432  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.432  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.432  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.432  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.432  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.432  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:46.432  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.432  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.433  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.433  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.433  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.433  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.433  3458  3505 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:46.435  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.437  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:46.438  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:46.438  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:46.439  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-12 17:45:46.439  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.439  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:46.439  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.439  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:46.440  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.442  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:46.442  3458  3505 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:46.442  3458  3505 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:46.444  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.444  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.444  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.444  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.444  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.444  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:46.444  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.444  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.444  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.444  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.444  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.444  3458  3505 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:46.445  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.447  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:46.448  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:46.448  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:46.448  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:46.449  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:46.450  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-12 17:45:46.450  3458  3505 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:46.450  3458  3505 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:46.451  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.452  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.452  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.452  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.452  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.452  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.452  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.452  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:46.452  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.452  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:46.452  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.452  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.452  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.452  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:46.453  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.453  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.453  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.453  3458  3505 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:46.454  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:46.456  3458  3505 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:46.457  3458  3505 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:46.457  3458  3505 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:46.457  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:46.457  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:46.457  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.457  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:46.458  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.459  3458  3458 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:46.461  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:46.461  3458  3505 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-12 17:45:46.461  3458  3505 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:46.461  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.461  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:46.461  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.461  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.461  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.461  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.461  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.461  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.461  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:46.461  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.461  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.461  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.461  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:46.462  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.462  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:46.462  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.462  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.462  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.462  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.462  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.462  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.462  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.462  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.462  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.462  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.462  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.462  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.462  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.462  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.462  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.463  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.463  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.463  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.463  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.463  3458  3505 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-12 17:45:46.463  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.463  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.463  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.463  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.463  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.463  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.463  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.463  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.463  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.463  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.463  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.463  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.463  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:46.463  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.463  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.463  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.464  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-12 17:45:46.464  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.464  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.464  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.464  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.464  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.464  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.464  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.464  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.464  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.464  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.464  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.464  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.464  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.464  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.464  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.464  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.464  3458  3505 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-12 17:45:46.464  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.464  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.464  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.464  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.465  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.465  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.465  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.465  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.465  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.465  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.465  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.465  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:46.465  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.465  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.465  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.465  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.465  3458  3505 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-12 17:45:46.465  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.465  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.465  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.465  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.465  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.465  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.465  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.465  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.465  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.465  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.465  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.465  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.465  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:46.465  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.465  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.465  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.466  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:46.466  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:46.466  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:46.466  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:46.466  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:46.466  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:46.466  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.466  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.466  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.466  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.466  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.466  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.466  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.466  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.466  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.466  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.466  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:46.466  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.466  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.466  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.466  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.466  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.467  3458  3505 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:46.467  3458  3505 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:46.467  3458  3505 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:46.467  3458  3505 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:46.467  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-12 17:45:46.468  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-12 17:45:46.468  3458  3505 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-12 17:45:46.468  3458  3505 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-12 17:45:46.468  3458  3505 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-12 17:45:46.468  3458  3505 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:46.469  3458  3505 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-12 17:45:46.469  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.469  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.469  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.469  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.469  3458  3505 W org.thaliproject.p2p.btconnectorl,ib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.469  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.469  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.469  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.469  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.469  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.469  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.469  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.469  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.469  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.469  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.469  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.470  3458  3505 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-12 17:45:46.470  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.470  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.470  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.470  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.470  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.470  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.470  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.470  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.470  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.470  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.471  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.471  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.471  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.471  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.471  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.471  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.471  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.471  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.471  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.471  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.471  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.471  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.471  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.471  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.471  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.471  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.471  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.471  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.471  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.471  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.471  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.471  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.472  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.472  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.472  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.472  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.472  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.472  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.472  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.472  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.472  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.472  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.472  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.472  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.472  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.472  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.472  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.472  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.472  3458  3505 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-12 17:45:46.473  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.473  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.473  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.473  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.473  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.473  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.473  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.473  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.473  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.473  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.473  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.473  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.473  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.473  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.473  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.473  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.473  3458  3505 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-12 17:45:46.473  3458  3505 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-12 17:45:46.473  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:46.473  3458  3505 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-12 17:45:46.473  3458  3505 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:46.473  3458  3505 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-12 17:45:46.473  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:46.473  3458  3505 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-12 17:45:46.474  3458  3505 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:46.474  3458  3505 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-12 17:45:46.474  3458  3505 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:46.474  3458  3505 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-12 17:45:46.474  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.474  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.474  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.474  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.474  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.474  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.474  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.474  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.474  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.474  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.474  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.474  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.474  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.474  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.474  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.474  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.474  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.474  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.474  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.474  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.474  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.474  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.474  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.474  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.474  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.474  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.474  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.474  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.474  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.474  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.475  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.475  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.475  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.475  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.475  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.475  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.475  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.475  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.475  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.475  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.475  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.475  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.475  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.475  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.475  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.475  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.475  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.476  3458  3505 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-12 17:45:46.476  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.476  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-12 17:45:46.477  3458  3505 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-12 17:45:46.477  3458  3505 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-12 17:45:46.477  3458  3458 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-12 17:45:46.477  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-12 17:45:46.477  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.477  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:46.477  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-12 17:45:46.477  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-12 17:45:46.477  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-12 17:45:46.477  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.477  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.477  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.477  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:46.477  3458  3505 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:46.477  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:46.477  3458  4084 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-12 17:45:46.477  3458  4084 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-12 17:45:46.478  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.478  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.478  3458  3505 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:46.478  3458  3458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:46.478  3458  3458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.478  3458  3458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:46.479  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.479  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.479  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.479  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:46.479  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.479  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.481  3458  3458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:46.481  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:46.481  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.481  3458  3458 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:46.481  3458  3458 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:46.481  3458  3458 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:46.481  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.481  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:46.481  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.481  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.481  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.481  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.481  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.481  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.481  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.481  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:46.484  3458  3458 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-12 17:45:46.484  3458  3505 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:46.484  3458  3458 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-12 17:45:46.484  3458  3458 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-12 17:45:46.484  3458  3458 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:46.484  3458  3458 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-12 17:45:46.484  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.484  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.484  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.485  3458  3505 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-12 17:45:46.485  3458  3505 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-12 17:45:46.485  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:46.485  3458  3505 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:46.485  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.485  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.485  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.485  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.485  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.485  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.485  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.485  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.485  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.485  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.485  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.485  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.485  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.485  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.485  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.485  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.488  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.488  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.488  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.488  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.488  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.488  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.488  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.488  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.488  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.488  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.488  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.488  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.488  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.488  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.488  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.488  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.488  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.488  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.488  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.488  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.488  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.489  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.489  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.489  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.489  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.489  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.489  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.489  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.489  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.489  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.489  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.489  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.489  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.489  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.489  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.489  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.489  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.489  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.489  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.489  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.489  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.489  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.489  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.489  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.489  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.489  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.489  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.489  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.490  3458  3505 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:46.490  3458  3505 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-12 17:45:46.490  3458  3458 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-12 17:45:46.490  3458  3505 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-12 17:45:46.490  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.490  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.490  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current, state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.490  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.490  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.490  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.490  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.490  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.490  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.490  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.490  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.490  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.490  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.490  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.490  3458  3505 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-12 17:45:46.490  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.490  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.491  3458  3505 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:46.491  3458  3505 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:46.491  3458  3505 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:46.491  3458  3505 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:46.491  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.491  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.491  3458  3505 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3239f85 not in the list
07-12 17:45:46.491  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.491  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.491  3458  3505 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:46.491  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.491  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.491  3458  3505 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:46.491  3458  3505 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:46.491  3458  3505 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:46.491  3458  3505 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a3a1da not in the list
07-12 17:45:46.491  3458  3505 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-12 17:45:46.491  3458  3505 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-12 17:45:46.492  3458  3505 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-12 17:45:46.492  3458  3505 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-12 17:45:46.492  3458  3505 E com.test.thalitest.ThaliTestRunner: Total duration: 29421 ms
07-12 17:45:46.493  3458  3505 I jxcore-log: PromiseSuccess
07-12 17:45:46.493  3458  3505 I jxcore-log: 
07-12 17:45:46.495  3458  3505 I jxcore-log: My device name is: LGE-Nexus 5
07-12 17:45:46.495  3458  3505 I jxcore-log: 
,07-12 17:45:50.458  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 17:45:50.458  3458  3505 I jxcore-log: 
,07-12 17:45:50.849  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 17:45:50.849  3458  3505 I jxcore-log: 
,07-12 17:45:50.872  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 17:45:50.872  3458  3505 I jxcore-log: 
,07-12 17:45:50.875  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 17:45:50.875  3458  3505 I jxcore-log: 
,07-12 17:45:50.891  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 17:45:50.891  3458  3505 I jxcore-log: 
,07-12 17:45:50.894  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 17:45:50.894  3458  3505 I jxcore-log: 
,07-12 17:45:52.819  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 17:45:52.819  3458  3505 I jxcore-log: 
,07-12 17:45:52.829  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 17:45:52.829  3458  3505 I jxcore-log: 
,07-12 17:45:52.837  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 17:45:52.837  3458  3505 I jxcore-log: 
,07-12 17:45:52.989  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 17:45:52.989  3458  3505 I jxcore-log: 
,07-12 17:45:53.692  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 17:45:53.692  3458  3505 I jxcore-log: 
,07-12 17:45:53.746  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 17:45:53.746  3458  3505 I jxcore-log: 
,07-12 17:45:53.752  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 17:45:53.752  3458  3505 I jxcore-log: 
,07-12 17:45:53.954  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 17:45:53.954  3458  3505 I jxcore-log: 
,07-12 17:45:53.974  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 17:45:53.974  3458  3505 I jxcore-log: 
,07-12 17:45:53.978  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 17:45:53.978  3458  3505 I jxcore-log: 
,07-12 17:45:53.983  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 17:45:53.983  3458  3505 I jxcore-log: 
,07-12 17:45:53.998  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 17:45:53.998  3458  3505 I jxcore-log: 
,07-12 17:45:54.017  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 17:45:54.017  3458  3505 I jxcore-log: 
,07-12 17:45:54.102  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 17:45:54.102  3458  3505 I jxcore-log: 
,07-12 17:45:54.106  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 17:45:54.106  3458  3505 I jxcore-log: 
,07-12 17:45:54.131  3458  3505 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 17:45:54.131  3458  3505 I jxcore-log: 
,07-12 17:45:54.139  3458  3505 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-12 17:45:54.141  3458  3505 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-12 17:45:54.141  3458  3505 I jxcore-log: 
,07-12 17:45:54.185  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:54.185  3458  3505 I jxcore-log: 
,07-12 17:45:54.186  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:54.186  3458  3505 I jxcore-log: 
07-12 17:45:54.186  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.186  3458  3505 I jxcore-log: 
07-12 17:45:54.187  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.187  3458  3505 I jxcore-log: 
07-12 17:45:54.188  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.188  3458  3505 I jxcore-log: 
07-12 17:45:54.190  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.190  3458  3505 I jxcore-log: 
07-12 17:45:54.190  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.190  3458  3505 I jxcore-log: 
,07-12 17:45:54.191  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.191  3458  3505 I jxcore-log: 
,07-12 17:45:54.191  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.191  3458  3505 I jxcore-log: 
07-12 17:45:54.192  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.192  3458  3505 I jxcore-log: 
07-12 17:45:54.192  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.192  3458  3505 I jxcore-log: 
07-12 17:45:54.193  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.193  3458  3505 I jxcore-log: 
07-12 17:45:54.193  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.193  3458  3505 I jxcore-log: 
07-12 17:45:54.193  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.193  3458  3505 I jxcore-log: 
07-12 17:45:54.194  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:45:54.194  3458  3505 I jxcore-log: 
,07-12 17:45:54.194  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.194  3458  3505 I jxcore-log: 
07-12 17:45:54.195  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.195  3458  3505 I jxcore-log: 
07-12 17:45:54.195  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.195  3458  3505 I jxcore-log: 
07-12 17:45:54.195  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.195  3458  3505 I jxcore-log: 
07-12 17:45:54.196  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.196  3458  3505 I jxcore-log: 
07-12 17:45:54.196  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.196  3458  3505 I jxcore-log: 
07-12 17:45:54.197  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.197  3458  3505 I jxcore-log: 
07-12 17:45:54.197  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.197  3458  3505 I jxcore-log: 
,07-12 17:45:54.197  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.197  3458  3505 I jxcore-log: 
07-12 17:45:54.198  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.198  3458  3505 I jxcore-log: 
07-12 17:45:54.198  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:45:54.198  3458  3505 I jxcore-log: 
07-12 17:45:54.199  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-12 17:45:54.199  3458  3505 I jxcore-log: 
07-12 17:45:54.199  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:45:54.199  3458  3505 I jxcore-log: 
07-12 17:45:54.200  3458  3505 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-12 17:45:54.200  3458  3505 I jxcore-log: 
,07-12 17:45:55.815  1622  2975 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 17:46:05.389  1240  1341 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-12 17:46:05.389  1240  1341 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 17:46:17.059   791   896 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:46:17.070   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:46:17.084  1622  4102 V CheckinChimeraService: No Subscriptions found on the device
,07-12 17:46:17.085  1622  4102 I CheckinChimeraService: Checking schedule, now: 1468338377085 next: 1468338354785
07-12 17:46:17.085  1622  4102 I CheckinChimeraService: active receiver: enabled
,07-12 17:46:17.108  1743  4107 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-12 17:46:17.113  1622  4101 I EventLogChimeraService: Aggregate from 1468336552031 (log), 1468336552031 (data)
,07-12 17:46:17.236  1622  4122 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 17:46:17.248  1622  4122 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 17:46:17.390   791   898 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-12 17:46:27.153   791   888 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 17:46:27.185   191   191 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6cca030
,07-12 17:46:27.185   191   191 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-12 17:46:27.185   191   191 I rmt_storage: wakelock acquired: 1, error no: 2
07-12 17:46:27.185   191   486 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229190864)
,07-12 17:46:27.223  1397  4145 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-12 17:46:27.258  1397  4145 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 34 ms] updated apps [took 34 ms] 
,07-12 17:46:27.258  1622  4150 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-12 17:46:27.270  1622  4150 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-12 17:46:27.270   191   486 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
07-12 17:46:27.270   191   486 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-12 17:46:27.270   191   486 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229190864) wakelock released: 1, error no: 0
07-12 17:46:27.270   191   486 I rmt_storage: 
,07-12 17:46:27.273   191   191 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6cca030
,07-12 17:46:27.290  1622  1777 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-12 17:46:27.336  1622  4162 W IcingInternalCorpora: getNumBytesRead when not calculated.
07-12 17:46:27.337  1743  1743 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-12 17:46:28.433  1622  1777 I Icing   : Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,07-12 17:46:28.474  1622  1777 I Icing   : Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,07-12 17:47:18.822   791   896 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:47:18.848   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:48:20.628   791   896 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:48:20.656   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:48:45.449  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:48:45.477  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 17:48:45.478  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:49:17.420  1743  2952 V NativeCrypto: SSL shutdown failed: ssl=0x9b821600: I/O error during system call, Connection timed out
,07-12 17:49:50.102  1743  2952 V NativeCrypto: SSL shutdown failed: ssl=0x9a513600: I/O error during system call, Connection timed out
,07-12 17:49:50.634  1743  2952 V NativeCrypto: SSL shutdown failed: ssl=0x9a4ab400: I/O error during system call, Connection timed out
,07-12 17:54:22.348   791   896 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:54:22.378   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 17:59:19.168  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:59:19.198  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 17:59:19.205  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:00:24.091   791   896 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 18:00:24.122   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 18:03:30.396   791   806 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 18:04:19.262  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:04:19.296  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:04:19.297  1743  1743 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 18:06:25.772   791   896 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 18:06:25.798   791   896 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,TIME-OUT KILL (timeout was 1400000ms)
```
