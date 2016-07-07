#### Test 7578926821ef376_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
07-07 20:27:47.423  1729  1905 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:27:48.062  3598  3598 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-07 20:27:48.066  3598  3598 D AndroidRuntime: CheckJNI is OFF
07-07 20:27:48.101  3598  3598 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-07 20:27:48.138  3598  3598 I Radio-JNI: register_android_hardware_Radio DONE
07-07 20:27:48.156  3598  3598 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-07 20:27:48.159   787  1147 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-07 20:27:48.178   787  1147 I ActivityManager: Start proc 3618:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-07 20:27:48.180  3598  3598 D AndroidRuntime: Shutting down VM
07-07 20:27:48.255  3618  3618 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-07 20:27:48.305  3618  3618 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2004-2009)
07-07 20:27:48.305  3618  3618 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:27:48.329  3618  3618 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fa314c3}
07-07 20:27:48.329  3618  3618 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:27:48.330  3618  3618 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-07 20:27:48.339  3618  3618 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-07 20:27:48.340  3618  3618 E SysUtils: ApplicationContext is null in ApplicationStatus
07-07 20:27:48.350  3618  3618 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-07 20:27:48.354  3618  3618 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-07 20:27:48.354  3618  3618 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-07 20:27:48.355  3618  3618 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-07 20:27:48.405   787   805 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c4c7288:true
,07-07 20:27:48.477  3618  3618 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 20:27:48.487  3618  3618 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-07 20:27:48.542  3618  3669 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-07 20:27:48.568  3618  3653 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-07 20:27:48.600  3618  3669 I OpenGLRenderer: Initialized EGL, version 1.4
,07-07 20:27:48.627  1232  1232 I Keyboard.Facilitator: onFinishInput()
,07-07 20:27:48.645   787   806 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +430ms (total +474ms)
,07-07 20:27:48.718  3618  3618 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3618
,07-07 20:27:48.799  3618  3618 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:27:48.909  3618  3678 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1655256784
,07-07 20:27:48.914  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 20:27:48.914  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:27:48.914  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:27:48.914  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:27:48.914  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-07 20:27:48.914  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bec556 added. We now have 1 listener(s)
,07-07 20:27:48.918  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
,07-07 20:27:48.919  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-07 20:27:48.920  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:27:48.921  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-07 20:27:48.924  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ced5ad added. We now have 1 listener(s)
07-07 20:27:48.924  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:48.927   787   893 D WifiService: New client listening to asynchronous messages
,07-07 20:27:48.929  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-07 20:27:48.931  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-07 20:27:48.931  3618  3678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-07 20:27:48.937  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:27:48.937  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:48.941  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:27:48.941  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 20:27:48.941  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:27:48.941  3618  3678 I io.jxcore.node.LifeCycleMonitor: start: OK
07-07 20:27:48.953  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:27:48.954  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:48.965  3618  3618 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:27:49.727  3618  3685 W jxcore-log: Initializing JXcore engine
07-07 20:27:49.727  3618  3685 W jxcore-log: JXcore engine is ready
,07-07 20:27:49.776  3685  3685 W Thread-276: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8023]" dev="sockfs" ino=8023 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-07 20:27:49.776  3685  3685 W Thread-276: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-07 20:27:49.776  3685  3685 W Thread-276: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21450]" dev="sockfs" ino=21450 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-07 20:27:49.806  3618  3685 W jxcore-log: Starting JXcore engine
,07-07 20:27:49.912  3618  3685 W jxcore-log: Platform android
07-07 20:27:49.912  3618  3685 W jxcore-log: 
,07-07 20:27:49.912  3618  3685 W jxcore-log: Process ARCH arm
07-07 20:27:49.912  3618  3685 W jxcore-log: 
,07-07 20:27:50.095  3618  3685 I jxcore-log: JXcore Cordova bridge is ready!
07-07 20:27:50.095  3618  3685 I jxcore-log: 
07-07 20:27:50.095  3618  3685 W jxcore-log: JXcore engine is started
,07-07 20:27:50.099  3618  3678 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 20:27:50.101  3618  3618 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 20:27:56.866  1614  1829 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:27:59.701  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-07 20:27:59.701  3618  3685 I jxcore-log: 
,07-07 20:27:59.703  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-07 20:27:59.703  3618  3685 I jxcore-log: 
,07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:59.707  3618  3685 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:27:59.708  3618  3685 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:27:59.710  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-07 20:27:59.710  3618  3685 I jxcore-log: 
,07-07 20:27:59.711  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-07 20:27:59.711  3618  3685 I jxcore-log: 
,07-07 20:28:00.042  3618  3685 I jxcore-log: Unit Test app is loaded
07-07 20:28:00.042  3618  3685 I jxcore-log: 
,07-07 20:28:00.047  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:28:00.047  3618  3685 I jxcore-log: 
,07-07 20:28:00.051  3618  3618 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-07 20:28:00.051  3618  3678 D JX-Cordova: Running tests
,07-07 20:28:00.057  3618  3685 I jxcore-log: My device name is: LGE-Nexus 5
07-07 20:28:00.057  3618  3685 I jxcore-log: 
,07-07 20:28:00.111  3618  3678 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-07 20:28:00.111  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-07 20:28:00.111  3618  3678 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-07 20:28:00.111  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-07 20:28:00.111  3618  3678 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-07 20:28:00.111  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-07 20:28:00.112  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-07 20:28:00.112  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-07 20:28:00.112  3618  3678 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-07 20:28:00.112  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:28:00.112  3618  3678 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-07 20:28:00.112  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:28:00.112  3618  3678 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-07 20:28:00.112  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:28:00.113  3618  3678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-07 20:28:00.113  3618  3678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-07 20:28:00.113  3618  3678 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-07 20:28:00.113  3618  3678 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-07 20:28:00.113  3618  3678 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-07 20:28:00.113  3618  3678 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-07 20:28:00.114  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:00.114  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a26423 added. We now have 2 listener(s)
07-07 20:28:00.114  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:00.115  3618  3678 D BluetoothAdapter: enable(): BT is already enabled..!
,07-07 20:28:00.116   787  1315 D WifiService: setWifiEnabled: true pid=3618, uid=10000,
,07-07 20:28:00.116   787  1315 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:28:00.116  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:00.116  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ab97d20 added. We now have 3 listener(s)
,07-07 20:28:00.116  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:00.119  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:28:00.119  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bda36d9 added. We now have 4 listener(s)
07-07 20:28:00.119  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:00.120  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:28:00.120  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d75a89e added. We now have 5 listener(s)
07-07 20:28:00.120  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:00.122   787  3021 D WifiService: setWifiEnabled: false pid=3618, uid=10000
07-07 20:28:00.122   787  3021 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:28:00.124   787   892 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-07 20:28:00.124   787   892 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-07 20:28:00.124   787   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:28:00.124   787   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-07 20:28:00.129  1952  2019 D BluetoothAdapterState: Current state: ON, message: 23
07-07 20:28:00.129  1952  2019 D BluetoothAdapterProperties: Setting state to 13
,07-07 20:28:00.129  1952  2019 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:28:00.129  1952  2019 D BluetoothAdapterProperties: onBluetoothDisable()
07-07 20:28:00.130  1952  2019 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:28:00.131  1952  1952 D BluetoothMapService: onReceive
07-07 20:28:00.131  1952  1952 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:28:00.131  1952  1952 D BluetoothMapService: STATE_TURNING_OFF
07-07 20:28:00.131  1952  1952 D BluetoothMapService: MAP Service closeService in
07-07 20:28:00.131  1952  1952 D BluetoothMapMasInstance0: MAP Service shutdown
,07-07 20:28:00.131  1952  1952 D ObexServerSockets0: shutdown(block = true)
07-07 20:28:00.132  1952  1952 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:28:00.132  1952  2208 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-07 20:28:00.132  1952  1952 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:28:00.132  1952  2195 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-07 20:28:00.132  1952  2209 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-07 20:28:00.134  1952  1952 I BtOppRfcommListener: stopping Accept Thread
07-07 20:28:00.139   787   892 E native  : do suspend true
07-07 20:28:00.141  1952  2635 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-07 20:28:00.142  1952  2635 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-07 20:28:00.154   787  2681 D DhcpClient: Clearing IP address
07-07 20:28:00.154   195   786 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:28:00.156   787   801 I ActivityManager: Start proc 3688:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-07 20:28:00.158  1952  2028 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:28:00.160  1952  2019 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:28:00.163  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:00.167   195   786 D CommandListener: Setting iface cfg
07-07 20:28:00.167  1952  1952 D HeadsetService: Received stop request...Stopping profile...
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:28:00.168  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:28:00.169  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-07 20:28:00.169  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:28:00.170  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:28:00.171   787   787 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:00.171  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID nam,e: f4:f2:6d:22:99:3e
07-07 20:28:00.171  1299  1726 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:00.171   787   787 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:00.171   941   954 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:00.171   787   787 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:00.172  1952  1952 D A2dpService: Received stop request...Stopping profile...
07-07 20:28:00.172  1952  2200 D A2dpStateMachine: Exit Disconnected: -1
07-07 20:28:00.173   787   787 D BluetoothA2dp: Proxy object disconnected
07-07 20:28:00.173  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:00.174   941   941 D HeadsetProfile: Bluetooth service disconnected
07-07 20:28:00.174   941   941 D BluetoothA2dp: Proxy object disconnected
07-07 20:28:00.175  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:00.176  1952  1952 D HidService: Received stop request...Stopping profile...
07-07 20:28:00.176  1952  1952 D HidService: Stopping Bluetooth HidService
07-07 20:28:00.177  1952  1952 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:00.177  1952  1952 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:00.177  1952  1952 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:00.177  1952  1952 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:00.178  1952  1952 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-07 20:28:00.178  1952  2028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-07 20:28:00.178  1952  2141 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:00.178  1952  2141 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:00.178  1952  2028 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-07 20:28:00.186  1952  1952 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-07 20:28:00.198  2781  2927 V NativeCrypto: Read error: ssl=0xa0778800: I/O error during system call, Connection timed out
07-07 20:28:00.198  2781  2927 V NativeCrypto: Write error: ssl=0xa0778800: I/O error during system call, Broken pipe
07-07 20:28:00.198  2781  2927 V NativeCrypto: Write error: ssl=0xa0778800: I/O error during system call, Broken pipe
07-07 20:28:00.199  2781  2927 V NativeCrypto: SSL shutdown failed: ssl=0xa0778800: I/O error during system call, Broken pipe
07-07 20:28:00.205   941   941 D BluetoothInputDevice: Proxy object disconnected
07-07 20:28:00.205   941   941 D HidProfile: Bluetooth service disconnected
07-07 20:28:00.205  1952  1952 D HealthService: Received stop request...Stopping profile...
07-07 20:28:00.206  1952  1952 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:00.206  1952  1952 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:00.206  1952  1952 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:00.206  1952  1952 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:00.206  1952  1952 D PanService: Received stop request...Stopping profile...
07-07 20:28:00.207   941   941 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:28:00.207   941   941 D PanProfile: Bluetooth service disconnected
07-07 20:28:00.210  1952  2028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-07 20:28:00.210  1952  2141 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:00.210  1952  2141 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:00.210  1952  2141 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:28:00.210  1952  2141 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:28:00.210  1952  2141 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:28:00.210  1952  2141 W bt_l2cap: L2CAP - PSM: 0x0017 not fou,nd for deregistration
07-07 20:28:00.213  1952  1952 D BluetoothMapService: Received stop request...Stopping profile...
07-07 20:28:00.213  1952  1952 D BluetoothMapService: stop()
07-07 20:28:00.214  1952  1952 D BluetoothMapAppObserver: deinitObservers()
07-07 20:28:00.214  1952  1952 D BluetoothMapAppObserver: removeReceiver()
07-07 20:28:00.216   941   941 D BluetoothMap: Proxy object disconnected
07-07 20:28:00.216   941   941 D MapProfile: Bluetooth service disconnected
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:00.217  1952  1952 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-07 20:28:00.217  1952  1952 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:28:00.217  1952  2028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:00.217  1952  1952 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:00.217  1952  1952 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:28:00.218  1952  1952 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:28:00.218  1952  1952 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:00.218  1952  1952 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:00.218  1952  1952 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:00.218  1952  1952 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:00.218  1952  1952 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-07 20:28:00.218  1952  2028 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-07 20:28:00.219  1952  1952 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-07 20:28:00.219  1952  1952 D BluetoothMapService: MAP Service closeService in
07-07 20:28:00.219  1952  1952 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:00.219  1952  1952 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:00.219  1952  1952 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:00.219  1952  1952 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:00.219  1952  2019 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-07 20:28:00.219  1952  2019 D BluetoothAdapterProperties: Setting state to 15
07-07 20:28:00.219  1952  2019 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:28:00.220  1952  2019 I BluetoothAdapterState: Entering BleOnState
07-07 20:28:00.220   941  1357 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:28:00.220  1952  1952 D BluetoothMapService: cleanup()
07-07 20:28:00.220  1952  1952 D BluetoothMapService: MAP Service closeService in
07-07 20:28:00.221   941   955 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:28:00.221   787   805 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:00.221   941  1358 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:28:00.221  1729  2889 V NativeCrypto: Read error: ssl=0x99b6b800: I/O error during system call, Connection timed out
07-07 20:28:00.222  1299  1429 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:00.222   787   805 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:28:00.223  1729  2889 V NativeCrypto: SSL shutdown failed: ssl=0x99b6b800: I/O error during system call, Broken pipe
07-07 20:28:00.223   941   954 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:28:00.223   941  1357 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:28:00.224  1729  28,89 E GCM     : Wifi connection closed with errorCode 20
07-07 20:28:00.224   787   805 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:00.224   941   955 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:00.225   787   798 D ConnectivityService: reportNetworkConnectivity(100, false) by 10008
07-07 20:28:00.225   787  2679 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10008
07-07 20:28:00.225   787   805 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:00.225  1952  2019 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-07 20:28:00.225  1952  2019 D BluetoothAdapterProperties: Setting state to 16
07-07 20:28:00.225  1952  2019 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-07 20:28:00.226  1952  2019 D BluetoothAdapterProperties: onBleDisable
07-07 20:28:00.226  1952  2019 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:28:00.226  1952  2020 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:28:00.228  1952  2141 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-07 20:28:00.228  1952  2141 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:00.228  1952  2028 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:28:00.232  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:00.232   787  2679 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-07 20:28:00.232   787   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-07 20:28:00.232   787   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-07 20:28:00.233   787   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-07 20:28:00.236  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:00.246  3688  3688 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-07 20:28:00.249   787  2686 D DhcpClient: Receive thread stopped
07-07 20:28:00.250   787   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-07 20:28:00.250   787   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-07 20:28:00.257   787   894 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-07 20:28:00.257   787   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:28:00.271   787   892 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-07 20:28:00.274   787   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:28:00.274   787   892 E native  : do suspend true
07-07 20:28:00.275   787   787 D RttService: SCAN_AVAILABLE : 1
07-07 20:28:00.275   787   906 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-07 20:28:00.284  2781  2961 V NativeCrypto: Read error: ssl=0x996ffa00: I/O error during system call, Connection timed out
,07-07 20:28:00.285  2781  2961 V NativeCrypto: Write error: ssl=0x996ffa00: I/O error during system call, Broken pipe
07-07 20:28:00.285  2781  2961 V NativeCrypto: Write error: ssl=0x996ffa00: I/O error during system call, Broken pipe
07-07 20:28:00.285  2781  2961 V NativeCrypto: SSL shutdown failed: ssl=0x996ffa00: I/O error during system call, Broken pipe
,07-07 20:28:00.300  3688  3688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:28:00.307   195   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-07 20:28:00.309   787   805 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c08701:true
,07-07 20:28:00.319  3688  3688 D LocalBluetoothProfileManager: Adding local MAP profile
,07-07 20:28:00.320  3688  3688 D BluetoothMap: Create BluetoothMap proxy object
,07-07 20:28:00.323   195   786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:28:00.323   195   786 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:28:00.324   787   894 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-07 20:28:00.324   787   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-07 20:28:00.325   787   892 D DhcpClient: doQuit
07-07 20:28:00.325   787   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:28:00.327   787   805 D Tethering: MasterInitialState.processMessage what=3
,07-07 20:28:00.333  1952  2028 I bt_hci  : shut_down
07-07 20:28:00.334  1952  2041 D bt_hwcfg: hw_epilog_process
,07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:00.336  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:00.337   787  2681 D DhcpClient: onQuitting
07-07 20:28:00.337  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:00.346  1362  1362 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-07 20:28:00.358  1952  2041 I bt_vendor: low_power_mode_cb
07-07 20:28:00.359  3688  3688 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-07 20:28:00.368   195   786 E Netd    : netlink response contains error (No such file or directory)
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:00.369  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:00.369   787   894 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-07 20:28:00.369   787   894 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-07 20:28:00.369  3688  3688 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:28:00.370  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:00.371  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:00.373  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:00.373  1952  2041 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-07 20:28:00.373  1952  2041 I bt_vendor: epilog_cb
07-07 20:28:00.373  1952  2041 I bt_hci  : epilog_finished_callback
,07-07 20:28:00.375  1952  2028 I bt_hci_h4: hal_close
,07-07 20:28:00.375  1952  2028 I bt_userial_vendor: device fd = 49 close
,07-07 20:28:00.380  1952  2020 D bt_stack_manager: event_shut_down_stack finished.
07-07 20:28:00.380  1952  2019 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-07 20:28:00.381  1952  2019 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-07 20:28:00.381  1952  1952 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:28:00.381   787   893 D WifiService: New client listening to asynchronous messages
,07-07 20:28:00.382  1952  1952 D BtGatt.GattService: Received stop request...Stopping profile...
07-07 20:28:00.382  1952  1952 D BtGatt.GattService: stop()
07-07 20:28:00.382  1952  1952 D BtGatt.AdvertiseManager: advertise clients cleared
,07-07 20:28:00.384  1952  1952 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:00.384  1952  1952 V BluetoothAdapterState: isTurningOn()=false
,07-07 20:28:00.384  1952  1952 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:00.384  1952  1952 V BluetoothAdapterState: isBleTurningOff()=true
07-07 20:28:00.384  1952  2019 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-07 20:28:00.384  1952  2019 D BluetoothAdapterProperties: Setting state to 10
,07-07 20:28:00.384  1952  2019 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-07 20:28:00.384  1952  2019 I BluetoothAdapterState: Entering OffState
07-07 20:28:00.385   787   805 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-07 20:28:00.388  1413  1413 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-07 20:28:00.391  1952  1952 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-07 20:28:00.391  1952  1952 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-07 20:28:00.391  1952  1952 I BluetoothServiceJni: cleanupNative: return from cleanup
07-07 20:28:00.392  1952  2020 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-07 20:28:00.399  1952  2020 D bt_stack_manager: event_clean_up_stack finished.
,07-07 20:28:00.401  1952  1952 I art     : System.exit called, status: 0
,07-07 20:28:00.401  1952  1952 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-07 20:28:00.412   787  1323 I ActivityManager: Killing 2761:com.google.android.apps.photos/u0a65 (adj 15): empty #17
,07-07 20:28:00.448  1413  1413 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-07 20:28:00.457  1413  1413 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-07 20:28:00.547  1413  1413 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-07 20:28:00.596   787  1313 I ActivityManager: Process com.android.bluetooth (pid 1952) has died
,07-07 20:28:00.607  1413  1413 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-07 20:28:00.617   787   801 I ActivityManager: Start proc 3732:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-07 20:28:00.713   787   892 D wifi    : In wifi stop Hal
,07-07 20:28:00.713   787   892 D wifi    : halHandle = 0xa07ec700, mVM = 0xb4d7c000, mCls = 0x200bca
07-07 20:28:00.713   787  1412 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-07 20:28:00.713   787  1412 D WifiHAL : Got a signal to exit!!!
,07-07 20:28:00.713   787  1412 I WifiHAL : Exit wifi_event_loop
07-07 20:28:00.713   787   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-07 20:28:00.714   787   892 E WifiHAL : Event processing terminated
07-07 20:28:00.714   787   892 D wifi    : In wifi cleaned up handler
07-07 20:28:00.714  2238  2238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:28:00.714   787   892 I WifiHAL : Internal cleanup completed
,07-07 20:28:00.715  1729  1802 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:28:00.715  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:00.716  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:00.821   787  1412 D wifi    : set interface wlan0 flags (DOWN)
,07-07 20:28:00.821   787   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-07 20:28:00.870  3732  3732 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-07 20:28:00.870  3732  3732 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:28:00.870  3732  3732 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:28:00.870  3732  3732 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.e.b(PG:170)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:28:00.870  3732  3732 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.k.d(PG:583)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.e.b(PG:170)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:28:00.870  3732  3732 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:28:00.870  3732  3732 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.870  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:28:00.871  3732  3732 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:28:00.871  3732  3732 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:28:00.873   787  1315 I ActivityManager: Killing 2238:com.google.android.talk/u0a54 (adj 15): empty #17
07-07 20:28:00.893  3732  3754 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-07 20:28:00.900   787   805 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e41115c:true
,07-07 20:28:00.999  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:01.002  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:01.006  3688  3688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:28:01.019   787  1313 I ActivityManager: Start proc 3764:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-07 20:28:01.020  3688  3688 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:28:01.025   787   805 D Tethering: InitialState.processMessage what=4
,07-07 20:28:01.027   787   805 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-07 20:28:01.066  3764  3764 D AdapterServiceConfig: Adding HeadsetService
,07-07 20:28:01.066  3764  3764 D AdapterServiceConfig: Adding A2dpService
,07-07 20:28:01.066  3764  3764 D AdapterServiceConfig: Adding HidService
,07-07 20:28:01.067  3764  3764 D AdapterServiceConfig: Adding HealthService
07-07 20:28:01.069  3764  3764 D AdapterServiceConfig: Adding PanService
07-07 20:28:01.069  3764  3764 D AdapterServiceConfig: Adding GattService
07-07 20:28:01.069  3764  3764 D AdapterServiceConfig: Adding BluetoothMapService
,07-07 20:28:01.086   787   797 I ActivityManager: Killing 2048:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-07 20:28:01.229  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:01.233  1729  3777 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:28:01.234  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:01.245   787  1323 I ActivityManager: Start proc 3778:com.google.android.talk/u0a54 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,07-07 20:28:01.260  1729  3777 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-07 20:28:01.415  3778  3798 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-07 20:28:01.415  3778  3798 I Babel_SMS: MmsConfig.loadMmsSettings
07-07 20:28:01.416  3778  3798 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
07-07 20:28:01.416  3778  3798 I Babel_SMS: MmsConfig.loadFromDatabase
,07-07 20:28:01.434  3778  3798 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-07 20:28:01.434  3778  3798 I Babel_SMS: MmsConfig.loadFromResources
07-07 20:28:01.435  3778  3798 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-07 20:28:01.435  3778  3798 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-07 20:28:01.449  3778  3801 I Babel_SMS: ApnsOta: OTA version -1
,07-07 20:28:01.463  3778  3802 I Babel   : deleted: false for 0
,07-07 20:28:01.472  3778  3778 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:28:01.474  3778  3778 I Babel_Crash: startup - clean
,07-07 20:28:01.492  3778  3778 I Babel_telephony: TeleModule.launchCompleted
,07-07 20:28:01.500   787  1313 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-07 20:28:01.502  3778  3778 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-07 20:28:01.503  3778  3778 W Babel   : BAM#gBA: invalid account id: -1
,07-07 20:28:01.503  3778  3778 W Babel   : BAM#gBA: invalid account id: -1
,07-07 20:28:01.503  3778  3778 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-07 20:28:01.507   787  1317 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-07 20:28:01.533   787   798 I ActivityManager: Start proc 3811:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-07 20:28:01.548  3778  3778 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-07 20:28:01.616  3778  3778 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-07 20:28:01.629  3778  3778 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-07 20:28:01.631  3778  3778 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-07 20:28:01.633  3778  3778 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-07 20:28:01.650  3778  3778 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-07 20:28:01.667  3778  3778 I vclib   : onServiceConnected
,07-07 20:28:01.677   787  1147 I ActivityManager: Start proc 3827:com.google.android.apps.photos/u0a65 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-07 20:28:01.680  3778  3826 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-07 20:28:01.683   787  3022 I ActivityManager: Killing 3120:com.google.android.gms:car/u0a8 (adj 15): empty #17
,07-07 20:28:01.866  3827  3827 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-07 20:28:02.026   787  1147 I ActivityManager: Killing 3213:com.google.android.youtube/u0a80 (adj 15): empty #17
,07-07 20:28:02.153  1614  1614 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-07 20:28:02.155  1614  2828 I iu.UploadsManager: num queued entries: 0
,07-07 20:28:02.165   787  3022 I ActivityManager: Start proc 3846:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-07 20:28:02.171  1614  2828 I iu.UploadsManager: num updated entries: 0
,07-07 20:28:02.172  1614  2828 I iu.SyncManager: NEXT; no task
,07-07 20:28:02.201  3846  3846 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-07 20:28:02.240  3846  3846 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-07 20:28:02.240  3846  3846 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-07 20:28:02.240  3846  3846 I GAv4    :   adb logcat -s GAv4
,07-07 20:28:02.257  3846  3846 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:28:02.261  3846  3846 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:28:02.265  3846  3867 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:28:02.353  3846  3846 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-07 20:28:02.386  3846  3846 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6087-6089)
,07-07 20:28:02.386  3846  3846 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:28:02.393  3846  3846 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fb776c7}
,07-07 20:28:02.393  3846  3846 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:28:02.394  3846  3846 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 20:28:02.399  3846  3846 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:28:02.400  3846  3846 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:28:02.410  3846  3846 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-07 20:28:02.415  3846  3846 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-07 20:28:02.415  3846  3846 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-07 20:28:02.416  3846  3846 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-07 20:28:02.458  3846  3899 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-07 20:28:02.468  3846  3846 I NSApplication: Starting up...
,07-07 20:28:02.475   787  1147 I ActivityManager: Killing 3305:com.google.android.gms.unstable/u0a8 (adj 15): empty #17
,07-07 20:28:02.673   787   797 I ActivityManager: Start proc 3905:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-07 20:28:02.712  3905  3905 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-07 20:28:02.754  3905  3905 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-07 20:28:02.757   787  1147 I ActivityManager: Killing 3472:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-07 20:28:03.170   787  1317 D WifiService: setWifiEnabled: true pid=3618, uid=10000
,07-07 20:28:03.170   787  1317 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:28:03.172   195   786 D SoftapController: Softap fwReload - Ok
,07-07 20:28:03.173   195   786 D CommandListener: Setting iface cfg
07-07 20:28:03.174   195   786 D CommandListener: Trying to bring down wlan0
07-07 20:28:03.174   195   786 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:28:03.176   787   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:28:03.921   787   892 D wifi    : set interface wlan0 flags (UP)
,07-07 20:28:03.921   787   892 I WifiHAL : Initializing wifi
07-07 20:28:03.921   787   892 I WifiHAL : Creating socket
07-07 20:28:03.921   787   805 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-07 20:28:03.922   787   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-07 20:28:03.922   787   892 D wifi    : Did set static halHandle = 0xa07ec700
07-07 20:28:03.922   787   892 D wifi    : halHandle = 0xa07ec700, mVM = 0xb4d7c000, mCls = 0x1014da
07-07 20:28:03.922   787   892 D wifi    : array field set
07-07 20:28:03.922   787   892 I WifiNative-HAL: interface[0] = p2p0
,07-07 20:28:03.922   787   892 I WifiNative-HAL: interface[1] = wlan0
07-07 20:28:03.926  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:03.927  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:03.927   787   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-07 20:28:03.927   787   892 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-07 20:28:03.929   787  3938 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602304256
07-07 20:28:03.929   787  3938 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0x1014da, env = 0x9929a7c0
,07-07 20:28:03.973  3939  3939 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-07 20:28:04.019  3939  3939 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:28:04.107  3939  3939 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:28:04.483  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-07 20:28:04.483  3618  3685 I jxcore-log: 
,07-07 20:28:04.880  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-07 20:28:04.880  3618  3685 I jxcore-log: 
,07-07 20:28:04.904  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-07 20:28:04.904  3618  3685 I jxcore-log: 
,07-07 20:28:04.908  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-07 20:28:04.908  3618  3685 I jxcore-log: 
,07-07 20:28:04.924  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-07 20:28:04.924  3618  3685 I jxcore-log: 
07-07 20:28:04.927  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-07 20:28:04.927  3618  3685 I jxcore-log: 
,07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:04.935  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:04.935  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:04.936  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:04.936  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:04.937   787   892 D WifiConfigStore: Loading config and enabling all networks 
07-07 20:28:04.951   787   892 D WifiConfigStore: loaded 0 passpoint configs
07-07 20:28:04.951   787   892 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:28:04.951   787   892 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-07 20:28:04.952   787   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-07 20:28:04.953   787   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:28:04.953   787   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-07 20:28:04.953   787   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-07 20:28:04.953   787   892 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-07 20:28:04.957   787   892 D WifiNative-HAL: Setting external_sim to 1
07-07 20:28:04.958   787   892 D wifi    : setting dfs flag to true, 0x9a1de680
,07-07 20:28:04.958   787   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-07 20:28:04.958   787   892 D wifi    : setting scan oui 0x9a1de680
07-07 20:28:04.958   787   892 D WifiHAL : Sending mac address OUI
07-07 20:28:04.959  3778  3778 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:28:04.977   787   892 E native  : do suspend true
,07-07 20:28:04.981   787   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-07 20:28:04.981   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-07 20:28:04.981   787   787 D RttService: SCAN_AVAILABLE : 3
07-07 20:28:04.981   787   906 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-07 20:28:04.982   195   786 D CommandListener: Setting iface cfg
07-07 20:28:04.982   195   786 D CommandListener: Trying to bring up p2p0
07-07 20:28:04.982   787   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-07 20:28:04.993   787   891 D WifiNative-HAL: p2pGetDeviceAddress
,07-07 20:28:04.993   787   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-07 20:28:06.171   787   797 D WifiService: setWifiEnabled: false pid=3618, uid=10000
,07-07 20:28:06.171   787   797 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:28:06.173   787   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:28:06.184   787   787 D RttService: SCAN_AVAILABLE : 1
,07-07 20:28:06.184   787   906 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-07 20:28:06.193   787   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-07 20:28:06.193   195   786 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:28:06.195   787   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:06.200  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:06.200  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:06.201  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:06.201  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:06.247  3939  3939 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-07 20:28:06.268   787  1314 I ActivityManager: Killing 3499:com.android.musicfx/u0a15 (adj 15): empty #17
,07-07 20:28:07.007  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-07 20:28:07.007  3618  3685 I jxcore-log: 
,07-07 20:28:07.018  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-07 20:28:07.018  3618  3685 I jxcore-log: 
,07-07 20:28:07.026  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-07 20:28:07.026  3618  3685 I jxcore-log: 
,07-07 20:28:07.178  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-07 20:28:07.178  3618  3685 I jxcore-log: 
,07-07 20:28:07.265  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-07 20:28:07.265  3618  3685 I jxcore-log: 
,07-07 20:28:07.276  3939  3939 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-07 20:28:07.323  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-07 20:28:07.323  3618  3685 I jxcore-log: 
,07-07 20:28:07.329  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-07 20:28:07.329  3618  3685 I jxcore-log: 
,07-07 20:28:07.426  3939  3939 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-07 20:28:07.506  3939  3939 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-07 20:28:07.524  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-07 20:28:07.524  3618  3685 I jxcore-log: 
,07-07 20:28:07.546  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-07 20:28:07.546  3618  3685 I jxcore-log: 
07-07 20:28:07.550  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-07 20:28:07.550  3618  3685 I jxcore-log: 
07-07 20:28:07.555  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-07 20:28:07.555  3618  3685 I jxcore-log: 
,07-07 20:28:07.571  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-07 20:28:07.571  3618  3685 I jxcore-log: 
,07-07 20:28:07.589  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-07 20:28:07.589  3618  3685 I jxcore-log: 
,07-07 20:28:07.609   787   892 D wifi    : In wifi stop Hal
,07-07 20:28:07.609   787   892 D wifi    : halHandle = 0xa07ec700, mVM = 0xb4d7c000, mCls = 0x1014da
07-07 20:28:07.609   787  3938 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-07 20:28:07.609   787  3938 D WifiHAL : Got a signal to exit!!!
07-07 20:28:07.609   787  3938 I WifiHAL : Exit wifi_event_loop
07-07 20:28:07.610  1729  1802 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:28:07.611  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:07.611   787   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,07-07 20:28:07.611   787   892 E WifiHAL : Event processing terminated
07-07 20:28:07.611   787   892 D wifi    : In wifi cleaned up handler
07-07 20:28:07.611   787   892 I WifiHAL : Internal cleanup completed
07-07 20:28:07.612  3778  3778 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:28:07.614  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:07.719  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-07 20:28:07.719  3618  3685 I jxcore-log: 
,07-07 20:28:07.721   787  3938 D wifi    : set interface wlan0 flags (DOWN)
07-07 20:28:07.721   787   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-07 20:28:07.725  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-07 20:28:07.725  3618  3685 I jxcore-log: 
,07-07 20:28:07.759  3618  3685 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-07 20:28:07.759  3618  3685 I jxcore-log: 
,07-07 20:28:07.768  3618  3685 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-07 20:28:07.769  3618  3685 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-07 20:28:07.769  3618  3685 I jxcore-log: 
,07-07 20:28:07.813  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:28:07.813  3618  3685 I jxcore-log: 
,07-07 20:28:07.813  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:28:07.813  3618  3685 I jxcore-log: 
07-07 20:28:07.814  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:28:07.814  3618  3685 I jxcore-log: 
07-07 20:28:07.814  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:28:07.814  3618  3685 I jxcore-log: 
,07-07 20:28:07.816  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:28:07.816  3618  3685 I jxcore-log: 
07-07 20:28:07.817  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:28:07.817  3618  3685 I jxcore-log: 
,07-07 20:28:07.818  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:28:07.818  3618  3685 I jxcore-log: 
,07-07 20:28:07.818  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:28:07.818  3618  3685 I jxcore-log: 
,07-07 20:28:07.923   787   805 D Tethering: InitialState.processMessage what=4
,07-07 20:28:07.924   787   805 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-07 20:28:09.227   787   805 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ecf0b4:true
,07-07 20:28:09.228  3764  3764 D BluetoothAdapterState: make() - Creating AdapterState
07-07 20:28:09.238  3764  3764 I bt_bluedroid: init
07-07 20:28:09.238  3764  3976 I BluetoothAdapterState: Entering OffState
07-07 20:28:09.241  3764  3977 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-07 20:28:09.241  3764  3977 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-07 20:28:09.241  3764  3977 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-07 20:28:09.241  3764  3977 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-07 20:28:09.241  3764  3764 I bt_bluedroid: get_profile_interface socket
07-07 20:28:09.242  3764  3764 I bt_bluedroid: get_profile_interface sdp
07-07 20:28:09.244  3764  3775 I bt_bluedroid: config_hci_snoop_log
07-07 20:28:09.244   787   805 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-07 20:28:09.247  3764  3976 D BluetoothAdapterState: Current state: OFF, message: 0
07-07 20:28:09.247  3764  3976 D BluetoothAdapterProperties: Setting state to 14
07-07 20:28:09.247  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-07 20:28:09.247  3764  3976 D BluetoothBondStateMachine: make
07-07 20:28:09.249  3764  3980 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-07 20:28:09.250  3764  3980 D BluetoothAdapterProperties: Name is: Nexus 5
07-07 20:28:09.253  3764  3764 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-07 20:28:09.254  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:09.255  3764  3976 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:28:09.255  3764  3764 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:28:09.255  3764  3764 D BtGatt.GattService: Received start request. Starting profile...
07-07 20:28:09.255  3764  3764 D BtGatt.GattService: start()
07-07 20:28:09.255  3764  3764 I bt_bluedroid: get_profile_interface gatt
07-07 20:28:09.256  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:09.256  3764  3764 D BtGatt.AdvertiseManager: advertise manager created
07-07 20:28:09.256  3764  3981 I BluetoothBondStateMachine: StableState(): Entering Off State
07-07 20:28:09.259  3764  3764 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:09.259  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:09.259  3764  3764 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:28:09.259  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:09.259  3764  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-07 20:28:09.260  3764  3976 I bt_bluedroid: enable
07-07 20:28:09.260  3764  3977 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-07 20:28:09.260  3764  3977 I bt_hci  : start_up
07-07 20:28:09.264  3764  3977 I bt_vendor: alloc value 0xb39f9631
07-07 20:28:09.264  3764  3977 I bt_vendor: init
07-07 20:28:09.264  3764  3977 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-07 20:28:09.264  3764  3977 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-07 20:28:09.296  3764  3977 D bt_hci  : start_up starting async portion
,07-07 20:28:09.297  3764  3984 I bt_hci  : event_finish_startup
07-07 20:28:09.297  3764  3984 I bt_hci_h4: hal_open
07-07 20:28:09.297  3764  3984 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-07 20:28:09.300  3764  3984 I bt_userial_vendor: device fd = 49 open
,07-07 20:28:09.386  3764  3984 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-07 20:28:09.413  3764  3984 D bt_hwcfg: Chipset BCM4335C0
,07-07 20:28:09.413  3764  3984 D bt_hwcfg: Target name = [BCM4335C0]
07-07 20:28:09.413  3764  3984 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-07 20:28:09.799  3764  3984 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-07 20:28:09.800  3764  3984 D bt_hwcfg: Settlement delay -- 100 ms
07-07 20:28:09.800  3764  3984 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:28:09.916  3764  3984 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-07 20:28:09.917  3764  3984 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-07 20:28:09.945  3764  3984 I bt_hwcfg: vendor lib fwcfg completed
,07-07 20:28:09.945  3764  3984 I bt_vendor: firmware callback
,07-07 20:28:09.945  3764  3984 I bt_hci  : firmware_config_callback
07-07 20:28:09.957  3764  3998 I bt_btu  : btu_task pending for preload complete event
07-07 20:28:09.957  3764  3998 I bt_btu_task: Bluetooth chip preload is complete
07-07 20:28:09.957  3764  3998 I bt_btu  : btu_task received preload complete event
07-07 20:28:09.968  3764  3998 I         : BTE_InitTraceLevels -- TRC_HCI
07-07 20:28:09.968  3764  3998 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-07 20:28:09.968  3764  3998 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-07 20:28:09.968  3764  3998 I         : BTE_InitTraceLevels -- TRC_AVDT
07-07 20:28:09.968  3764  3998 I         : BTE_InitTraceLevels -- TRC_AVRC
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_A2D
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_BNEP
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_BTM
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_GAP
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_PAN
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_SDP
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_GATT
07-07 20:28:09.969  3764  3998 I         : BTE_InitTraceLevels -- TRC_SMP
07-07 20:28:09.970  3764  3998 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-07 20:28:09.970  3764  3998 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:28:10.193  3764  3998 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39779b5
,07-07 20:28:10.193  3764  3998 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39779b5 
,07-07 20:28:10.286  3764  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-07 20:28:10.286  3764  3980 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-07 20:28:10.306  3764  3980 D BluetoothAdapterProperties: Name is: Nexus 5
07-07 20:28:10.308  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:10.308  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:10.308  3764  3980 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:28:10.308  3764  3980 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:28:10.308  3764  3980 D bt_hci  : do_postload posting postload work item
07-07 20:28:10.309  3764  3984 I bt_hci  : event_postload
07-07 20:28:10.309  3764  3984 I bt_vendor: sco_config_cb
07-07 20:28:10.309  3764  3984 I bt_hci  : sco_config_callback postload finished.
07-07 20:28:10.326  3764  3984 I bt_vendor: low_power_mode_cb
,07-07 20:28:10.327  3764  3980 D bt_bte_conf: Device ID record 1 : primary
,07-07 20:28:10.327  3764  3980 D bt_bte_conf:   vendorId            = 000f
07-07 20:28:10.327  3764  3980 D bt_bte_conf:   vendorIdSource      = 0001
07-07 20:28:10.327  3764  3980 D bt_bte_conf:   product             = 1200
07-07 20:28:10.327  3764  3980 D bt_bte_conf:   version             = 1436
07-07 20:28:10.327  3764  3980 D bt_bte_conf:   clientExecutableURL = 
07-07 20:28:10.327  3764  3980 D bt_bte_conf:   serviceDescription  = 
,07-07 20:28:10.327  3764  3980 D bt_bte_conf:   documentationURL    = 
07-07 20:28:10.349  3764  3980 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-07 20:28:10.349  3764  3977 D bt_stack_manager: event_start_up_stack finished
07-07 20:28:10.351  3764  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-07 20:28:10.351  3764  3976 D BluetoothAdapterProperties: Setting state to 15
07-07 20:28:10.351  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-07 20:28:10.352  3764  3976 I BluetoothAdapterState: Entering BleOnState
07-07 20:28:10.353  3764  3976 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-07 20:28:10.353  3764  3976 D BluetoothAdapterProperties: Setting state to 11
07-07 20:28:10.353  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-07 20:28:10.356  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:10.357  3764  3764 D HeadsetService: Received start request. Starting profile...
07-07 20:28:10.359  3764  3764 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-07 20:28:10.359  3764  3764 D HeadsetStateMachine: make
07-07 20:28:10.365  3764  3764 D HeadsetStateMachine: max_hf_connections = 1
07-07 20:28:10.365  3764  3764 I bt_bluedroid: get_profile_interface handsfree
07-07 20:28:10.365  3764  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-07 20:28:10.366  3764  3980 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-07 20:28:10.368  3764  3976 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:28:10.369  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
,07-07 20:28:10.369  3764  3764 D A2dpService: Received start request. Starting profile...
07-07 20:28:10.369  3764  3764 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-07 20:28:10.370  3764  3764 I bt_bluedroid: get_profile_interface avrcp
,07-07 20:28:10.374  3764  3764 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-07 20:28:10.374  3764  3764 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-07 20:28:10.374  3764  3764 D A2dpStateMachine: make
07-07 20:28:10.375  3764  3764 I bt_bluedroid: get_profile_interface a2dp
07-07 20:28:10.375  3764  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-07 20:28:10.377  3764  3764 I BluetoothHidServiceJni: classInitNative: succeeds
,07-07 20:28:10.377  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:10.378  3764  4021 D A2dpStateMachine: Enter Disconnected: -2
07-07 20:28:10.378  3764  3764 D HidService: Received start request. Starting profile...
07-07 20:28:10.378  3764  3764 I bt_bluedroid: get_profile_interface hidhost
07-07 20:28:10.378  3764  3764 D HidService: setHidService(): set to: null
07-07 20:28:10.378  3764  3980 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3959099
07-07 20:28:10.379  3764  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-07 20:28:10.380  3764  3764 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-07 20:28:10.380  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:10.380  3764  3764 D HealthService: Received start request. Starting profile...
07-07 20:28:10.384  3764  3764 I bt_bluedroid: get_profile_interface health
07-07 20:28:10.385  3764  3764 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-07 20:28:10.385  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:10.386  3688  3688 D BluetoothInputDevice: Proxy object connected
07-07 20:28:10.386  3764  3764 D PanService: Received start request. Starting profile...
07-07 20:28:10.386  3688  3688 D HidProfile: Bluetooth service connected
07-07 20:28:10.386  3764  3764 D BluetoothPanServiceJni: initializeNative(L110): pan
07-07 20:28:10.386  3764  3764 I bt_bluedroid: get_profile_interface pan
07-07 20:28:10.387  3764  3980 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:28:10.388  3764  3764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
,07-07 20:28:10.388  3764  4017 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-07 20:28:10.389  3764  3764 D BluetoothMapService: Received start request. Starting profile...
07-07 20:28:10.389  3764  3764 D BluetoothMapService: start()
07-07 20:28:10.391  3764  3764 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-07 20:28:10.391  3764  3764 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-07 20:28:10.391  3764  3764 D BluetoothMapAppObserver: createReceiver()
07-07 20:28:10.392  3764  3764 D BluetoothMapAppObserver: initObservers()
07-07 20:28:10.392  3764  3764 D BluetoothMapAppObserver: getEnabledAccountItems()
07-07 20:28:10.392  3688  3688 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:28:10.393  3688  3688 D PanProfile: Bluetooth service connected
,07-07 20:28:10.393  3688  3688 D BluetoothMap: Proxy object connected
07-07 20:28:10.393  3688  3688 D MapProfile: Bluetooth service connected
07-07 20:28:10.393  3688  3688 D BluetoothMap: getConnectedDevices()
07-07 20:28:10.393  3688  3688 D BluetoothMap: Bluetooth is Not enabled
,07-07 20:28:10.396  3764  3764 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:10.396  3764  3764 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:10.396  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:10.396  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:10.397  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:10.398  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:10.399  3764  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-07 20:28:10.399  3764  3976 D BluetoothAdapterProperties: ScanMode =  20
07-07 20:28:10.399  3764  3976 D BluetoothAdapterProperties: State =  11
,07-07 20:28:10.399  3764  3976 D BluetoothAdapterProperties: Setting state to 12
07-07 20:28:10.399  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:28:10.402  3764  3976 I BluetoothAdapterState: Entering OnState
,07-07 20:28:10.402  3688  3698 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:28:10.403  3764  3980 D BluetoothAdapterProperties: Scan Mode:21
07-07 20:28:10.403  3764  3980 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:28:10.403   941  1357 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:28:10.404   941   941 D BluetoothMap: Proxy object connected
,07-07 20:28:10.404   941   941 D MapProfile: Bluetooth service connected
07-07 20:28:10.404   941   941 D BluetoothMap: getConnectedDevices()
07-07 20:28:10.405   941   955 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:10.406  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:10.407   787   805 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:28:10.408   941  1358 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:28:10.408   941   941 D BluetoothInputDevice: Proxy object connected
07-07 20:28:10.408   941   941 D HidProfile: Bluetooth service connected
,07-07 20:28:10.410  1299  1312 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:28:10.410  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:10.411   941   941 D BluetoothA2dp: Proxy object connected
07-07 20:28:10.411  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:28:10.411  3618  3685 I jxcore-log: 
07-07 20:28:10.411  3688  3708 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:28:10.413  3688  3698 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:28:10.413   787   805 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:28:10.413   787   787 D BluetoothA2dp: Proxy object connected
,07-07 20:28:10.413   941   954 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:10.414  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:10.415   941   941 D BluetoothPan: BluetoothPAN Proxy object connected
,07-07 20:28:10.415   941   941 D PanProfile: Bluetooth service connected
07-07 20:28:10.415   941  1357 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:28:10.416  3688  3708 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:28:10.416  3764  3764 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-07 20:28:10.417  3764  3764 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-07 20:28:10.417   787   805 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:10.418  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:10.418  3764  3764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-07 20:28:10.418   941  1358 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:10.418   787   805 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:10.420  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:28:10.420  3618  3685 I jxcore-log: 
07-07 20:28:10.421   787   787 I Telecom : BluetoothPhoneService: queryPhoneState
07-07 20:28:10.421  3764  3764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-07 20:28:10.422  3688  3688 D LocalBluetoothProfileManager: Adding local A2DP profile
07-07 20:28:10.423  3764  3764 D ObexServerSockets: Succeed to create listening sockets 
07-07 20:28:10.423  3764  3764 D ObexServerSockets0: startAccept()
,07-07 20:28:10.423  3764  3764 D ObexServerSockets0: prepareForNewConnect()
07-07 20:28:10.424  3764  3764 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-07 20:28:10.424  3764  3764 D BluetoothSdpJni: SDP Create record success - handle: 0
07-07 20:28:10.425  3764  3764 D BluetoothMapService: onReceive
07-07 20:28:10.425  3764  3764 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:28:10.425  3764  3764 D BluetoothMapService: STATE_ON
07-07 20:28:10.425  3688  3688 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-07 20:28:10.425  3764  4033 D ObexServerSockets0: Accepting socket connection...
07-07 20:28:10.425  3764  4034 D ObexServerSockets0: Accepting socket connection...
07-07 20:28:10.430  3688  3688 D BluetoothA2dp: Proxy object connected
,07-07 20:28:10.445  3764  3764 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-07 20:28:10.445  3764  3764 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:28:10.454  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:10.459  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:10.461  3688  3688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:28:10.465  3688  3688 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:28:10.471  3688  3688 D BluetoothPbap: Proxy object connected
,07-07 20:28:10.471   941   941 D BluetoothPbap: Proxy object connected
07-07 20:28:10.471   941   941 D PbapServerProfile: Bluetooth service connected
07-07 20:28:10.472  3688  3688 D PbapServerProfile: Bluetooth service connected
,07-07 20:28:10.477  3764  4043 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:28:10.480  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:10.483  1729  4044 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:28:10.485  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:10.494  3764  4048 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:28:10.496  3764  4048 I BtOppRfcommListener: Accept thread started.
,07-07 20:28:10.498  1729  4044 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-07 20:28:10.509   787   787 D BluetoothHeadset: Proxy object connected
,07-07 20:28:10.509  1299  1726 D BluetoothHeadset: Proxy object connected
07-07 20:28:10.509   787   787 D BluetoothHeadset: Proxy object connected
07-07 20:28:10.509   941   955 D BluetoothHeadset: Proxy object connected
07-07 20:28:10.509   941   941 D HeadsetProfile: Bluetooth service connected
07-07 20:28:10.509   787   787 D BluetoothHeadset: Proxy object connected
,07-07 20:28:10.511  1299  1429 D BluetoothHeadset: Proxy object connected
,07-07 20:28:10.518   787   805 D BluetoothHeadset: Proxy object connected
,07-07 20:28:10.519   941  1357 D BluetoothHeadset: Proxy object connected
,07-07 20:28:10.519   941   941 D HeadsetProfile: Bluetooth service connected
07-07 20:28:10.519   787   805 D BluetoothHeadset: Proxy object connected
,07-07 20:28:10.528  3688  3698 D BluetoothHeadset: Proxy object connected
07-07 20:28:10.528  3688  3688 D HeadsetProfile: Bluetooth service connected
,07-07 20:28:12.179  3764  3976 D BluetoothAdapterState: Current state: ON, message: 23
07-07 20:28:12.179  3764  3976 D BluetoothAdapterProperties: Setting state to 13
07-07 20:28:12.179  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:28:12.179  3764  3976 D BluetoothAdapterProperties: onBluetoothDisable()
07-07 20:28:12.183  3764  3764 D BluetoothMapService: onReceive
07-07 20:28:12.183  3764  3764 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:28:12.183  3764  3764 D BluetoothMapService: STATE_TURNING_OFF
07-07 20:28:12.183  3764  3764 D BluetoothMapService: MAP Service closeService in
07-07 20:28:12.183  3764  3764 D BluetoothMapMasInstance0: MAP Service shutdown
07-07 20:28:12.183  3764  3764 D ObexServerSockets0: shutdown(block = true)
07-07 20:28:12.183  3764  3764 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:28:12.183  3764  3764 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:28:12.184  3764  4033 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-07 20:28:12.184  3764  4001 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-07 20:28:12.184  3764  4034 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-07 20:28:12.185  3764  3976 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:28:12.189  3764  3764 I BtOppRfcommListener: stopping Accept Thread
,07-07 20:28:12.189  3764  4048 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-07 20:28:12.189  3764  4048 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-07 20:28:12.193  3764  3980 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:28:12.193  3764  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:12.196  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:12.196  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:12.197  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:12.198  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:12.199  3764  3764 D HeadsetService: Received stop request...Stopping profile...
07-07 20:28:12.200   787   787 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:12.200  1299  1322 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:12.200   787   787 D BluetoothHeadset: Proxy object disconnected
,07-07 20:28:12.200  3688  3698 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:12.201   941  1358 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:12.201   941   941 D HeadsetProfile: Bluetooth service disconnected
07-07 20:28:12.201   787   787 D BluetoothHeadset: Proxy object disconnected
07-07 20:28:12.205  3764  3764 D A2dpService: Received stop request...Stopping profile...
,07-07 20:28:12.205  3764  4021 D A2dpStateMachine: Exit Disconnected: -1
07-07 20:28:12.206   941   941 D BluetoothA2dp: Proxy object disconnected
07-07 20:28:12.207   787   787 D BluetoothA2dp: Proxy object disconnected
,07-07 20:28:12.207  3764  3764 D HidService: Received stop request...Stopping profile...
07-07 20:28:12.207  3764  3764 D HidService: Stopping Bluetooth HidService
07-07 20:28:12.208   941   941 D BluetoothInputDevice: Proxy object disconnected
,07-07 20:28:12.208   941   941 D HidProfile: Bluetooth service disconnected
07-07 20:28:12.208  3764  3764 D HealthService: Received stop request...Stopping profile...
07-07 20:28:12.209  3764  3764 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:12.209  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:12.209  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:12.209  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:12.210  3764  3764 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-07 20:28:12.210  3764  3998 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:12.210  3764  3998 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:12.211  3764  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-07 20:28:12.211  3764  3980 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-07 20:28:12.243  3764  3764 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-07 20:28:12.244  3764  3764 D PanService: Received stop request...Stopping profile...
,07-07 20:28:12.245   941   941 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:28:12.245   941   941 D PanProfile: Bluetooth service disconnected
07-07 20:28:12.246  3764  3764 D BluetoothMapService: Received stop request...Stopping profile...
07-07 20:28:12.246  3764  3764 D BluetoothMapService: stop()
07-07 20:28:12.246  3764  3764 D BluetoothMapAppObserver: deinitObservers()
07-07 20:28:12.247  3764  3764 D BluetoothMapAppObserver: removeReceiver()
07-07 20:28:12.248   941   941 D BluetoothMap: Proxy object disconnected
07-07 20:28:12.248   941   941 D MapProfile: Bluetooth service disconnected
07-07 20:28:12.249  3764  3764 V BluetoothAdapterState: isTurningOff()=true
,07-07 20:28:12.249  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:12.249  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:12.249  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:12.250  3764  3998 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:12.250  3764  3998 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:12.250  3764  3998 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:28:12.250  3764  3998 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:28:12.250  3764  3998 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-07 20:28:12.250  3764  3998 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:28:12.250  3764  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-07 20:28:12.273  3764  3764 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:12.273  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:12.273  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:12.273  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:12.274  3764  3764 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-07 20:28:12.274  3764  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:28:12.274  3764  3764 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:28:12.274  3764  3764 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:12.274  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:12.274  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:12.274  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:12.275  3764  3764 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:28:12.275  3764  3980 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-07 20:28:12.276  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:28:12.276  3618  3685 I jxcore-log: 
,07-07 20:28:12.277  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:28:12.277  3618  3685 I jxcore-log: 
07-07 20:28:12.277  3764  3764 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:28:12.278  3764  3764 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:12.278  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:12.278  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:28:12.278  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:12.278  3764  3764 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-07 20:28:12.306  3764  3764 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-07 20:28:12.312  3688  3688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:28:12.315  3764  3764 D BluetoothMapService: MAP Service closeService in
07-07 20:28:12.315  3764  3764 V BluetoothAdapterState: isTurningOff()=true
07-07 20:28:12.315  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:12.315  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:12.315  3764  3764 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:12.315  3764  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-07 20:28:12.315  3764  3976 D BluetoothAdapterProperties: Setting state to 15
07-07 20:28:12.315  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:28:12.315  3764  3976 I BluetoothAdapterState: Entering BleOnState
07-07 20:28:12.315  3764  3764 D BluetoothMapService: cleanup()
07-07 20:28:12.315  3764  3764 D BluetoothMapService: MAP Service closeService in
07-07 20:28:12.317  3688  3698 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-07 20:28:12.318   941  1358 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:28:12.319   941   955 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:28:12.320   787   805 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-07 20:28:12.320   941   954 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-07 20:28:12.320  3688  3688 D HeadsetProfile: Bluetooth service disconnected
07-07 20:28:12.326  1299  1312 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:12.326  3688  3698 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:28:12.326  3688  3688 D BluetoothA2dp: Proxy object disconnected
07-07 20:28:12.327  3688  3708 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:12.328  3688  3708 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:28:12.329  3688  3688 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:28:12.329   787   805 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:28:12.329   941  1358 D BluetoothPan: onBluetoothStateChange on: false
,07-07 20:28:12.329  3688  3688 D PanProfile: Bluetooth service disconnected
,07-07 20:28:12.329   941   941 D BluetoothPbap: Proxy object disconnected
07-07 20:28:12.329   941   941 D PbapServerProfile: Bluetooth service disconnected
07-07 20:28:12.329   941  1358 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:28:12.329  3688  3688 D BluetoothMap: Proxy object disconnected
07-07 20:28:12.330  3688  3688 D MapProfile: Bluetooth service disconnected
07-07 20:28:12.330  3688  3708 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:28:12.331  3688  3708 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:28:12.331   787   805 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:12.331   941  1357 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:12.331   787   805 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:28:12.331  3764  3976 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-07 20:28:12.331  3764  3976 D BluetoothAdapterProperties: Setting state to 16
07-07 20:28:12.332  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-07 20:28:12.332  3764  3976 D BluetoothAdapterProperties: onBleDisable
07-07 20:28:12.332  3764  3976 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:28:12.332  3764  3977 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:28:12.334  3764  3980 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:28:12.335  3764  3998 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-07 20:28:12.335  3764  3998 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:28:12.337  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:12.339  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:12.340  3688  3688 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:28:12.391  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:12.395  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:12.397  3688  3688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:28:12.403  3688  3688 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:28:12.414  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:12.418  1729  4088 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:28:12.419  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:12.426  1729  4088 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-07 20:28:12.439  3764  3980 I bt_hci  : shut_down
,07-07 20:28:12.439  3764  3984 D bt_hwcfg: hw_epilog_process
,07-07 20:28:12.442  3764  3984 I bt_vendor: low_power_mode_cb
,07-07 20:28:12.458  3764  3984 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-07 20:28:12.458  3764  3984 I bt_vendor: epilog_cb
07-07 20:28:12.458  3764  3984 I bt_hci  : epilog_finished_callback
07-07 20:28:12.460  3764  3980 I bt_hci_h4: hal_close
07-07 20:28:12.460  3764  3980 I bt_userial_vendor: device fd = 49 close
07-07 20:28:12.464  3764  3977 D bt_stack_manager: event_shut_down_stack finished.
07-07 20:28:12.464  3764  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-07 20:28:12.466  3764  3764 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:28:12.466  3764  3976 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-07 20:28:12.466  3764  3764 D BtGatt.GattService: Received stop request...Stopping profile...
07-07 20:28:12.466  3764  3764 D BtGatt.GattService: stop()
07-07 20:28:12.466  3764  3764 D BtGatt.AdvertiseManager: advertise clients cleared
07-07 20:28:12.467  3764  3764 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:12.467  3764  3764 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:12.467  3764  3764 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:12.467  3764  3764 V BluetoothAdapterState: isBleTurningOff()=true
07-07 20:28:12.467  3764  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-07 20:28:12.467  3764  3976 D BluetoothAdapterProperties: Setting state to 10
07-07 20:28:12.467  3764  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-07 20:28:12.468  3764  3976 I BluetoothAdapterState: Entering OffState
07-07 20:28:12.468   787   805 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-07 20:28:12.472  3764  3764 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-07 20:28:12.472  3764  3764 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-07 20:28:12.472  3764  3764 I BluetoothServiceJni: cleanupNative: return from cleanup
07-07 20:28:12.472  3764  3977 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-07 20:28:12.475  3764  3977 D bt_stack_manager: event_clean_up_stack finished.
07-07 20:28:12.475  3764  3764 I art     : System.exit called, status: 0
07-07 20:28:12.475  3764  3764 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-07 20:28:12.556   787  1317 I ActivityManager: Process com.android.bluetooth (pid 3764) has died
,07-07 20:28:15.179  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:28:15.180  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:28:15.186  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:28:15.188  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@894b4c added. We now have 6 listener(s)
07-07 20:28:15.188  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:15.191  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:15.191  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@82e6795 added. We now have 7 listener(s)
,07-07 20:28:15.191  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:15.195  3618  3678 I System.out: IsBluetoothEnabled
,07-07 20:28:15.211  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:15.247   787   805 I ActivityManager: Start proc 4101:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-07 20:28:15.313  4101  4101 D AdapterServiceConfig: Adding HeadsetService
,07-07 20:28:15.313  4101  4101 D AdapterServiceConfig: Adding A2dpService
07-07 20:28:15.314  4101  4101 D AdapterServiceConfig: Adding HidService
07-07 20:28:15.314  4101  4101 D AdapterServiceConfig: Adding HealthService
07-07 20:28:15.314  4101  4101 D AdapterServiceConfig: Adding PanService
07-07 20:28:15.314  4101  4101 D AdapterServiceConfig: Adding GattService
07-07 20:28:15.315  4101  4101 D AdapterServiceConfig: Adding BluetoothMapService
,07-07 20:28:15.324   787   805 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c7e25e:true
,07-07 20:28:15.324  4101  4101 D BluetoothAdapterState: make() - Creating AdapterState
,07-07 20:28:15.327  4101  4101 I bt_bluedroid: init
07-07 20:28:15.327  4101  4125 I BluetoothAdapterState: Entering OffState
,07-07 20:28:15.328  4101  4126 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-07 20:28:15.328  4101  4126 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-07 20:28:15.328  4101  4126 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-07 20:28:15.328  4101  4126 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-07 20:28:15.329  4101  4101 I bt_bluedroid: get_profile_interface socket
,07-07 20:28:15.330  4101  4101 I bt_bluedroid: get_profile_interface sdp
,07-07 20:28:15.331  4101  4130 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-07 20:28:15.332  4101  4130 D BluetoothAdapterProperties: Name is: Nexus 5
07-07 20:28:15.332  4101  4111 I bt_bluedroid: config_hci_snoop_log
07-07 20:28:15.333   787   805 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-07 20:28:15.335  4101  4125 D BluetoothAdapterState: Current state: OFF, message: 0
,07-07 20:28:15.335  4101  4125 D BluetoothAdapterProperties: Setting state to 14
07-07 20:28:15.335  4101  4125 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-07 20:28:15.336  4101  4125 D BluetoothBondStateMachine: make
07-07 20:28:15.337  4101  4135 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-07 20:28:15.340  4101  4125 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:28:15.340  4101  4101 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-07 20:28:15.342  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
,07-07 20:28:15.342  4101  4101 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:28:15.343  4101  4101 D BtGatt.GattService: Received start request. Starting profile...
07-07 20:28:15.343  4101  4101 D BtGatt.GattService: start()
,07-07 20:28:15.343  4101  4101 I bt_bluedroid: get_profile_interface gatt
07-07 20:28:15.343  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:15.343  4101  4101 D BtGatt.AdvertiseManager: advertise manager created
,07-07 20:28:15.347  4101  4101 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:15.347  4101  4101 V BluetoothAdapterState: isTurningOn()=false
07-07 20:28:15.347  4101  4101 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:28:15.347  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:15.347  4101  4125 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-07 20:28:15.347  4101  4125 I bt_bluedroid: enable
07-07 20:28:15.347  4101  4126 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-07 20:28:15.347  4101  4126 I bt_hci  : start_up
,07-07 20:28:15.352  4101  4126 I bt_vendor: alloc value 0xb3a5b631
,07-07 20:28:15.352  4101  4126 I bt_vendor: init
07-07 20:28:15.352  4101  4126 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-07 20:28:15.352  4101  4126 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-07 20:28:15.387  4101  4126 D bt_hci  : start_up starting async portion
,07-07 20:28:15.387  4101  4139 I bt_hci  : event_finish_startup
07-07 20:28:15.387  4101  4139 I bt_hci_h4: hal_open
07-07 20:28:15.387  4101  4139 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-07 20:28:15.390  4101  4139 I bt_userial_vendor: device fd = 49 open
,07-07 20:28:15.476  4101  4139 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-07 20:28:15.503  4101  4139 D bt_hwcfg: Chipset BCM4335C0
,07-07 20:28:15.503  4101  4139 D bt_hwcfg: Target name = [BCM4335C0]
07-07 20:28:15.503  4101  4139 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-07 20:28:15.901  4101  4139 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-07 20:28:15.901  4101  4139 D bt_hwcfg: Settlement delay -- 100 ms
07-07 20:28:15.901  4101  4139 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:28:16.017  4101  4139 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-07 20:28:16.018  4101  4139 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-07 20:28:16.050  4101  4139 I bt_hwcfg: vendor lib fwcfg completed
,07-07 20:28:16.050  4101  4139 I bt_vendor: firmware callback
,07-07 20:28:16.050  4101  4139 I bt_hci  : firmware_config_callback
,07-07 20:28:16.060  4101  4152 I bt_btu  : btu_task pending for preload complete event
,07-07 20:28:16.060  4101  4152 I bt_btu_task: Bluetooth chip preload is complete
,07-07 20:28:16.060  4101  4152 I bt_btu  : btu_task received preload complete event
,07-07 20:28:16.071  4101  4152 I         : BTE_InitTraceLevels -- TRC_HCI
,07-07 20:28:16.071  4101  4152 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-07 20:28:16.071  4101  4152 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-07 20:28:16.071  4101  4152 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_A2D
,07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_BTM
,07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_GAP
07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_PAN
07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_SDP
07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_GATT
07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_SMP
07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-07 20:28:16.072  4101  4152 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:28:16.295  4101  4152 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d99b5
,07-07 20:28:16.295  4101  4152 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d99b5 
,07-07 20:28:16.377  4101  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:28:16.378  4101  4130 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-07 20:28:16.406  4101  4130 D BluetoothAdapterProperties: Name is: Nexus 5
07-07 20:28:16.408  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:16.408  4101  4130 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:28:16.408  4101  4130 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:28:16.408  4101  4130 D bt_hci  : do_postload posting postload work item
07-07 20:28:16.408  4101  4139 I bt_hci  : event_postload
07-07 20:28:16.408  4101  4139 I bt_vendor: sco_config_cb
07-07 20:28:16.408  4101  4139 I bt_hci  : sco_config_callback postload finished.
07-07 20:28:16.426  4101  4139 I bt_vendor: low_power_mode_cb
,07-07 20:28:16.427  4101  4130 D bt_bte_conf: Device ID record 1 : primary
07-07 20:28:16.427  4101  4130 D bt_bte_conf:   vendorId            = 000f
07-07 20:28:16.427  4101  4130 D bt_bte_conf:   vendorIdSource      = 0001
07-07 20:28:16.427  4101  4130 D bt_bte_conf:   product             = 1200
,07-07 20:28:16.427  4101  4130 D bt_bte_conf:   version             = 1436
07-07 20:28:16.427  4101  4130 D bt_bte_conf:   clientExecutableURL = 
07-07 20:28:16.427  4101  4130 D bt_bte_conf:   serviceDescription  = 
07-07 20:28:16.427  4101  4130 D bt_bte_conf:   documentationURL    = 
07-07 20:28:16.446  4101  4130 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-07 20:28:16.446  4101  4126 D bt_stack_manager: event_start_up_stack finished
07-07 20:28:16.447  4101  4125 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-07 20:28:16.447  4101  4125 D BluetoothAdapterProperties: Setting state to 15
,07-07 20:28:16.447  4101  4125 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-07 20:28:16.448  4101  4125 I BluetoothAdapterState: Entering BleOnState
07-07 20:28:16.448  4101  4125 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-07 20:28:16.448  4101  4125 D BluetoothAdapterProperties: Setting state to 11
07-07 20:28:16.448  4101  4125 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-07 20:28:16.450  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:16.460  4101  4101 D HeadsetService: Received start request. Starting profile...
07-07 20:28:16.461  4101  4101 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-07 20:28:16.462  4101  4101 D HeadsetStateMachine: make
,07-07 20:28:16.465  4101  4125 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:28:16.473  4101  4101 D HeadsetStateMachine: max_hf_connections = 1
07-07 20:28:16.473  4101  4101 I bt_bluedroid: get_profile_interface handsfree
07-07 20:28:16.496  4101  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-07 20:28:16.496  4101  4130 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-07 20:28:16.527  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:16.529  4101  4101 D A2dpService: Received start request. Starting profile...
07-07 20:28:16.530  4101  4101 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-07 20:28:16.531  4101  4101 I bt_bluedroid: get_profile_interface avrcp
,07-07 20:28:16.539  4101  4101 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-07 20:28:16.539  4101  4101 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-07 20:28:16.539  4101  4101 D A2dpStateMachine: make
07-07 20:28:16.540  4101  4101 I bt_bluedroid: get_profile_interface a2dp
07-07 20:28:16.541  4101  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-07 20:28:16.544  4101  4167 D A2dpStateMachine: Enter Disconnected: -2
,07-07 20:28:16.544  4101  4101 I BluetoothHidServiceJni: classInitNative: succeeds
,07-07 20:28:16.545  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:16.545  4101  4101 D HidService: Received start request. Starting profile...
07-07 20:28:16.545  4101  4101 I bt_bluedroid: get_profile_interface hidhost
07-07 20:28:16.546  4101  4130 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb099
07-07 20:28:16.546  4101  4130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-07 20:28:16.546  4101  4101 D HidService: setHidService(): set to: null
07-07 20:28:16.546  4101  4101 I BluetoothHealthServiceJni: classInitNative: succeeds
07-07 20:28:16.547  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:16.547  4101  4101 D HealthService: Received start request. Starting profile...
,07-07 20:28:16.549  4101  4101 I bt_bluedroid: get_profile_interface health
07-07 20:28:16.550  4101  4101 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-07 20:28:16.550  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:16.551  4101  4101 D PanService: Received start request. Starting profile...
07-07 20:28:16.551  4101  4101 D BluetoothPanServiceJni: initializeNative(L110): pan
07-07 20:28:16.551  4101  4101 I bt_bluedroid: get_profile_interface pan
07-07 20:28:16.551  4101  4130 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:28:16.558  4101  4101 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4609335
07-07 20:28:16.559  4101  4101 D BluetoothMapService: Received start request. Starting profile...
07-07 20:28:16.559  4101  4101 D BluetoothMapService: start()
,07-07 20:28:16.561  4101  4101 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-07 20:28:16.562  4101  4101 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-07 20:28:16.562  4101  4101 D BluetoothMapAppObserver: createReceiver()
07-07 20:28:16.563  4101  4101 D BluetoothMapAppObserver: initObservers()
07-07 20:28:16.563  4101  4101 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-07 20:28:16.571  4101  4101 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:16.571  4101  4101 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:16.571  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:16.571  4101  4159 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-07 20:28:16.571  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:16.574  4101  4101 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:16.575  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:16.575  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:16.575  4101  4101 V BluetoothAdapterState: isTurningOff()=false
07-07 20:28:16.575  4101  4101 V BluetoothAdapterState: isTurningOn()=true
07-07 20:28:16.575  4101  4101 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:28:16.575  4101  4101 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:28:16.575  4101  4125 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-07 20:28:16.575  4101  4125 D BluetoothAdapterProperties: ScanMode =  20
07-07 20:28:16.575  4101  4125 D BluetoothAdapterProperties: State =  11
07-07 20:28:16.575  4101  4125 D BluetoothAdapterProperties: Setting state to 12
,07-07 20:28:16.575  4101  4125 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:28:16.576  3688  3698 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:28:16.576  4101  4125 I BluetoothAdapterState: Entering OnState
07-07 20:28:16.576  4101  4130 D BluetoothAdapterProperties: Scan Mode:21
07-07 20:28:16.577  4101  4130 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:28:16.578   941  1358 D BluetoothMap: onBluetoothStateChange: up=true
,07-07 20:28:16.580   941   941 D BluetoothMap: Proxy object connected
07-07 20:28:16.580   941   941 D MapProfile: Bluetooth service connected
07-07 20:28:16.580   941   941 D BluetoothMap: getConnectedDevices()
07-07 20:28:16.580   941  1357 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-07 20:28:16.582   787   805 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:16.582   941  1358 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:16.583  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:16.584   941   941 D BluetoothInputDevice: Proxy object connected
07-07 20:28:16.584   941   941 D HidProfile: Bluetooth service connected
,07-07 20:28:16.585  1299  1312 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:16.586  3688  3698 D BluetoothPbap: onBluetoothStateChange: up=true
,07-07 20:28:16.588  3688  3708 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:28:16.588   941   941 D BluetoothA2dp: Proxy object connected
07-07 20:28:16.589  3688  3698 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:28:16.589  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:16.590  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:28:16.590  3618  3685 I jxcore-log: 
,07-07 20:28:16.591  4101  4101 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-07 20:28:16.591  4101  4101 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-07 20:28:16.592  4101  4101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-07 20:28:16.593  3688  3688 D BluetoothInputDevice: Proxy object connected
07-07 20:28:16.593  3688  3688 D HidProfile: Bluetooth service connected
,07-07 20:28:16.595   787   805 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-07 20:28:16.597  4101  4101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:28:16.597   787   787 D BluetoothA2dp: Proxy object connected
,07-07 20:28:16.598   941   955 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:28:16.598  4101  4101 D ObexServerSockets: Succeed to create listening sockets 
07-07 20:28:16.598  4101  4101 D ObexServerSockets0: startAccept()
07-07 20:28:16.598  4101  4101 D ObexServerSockets0: prepareForNewConnect()
07-07 20:28:16.600  4101  4101 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-07 20:28:16.600  4101  4101 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-07 20:28:16.600   941  1357 D BluetoothPbap: onBluetoothStateChange: up=true
,07-07 20:28:16.602   941   941 D BluetoothPan: BluetoothPAN Proxy object connected
,07-07 20:28:16.602   941   941 D PanProfile: Bluetooth service connected
07-07 20:28:16.602  4101  4191 D ObexServerSockets0: Accepting socket connection...
07-07 20:28:16.602  3688  3688 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:28:16.602  3688  3688 D PanProfile: Bluetooth service connected
07-07 20:28:16.604  4101  4192 D ObexServerSockets0: Accepting socket connection...
07-07 20:28:16.604  3688  3708 D BluetoothMap: onBluetoothStateChange: up=true
,07-07 20:28:16.605  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:16.607  3688  3688 D BluetoothMap: Proxy object connected
07-07 20:28:16.607  3688  3708 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:28:16.607  3688  3688 D MapProfile: Bluetooth service connected
,07-07 20:28:16.607  3688  3688 D BluetoothMap: getConnectedDevices()
07-07 20:28:16.607  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:16.609   787   805 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:28:16.609   941   954 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:28:16.609  3688  3688 D BluetoothA2dp: Proxy object connected
,07-07 20:28:16.610   787   805 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:28:16.610   787   787 I Telecom : BluetoothPhoneService: queryPhoneState
07-07 20:28:16.611  4101  4101 D BluetoothMapService: onReceive
07-07 20:28:16.611  4101  4101 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:28:16.611  4101  4101 D BluetoothMapService: STATE_ON
,07-07 20:28:16.616  3688  3688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:28:16.624  3688  3688 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:28:16.628  4101  4195 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:28:16.628  3688  3688 D BluetoothPbap: Proxy object connected
07-07 20:28:16.628  3688  3688 D PbapServerProfile: Bluetooth service connected
,07-07 20:28:16.635  4101  4101 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-07 20:28:16.635  4101  4101 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:28:16.638   941   941 D BluetoothPbap: Proxy object connected
,07-07 20:28:16.638   941   941 D PbapServerProfile: Bluetooth service connected
,07-07 20:28:16.647  4101  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:28:16.648  4101  4202 I BtOppRfcommListener: Accept thread started.
,07-07 20:28:16.683   787   787 D BluetoothHeadset: Proxy object connected
,07-07 20:28:16.683  1299  1726 D BluetoothHeadset: Proxy object connected
07-07 20:28:16.683   787   787 D BluetoothHeadset: Proxy object connected
07-07 20:28:16.684  3688  3698 D BluetoothHeadset: Proxy object connected
07-07 20:28:16.684  3688  3688 D HeadsetProfile: Bluetooth service connected
,07-07 20:28:16.684   941   954 D BluetoothHeadset: Proxy object connected
07-07 20:28:16.684   941   941 D HeadsetProfile: Bluetooth service connected
07-07 20:28:16.684   787   787 D BluetoothHeadset: Proxy object connected
,07-07 20:28:16.686  1299  1429 D BluetoothHeadset: Proxy object connected
,07-07 20:28:16.688  3688  3708 D BluetoothHeadset: Proxy object connected
,07-07 20:28:16.689  3688  3688 D HeadsetProfile: Bluetooth service connected
,07-07 20:28:16.693  1729  1729 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-07 20:28:16.701  1729  4205 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-07 20:28:16.703  1729  1729 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-07 20:28:16.710   787   805 D BluetoothHeadset: Proxy object connected
,07-07 20:28:16.710   941   955 D BluetoothHeadset: Proxy object connected
07-07 20:28:16.710   941   941 D HeadsetProfile: Bluetooth service connected
07-07 20:28:16.710   787   805 D BluetoothHeadset: Proxy object connected
,07-07 20:28:16.712  1729  4205 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:17.256  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:17.262  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:17.265  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:17.266  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18fb0aa added. We now have 8 listener(s)
07-07 20:28:17.266  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:17.271  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:28:17.271  3618  3685 I jxcore-log: 
07-07 20:28:17.276   787  3021 D WifiService: setWifiEnabled: false pid=3618, uid=10000
07-07 20:28:17.276   787  3021 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:28:17.289  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:17.289   787   962 D WifiService: setWifiEnabled: true pid=3618, uid=10000
07-07 20:28:17.290   787   962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:28:17.302   195   786 D SoftapController: Softap fwReload - Ok
07-07 20:28:17.307   195   786 D CommandListener: Setting iface cfg
07-07 20:28:17.308   195   786 D CommandListener: Trying to bring down wlan0
07-07 20:28:17.310   195   786 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:28:17.321   787   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-07 20:28:18.073   787   892 D wifi    : set interface wlan0 flags (UP)
,07-07 20:28:18.073   787   892 I WifiHAL : Initializing wifi
07-07 20:28:18.073   787   892 I WifiHAL : Creating socket
07-07 20:28:18.075   787   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-07 20:28:18.075   787   892 D wifi    : Did set static halHandle = 0xa07ec700
07-07 20:28:18.075   787   892 D wifi    : halHandle = 0xa07ec700, mVM = 0xb4d7c000, mCls = 0xfea
07-07 20:28:18.075   787   892 D wifi    : array field set
07-07 20:28:18.075   787   892 I WifiNative-HAL: interface[0] = p2p0
07-07 20:28:18.075   787   805 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-07 20:28:18.075   787   892 I WifiNative-HAL: interface[1] = wlan0
07-07 20:28:18.079  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:28:18.079   787   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-07 20:28:18.080   787   892 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-07 20:28:18.086   787  4227 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1602304256
07-07 20:28:18.086   787  4227 D wifi    : waitForHalEvents called, vm = 0xb4d7c000, obj = 0xfea, env = 0x9810f1e0
,07-07 20:28:18.113  4228  4228 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-07 20:28:18.156  4228  4228 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:28:18.164  4228  4228 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.123  3618  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:19.129  3618  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.133  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.133  3618  3685 I jxcore-log: 
07-07 20:28:19.143   787   892 D WifiConfigStore: Loading config and enabling all networks 
07-07 20:28:19.150   787   892 D WifiConfigStore: loaded 0 passpoint configs
07-07 20:28:19.150   787   892 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:28:19.151   787   892 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-07 20:28:19.151   787   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-07 20:28:19.151   787   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-07 20:28:19.151   787   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-07 20:28:19.152   787   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-07 20:28:19.152   787   892 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-07 20:28:19.154   787   892 D WifiNative-HAL: Setting external_sim to 1
07-07 20:28:19.154   787   892 D wifi    : setting dfs flag to true, 0x9a1e2e20
07-07 20:28:19.155   787   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-07 20:28:19.155   787   892 D wifi    : setting scan oui 0x9a1e2e20
07-07 20:28:19.155   787   892 D WifiHAL : Sending mac address OUI
,07-07 20:28:19.156  3778  3778 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:28:19.174   787   892 E native  : do suspend true
,07-07 20:28:19.179   787   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-07 20:28:19.179   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-07 20:28:19.179   787   787 D RttService: SCAN_AVAILABLE : 3
07-07 20:28:19.179   787   906 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-07 20:28:19.180   195   786 D CommandListener: Setting iface cfg
07-07 20:28:19.180   195   786 D CommandListener: Trying to bring up p2p0
07-07 20:28:19.180   787   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-07 20:28:19.188   787   891 D WifiNative-HAL: p2pGetDeviceAddress
,07-07 20:28:19.189   787   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.326  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:28:19.327  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:19.328  3618  3678 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-07 20:28:19.329  3618  3678 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-07 20:28:19.331  3618  3678 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3142db1 Bundle[{}]
,07-07 20:28:19.331  3618  3678 I io.jxcore.node.LifeCycleMonitor: start: OK
07-07 20:28:19.331  3618  3678 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-07 20:28:19.331  3618  3678 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-07 20:28:19.331  3618  3678 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-07 20:28:19.332  3618  3678 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-07 20:28:19.332  3618  3678 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-07 20:28:19.335  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-07 20:28:19.335  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,07-07 20:28:19.335  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-07 20:28:19.335  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-07 20:28:19.336  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,07-07 20:28:19.336  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:28:19.337  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.337  3618  3685 I jxcore-log: 
,07-07 20:28:19.343  3618  3678 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 303)
,07-07 20:28:19.343  3618  3678 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 303)
,07-07 20:28:19.343  3618  3678 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 303)
,07-07 20:28:19.343  3618  3678 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 303)
,07-07 20:28:19.346  3618  3678 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 309)
,07-07 20:28:19.346  3618  3678 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 309)
,07-07 20:28:19.346  3618  3678 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 309)
,07-07 20:28:19.347  3618  3678 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 310)
07-07 20:28:19.349  3618  3678 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 312)
,07-07 20:28:19.351  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-07 20:28:19.352  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e349b added. We now have 2 listener(s)
,07-07 20:28:19.354  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-07 20:28:19.354  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:28:19.354  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:28:19.354  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.354  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5d038 added. We now have 9 listener(s)
,07-07 20:28:19.354  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:28:19.357  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:28:19.357  3618  3678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:28:19.360  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.363  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.364  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.364  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.366  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.367  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.368  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.368  3618  3685 I jxcore-log: 
07-07 20:28:19.368  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-07 20:28:19.368  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9902d76 added. We now have 3 listener(s)
,07-07 20:28:19.370  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-07 20:28:19.371  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:28:19.371  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.371  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.371  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f817f77 added. We now have 10 listener(s)
07-07 20:28:19.371  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.372  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.372  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:28:19.372  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.372  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.372  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.372  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.372  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.372  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e349b removed from the list
07-07 20:28:19.372  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.373  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5d038 removed from the list
07-07 20:28:19.373  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.373  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.373  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.373  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:28:19.373  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.373  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5d038 not in the list
07-07 20:28:19.373  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.373  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.373  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.373  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f817f77 removed from the list
07-07 20:28:19.373  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.373  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.373  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.373  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.373  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9902d76 removed from the list
07-07 20:28:19.375  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-07 20:28:19.375  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03b7e4 added. We now have 2 listener(s)
07-07 20:28:19.377  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.377  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.377  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.377  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.377  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df4f44d added. We now have 9 listener(s)
07-07 20:28:19.377  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.379  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:28:19.379  3618  3678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:28:19.382  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.385  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.386  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:28:19.387  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.387  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.388  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.388  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.388  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b049c13 added. We now have 3 listener(s)
07-07 20:28:19.389  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.389  3618  3685 I jxcore-log: 
07-07 20:28:19.390  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.390  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.390  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.391  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.391  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2366e50 added. We now have 10 listener(s)
07-07 20:28:19.391  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.391  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:19.391  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:19.391  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.391  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:28:19.395  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.395  3618  3678 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:28:19.395  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.395  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.396  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.396  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.396  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.396  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.396  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.396  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:19.396  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.397  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03b7e4 removed from the list
07-07 20:28:19.397  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:28:19.397  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df4f44d removed from the list
07-07 20:28:19.397  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.397  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.397  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.397  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:28:19.397  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.397  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.397  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.397  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df4f44d not in the list
07-07 20:28:19.397  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:19.398  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.398  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.398  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2366e50 removed from the list
07-07 20:28:19.398  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.398  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.398  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:28:19.398  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.398  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b049c13 removed from the list
07-07 20:28:19.399  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.399  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92b754e added. We now have 2 listener(s)
07-07 20:28:19.400  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.400  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.400  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.400  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.400  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d92e66f added. We now have 9 listener(s)
07-07 20:28:19.400  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.401  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:28:19.401  3618  3678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:28:19.403  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.404  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.405  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.405  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.406  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.407  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.407  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.407  3618  3685 I jxcore-log: 
07-07 20:28:19.408  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.408  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject,.p2p.btconnectorlib.ConnectionManager@3f96005 added. We now have 3 listener(s)
07-07 20:28:19.409  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.409  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.409  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.409  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.409  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54d985a added. We now have 10 listener(s)
07-07 20:28:19.409  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.409  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:19.409  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:19.409  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:19.409  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.409  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:19.412  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.412  3618  3678 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:28:19.412  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.412  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.412  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.412  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.412  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.412  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:19.412  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.412  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92b754e removed from the list
07-07 20:28:19.412  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.412  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d92e66f removed from the list
07-07 20:28:19.412  3618  3678 D io.jxcore.node.Connectivit,yMonitor: stop
07-07 20:28:19.412  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.413  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.413  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:28:19.413  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.413  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.413  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.413  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d92e66f not in the list
07-07 20:28:19.413  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:19.413  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.413  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.413  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54d985a removed from the list
07-07 20:28:19.413  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.413  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.413  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.413  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.413  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f96005 removed from the list
07-07 20:28:19.414  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.414  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b49b768 added. We now have 2 listener(s)
07-07 20:28:19.415  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.415  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.415  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.415  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.415  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b4f781 added. We now have 9 listener(s)
07-07 20:28:19.415  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.417  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:28:19.417  3618  3678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:28:19.419  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.421  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.422  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.422  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.423  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.424  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.424  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.424  3618  3685 I jxcore-log: 
07-07 20:28:19.424  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.424  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29b3467 added. We now have 3 listener(s)
07-07 20:28:19.425  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.426  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.426  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.426  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.426  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b6e214 added. We now have 10 listener(s)
07-07 20:28:19.435  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.437  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:19.437  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:19.437  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.437  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:19.441  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.441  3618  3678 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:28:19.443  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.443  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.443  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.443  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.443  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.443  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:19.443  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.443  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b49b768 removed from the list
07-07 20:28:19.443  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.443  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b4f781 removed from the list
07-07 20:28:19.443  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.443  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.444  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.444  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:28:19.444  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.444  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.444  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.444  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b4f781 not in the list
07-07 20:28:19.444  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:19.444  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.444  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.444  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b6e214 removed from the list
07-07 20:28:19.444  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.444  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.444  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.444  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.444  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29b3467 removed from the list
07-07 20:28:19.445  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.445  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f86d8b2 added. We now have 2 listener(s)
07-07 20:28:19.447  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.447  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.447  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.447  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.447  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1cb003 added. We now have 9 listener(s)
07-07 20:28:19.447  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.448  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:28:19.449  3618  3678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:28:19.450  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.452  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.453  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.454  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.454  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.454  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76815b9 added. We now have 3 listener(s)
07-07 20:28:19.455  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.456  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.456  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.456  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.456  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.456  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.456  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405cdfe added. We now have 10 listener(s)
07-07 20:28:19.456  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.456  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.456  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.456  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.456  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.456  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.456  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.456  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.456  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f86d8b2 removed from the list
07-07 20:28:19.456  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.456  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1cb003 removed from the list
07-07 20:28:19.457  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.457  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.457  3618  3685 I jxcore-log: 
07-07 20:28:19.457  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.457  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.457  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.457  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.457  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1cb003 not in the list
07-07 20:28:19.457  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.457  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.457  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.457  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405cdfe removed from the list
07-07 20:28:19.457  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.457  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.457  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.457  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.457  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76815b9 removed from the list
07-07 20:28:19.458  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:28:19.458  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f added. We now have 2 listener(s)
07-07 20:28:19.460  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-07 20:28:19.460  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:28:19.460  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:28:19.460  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:28:19.460  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac added. We now have 9 listener(s)
07-07 20:28:19.460  3618  3678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:28:19.461  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-07 20:28:19.461  3618  3678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-07 20:28:19.463  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.465  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.466  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.466  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.467  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:28:19.467  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:28:19.467  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:28:19.467  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.468  3618  3678 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-07 20:28:19.468  3618  3678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-07 20:28:19.468  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:28:19.468  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:28:19.468  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:28:19.468  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.468  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.468  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.468  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.468  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.468  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.468  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.468  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:28:19.468  3618  3678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f removed from the list
07-07 20:28:19.468  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.468  3618  3678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac removed from the list
07-07 20:28:19.468  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.469  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.469  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.469  3618  3685 I jxcore-log: 
07-07 20:28:19.470  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.470  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.470  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.470  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.471  3618  3678 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-07 20:28:19.471  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.471  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.471  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.472  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.472  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.472  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.472  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.472  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.472  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.472  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.472  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.472  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.472  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.472  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.472  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.472  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.474  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:,910:910:910:910:910]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-07 20:28:19.474  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:28:19.475  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.475  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.475  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.475  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.475  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.475  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.475  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.475  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.475  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.475  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.476  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.476  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.476  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.476  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.476  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.476  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.476  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.476  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.476  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.476  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.476  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.476  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.477  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.477  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
,07-07 20:28:19.477  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.477  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.477  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.477  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.477  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.477  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.477  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.477  3618  3678 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:28:19.478  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.482  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.483  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.483  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.483  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:19.483  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:19.483  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.484  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:19.484  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.485  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.486  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.486  3618  3685 I jxcore-log: 
07-07 20:28:19.487  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.487  3618  3678 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:28:19.487  3618  3678 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:28:19.489  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.489  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.489  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.489  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.489  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.489  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:19.489  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.489  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.489  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.489  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.489  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.489  3618  3678 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:28:19.490  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.493  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.494  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.494  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.494  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:19.494  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:19.495  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.496  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.496  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.496  3618  3678 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:28:19.496  3618  3678 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:28:19.497  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.497  3618  3685 I jxcore-log: 
07-07 20:28:19.498  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.498  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.498  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.498  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.498  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.498  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:19.498  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.498  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.498  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.498  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.498  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.499  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:19.499  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.499  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.499  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.500  3618  3678 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:28:19.501  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:28:19.503  3618  3678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:28:19.504  3618  3678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:28:19.504  3618  3678 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:28:19.504  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:28:19.504  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:28:19.504  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.504  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:19.505  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.506  3618  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:28:19.507  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:28:19.507  3618  3685 I jxcore-log: 
07-07 20:28:19.508  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.508  3618  3678 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-07 20:28:19.508  3618  3678 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:28:19.508  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.508  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.508  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.508  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.509  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.509  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.509  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.509  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.509  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:28:19.509  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.509  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.509  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.509  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.509  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.509  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:19.509  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.509  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.509  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.510  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.510  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.510  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.510  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.510  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.510  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.510  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.510  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.510  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.510  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.510  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.510  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.510  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.510  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.510  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.510  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.510  3618  3678 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-07 20:28:19.510  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.510  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.511  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.511  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.511  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.511  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.511  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.511  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.511  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.511  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.511  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.511  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.511  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.511  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.511  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.511  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.511  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-07 20:28:19.511  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.511  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.511  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.511  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.511  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.511  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.511  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.511  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.511  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.511  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.511  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.511  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.511  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.511  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.511  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.511  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.512  3618  3678 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-07 20:28:19.512  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.512  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.512  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current stat,e already matches the desired outcome of this operation, skipping...
07-07 20:28:19.512  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.512  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.512  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.512  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.512  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.512  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.512  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.512  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.512  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.512  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.512  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.512  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.512  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.512  3618  3678 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-07 20:28:19.512  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.512  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_ST,ARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.512  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.512  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.512  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.512  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.513  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.513  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.513  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.513  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.513  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.513  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.513  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.513  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.513  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.513  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.513  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:28:19.513  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:28:19.513  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:28:19.513  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:28:19.513  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-07 20:28:19.513  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:28:19.513  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.513  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.513  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.513  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.513  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.513  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.,bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.513  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.513  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.513  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.513  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.513  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.513  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.513  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.513  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.514  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.514  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.514  3618  3678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:28:19.514  3618  3678 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:28:19.514  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:28:19.515  3618  3678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:28:19.515  3618  3678 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:28:19.515  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:28:19.516  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:28:19.516  3618  3678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-07 20:28:19.516  3618  3678 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-07 20:28:19.516  3618  3678 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-07 20:28:19.516  3618  3678 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:28:19.517  3618  3678 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-07 20:28:19.517  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.518  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.518  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.518  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.518  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.518  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.518  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.518  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.518  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.518  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.518  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.518  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.518  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.518  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.518  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.518  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.518  3618  3678 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-07 20:28:19.519  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.519  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.519  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.519  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.519  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.519  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.519  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.519  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.519  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.519  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.519  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.519  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.519  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.519  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.519  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.519  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.520  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.520  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.520  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.520  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.520  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.520  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.520  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.520  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.521  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.521  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.521  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.521  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.521  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.521  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.521  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.521  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.521  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.521  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.521  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.521  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.521  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.521  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.521  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.521  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.521  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.521  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.521  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.521  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.521  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.521  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.521  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.521  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.522  3618  3678 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-07 20:28:19.522  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.522  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.522  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.522  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.522  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.522  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.522  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.522  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.522  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.522  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.522  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.522  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.522  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.522  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.522  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.522  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.523  3618  3678 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-07 20:28:19.523  3618  3678 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-07 20:28:19.523  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-07 20:28:19.523  3618  3685 I jxcore-log: 
07-07 20:28:19.523  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:28:19.523  3618  3678 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-07 20:28:19.523  3618  3678 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:28:19.523  3618  3678 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-07 20:28:19.523  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:28:19.523  3618  3678 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-07 20:28:19.523  3618  3678 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:28:19.523  3618  3678 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:28:19.523  3618  3678 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:28:19.523  3618  3678 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-07 20:28:19.523  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.523  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.523  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.523  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.523  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.523  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.523  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.523  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.523  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.523  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.523  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.523  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.523  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.523  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.523  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.523  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.524  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.524  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.524  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.524  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.524  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.524  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.524  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.524  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.524  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.524  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.524  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.524  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.524  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.524  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.524  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.524  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.524  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.524  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.524  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.524  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.524  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.525  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.525  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.525  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.525  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.525  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.525  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.525  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.525  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.525  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.525  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.526  3618  3678 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-07 20:28:19.526  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.527  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-07 20:28:19.528  3618  3678 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-07 20:28:19.528  3618  3678 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-07 20:28:19.528  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-07 20:28:19.528  3618  3618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-07 20:28:19.528  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.528  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:28:19.528  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-07 20:28:19.528  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-07 20:28:19.528  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-07 20:28:19.528  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.528  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.528  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.528  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:28:19.528  3618  3678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:28:19.528  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:28:19.528  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.528  3618  4253 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-07 20:28:19.528  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.529  3618  3678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:19.529  3618  4253 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-07 20:28:19.529  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.529  3618  3618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:19.529  3618  3618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.529  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.529  3618  3618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:19.529  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.529  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:28:19.529  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.529  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.531  3618  3618 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.531  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:19.532  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.532  3618  3618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:28:19.532  3618  3618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:28:19.532  3618  3618 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:28:19.532  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.532  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:28:19.532  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.532  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.532  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.532  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.532  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.532  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.532  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.532  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:28:19.534  3618  3618 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-07 20:28:19.534  3618  3678 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:28:19.534  3618  3618 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:28:19.534  3618  3618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-07 20:28:19.534  3618  3618 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-07 20:28:19.535  3618  3618 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-07 20:28:19.535  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.535  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.535  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.535  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:28:19.535  3618  3685 I jxcore-log: 
07-07 20:28:19.535  3618  3678 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-07 20:28:19.535  3618  3678 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-07 20:28:19.535  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:28:19.535  3618  3678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:28:19.536  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.536  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.536  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.536  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.536  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.536  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.536  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.536  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.536  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.536  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.536  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.536  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.536  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.536  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.536  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.536  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.538  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.538  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.538  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.538  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.538  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.538  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.538  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.538  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.538  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.538  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.539  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.539  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.539  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.539  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.539  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.539  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.539  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.539  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.539  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.539  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.539  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.539  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.539  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.539  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.539  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.539  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.539  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.539  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.539  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.539  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.539  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.539  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.540  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.540  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.540  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.540  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.540  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.540  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.540  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.540  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.540  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.540  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.540  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.540  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.540  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.540  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.540  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.540  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.541  3618  3678 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-07 20:28:19.541  3618  3678 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-07 20:28:19.541  3618  3618 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-07 20:28:19.541  3618  3678 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-07 20:28:19.541  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.541  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.541  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.541  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.541  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.541  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.541  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.541  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.542  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.542  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.542  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.542  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.542  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.542  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.542  3618  3678 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-07 20:28:19.542  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.542  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.542  3618  3678 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:28:19.542  3618  3678 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:28:19.542  3618  3678 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:28:19.542  3618  3678 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:28:19.542  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.542  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.542  3618  3678 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb0495f not in the list
07-07 20:28:19.542  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.542  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.542  3618  3678 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:28:19.542  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.542  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:28:19.542  3618  3678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:28:19.542  3618  3678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:28:19.542  3618  3678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:28:19.542  3618  3678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee45fac not in the list
07-07 20:28:19.542  3618  3685 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-07 20:28:19.542  3618  3685 I jxcore-log: 
07-07 20:28:19.543  3618  3678 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-07 20:28:19.543  3618  3678 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-07 20:28:19.543  3618  3678 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-07 20:28:19.543  3618  3678 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-07 20:28:19.543  3618  3678 E com.test.thalitest.ThaliTestRunner: Total duration: 19436 ms
07-07 20:28:19.543  3618  3678 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 19492ms. Plugin should use CordovaInterface.getThreadPool().
,07-07 20:28:28.789   192   192 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6d0a030
,07-07 20:28:28.789   192   192 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,07-07 20:28:28.789   192   192 I rmt_storage: wakelock acquired: 1, error no: 2
,07-07 20:28:28.790   192   471 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1228941008)
,07-07 20:28:28.907   192   471 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,07-07 20:28:28.907   192   471 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-07 20:28:28.907   192   471 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1228941008) wakelock released: 1, error no: 0
07-07 20:28:28.907   192   471 I rmt_storage: 
,07-07 20:28:28.909   192   192 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6d0a030
,07-07 20:28:48.628  1232  1351 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-07 20:28:48.628  1232  1351 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-07 20:28:51.012   787   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:28:51.035   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:29:00.325   787   894 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-07 20:29:52.662   787   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:29:52.685   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:30:47.056  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:30:47.092  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:30:47.092  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:30:54.322   787   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:30:54.342   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:30:55.675  1729  2951 V NativeCrypto: SSL shutdown failed: ssl=0x99c7b800: I/O error during system call, Connection timed out
,07-07 20:31:53.528  1729  2951 V NativeCrypto: SSL shutdown failed: ssl=0x9aff2a00: I/O error during system call, Connection timed out
,07-07 20:31:55.528  1729  2951 V NativeCrypto: SSL shutdown failed: ssl=0x9a25a600: I/O error during system call, Connection timed out
,07-07 20:36:55.996   787   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:36:56.023   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:41:20.739  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:41:20.773  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-07 20:41:20.776  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:42:57.746   787   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:42:57.774   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:43:20.825  1729  1905 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:45:31.693   787   799 I UsageStatsService: User[0] Flushing usage stats to disk
,07-07 20:46:20.892  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:46:20.896  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-07 20:46:20.897  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:46:20.965   787   796 I art     : Background partial concurrent mark sweep GC freed 35604(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 24MB/36MB, paused 797us total 123.459ms
,07-07 20:50:35.945   787   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:50:35.982   787   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:50:36.026  1614  4356 I EventLogChimeraService: Aggregate from 1467915635852 (log), 1467915635852 (data)
,07-07 20:50:36.207  1614  4369 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-07 20:50:36.220  1614  4369 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,TIME-OUT KILL (timeout was 1400000ms),07-07 20:51:20.974  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-07 20:51:21.003  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-07 20:51:21.003  1729  1729 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-07 20:51:26.487  4396  4396 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-07 20:51:26.491  4396  4396 D AndroidRuntime: CheckJNI is OFF
07-07 20:51:26.527  4396  4396 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-07 20:51:26.562  4396  4396 I Radio-JNI: register_android_hardware_Radio DONE
07-07 20:51:26.582  4396  4396 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-07 20:51:26.588   787   801 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-07 20:51:26.588   787   801 I ActivityManager: Killing 3618:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-07 20:51:26.622   787   797 D GraphicsStats: Buffer count: 2
07-07 20:51:26.622   787   797 I WindowState: WIN DEATH: Window{4458db8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-07 20:51:26.626   787   893 D WifiService: Client connection lost with reason: 4
07-07 20:51:26.676   787   812 W PackageSettings: Skipping PackageSetting{268ab59 com.example.hello/10278} due to missing metadata
07-07 20:51:26.705   787   801 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-07 20:51:26.705   787   801 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-07 20:51:26.705   787   812 I art     : Starting a blocking GC Explicit
07-07 20:51:26.707   787   801 E ActivityManager: Failure starting process com.test.thalitest
07-07 20:51:26.707   787   801 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-07 20:51:26.707   787   801 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:51:26.707   787   801 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:51:26.707   787   801 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:51:26.707   787   801 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-07 20:51:26.708   787   801 I ActivityManager:   Force finishing activity ActivityRecord{683a2ed u0 com.test.thalitest/.MainActivity t243}
07-07 20:51:26.713   787  3022 W ActivityManager: Spurious death for ProcessRecord{6a14a33 0:com.test.thalitest/u0a0}, curProc for 3618: null
07-07 20:51:26.745   787   812 I art     : Explicit concurrent mark sweep GC freed 17225(1171KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 24MB/36MB, paused 728us total 38.627ms
07-07 20:51:26.766   787   812 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-07 20:51:26.768  4396  4396 I art     : System.exit called, status: 0
07-07 20:51:26.768  4396  4396 I AndroidRuntime: VM exiting with result code 0.
07-07 20:51:26.775   787   812 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-07 20:51:26.808   787   801 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-07 20:51:26.813  4101  4101 D BluetoothMapAppObserver: onReceive
07-07 20:51:26.813  4101  4101 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-07 20:51:26.813  1729  1798 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-07 20:51:26.815   787   884 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-07 20:51:26.839  1232  1232 I Keyboard.Facilitator: resetDictionaries() : en_US
07-07 20:51:26.843  1299  1299 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-07 20:51:26.850  1232  4431 I Keyboard.Facilitator.DecoderInitializer: run()
07-07 20:51:26.861  1232  4431 I Decoder : createOrResetDecoder
07-07 20:51:26.867  2560  4437 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-07 20:51:26.868   787  1323 I ActivityManager: Start proc 4433:com.android.musicfx/u0a15 for broadcast com.android.musicfx/.Compatibility$Receiver
07-07 20:51:26.901  4433  4433 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-07 20:51:26.910   787   787 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-07 20:51:26.916  1362  4449 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-07 20:51:26.920  2560  4437 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
07-07 20:51:26.923  2560  4437 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-07 20:51:26.923  2560  4437 E AndroidRuntime: Process: android.process.acore, PID: 2560
07-07 20:51:26.923  2560  4437 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:51:26.923  2560  4437 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:51:26.929  2560  4437 I Process : Sending signal. PID: 2560 SIG: 9
07-07 20:51:26.933   787  4452 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:51:26.933   787  4452 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-07 20:51:26.933   787  4452 E DropBoxManagerService: 	... 5 more
07-07 20:51:26.940   189   189 E lowmemorykiller: Error writing /proc/2560/oom_score_adj; errno=22
07-07 20:51:26.948   787  3021 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3618 uid 10000
07-07 20:51:26.949  1362  4449 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-07 20:51:26.950  1232  4431 I Keyboard.Facilitator.MainLanguageModelLoader: run()
07-07 20:51:26.954  1232  1232 I Keyboard.Facilitator: onFinishInput()
07-07 20:51:26.959   787  1323 I ActivityManager: Start proc 4454:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
07-07 20:51:26.975   787  1314 I ActivityManager: Start proc 4466:com.google.android.googlequicksearchbox:crash_report/u0a22 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
07-07 20:51:26.977  1362  4449 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
07-07 20:51:26.977  1362  4449 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-07 20:51:26.977  1362  4449 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1362
07-07 20:51:26.977  1362  4449 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:51:26.977  1362  4449 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
