#### Test 75789268514fc25_thali04_LGE-Nexus 5 Logs


```
--------- beginning of system
07-15 15:21:53.184   788  1340 I ActivityManager: Killing 2722:com.android.chrome/u0a34 (adj 15): empty #17
,--------- beginning of main
07-15 15:21:53.773  3475  3475 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-15 15:21:53.777  3475  3475 D AndroidRuntime: CheckJNI is OFF
07-15 15:21:53.810  3475  3475 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-15 15:21:53.845  3475  3475 I Radio-JNI: register_android_hardware_Radio DONE
07-15 15:21:53.863  3475  3475 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-15 15:21:53.866   788  1342 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-15 15:21:53.885   788  1342 I ActivityManager: Start proc 3491:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-15 15:21:53.888  3475  3475 D AndroidRuntime: Shutting down VM
07-15 15:21:53.948  3491  3491 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-15 15:21:53.990  3491  3491 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9180-9183)
07-15 15:21:53.990  3491  3491 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:54.013  3491  3491 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9410788}
07-15 15:21:54.013  3491  3491 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:54.013  3491  3491 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-15 15:21:54.019  3491  3491 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-15 15:21:54.020  3491  3491 E SysUtils: ApplicationContext is null in ApplicationStatus
07-15 15:21:54.031  3491  3491 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-15 15:21:54.035  3491  3491 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-15 15:21:54.035  3491  3491 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-15 15:21:54.036  3491  3491 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-15 15:21:54.077   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f1bf522:true
,07-15 15:21:54.198  3491  3491 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-15 15:21:54.212  3491  3491 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-15 15:21:54.263  3491  3539 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-15 15:21:54.282  3491  3523 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-15 15:21:54.306  3491  3539 I OpenGLRenderer: Initialized EGL, version 1.4
,07-15 15:21:54.331  1230  1230 I Keyboard.Facilitator: onFinishInput()
,07-15 15:21:54.352   788   809 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +436ms (total +475ms)
,07-15 15:21:54.431  3491  3491 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3491
,07-15 15:21:54.512  3491  3491 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-15 15:21:54.621  3491  3542 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1657206480
,07-15 15:21:54.625  3491  3542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-15 15:21:54.625  3491  3542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-15 15:21:54.625  3491  3542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-15 15:21:54.625  3491  3542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-15 15:21:54.625  3491  3542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-15 15:21:54.625  3491  3542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a6e7bf added. We now have 1 listener(s)
,07-15 15:21:54.628  3491  3542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
,07-15 15:21:54.629  3491  3542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-15 15:21:54.629  3491  3542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:54.629  3491  3542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-15 15:21:54.632  3491  3542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57945ea added. We now have 1 listener(s)
07-15 15:21:54.632  3491  3542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:54.634   788   893 D WifiService: New client listening to asynchronous messages
,07-15 15:21:54.635  3491  3542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-15 15:21:54.637  3491  3542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-15 15:21:54.637  3491  3542 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-15 15:21:54.638  3491  3542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:54.639  3491  3542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:54.645  3491  3542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:21:54.645  3491  3542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-15 15:21:54.645  3491  3542 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:54.645  3491  3542 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:21:54.645  3491  3542 D io.jxcore.node.JXcoreExtension: Unit Tests on
07-15 15:21:54.646  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:54.648  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:54.672  3491  3491 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-15 15:21:55.369  3491  3549 W jxcore-log: Initializing JXcore engine
,07-15 15:21:55.369  3491  3549 W jxcore-log: JXcore engine is ready
,07-15 15:21:55.403  3549  3549 W Thread-274: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7951]" dev="sockfs" ino=7951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-15 15:21:55.403  3549  3549 W Thread-274: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-15 15:21:55.403  3549  3549 W Thread-274: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21065]" dev="sockfs" ino=21065 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-15 15:21:55.419  3491  3549 W jxcore-log: Starting JXcore engine
,07-15 15:21:55.519  3491  3549 W jxcore-log: Platform android
07-15 15:21:55.519  3491  3549 W jxcore-log: 
,07-15 15:21:55.519  3491  3549 W jxcore-log: Process ARCH arm
07-15 15:21:55.519  3491  3549 W jxcore-log: 
,07-15 15:21:55.710  3491  3549 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:21:55.710  3491  3549 I jxcore-log: 
07-15 15:21:55.711  3491  3549 W jxcore-log: JXcore engine is started
,07-15 15:21:55.714  3491  3542 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-15 15:21:55.716  3491  3491 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:22:04.826  2462  2497 I Finsky  : [214] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-15 15:22:04.917  2462  2497 I Finsky  : [214] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-15 15:22:04.918  2462  2462 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-15 15:22:05.514  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-15 15:22:05.514  3491  3549 I jxcore-log: 
07-15 15:22:05.515  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-15 15:22:05.515  3491  3549 I jxcore-log: 
,07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:05.519  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:22:05.521  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:22:05.523  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-15 15:22:05.523  3491  3549 I jxcore-log: 
,07-15 15:22:05.524  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-15 15:22:05.524  3491  3549 I jxcore-log: 
,07-15 15:22:05.863  3491  3491 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-15 15:22:05.866  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:05.866  3491  3549 I jxcore-log: 
,07-15 15:22:05.869  3491  3549 D ExecuteNativeTests: Running unit tests
,07-15 15:22:05.928  3491  3549 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-15 15:22:05.928  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-15 15:22:05.928  3491  3549 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-15 15:22:05.928  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-15 15:22:05.928  3491  3549 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-15 15:22:05.928  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:22:05.929  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-15 15:22:05.929  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-15 15:22:05.930  3491  3549 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-15 15:22:05.930  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-15 15:22:05.930  3491  3549 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-15 15:22:05.930  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-15 15:22:05.930  3491  3549 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-15 15:22:05.930  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-15 15:22:05.930  3491  3549 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-15 15:22:05.930  3491  3549 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-15 15:22:05.931  3491  3549 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-15 15:22:05.931  3491  3549 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-15 15:22:05.931  3491  3549 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-15 15:22:05.931  3491  3549 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-15 15:22:05.931  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:05.931  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba9fdfe added. We now have 2 listener(s)
07-15 15:22:05.931  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:05.933  3491  3549 D BluetoothAdapter: enable(): BT is already enabled..!
07-15 15:22:05.934   788   968 D WifiService: setWifiEnabled: true pid=3491, uid=10000
07-15 15:22:05.934   788   968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:05.935  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:05.935  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@338b95f added. We now have 3 listener(s)
07-15 15:22:05.935  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:05.940  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:05.940  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61c0fac added. We now have 4 listener(s)
07-15 15:22:05.941  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:05.942  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:05.942  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c14475 added. We now have 5 listener(s)
07-15 15:22:05.942  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:05.943   788   798 D WifiService: setWifiEnabled: false pid=3491, uid=10000
07-15 15:22:05.943   788   798 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:05.947  1965  2040 D BluetoothAdapterState: Current state: ON, message: 23
,07-15 15:22:05.947  1965  2040 D BluetoothAdapterProperties: Setting state to 13
07-15 15:22:05.947  1965  2040 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-15 15:22:05.947  1965  2040 D BluetoothAdapterProperties: onBluetoothDisable()
07-15 15:22:05.948  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:05.948  1965  2040 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:05.949  1965  2048 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:05.949  1965  2040 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-15 15:22:05.950   788   892 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-15 15:22:05.950   788   892 D IpReachabilityMonitor: clear: iface{wlan0/21}, v{4}, ntable=[]
07-15 15:22:05.950   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:22:05.951  1965  1965 D HeadsetService: Received stop request...Stopping profile...
,07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:05.957  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:22:05.958  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-15 15:22:05.958  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:05.959  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:05.960  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:22:05.961  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-15 15:22:05.962  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-15 15:22:05.963  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:05.950   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-15 15:22:05.976   788   892 E native  : do suspend true
,07-15 15:22:05.977   788   801 I ActivityManager: Start proc 3561:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-15 15:22:05.983   788   788 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:05.983   788   788 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:05.983   926  1349 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:05.983   926   926 D HeadsetProfile: Bluetooth service disconnected
07-15 15:22:05.983   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:05.984  1298  1450 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:05.984  1965  1965 D BluetoothMapService: onReceive
,07-15 15:22:05.984  1965  1965 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-15 15:22:05.984  1965  1965 D BluetoothMapService: STATE_TURNING_OFF
07-15 15:22:05.984  1965  1965 V BluetoothAdapterState: isTurningOff()=true
,07-15 15:22:05.984  1965  1965 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:05.984  1965  1965 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:05.984  1965  1965 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:05.990  1965  1965 D A2dpService: Received stop request...Stopping profile...
07-15 15:22:05.990  1965  2218 D A2dpStateMachine: Exit Disconnected: -1
07-15 15:22:05.991   926   926 D BluetoothA2dp: Proxy object disconnected
07-15 15:22:05.992   788   788 D BluetoothA2dp: Proxy object disconnected
07-15 15:22:05.993  1965  1965 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-15 15:22:05.993  1965  1965 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-15 15:22:05.993  1965  2048 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,07-15 15:22:05.993  1965  2180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:05.993  1965  2180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:05.993  1965  2048 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,07-15 15:22:05.994  1965  1965 D HidService: Received stop request...Stopping profile...
07-15 15:22:05.994  1965  1965 D HidService: Stopping Bluetooth HidService
07-15 15:22:05.995   788  2690 D DhcpClient: Clearing IP address
07-15 15:22:05.995   926   926 D BluetoothInputDevice: Proxy object disconnected
07-15 15:22:05.995   926   926 D HidProfile: Bluetooth service disconnected
07-15 15:22:05.995  1965  1965 D BluetoothMapService: MAP Service closeService in
07-15 15:22:05.995  1965  1965 D BluetoothMapMasInstance0: MAP Service shutdown
07-15 15:22:05.995   192   653 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:05.995  1965  1965 D ObexServerSockets0: shutdown(block = true)
07-15 15:22:05.996  1965  1965 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:22:05.996  1965  2225 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-15 15:22:05.996  1965  2226 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-15 15:22:05.997  1965  2213 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-15 15:22:05.997  1965  1965 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:22:05.997  1965  1965 I BtOppRfcommListener: stopping Accept Thread
07-15 15:22:05.997  1965  2643 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-15 15:22:05.998  1965  2643 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-15 15:22:05.999  1965  1965 D HealthService: Received stop request...Stopping profile...
07-15 15:22:06.000  1965  1965 D PanService: Received stop request...Stopping profile...
07-15 15:22:06.000   926   926 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-15 15:22:06.000   926   926 D PanProfile: Bluetooth service disconnected
07-15 15:22:06.001  1965  1965 V BluetoothAdapterState: isTurningOff()=true
,07-15 15:22:06.001  1965  1965 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:06.001  1965  1965 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:06.001  1965  1965 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:06.001  1965  2048 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-15 15:22:06.001  1965  2180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:06.001  1965  2180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:06.001  1965  2180 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:22:06.001  1965  2180 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-15 15:22:06.002  1965  2180 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:22:06.002  1965  2180 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-15 15:22:06.002  1965  1965 D BluetoothMapService: Received stop request...Stopping profile...
07-15 15:22:06.002  1965  1965 D BluetoothMapService: stop()
07-15 15:22:06.002  1965  1965 D BluetoothMapAppObserver: deinitObservers()
07-15 15:22:06.002  1965  1965 D BluetoothMapAppObserver: removeReceiver()
07-15 15:22:06.003   926   926 D BluetoothMap: Proxy object disconnected
07-15 15:22:06.003   926   926 D MapProfile: Bluetooth service disconnected
07-15 15:22:06.003  1965  1965 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:06.003  1965  1965 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:06.003  1965  1965 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:06.003  1965  1965 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:06.004  1965  1965 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-15 15:22:06.004  1965  2048 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:22:06.004  1965  1965 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-15 15:22:06.005  1965  1965 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:06.005  1965  1965 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:06.005  1965  1965 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:06.005  1965  1965 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:06.005  1965  1965 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-15 15:22:06.005  1965  2048 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-15 15:22:06.006  1965  1965 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-15 15:22:06.007  1965  1965 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:06.007  1965  1965 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:06.007  1965  1965 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:06.007  1965  1965 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:06.007  1965  1965 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-15 15:22:06.007  1965  1965 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-15 15:22:06.008  1965  1965 D BluetoothMapService: MAP Service closeService in
07-15 15:22:06.008  1965  1965 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:06.008  1965  1965 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:06.008  1965  1965 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:06.008  1965  1965 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:06.008  1965  1965 D BluetoothMapService: cleanup()
,07-15 15:22:06.008  1965  1965 D BluetoothMapService: MAP Service closeService in
07-15 15:22:06.008  1965  2040 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-15 15:22:06.008  1965  2040 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:06.008  1965  2040 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-15 15:22:06.008   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:06.009   926  1634 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:06.009   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:06.009   926  1349 D BluetoothPbap: onBluetoothStateChange: up=false
07-15 15:22:06.009  1965  2040 I BluetoothAdapterState: Entering BleOnState
07-15 15:22:06.009  1298  1533 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:06.010   926   952 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:22:06.010   926  1633 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:22:06.010   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:06.010   926   946 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:06.011   788   808 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:06.011   926  1634 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-15 15:22:06.011  1965  2040 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-15 15:22:06.011  1965  2040 D BluetoothAdapterProperties: Setting state to 16
07-15 15:22:06.011  1965  2040 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-15 15:22:06.012  1965  2040 D BluetoothAdapterProperties: onBleDisable
07-15 15:22:06.012  1965  2040 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:06.012  1965  2044 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-15 15:22:06.014  1965  2180 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-15 15:22:06.014  1965  2180 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:06.014  1965  2048 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:06.015  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:06.016  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:06.018   192   653 D CommandListener: Setting iface cfg
07-15 15:22:06.053  1744  2886 V NativeCrypto: Read error: ssl=0x99bc9000: I/O error during system call, Connection timed out
07-15 15:22:06.058  1744  2886 V NativeCrypto: SSL shutdown failed: ssl=0x99bc9000: I/O error during system call, Broken pipe
07-15 15:22:06.061  1744  2886 E GCM     : Wifi connection closed with errorCode 20
07-15 15:22:06.061   788  1344 D ConnectivityService: reportNetworkConnectivity(100, false) by 10008
07-15 15:22:06.061   788  2688 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10008
07-15 15:22:06.070   788  2688 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-15 15:22:06.070   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-15 15:22:06.070   788   894 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-15 15:22:06.071   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-15 15:22:06.104  2808  2944 V NativeCrypto: Read error: ssl=0xa093e000: I/O error during system call, Connection timed out
07-15 15:22:06.104  2808  2944 V NativeCrypto: Write error: ssl=0xa093e000: I/O error during system call, Broken pipe
07-15 15:22:06.104  2808  2944 V NativeCrypto: Write error: ssl=0xa093e000: I/O error during system call, Broken pipe
07-15 15:22:06.104  2808  2944 V NativeCrypto: SSL shutdown failed: ssl=0xa093e000: I/O error during system call, Broken pipe
07-15 15:22:06.105   788  2702 D DhcpClient: Receive thread stopped
07-15 15:22:06.106  3561  3561 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-15 15:22:06.109   788   892 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-15 15:22:06.110   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-15 15:22:06.110   788   894 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-15 15:22:06.113  1965  2048 I bt_hci  : shut_down
07-15 15:22:06.114  1965  2057 D bt_hwcfg: hw_epilog_process
07-15 15:22:06.118  1965  2057 I bt_vendor: low_power_mode_cb
07-15 15:22:06.119   788   894 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-15 15:22:06.122   788   788 D RttService: SCAN_AVAILABLE : 1
07-15 15:22:06.123   788   906 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-15 15:22:06.124   788   892 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-15 15:22:06.127   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-15 15:22:06.127   788   892 E native  : do suspend true
07-15 15:22:06.133  3561  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-15 15:22:06.139  1965  2057 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-15 15:22:06.139  1965  2057 I bt_vendor: epilog_cb
07-15 15:22:06.139  1965  2057 I bt_hci  : epilog_finished_callback
07-15 15:22:06.140  1965  2048 I bt_hci_h4: hal_close
07-15 15:22:06.141  1965  2048 I bt_userial_vendor: device fd = 49 close
07-15 15:22:06.141   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8fb97c9:true
07-15 15:22:06.145  1965  2044 D bt_stack_manager: event_shut_down_stack finished.
07-15 15:22:06.145  1965  2040 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-15 15:22:06.146  1965  2040 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-15 15:22:06.146  1965  1965 D BtGatt.DebugUtils: handleDebugAction() action=null
07-15 15:22:06.146  1965  1965 D BtGatt.GattService: Received stop request...Stopping profile...
07-15 15:22:06.146  1965  1965 D BtGatt.GattService: stop()
07-15 15:22:06.146  1965  1965 D BtGatt.AdvertiseManager: advertise clients cleared
,07-15 15:22:06.147  1965  1965 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:06.147  1965  1965 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:06.147  1965  1965 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:06.147  1965  1965 V BluetoothAdapterState: isBleTurningOff()=true
07-15 15:22:06.147  1965  2040 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-15 15:22:06.147  1965  2040 D BluetoothAdapterProperties: Setting state to 10
07-15 15:22:06.147  1965  2040 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-15 15:22:06.147  1965  2040 I BluetoothAdapterState: Entering OffState
07-15 15:22:06.148   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-15 15:22:06.151  1965  1965 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-15 15:22:06.151  1965  1965 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-15 15:22:06.152  1965  1965 I BluetoothServiceJni: cleanupNative: return from cleanup
07-15 15:22:06.152  1965  2044 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-15 15:22:06.154  3561  3561 D LocalBluetoothProfileManager: Adding local MAP profile
07-15 15:22:06.154  1965  2044 D bt_stack_manager: event_clean_up_stack finished.
07-15 15:22:06.155   192   653 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-15 15:22:06.155  1965  1965 I art     : System.exit called, status: 0
07-15 15:22:06.155  1965  1965 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-15 15:22:06.157  3561  3561 D BluetoothMap: Create BluetoothMap proxy object
07-15 15:22:06.161  3561  3561 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-15 15:22:06.177   192   653 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-15 15:22:06.177   192   653 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:06.177   788   894 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-15 15:22:06.177   788   894 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-15 15:22:06.186   788  1344 I ActivityManager: Process com.android.bluetooth (pid 1965) has died
,07-15 15:22:06.188  3561  3561 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:06.189   788   892 D DhcpClient: doQuit
,07-15 15:22:06.189   788   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-15 15:22:06.189   788  2690 D DhcpClient: onQuitting
,07-15 15:22:06.190   788   808 D Tethering: MasterInitialState.processMessage what=3
07-15 15:22:06.191  1394  1394 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:06.196  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:06.196  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:06.196  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:06.197  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:06.198  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:06.205   788   893 D WifiService: New client listening to asynchronous messages
,07-15 15:22:06.222   788  1314 I ActivityManager: Start proc 3602:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,07-15 15:22:06.225   788  1314 I ActivityManager: Killing 2842:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,07-15 15:22:06.245   192   653 E Netd    : netlink response contains error (No such file or directory)
,07-15 15:22:06.245   788   894 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-15 15:22:06.247  1424  1424 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-15 15:22:06.311  1424  1424 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-15 15:22:06.321  1424  1424 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-15 15:22:06.356  3602  3602 D AdapterServiceConfig: Adding HeadsetService
,07-15 15:22:06.357  3602  3602 D AdapterServiceConfig: Adding A2dpService
,07-15 15:22:06.357  3602  3602 D AdapterServiceConfig: Adding HidService
07-15 15:22:06.357  3602  3602 D AdapterServiceConfig: Adding HealthService
07-15 15:22:06.357  3602  3602 D AdapterServiceConfig: Adding PanService
07-15 15:22:06.357  3602  3602 D AdapterServiceConfig: Adding GattService
,07-15 15:22:06.357  3602  3602 D AdapterServiceConfig: Adding BluetoothMapService
,07-15 15:22:06.367  1424  1424 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-15 15:22:06.369   788  1340 I ActivityManager: Start proc 3618:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-15 15:22:06.370   788  1340 I ActivityManager: Killing 2775:com.google.android.apps.photos/u0a65 (adj 15): empty #17
,07-15 15:22:06.387  1424  1424 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-15 15:22:06.489  2252  2252 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-15 15:22:06.489   788   892 D wifi    : In wifi stop Hal
07-15 15:22:06.489   788   892 D wifi    : halHandle = 0x966b8000, mVM = 0xb4dbc000, mCls = 0x100c56
,07-15 15:22:06.489   788  1423 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-15 15:22:06.489   788  1423 D WifiHAL : Got a signal to exit!!!
07-15 15:22:06.489   788  1423 I WifiHAL : Exit wifi_event_loop
07-15 15:22:06.490   788   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
07-15 15:22:06.490   788   892 E WifiHAL : Event processing terminated
,07-15 15:22:06.490   788   892 D wifi    : In wifi cleaned up handler
07-15 15:22:06.490   788   892 I WifiHAL : Internal cleanup completed
07-15 15:22:06.490  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:06.491  1744  1819 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-15 15:22:06.491  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:06.569  3618  3618 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at java.io.File.exists(File.java:361)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.569  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-15 15:22:06.571  3618  3618 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.571  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-15 15:22:06.572  3618  3618 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-15 15:22:06.572  3618  3618 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:170)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.572  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-15 15:22:06.573  3618  3618 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.r.k.d(PG:583)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:170)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.573  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-15 15:22:06.574  3618  3618 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at java.io.File.exists(File.java:361)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:06.574  3618  3618 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at java.io.File.exists(File.java:361)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.574,  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.574  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-15 15:22:06.576  3618  3618 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-15 15:22:06.576  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-15 15:22:06.580   788  1340 I ActivityManager: Killing 2252:com.google.android.talk/u0a54 (adj 15): empty #17
,07-15 15:22:06.598   788  1423 D wifi    : set interface wlan0 flags (DOWN)
,07-15 15:22:06.598   788   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-15 15:22:06.616  3618  3639 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-15 15:22:06.619  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:06.622  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:06.626   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f9d2271:true
,07-15 15:22:06.626  3561  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:22:06.635  3561  3561 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:06.651  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:06.659  1744  3648 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:22:06.660  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:06.674   788   962 I ActivityManager: Start proc 3649:com.google.android.talk/u0a54 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,07-15 15:22:06.691  1744  3648 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-15 15:22:06.801   788   808 D Tethering: InitialState.processMessage what=4
,07-15 15:22:06.802   788   808 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-15 15:22:06.840  3649  3666 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-15 15:22:06.841  3649  3666 I Babel_SMS: MmsConfig.loadMmsSettings
07-15 15:22:06.841  3649  3666 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
07-15 15:22:06.841  3649  3666 I Babel_SMS: MmsConfig.loadFromDatabase
,07-15 15:22:06.855  3649  3666 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-15 15:22:06.855  3649  3666 I Babel_SMS: MmsConfig.loadFromResources
,07-15 15:22:06.857  3649  3666 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-15 15:22:06.858  3649  3666 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,07-15 15:22:06.867  3649  3669 I Babel_SMS: ApnsOta: OTA version -1
,07-15 15:22:06.880  3649  3670 I Babel   : deleted: false for 0
,07-15 15:22:06.881  3649  3649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-15 15:22:06.885  3649  3649 I Babel_Crash: startup - clean
,07-15 15:22:06.896  3649  3649 I Babel_telephony: TeleModule.launchCompleted
,07-15 15:22:06.901   788   799 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-15 15:22:06.904  3649  3649 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-15 15:22:06.904  3649  3649 W Babel   : BAM#gBA: invalid account id: -1
07-15 15:22:06.905  3649  3649 W Babel   : BAM#gBA: invalid account id: -1
07-15 15:22:06.905  3649  3649 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-15 15:22:06.909   788  1340 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-15 15:22:06.942   788  1585 I ActivityManager: Start proc 3677:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-15 15:22:06.980  3649  3649 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-15 15:22:07.040  3649  3649 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-15 15:22:07.045  3649  3649 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-15 15:22:07.046  3649  3649 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-15 15:22:07.049  3649  3649 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-15 15:22:07.059  3649  3649 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-15 15:22:07.071  3649  3649 I vclib   : onServiceConnected
,07-15 15:22:07.083   788   799 I ActivityManager: Start proc 3693:com.google.android.apps.photos/u0a65 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-15 15:22:07.085  3649  3692 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-15 15:22:07.088   788  1314 I ActivityManager: Killing 2063:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-15 15:22:07.144  3693  3693 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-15 15:22:07.258   788  1342 I ActivityManager: Killing 3131:com.google.android.gms:car/u0a8 (adj 15): empty #17
,07-15 15:22:07.856  1636  1636 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-15 15:22:07.886  1636  2840 I iu.UploadsManager: num queued entries: 0
,07-15 15:22:07.908   788  1326 I ActivityManager: Start proc 3711:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-15 15:22:07.933  1636  2840 I iu.UploadsManager: num updated entries: 0
,07-15 15:22:07.934  1636  2840 I iu.SyncManager: NEXT; no task
,07-15 15:22:07.938  3711  3711 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-15 15:22:07.979  3711  3711 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-15 15:22:07.979  3711  3711 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-15 15:22:07.979  3711  3711 I GAv4    :   adb logcat -s GAv4
,07-15 15:22:07.986  3711  3711 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:22:07.990  3711  3711 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:22:07.994  3711  3737 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-15 15:22:08.071  3711  3711 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-15 15:22:08.125  3711  3711 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3314-3318)
07-15 15:22:08.126  3711  3711 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:22:08.139  3711  3711 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c1132bc}
,07-15 15:22:08.139  3711  3711 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:22:08.140  3711  3711 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-15 15:22:08.149  3711  3711 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-15 15:22:08.151  3711  3711 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-15 15:22:08.166  3711  3711 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-15 15:22:08.174  3711  3711 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-15 15:22:08.174  3711  3711 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-15 15:22:08.174  3711  3711 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-15 15:22:08.229  3711  3776 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-15 15:22:08.231  3711  3711 I NSApplication: Starting up...
,07-15 15:22:08.239   788   798 I ActivityManager: Killing 3275:com.google.android.gms.unstable/u0a8 (adj 15): empty #17
,07-15 15:22:08.424   788  1340 I ActivityManager: Start proc 3790:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-15 15:22:08.449  3790  3790 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-15 15:22:08.477  3790  3790 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-15 15:22:08.483   788  1303 I ActivityManager: Killing 2571:android.process.acore/u0a4 (adj 15): empty #17
,07-15 15:22:08.959   788  1585 D WifiService: setWifiEnabled: true pid=3491, uid=10000
,07-15 15:22:08.959   788  1585 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:08.964   192   653 D SoftapController: Softap fwReload - Ok
07-15 15:22:08.968   192   653 D CommandListener: Setting iface cfg
,07-15 15:22:08.968   192   653 D CommandListener: Trying to bring down wlan0
,07-15 15:22:08.970   192   653 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:08.975   788   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-15 15:22:09.734   788   892 D wifi    : set interface wlan0 flags (UP)
,07-15 15:22:09.734   788   892 I WifiHAL : Initializing wifi
,07-15 15:22:09.734   788   892 I WifiHAL : Creating socket
,07-15 15:22:09.735   788   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-15 15:22:09.735   788   892 D wifi    : Did set static halHandle = 0x966b8000
,07-15 15:22:09.735   788   892 D wifi    : halHandle = 0x966b8000, mVM = 0xb4dbc000, mCls = 0x201482
07-15 15:22:09.735   788   892 D wifi    : array field set
07-15 15:22:09.735   788   892 I WifiNative-HAL: interface[0] = p2p0
,07-15 15:22:09.735   788   892 I WifiNative-HAL: interface[1] = wlan0
,07-15 15:22:09.736   788   808 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-15 15:22:09.741  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:09.741  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:09.743   788   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-15 15:22:09.744   788  3824 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1771339776
07-15 15:22:09.744   788  3824 D wifi    : waitForHalEvents called, vm = 0xb4dbc000, obj = 0x201482, env = 0xa082ef60
,07-15 15:22:09.797  3825  3825 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-15 15:22:09.835  3825  3825 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:22:09.847  3825  3825 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:09.871  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:09.871  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:09.872  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:09.872  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:09.873   788   892 D WifiConfigStore: Loading config and enabling all networks 
,07-15 15:22:09.882   788   892 D WifiConfigStore: loaded 0 passpoint configs
,07-15 15:22:09.883   788   892 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-15 15:22:09.883   788   892 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-15 15:22:09.884   788   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-15 15:22:09.884   788   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-15 15:22:09.884   788   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-15 15:22:09.884   788   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-15 15:22:09.884   788   892 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-15 15:22:09.887   788   892 D WifiNative-HAL: Setting external_sim to 1
,07-15 15:22:09.887  3649  3649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-15 15:22:09.887   788   892 D wifi    : setting dfs flag to true, 0x98044718
,07-15 15:22:09.887   788   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-15 15:22:09.888   788   892 D wifi    : setting scan oui 0x98044718
,07-15 15:22:09.888   788   892 D WifiHAL : Sending mac address OUI
,07-15 15:22:09.901   788   892 E native  : do suspend true
,07-15 15:22:09.906   788   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-15 15:22:09.906   788   788 D RttService: SCAN_AVAILABLE : 3
07-15 15:22:09.907   192   653 D CommandListener: Setting iface cfg
07-15 15:22:09.907   788   906 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-15 15:22:09.907   192   653 D CommandListener: Trying to bring up p2p0
07-15 15:22:09.907   788   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-15 15:22:09.907   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:22:09.917   788   891 D WifiNative-HAL: p2pGetDeviceAddress
,07-15 15:22:09.918   788   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-15 15:22:11.703   788   798 I ActivityManager: Killing 3374:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-15 15:22:11.964   788   968 D WifiService: setWifiEnabled: false pid=3491, uid=10000
,07-15 15:22:11.964   788   968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-15 15:22:11.965   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:22:11.972   788   788 D RttService: SCAN_AVAILABLE : 1
,07-15 15:22:11.972   788   906 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-15 15:22:11.977   788   892 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-15 15:22:11.977   192   653 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:11.979   788   892 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:11.984  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:11.984  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:11.984  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:12.023  3825  3825 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-15 15:22:13.026  3825  3825 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-15 15:22:13.041  3825  3825 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-15 15:22:13.047  3825  3825 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-15 15:22:13.051   788   892 D wifi    : In wifi stop Hal
07-15 15:22:13.051   788   892 D wifi    : halHandle = 0x966b8000, mVM = 0xb4dbc000, mCls = 0x201482
07-15 15:22:13.052   788  3824 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,07-15 15:22:13.052   788  3824 D WifiHAL : Got a signal to exit!!!
,07-15 15:22:13.052   788  3824 I WifiHAL : Exit wifi_event_loop
07-15 15:22:13.054  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:13.054  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:13.054  1744  1819 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-15 15:22:13.056   788   892 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,07-15 15:22:13.056   788   892 E WifiHAL : Event processing terminated
07-15 15:22:13.056   788   892 D wifi    : In wifi cleaned up handler
07-15 15:22:13.056   788   892 I WifiHAL : Internal cleanup completed
07-15 15:22:13.057  3649  3649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-15 15:22:13.178   788  3824 D wifi    : set interface wlan0 flags (DOWN)
,07-15 15:22:13.178   788   892 D WifiNative-HAL: HAL event thread stopped successfully
,07-15 15:22:13.391   788   808 D Tethering: InitialState.processMessage what=4
,07-15 15:22:13.415   788   808 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-15 15:22:15.024   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b9f2a2:true
,07-15 15:22:15.024  3602  3602 D BluetoothAdapterState: make() - Creating AdapterState
,07-15 15:22:15.026  3602  3602 I bt_bluedroid: init
,07-15 15:22:15.027  3602  3842 I BluetoothAdapterState: Entering OffState
,07-15 15:22:15.028  3602  3843 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-15 15:22:15.028  3602  3843 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-15 15:22:15.028  3602  3843 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-15 15:22:15.029  3602  3843 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-15 15:22:15.029  3602  3602 I bt_bluedroid: get_profile_interface socket
,07-15 15:22:15.030  3602  3602 I bt_bluedroid: get_profile_interface sdp
07-15 15:22:15.032  3602  3613 I bt_bluedroid: config_hci_snoop_log
07-15 15:22:15.032   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
07-15 15:22:15.035  3602  3842 D BluetoothAdapterState: Current state: OFF, message: 0
,07-15 15:22:15.035  3602  3842 D BluetoothAdapterProperties: Setting state to 14
,07-15 15:22:15.035  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-15 15:22:15.035  3602  3842 D BluetoothBondStateMachine: make
,07-15 15:22:15.037  3602  3846 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-15 15:22:15.038  3602  3846 D BluetoothAdapterProperties: Name is: Nexus 5
07-15 15:22:15.041  3602  3602 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-15 15:22:15.043  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:15.043  3602  3842 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:15.043  3602  3602 D BtGatt.DebugUtils: handleDebugAction() action=null
07-15 15:22:15.043  3602  3602 D BtGatt.GattService: Received start request. Starting profile...
07-15 15:22:15.043  3602  3602 D BtGatt.GattService: start()
07-15 15:22:15.043  3602  3602 I bt_bluedroid: get_profile_interface gatt
07-15 15:22:15.044  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
,07-15 15:22:15.044  3602  3602 D BtGatt.AdvertiseManager: advertise manager created
07-15 15:22:15.044  3602  3847 I BluetoothBondStateMachine: StableState(): Entering Off State
07-15 15:22:15.049  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:15.049  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:15.049  3602  3602 V BluetoothAdapterState: isBleTurningOn()=true
07-15 15:22:15.049  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:15.049  3602  3842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-15 15:22:15.049  3602  3842 I bt_bluedroid: enable
07-15 15:22:15.050  3602  3843 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-15 15:22:15.050  3602  3843 I bt_hci  : start_up
07-15 15:22:15.054  3602  3843 I bt_vendor: alloc value 0xb39f9631
07-15 15:22:15.054  3602  3843 I bt_vendor: init
07-15 15:22:15.054  3602  3843 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-15 15:22:15.054  3602  3843 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-15 15:22:15.086  3602  3843 D bt_hci  : start_up starting async portion
,07-15 15:22:15.087  3602  3850 I bt_hci  : event_finish_startup
07-15 15:22:15.087  3602  3850 I bt_hci_h4: hal_open
07-15 15:22:15.087  3602  3850 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-15 15:22:15.090  3602  3850 I bt_userial_vendor: device fd = 49 open
,07-15 15:22:15.176  3602  3850 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:22:15.203  3602  3850 D bt_hwcfg: Chipset BCM4335C0
,07-15 15:22:15.203  3602  3850 D bt_hwcfg: Target name = [BCM4335C0]
07-15 15:22:15.203  3602  3850 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-15 15:22:15.675  3602  3850 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-15 15:22:15.675  3602  3850 D bt_hwcfg: Settlement delay -- 100 ms
,07-15 15:22:15.675  3602  3850 I bt_hwcfg: Setting fw settlement delay to 100 
,07-15 15:22:15.793  3602  3850 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:22:15.794  3602  3850 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-15 15:22:15.821  3602  3850 I bt_hwcfg: vendor lib fwcfg completed
,07-15 15:22:15.821  3602  3850 I bt_vendor: firmware callback
,07-15 15:22:15.821  3602  3850 I bt_hci  : firmware_config_callback
,07-15 15:22:15.832  3602  3852 I bt_btu  : btu_task pending for preload complete event
,07-15 15:22:15.832  3602  3852 I bt_btu_task: Bluetooth chip preload is complete
,07-15 15:22:15.832  3602  3852 I bt_btu  : btu_task received preload complete event
,07-15 15:22:15.841  3602  3852 I         : BTE_InitTraceLevels -- TRC_HCI
,07-15 15:22:15.841  3602  3852 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_AVRC
07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_A2D
,07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_BTM
,07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_GAP
07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_PAN
,07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_SDP
07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_GATT
,07-15 15:22:15.842  3602  3852 I         : BTE_InitTraceLevels -- TRC_SMP
,07-15 15:22:15.843  3602  3852 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-15 15:22:15.843  3602  3852 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-15 15:22:16.078  3602  3852 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39779b5
,07-15 15:22:16.078  3602  3852 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39779b5 
,07-15 15:22:16.258  3602  3846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:22:16.258  3602  3846 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-15 15:22:16.278  3602  3846 D BluetoothAdapterProperties: Name is: Nexus 5
07-15 15:22:16.283  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:16.286  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:16.286  3602  3846 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:16.287  3602  3846 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:22:16.287  3602  3846 D bt_hci  : do_postload posting postload work item
07-15 15:22:16.287  3602  3850 I bt_hci  : event_postload
07-15 15:22:16.287  3602  3850 I bt_vendor: sco_config_cb
07-15 15:22:16.287  3602  3850 I bt_hci  : sco_config_callback postload finished.
,07-15 15:22:16.290  3602  3846 D bt_bte_conf: Device ID record 1 : primary
,07-15 15:22:16.290  3602  3846 D bt_bte_conf:   vendorId            = 000f
,07-15 15:22:16.290  3602  3846 D bt_bte_conf:   vendorIdSource      = 0001
,07-15 15:22:16.290  3602  3846 D bt_bte_conf:   product             = 1200
,07-15 15:22:16.290  3602  3846 D bt_bte_conf:   version             = 1436
,07-15 15:22:16.290  3602  3846 D bt_bte_conf:   clientExecutableURL = 
,07-15 15:22:16.290  3602  3846 D bt_bte_conf:   serviceDescription  = 
,07-15 15:22:16.290  3602  3846 D bt_bte_conf:   documentationURL    = 
07-15 15:22:16.291  3602  3846 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-15 15:22:16.291  3602  3843 D bt_stack_manager: event_start_up_stack finished
,07-15 15:22:16.292  3602  3842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-15 15:22:16.292  3602  3842 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:16.293  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-15 15:22:16.298  3602  3842 I BluetoothAdapterState: Entering BleOnState
07-15 15:22:16.298  3602  3842 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-15 15:22:16.298  3602  3842 D BluetoothAdapterProperties: Setting state to 11
07-15 15:22:16.299  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-15 15:22:16.300  3602  3850 I bt_vendor: low_power_mode_cb
07-15 15:22:16.310  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:16.311  3602  3602 D HeadsetService: Received start request. Starting profile...
07-15 15:22:16.312  3602  3602 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-15 15:22:16.312  3602  3602 D HeadsetStateMachine: make
07-15 15:22:16.318  3602  3842 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:16.332  3602  3602 D HeadsetStateMachine: max_hf_connections = 1
07-15 15:22:16.332  3602  3602 I bt_bluedroid: get_profile_interface handsfree
07-15 15:22:16.338  3602  3846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-15 15:22:16.338  3602  3846 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-15 15:22:16.340  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:16.341  3602  3602 D A2dpService: Received start request. Starting profile...
07-15 15:22:16.341  3602  3602 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-15 15:22:16.342  3602  3602 I bt_bluedroid: get_profile_interface avrcp
07-15 15:22:16.355  3602  3602 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-15 15:22:16.356  3602  3602 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-15 15:22:16.356  3602  3602 D A2dpStateMachine: make
,07-15 15:22:16.356  3602  3602 I bt_bluedroid: get_profile_interface a2dp
07-15 15:22:16.358  3602  3846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-15 15:22:16.368  3602  3602 I BluetoothHidServiceJni: classInitNative: succeeds
07-15 15:22:16.368  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:16.369  3602  3602 D HidService: Received start request. Starting profile...
07-15 15:22:16.369  3602  3602 I bt_bluedroid: get_profile_interface hidhost
07-15 15:22:16.369  3602  3846 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3959099
07-15 15:22:16.369  3602  3846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-15 15:22:16.369  3602  3602 D HidService: setHidService(): set to: null
07-15 15:22:16.370  3602  3602 I BluetoothHealthServiceJni: classInitNative: succeeds
07-15 15:22:16.370  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:16.371  3602  3868 D A2dpStateMachine: Enter Disconnected: -2
07-15 15:22:16.371  3602  3602 D HealthService: Received start request. Starting profile...
07-15 15:22:16.376  3602  3602 I bt_bluedroid: get_profile_interface health
,07-15 15:22:16.379  3602  3602 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-15 15:22:16.379  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:16.380  3602  3602 D PanService: Received start request. Starting profile...
07-15 15:22:16.380  3602  3602 D BluetoothPanServiceJni: initializeNative(L110): pan
07-15 15:22:16.380  3602  3602 I bt_bluedroid: get_profile_interface pan
07-15 15:22:16.381  3602  3846 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-15 15:22:16.382  3602  3602 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:16.383  3602  3602 D BluetoothMapService: Received start request. Starting profile...
07-15 15:22:16.383  3602  3602 D BluetoothMapService: start()
07-15 15:22:16.386  3602  3602 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-15 15:22:16.387  3602  3602 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:22:16.387  3602  3602 D BluetoothMapAppObserver: createReceiver()
07-15 15:22:16.387  3602  3602 D BluetoothMapAppObserver: initObservers()
07-15 15:22:16.387  3602  3602 D BluetoothMapAppObserver: getEnabledAccountItems()
07-15 15:22:16.390  3561  3561 D BluetoothInputDevice: Proxy object connected
07-15 15:22:16.390  3561  3561 D HidProfile: Bluetooth service connected
07-15 15:22:16.397  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:16.397  3602  3602 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:16.397  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:16.397  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:16.398  3602  3865 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:16.399  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:16.401  3602  3842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-15 15:22:16.401  3602  3842 D BluetoothAdapterProperties: ScanMode =  20
07-15 15:22:16.401  3602  3842 D BluetoothAdapterProperties: State =  11
07-15 15:22:16.401  3602  3842 D BluetoothAdapterProperties: Setting state to 12
07-15 15:22:16.401  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-15 15:22:16.402   788   808 D BluetoothHeadset: onBl,uetoothStateChange: up=true
07-15 15:22:16.402   926  1634 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:16.403  3602  3846 D BluetoothAdapterProperties: Scan Mode:21
07-15 15:22:16.403  3602  3846 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:22:16.403   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:16.404   926  1349 D BluetoothPbap: onBluetoothStateChange: up=true
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:16.407  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:16.408  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:16.409  3602  3842 I BluetoothAdapterState: Entering OnState
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:16.410  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:16.411  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:16.412  3561  3574 D BluetoothPbap: onBluetoothStateChange: up=true
07-15 15:22:16.413  1298  1313 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:16.413   926   952 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:16.414   926  1633 D BluetoothPan: onBluetoothStateChange on: true
07-15 15:22:16.416   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:16.416   926  1349 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:22:16.416  3602  3602 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-15 15:22:16.418   788   808 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:22:16.419  3561  3572 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:22:16.419  3561  3574 D BluetoothPan: onBluetoothStateChange on: true
07-15 15:22:16.420   926   952 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:22:16.421  3561  3572 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:16.423   788   788 I Telecom : BluetoothPhoneService: queryPhoneState
07-15 15:22:16.425  3602  3602 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-15 15:22:16.426  3561  3561 D BluetoothPan: BluetoothPAN Proxy object connected
07-15 15:22:16.426  3602  3602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:22:16.426  3561  3561 D PanProfile: Bluetooth service connected
07-15 15:22:16,.426  3561  3561 D BluetoothMap: Proxy object connected
07-15 15:22:16.427  3561  3561 D MapProfile: Bluetooth service connected
07-15 15:22:16.427  3561  3561 D BluetoothMap: getConnectedDevices()
07-15 15:22:16.430  3602  3602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:22:16.431  3602  3602 D ObexServerSockets: Succeed to create listening sockets 
07-15 15:22:16.431  3602  3602 D ObexServerSockets0: startAccept()
07-15 15:22:16.431  3602  3602 D ObexServerSockets0: prepareForNewConnect()
07-15 15:22:16.432   926   926 D BluetoothMap: Proxy object connected
07-15 15:22:16.432   926   926 D MapProfile: Bluetooth service connected
07-15 15:22:16.432   926   926 D BluetoothMap: getConnectedDevices()
07-15 15:22:16.433  3602  3602 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-15 15:22:16.433  3602  3602 D BluetoothSdpJni: SDP Create record success - handle: 0
07-15 15:22:16.434  3602  3883 D ObexServerSockets0: Accepting socket connection...
07-15 15:22:16.434   788   788 D BluetoothA2dp: Proxy object connected
07-15 15:22:16.435  3602  3602 D BluetoothMapService: onReceive
07-15 15:22:16.435  3602  3602 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:22:16.435  3602  3602 D BluetoothMapService: STATE_ON
07-15 15:22:16.436  3602  3884 D ObexServerSockets0: Accepting socket connection...
07-15 15:22:16.439   926   926 D BluetoothPan: BluetoothPAN Proxy object connected
07-15 15:22:16.439   926   926 D PanProfile: Bluetooth service connected
07-15 15:22:16.439   926   926 D BluetoothInputDevice: Proxy object connected
07-15 15:22:16.439   926   926 D HidProfile: Bluetooth service connected
07-15 15:22:16.441   926   926 D BluetoothA2dp: Proxy object connected
,07-15 15:22:16.451  3561  3561 D LocalBluetoothProfileManager: Adding local A2DP profile,
,07-15 15:22:16.454  3561  3561 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-15 15:22:16.456  3602  3602 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-15 15:22:16.456  3602  3602 D ObexServerSockets0: prepareForNewConnect()
,07-15 15:22:16.457  3561  3561 D BluetoothA2dp: Proxy object connected
,07-15 15:22:16.469  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:16.471  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:16.473  3561  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:22:16.477  3561  3561 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:16.482   926   926 D BluetoothPbap: Proxy object connected
07-15 15:22:16.482   926   926 D PbapServerProfile: Bluetooth service connected
,07-15 15:22:16.483  3561  3561 D BluetoothPbap: Proxy object connected
07-15 15:22:16.483  3561  3561 D PbapServerProfile: Bluetooth service connected
,07-15 15:22:16.485  3602  3895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:16.491  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:16.495  1744  3898 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:22:16.496  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:16.507   788   788 D BluetoothHeadset: Proxy object connected
,07-15 15:22:16.507   788   788 D BluetoothHeadset: Proxy object connected
,07-15 15:22:16.507   926  1349 D BluetoothHeadset: Proxy object connected
07-15 15:22:16.507   926   926 D HeadsetProfile: Bluetooth service connected
07-15 15:22:16.507   788   788 D BluetoothHeadset: Proxy object connected
07-15 15:22:16.508  1298  1533 D BluetoothHeadset: Proxy object connected
07-15 15:22:16.508  1744  3898 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
07-15 15:22:16.509  3602  3902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:16.510  3602  3902 I BtOppRfcommListener: Accept thread started.
,07-15 15:22:16.513  1298  1319 D BluetoothHeadset: Proxy object connected
,07-15 15:22:16.516   788   808 D BluetoothHeadset: Proxy object connected
,07-15 15:22:16.555  3561  3878 D BluetoothHeadset: Proxy object connected
,07-15 15:22:16.555  3561  3561 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:16.919   190   190 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c4a030
,07-15 15:22:16.920   190   190 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,07-15 15:22:16.920   190   190 I rmt_storage: wakelock acquired: 1, error no: 2
07-15 15:22:16.920   190   485 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228670672)
,07-15 15:22:16.995   190   485 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,07-15 15:22:16.995   190   485 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
07-15 15:22:16.995   190   485 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228670672) wakelock released: 1, error no: 0
07-15 15:22:16.995   190   485 I rmt_storage: 
,07-15 15:22:16.997   190   190 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c4a030
,07-15 15:22:17.987  3602  3842 D BluetoothAdapterState: Current state: ON, message: 23
,07-15 15:22:17.987  3602  3842 D BluetoothAdapterProperties: Setting state to 13
07-15 15:22:17.987  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-15 15:22:17.989  3602  3842 D BluetoothAdapterProperties: onBluetoothDisable()
07-15 15:22:18.031  3602  3842 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:18.032  3602  3846 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:18.033  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:18.033  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:18.034  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:18.034  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:18.034  3602  3842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-15 15:22:18.035  3602  3602 D HeadsetService: Received stop request...Stopping profile...
07-15 15:22:18.037  3602  3602 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:18.037  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:18.037  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:18.037  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:18.038  3602  3602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-15 15:22:18.038  3602  3602 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-15 15:22:18.038  3602  3852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:22:18.038  3602  3852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:18.038  3602  3846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-15 15:22:18.039  3602  3846 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-15 15:22:18.039   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:18.039   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:18.040   926  1633 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:18.040   926   926 D HeadsetProfile: Bluetooth service disconnected
07-15 15:22:18.040  3561  3574 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:18.040   788   788 D BluetoothHeadset: Proxy object disconnected
07-15 15:22:18.040  1298  1450 D BluetoothHeadset: Proxy object disconnected
,07-15 15:22:18.048  3602  3602 D BluetoothMapService: onReceive
07-15 15:22:18.048  3602  3602 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:22:18.048  3602  3602 D BluetoothMapService: STATE_TURNING_OFF
07-15 15:22:18.048  3602  3602 D BluetoothMapService: MAP Service closeService in
07-15 15:22:18.049  3602  3602 D BluetoothMapMasInstance0: MAP Service shutdown
07-15 15:22:18.049  3602  3602 D ObexServerSockets0: shutdown(block = true)
07-15 15:22:18.049  3602  3602 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:22:18.049  3602  3602 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-15 15:22:18.049  3602  3883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,07-15 15:22:18.049  3602  3859 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-15 15:22:18.050  3602  3884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-15 15:22:18.051  3602  3602 I BtOppRfcommListener: stopping Accept Thread
07-15 15:22:18.051  3602  3902 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-15 15:22:18.051  3602  3902 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-15 15:22:18.056  3602  3602 D A2dpService: Received stop request...Stopping profile...
07-15 15:22:18.057  3602  3868 D A2dpStateMachine: Exit Disconnected: -1
07-15 15:22:18.058   926   926 D BluetoothA2dp: Proxy object disconnected
,07-15 15:22:18.058   788   788 D BluetoothA2dp: Proxy object disconnected
,07-15 15:22:18.060  3602  3602 V BluetoothAdapterState: isTurningOff()=true
,07-15 15:22:18.060  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:18.060  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:18.060  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:18.061  3602  3852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:18.061  3602  3852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-15 15:22:18.062  3602  3852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:22:18.062  3602  3852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-15 15:22:18.062  3602  3852 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-15 15:22:18.062  3602  3852 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-15 15:22:18.062  3602  3846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-15 15:22:18.145  3602  3602 D HidService: Received stop request...Stopping profile...
07-15 15:22:18.145  3602  3602 D HidService: Stopping Bluetooth HidService
07-15 15:22:18.145   926   926 D BluetoothInputDevice: Proxy object disconnected
07-15 15:22:18.145   926   926 D HidProfile: Bluetooth service disconnected
07-15 15:22:18.147  3602  3602 D HealthService: Received stop request...Stopping profile...
07-15 15:22:18.156  3602  3602 D PanService: Received stop request...Stopping profile...
07-15 15:22:18.157   926   926 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-15 15:22:18.157   926   926 D PanProfile: Bluetooth service disconnected
,07-15 15:22:18.158  3602  3602 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:18.158  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:18.158  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:18.158  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:18.158  3602  3602 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,07-15 15:22:18.158  3602  3846 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:22:18.158  3602  3602 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-15 15:22:18.159  3602  3602 D BluetoothMapService: Received stop request...Stopping profile...
07-15 15:22:18.159  3602  3602 D BluetoothMapService: stop()
07-15 15:22:18.159  3602  3602 D BluetoothMapAppObserver: deinitObservers()
07-15 15:22:18.159  3602  3602 D BluetoothMapAppObserver: removeReceiver()
07-15 15:22:18.160   926   926 D BluetoothMap: Proxy object disconnected
07-15 15:22:18.160   926   926 D MapProfile: Bluetooth service disconnected
07-15 15:22:18.160  3602  3602 V BluetoothAdapterState: isTurningOff()=true
,07-15 15:22:18.160  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:18.160  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:18.160  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:18.160  3602  3602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-15 15:22:18.160  3602  3846 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-15 15:22:18.161  3602  3602 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-15 15:22:18.161  3602  3602 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:18.161  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:18.161  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:22:18.161  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:18.166  3602  3602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-15 15:22:18.187  3602  3602 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-15 15:22:18.188  3602  3602 D BluetoothMapService: MAP Service closeService in
07-15 15:22:18.189  3602  3602 V BluetoothAdapterState: isTurningOff()=true
07-15 15:22:18.189  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:18.189  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:18.189  3602  3602 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:18.189  3602  3842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,07-15 15:22:18.189  3602  3842 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:18.189  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,07-15 15:22:18.189   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:18.190   926  1633 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:18.190   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:18.190   926  1634 D BluetoothPbap: onBluetoothStateChange: up=false
07-15 15:22:18.191  3561  3572 D BluetoothPbap: onBluetoothStateChange: up=false
07-15 15:22:18.191  3602  3842 I BluetoothAdapterState: Entering BleOnState
07-15 15:22:18.192  1298  1534 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-15 15:22:18.192   926   952 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:22:18.192   926   946 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:22:18.193   788   808 D BluetoothHeadset: onBluetoothStateChange: up=false
07-15 15:22:18.193   926  1349 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:18.193   788   808 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:18.193  3561  3878 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-15 15:22:18.194  3561  3574 D BluetoothA2dp: onBluetoothStateChange: up=false
07-15 15:22:18.194  3561  3572 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-15 15:22:18.195  3561  3878 D BluetoothPan: onBluetoothStateChange on: false
07-15 15:22:18.196   926  1633 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-15 15:22:18.197  3561  3574 D BluetoothMap: onBluetoothStateChange: up=false
07-15 15:22:18.197  3602  3602 D BluetoothMapService: cleanup()
07-15 15:22:18.197  3602  3602 D BluetoothMapService: MAP Service closeService in
07-15 15:22:18.198  3602  3842 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-15 15:22:18.198  3602  3842 D BluetoothAdapterProperties: Setting state to 16
,07-15 15:22:18.198  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-15 15:22:18.198  3602  3842 D BluetoothAdapterProperties: onBleDisable
07-15 15:22:18.198  3602  3842 I BluetoothAdapterState: Entering PendingCommandState
07-15 15:22:18.198  3602  3843 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-15 15:22:18.199  3602  3846 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:18.200  3602  3852 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
07-15 15:22:18.200  3602  3852 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-15 15:22:18.201  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:18.202  3561  3561 D HeadsetProfile: Bluetooth service disconnected
07-15 15:22:18.203  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:18.209  3561  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-15 15:22:18.217  3561  3561 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:18.275  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:18.278  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:18.280  3561  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:22:18.284  3561  3561 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:18.292  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:18.296  1744  3942 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:22:18.297  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:18.303  1744  3942 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-15 15:22:18.307  3602  3846 I bt_hci  : shut_down
,07-15 15:22:18.309  3602  3850 D bt_hwcfg: hw_epilog_process
,07-15 15:22:18.310  3602  3850 I bt_vendor: low_power_mode_cb
,07-15 15:22:18.332  3602  3850 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-15 15:22:18.332  3602  3850 I bt_vendor: epilog_cb
07-15 15:22:18.332  3602  3850 I bt_hci  : epilog_finished_callback
,07-15 15:22:18.333  3602  3846 I bt_hci_h4: hal_close
,07-15 15:22:18.334  3602  3846 I bt_userial_vendor: device fd = 49 close
,07-15 15:22:18.338  3602  3843 D bt_stack_manager: event_shut_down_stack finished.
07-15 15:22:18.338  3602  3842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-15 15:22:18.339  3602  3602 D BtGatt.DebugUtils: handleDebugAction() action=null
07-15 15:22:18.339  3602  3842 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-15 15:22:18.339  3602  3602 D BtGatt.GattService: Received stop request...Stopping profile...
07-15 15:22:18.340  3602  3602 D BtGatt.GattService: stop()
07-15 15:22:18.340  3602  3602 D BtGatt.AdvertiseManager: advertise clients cleared
,07-15 15:22:18.340  3602  3602 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:18.340  3602  3602 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:18.340  3602  3602 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:18.340  3602  3602 V BluetoothAdapterState: isBleTurningOff()=true
,07-15 15:22:18.341  3602  3842 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-15 15:22:18.341  3602  3842 D BluetoothAdapterProperties: Setting state to 10
07-15 15:22:18.341  3602  3842 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-15 15:22:18.341  3602  3842 I BluetoothAdapterState: Entering OffState
07-15 15:22:18.341   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-15 15:22:18.344  3602  3602 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-15 15:22:18.344  3602  3602 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-15 15:22:18.345  3602  3602 I BluetoothServiceJni: cleanupNative: return from cleanup
07-15 15:22:18.345  3602  3843 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-15 15:22:18.347  3602  3843 D bt_stack_manager: event_clean_up_stack finished.
,07-15 15:22:18.347  3602  3602 I art     : System.exit called, status: 0
07-15 15:22:18.347  3602  3602 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-15 15:22:18.367   788   798 I ActivityManager: Process com.android.bluetooth (pid 3602) has died
,07-15 15:22:21.040  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
,07-15 15:22:21.041  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:22:24.051  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:24.051  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b598c7b added. We now have 6 listener(s)
,07-15 15:22:24.051  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:22:24.055  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-15 15:22:24.055  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@107a98 added. We now have 7 listener(s)
,07-15 15:22:24.055  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:24.056  3491  3549 I System.out: IsBluetoothEnabled
07-15 15:22:24.070  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:24.106   788   808 I ActivityManager: Start proc 3956:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-15 15:22:24.157  3956  3956 D AdapterServiceConfig: Adding HeadsetService
,07-15 15:22:24.157  3956  3956 D AdapterServiceConfig: Adding A2dpService
07-15 15:22:24.157  3956  3956 D AdapterServiceConfig: Adding HidService
07-15 15:22:24.157  3956  3956 D AdapterServiceConfig: Adding HealthService
07-15 15:22:24.157  3956  3956 D AdapterServiceConfig: Adding PanService
07-15 15:22:24.157  3956  3956 D AdapterServiceConfig: Adding GattService
07-15 15:22:24.158  3956  3956 D AdapterServiceConfig: Adding BluetoothMapService
,07-15 15:22:24.167   788   808 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d26aba:true
,07-15 15:22:24.167  3956  3956 D BluetoothAdapterState: make() - Creating AdapterState
,07-15 15:22:24.170  3956  3956 I bt_bluedroid: init
07-15 15:22:24.170  3956  3980 I BluetoothAdapterState: Entering OffState
,07-15 15:22:24.172  3956  3981 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-15 15:22:24.172  3956  3981 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-15 15:22:24.172  3956  3981 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-15 15:22:24.172  3956  3981 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-15 15:22:24.173  3956  3956 I bt_bluedroid: get_profile_interface socket
07-15 15:22:24.174  3956  3956 I bt_bluedroid: get_profile_interface sdp
,07-15 15:22:24.174  3956  3984 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-15 15:22:24.176  3956  3984 D BluetoothAdapterProperties: Name is: Nexus 5
,07-15 15:22:24.176  3956  3967 I bt_bluedroid: config_hci_snoop_log
,07-15 15:22:24.177   788   808 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-15 15:22:24.179  3956  3980 D BluetoothAdapterState: Current state: OFF, message: 0
,07-15 15:22:24.179  3956  3980 D BluetoothAdapterProperties: Setting state to 14
07-15 15:22:24.179  3956  3980 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-15 15:22:24.181  3956  3980 D BluetoothBondStateMachine: make
,07-15 15:22:24.182  3956  3987 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-15 15:22:24.184  3956  3980 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:22:24.185  3956  3956 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-15 15:22:24.188  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
,07-15 15:22:24.188  3956  3956 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-15 15:22:24.188  3956  3956 D BtGatt.GattService: Received start request. Starting profile...
,07-15 15:22:24.188  3956  3956 D BtGatt.GattService: start()
,07-15 15:22:24.189  3956  3956 I bt_bluedroid: get_profile_interface gatt
07-15 15:22:24.189  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
,07-15 15:22:24.189  3956  3956 D BtGatt.AdvertiseManager: advertise manager created
,07-15 15:22:24.193  3956  3956 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:24.194  3956  3956 V BluetoothAdapterState: isTurningOn()=false
07-15 15:22:24.194  3956  3956 V BluetoothAdapterState: isBleTurningOn()=true
,07-15 15:22:24.194  3956  3956 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:24.194  3956  3980 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-15 15:22:24.194  3956  3980 I bt_bluedroid: enable
07-15 15:22:24.194  3956  3981 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-15 15:22:24.194  3956  3981 I bt_hci  : start_up
,07-15 15:22:24.201  3956  3981 I bt_vendor: alloc value 0xb3a66631
,07-15 15:22:24.201  3956  3981 I bt_vendor: init
07-15 15:22:24.201  3956  3981 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-15 15:22:24.201  3956  3981 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-15 15:22:24.238  3956  3981 D bt_hci  : start_up starting async portion
,07-15 15:22:24.238  3956  3991 I bt_hci  : event_finish_startup
07-15 15:22:24.238  3956  3991 I bt_hci_h4: hal_open
07-15 15:22:24.238  3956  3991 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-15 15:22:24.241  3956  3991 I bt_userial_vendor: device fd = 49 open
,07-15 15:22:24.327  3956  3991 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:22:24.353  3956  3991 D bt_hwcfg: Chipset BCM4335C0
07-15 15:22:24.353  3956  3991 D bt_hwcfg: Target name = [BCM4335C0]
,07-15 15:22:24.354  3956  3991 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-15 15:22:24.808  3956  3991 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-15 15:22:24.809  3956  3991 D bt_hwcfg: Settlement delay -- 100 ms
07-15 15:22:24.809  3956  3991 I bt_hwcfg: Setting fw settlement delay to 100 
,07-15 15:22:24.927  3956  3991 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-15 15:22:24.928  3956  3991 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-15 15:22:24.952  3956  3991 I bt_hwcfg: vendor lib fwcfg completed
,07-15 15:22:24.952  3956  3991 I bt_vendor: firmware callback
07-15 15:22:24.952  3956  3991 I bt_hci  : firmware_config_callback
,07-15 15:22:24.965  3956  4008 I bt_btu  : btu_task pending for preload complete event
,07-15 15:22:24.965  3956  4008 I bt_btu_task: Bluetooth chip preload is complete
,07-15 15:22:24.965  3956  4008 I bt_btu  : btu_task received preload complete event
,07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_HCI
,07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_AVRC
07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_A2D
,07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_BNEP
07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_BTM
,07-15 15:22:24.974  3956  4008 I         : BTE_InitTraceLevels -- TRC_GAP
,07-15 15:22:24.975  3956  4008 I         : BTE_InitTraceLevels -- TRC_PAN
07-15 15:22:24.975  3956  4008 I         : BTE_InitTraceLevels -- TRC_SDP
,07-15 15:22:24.975  3956  4008 I         : BTE_InitTraceLevels -- TRC_GATT
,07-15 15:22:24.975  3956  4008 I         : BTE_InitTraceLevels -- TRC_SMP
,07-15 15:22:24.975  3956  4008 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-15 15:22:24.975  3956  4008 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-15 15:22:25.193  3956  4008 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e49b5
,07-15 15:22:25.193  3956  4008 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e49b5 
,07-15 15:22:25.262  3956  3984 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-15 15:22:25.262  3956  3984 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-15 15:22:25.297  3956  3984 D BluetoothAdapterProperties: Name is: Nexus 5
07-15 15:22:25.298  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:25.298  3956  3984 D BluetoothAdapterProperties: Scan Mode:20
07-15 15:22:25.298  3956  3984 D BluetoothAdapterProperties: Discoverable Timeout:120
07-15 15:22:25.298  3956  3984 D bt_hci  : do_postload posting postload work item
,07-15 15:22:25.298  3956  3991 I bt_hci  : event_postload
07-15 15:22:25.298  3956  3991 I bt_vendor: sco_config_cb
07-15 15:22:25.298  3956  3991 I bt_hci  : sco_config_callback postload finished.
07-15 15:22:25.316  3956  3991 I bt_vendor: low_power_mode_cb
07-15 15:22:25.317  3956  3984 D bt_bte_conf: Device ID record 1 : primary
07-15 15:22:25.317  3956  3984 D bt_bte_conf:   vendorId            = 000f
07-15 15:22:25.317  3956  3984 D bt_bte_conf:   vendorIdSource      = 0001
07-15 15:22:25.317  3956  3984 D bt_bte_conf:   product             = 1200
07-15 15:22:25.317  3956  3984 D bt_bte_conf:   version             = 1436
,07-15 15:22:25.317  3956  3984 D bt_bte_conf:   clientExecutableURL = 
07-15 15:22:25.317  3956  3984 D bt_bte_conf:   serviceDescription  = 
07-15 15:22:25.317  3956  3984 D bt_bte_conf:   documentationURL    = 
07-15 15:22:25.336  3956  3984 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-15 15:22:25.336  3956  3981 D bt_stack_manager: event_start_up_stack finished
07-15 15:22:25.337  3956  3980 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-15 15:22:25.337  3956  3980 D BluetoothAdapterProperties: Setting state to 15
07-15 15:22:25.337  3956  3980 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-15 15:22:25.338  3956  3980 I BluetoothAdapterState: Entering BleOnState
07-15 15:22:25.338  3956  3980 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-15 15:22:25.338  3956  3980 D BluetoothAdapterProperties: Setting state to 11
07-15 15:22:25.338  3956  3980 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-15 15:22:25.340  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:25.352  3956  3956 D HeadsetService: Received start request. Starting profile...
07-15 15:22:25.354  3956  3956 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-15 15:22:25.354  3956  3956 D HeadsetStateMachine: make
,07-15 15:22:25.363  3956  3956 D HeadsetStateMachine: max_hf_connections = 1
07-15 15:22:25.363  3956  3956 I bt_bluedroid: get_profile_interface handsfree
,07-15 15:22:25.367  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:25.368  3956  3984 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-15 15:22:25.368  3956  3984 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-15 15:22:25.368  3956  3956 D A2dpService: Received start request. Starting profile...
07-15 15:22:25.369  3956  3956 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-15 15:22:25.369  3956  3956 I bt_bluedroid: get_profile_interface avrcp
07-15 15:22:25.370  3956  3980 I BluetoothAdapterState: Entering PendingCommandState
,07-15 15:22:25.376  3956  3956 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-15 15:22:25.377  3956  3956 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-15 15:22:25.377  3956  3956 D A2dpStateMachine: make
,07-15 15:22:25.378  3956  3956 I bt_bluedroid: get_profile_interface a2dp
,07-15 15:22:25.379  3956  3984 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-15 15:22:25.380  3956  4031 D A2dpStateMachine: Enter Disconnected: -2
,07-15 15:22:25.383  3956  3956 I BluetoothHidServiceJni: classInitNative: succeeds
,07-15 15:22:25.384  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
,07-15 15:22:25.385  3956  3956 D HidService: Received start request. Starting profile...
07-15 15:22:25.386  3956  3956 I bt_bluedroid: get_profile_interface hidhost
07-15 15:22:25.386  3956  3984 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c6099
07-15 15:22:25.386  3956  3984 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-15 15:22:25.386  3956  3956 D HidService: setHidService(): set to: null
,07-15 15:22:25.387  3956  3956 I BluetoothHealthServiceJni: classInitNative: succeeds
07-15 15:22:25.388  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:25.388  3956  3956 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:25.388  3956  3956 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:25.388  3956  3956 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:25.388  3956  3956 V BluetoothAdapterState: isBleTurningOff()=false
,07-15 15:22:25.390  3956  3956 D HealthService: Received start request. Starting profile...
,07-15 15:22:25.393  3956  3956 I bt_bluedroid: get_profile_interface health
,07-15 15:22:25.394  3956  3956 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-15 15:22:25.395  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
,07-15 15:22:25.395  3956  3956 D PanService: Received start request. Starting profile...
07-15 15:22:25.395  3956  3956 D BluetoothPanServiceJni: initializeNative(L110): pan
07-15 15:22:25.396  3956  3956 I bt_bluedroid: get_profile_interface pan
07-15 15:22:25.396  3956  3984 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-15 15:22:25.399  3956  3956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ccea7d2
07-15 15:22:25.399  3956  3956 D BluetoothMapService: Received start request. Starting profile...
07-15 15:22:25.399  3956  3956 D BluetoothMapService: start()
07-15 15:22:25.401  3956  3956 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-15 15:22:25.402  3956  3956 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-15 15:22:25.402  3956  3956 D BluetoothMapAppObserver: createReceiver()
07-15 15:22:25.403  3956  3956 D BluetoothMapAppObserver: initObservers()
07-15 15:22:25.403  3956  3956 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-15 15:22:25.411  3956  4022 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-15 15:22:25.411  3956  3956 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:25.411  3956  3956 V BluetoothAdapterState: isTurningOn()=true
,07-15 15:22:25.411  3956  3956 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:25.411  3956  3956 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:25.412  3956  3956 V BluetoothAdapterState: isTurningOff()=false
,07-15 15:22:25.413  3956  3956 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:25.413  3956  3956 V BluetoothAdapterState: isBleTurningOn()=false
07-15 15:22:25.413  3956  3956 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:25.413  3956  3956 V BluetoothAdapterState: isTurningOff()=false
07-15 15:22:25.413  3956  3956 V BluetoothAdapterState: isTurningOn()=true
07-15 15:22:25.413  3956  3956 V BluetoothAdapterState: isBleTurningOn()=false
,07-15 15:22:25.413  3956  3956 V BluetoothAdapterState: isBleTurningOff()=false
07-15 15:22:25.413  3956  3980 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-15 15:22:25.413  3956  3980 D BluetoothAdapterProperties: ScanMode =  20
07-15 15:22:25.413  3956  3980 D BluetoothAdapterProperties: State =  11
07-15 15:22:25.414  3956  3980 D BluetoothAdapterProperties: Setting state to 12
07-15 15:22:25.414  3956  3980 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-15 15:22:25.414   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:25.415  3956  3980 I BluetoothAdapterState: Entering OnState
07-15 15:22:25.415   926  1349 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-15 15:22:25.416   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:25.417   926   952 D BluetoothPbap: onBluetoothStateChange: up=true
07-15 15:22:25.417  3956  3984 D BluetoothAdapterProperties: Scan Mode:21
07-15 15:22:25.418  3956  3984 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-15 15:22:25.422  3561  3572 D BluetoothPbap: onBluetoothStateChange: up=true
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:25.422  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:25.423  1298  1534 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:25.424  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:25.424   926   946 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:25.427   926  1633 D BluetoothPan: onBluetoothStateChange on: true
,07-15 15:22:25.427   926   926 D BluetoothMap: Proxy object connected
,07-15 15:22:25.427   926   926 D MapProfile: Bluetooth service connected
07-15 15:22:25.427   926   926 D BluetoothMap: getConnectedDevices()
,07-15 15:22:25.428   788   808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:25.429   926   946 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:22:25.430   926   926 D BluetoothPan: BluetoothPAN Proxy object connected
,07-15 15:22:25.430   926   926 D PanProfile: Bluetooth service connected
,07-15 15:22:25.430   788   808 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-15 15:22:25.431  3561  3878 D BluetoothHeadset: onBluetoothStateChange: up=true
07-15 15:22:25.431  3956  3956 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-15 15:22:25.432  3561  3574 D BluetoothA2dp: onBluetoothStateChange: up=true
07-15 15:22:25.432  3956  3956 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-15 15:22:25.433  3956  3956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:25.433  3561  3572 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:22:25.435  3956  3956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:25.436  3561  3878 D BluetoothPan: onBluetoothStateChange on: true
07-15 15:22:25.437  3956  3956 D ObexServerSockets: Succeed to create listening sockets 
07-15 15:22:25.437  3956  3956 D ObexServerSockets0: startAccept()
07-15 15:22:25.437  3956  3956 D ObexServerSockets0: prepareForNewConnect()
07-15 15:22:25.438  3561  3561 D BluetoothPan: BluetoothPAN Proxy object connected
,07-15 15:22:25.438  3561  3561 D PanProfile: Bluetooth service connected
,07-15 15:22:25.439   926  1634 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-15 15:22:25.439  3956  3956 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-15 15:22:25.440  3956  3956 D BluetoothSdpJni: SDP Create record success - handle: 0
07-15 15:22:25.442   788   788 D BluetoothA2dp: Proxy object connected
,07-15 15:22:25.443   926   926 D BluetoothA2dp: Proxy object connected
,07-15 15:22:25.443  3956  4041 D ObexServerSockets0: Accepting socket connection...
07-15 15:22:25.444  3561  3878 D BluetoothMap: onBluetoothStateChange: up=true
07-15 15:22:25.444  3561  3561 D BluetoothA2dp: Proxy object connected
,07-15 15:22:25.448   788   788 I Telecom : BluetoothPhoneService: queryPhoneState
,07-15 15:22:25.449  3956  3956 D BluetoothMapService: onReceive
07-15 15:22:25.449  3956  3956 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-15 15:22:25.449  3956  3956 D BluetoothMapService: STATE_ON
07-15 15:22:25.449   926   926 D BluetoothInputDevice: Proxy object connected
07-15 15:22:25.449   926   926 D HidProfile: Bluetooth service connected
07-15 15:22:25.449  3956  4042 D ObexServerSockets0: Accepting socket connection...
,07-15 15:22:25.451  3561  3561 D BluetoothInputDevice: Proxy object connected
,07-15 15:22:25.451  3561  3561 D HidProfile: Bluetooth service connected
,07-15 15:22:25.452  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:25.454  3561  3561 D BluetoothMap: Proxy object connected
,07-15 15:22:25.454  3561  3561 D MapProfile: Bluetooth service connected
07-15 15:22:25.454  3561  3561 D BluetoothMap: getConnectedDevices()
,07-15 15:22:25.458  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:25.462  3561  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-15 15:22:25.467  3561  3561 D DockEventReceiver: finishStartingService: stopping service
,07-15 15:22:25.471  3956  3956 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-15 15:22:25.471  3956  3956 D ObexServerSockets0: prepareForNewConnect()
,07-15 15:22:25.473  3956  4052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:25.475  3561  3561 D BluetoothPbap: Proxy object connected
07-15 15:22:25.475  3561  3561 D PbapServerProfile: Bluetooth service connected
,07-15 15:22:25.480   926   926 D BluetoothPbap: Proxy object connected
,07-15 15:22:25.480   926   926 D PbapServerProfile: Bluetooth service connected
,07-15 15:22:25.485  1744  1744 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-15 15:22:25.489  1744  4055 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-15 15:22:25.491  1744  1744 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-15 15:22:25.502  3956  4059 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-15 15:22:25.503  3956  4059 I BtOppRfcommListener: Accept thread started.
,07-15 15:22:25.505  1744  4055 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-15 15:22:25.517   788   788 D BluetoothHeadset: Proxy object connected
07-15 15:22:25.517   788   788 D BluetoothHeadset: Proxy object connected
,07-15 15:22:25.517   926  1634 D BluetoothHeadset: Proxy object connected
07-15 15:22:25.517   926   926 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:25.518  3561  3878 D BluetoothHeadset: Proxy object connected
07-15 15:22:25.518   788   788 D BluetoothHeadset: Proxy object connected
07-15 15:22:25.518  3561  3561 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:25.518  1298  1313 D BluetoothHeadset: Proxy object connected
,07-15 15:22:25.524  1298  1533 D BluetoothHeadset: Proxy object connected
,07-15 15:22:25.529   788   808 D BluetoothHeadset: Proxy object connected
,07-15 15:22:25.531  3561  3574 D BluetoothHeadset: Proxy object connected
,07-15 15:22:25.531  3561  3561 D HeadsetProfile: Bluetooth service connected
,07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:26.117  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:26.123  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:26.127  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:26.127  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5eeb2f1 added. We now have 8 listener(s)
07-15 15:22:26.127  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:26.133   788   968 D WifiService: setWifiEnabled: false pid=3491, uid=10000
07-15 15:22:26.133   788   968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-15 15:22:26.143  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:26.144   788  1314 D WifiService: setWifiEnabled: true pid=3491, uid=10000
,07-15 15:22:26.144   788  1314 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-15 15:22:26.155   192   653 D SoftapController: Softap fwReload - Ok
07-15 15:22:26.161   192   653 D CommandListener: Setting iface cfg
,07-15 15:22:26.161   192   653 D CommandListener: Trying to bring down wlan0
07-15 15:22:26.161   192   653 D CommandListener: Clearing all IP addresses on wlan0
07-15 15:22:26.162   788   892 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-15 15:22:26.920   788   892 D wifi    : set interface wlan0 flags (UP)
,07-15 15:22:26.920   788   892 I WifiHAL : Initializing wifi
07-15 15:22:26.920   788   892 I WifiHAL : Creating socket
07-15 15:22:26.921   788   892 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-15 15:22:26.921   788   892 D wifi    : Did set static halHandle = 0x966b8000
07-15 15:22:26.921   788   892 D wifi    : halHandle = 0x966b8000, mVM = 0xb4dbc000, mCls = 0x201136
07-15 15:22:26.921   788   892 D wifi    : array field set
,07-15 15:22:26.921   788   892 I WifiNative-HAL: interface[0] = p2p0
07-15 15:22:26.921   788   892 I WifiNative-HAL: interface[1] = wlan0
07-15 15:22:26.927  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:26.927   788   892 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-15 15:22:26.928   788   892 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-15 15:22:26.928   788   808 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-15 15:22:26.936   788  4101 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1771339776
07-15 15:22:26.937   788  4101 D wifi    : waitForHalEvents called, vm = 0xb4dbc000, obj = 0x201136, env = 0x95d97180
,07-15 15:22:26.966  4102  4102 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-15 15:22:27.005  4102  4102 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:22:27.017  4102  4102 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:27.940  3491  3491 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:27.942   788   892 D WifiConfigStore: Loading config and enabling all networks 
07-15 15:22:27.944  3491  3491 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:27.956   788   892 D WifiConfigStore: loaded 0 passpoint configs
07-15 15:22:27.956   788   892 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-15 15:22:27.956   788   892 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-15 15:22:27.957   788   892 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-15 15:22:27.957   788   892 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-15 15:22:27.957   788   892 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-15 15:22:27.957   788   892 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-15 15:22:27.957   788   892 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-15 15:22:27.959   788   892 D WifiNative-HAL: Setting external_sim to 1
07-15 15:22:27.960   788   892 D wifi    : setting dfs flag to true, 0x9807bb88
07-15 15:22:27.960   788   892 D WifiStateMachine: Setting OUI to DA-A1-19
07-15 15:22:27.960   788   892 D wifi    : setting scan oui 0x9807bb88
07-15 15:22:27.960   788   892 D WifiHAL : Sending mac address OUI
07-15 15:22:27.961  3649  3649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-15 15:22:27.976   788   892 E native  : do suspend true
,07-15 15:22:27.979   788   892 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-15 15:22:27.979   788   788 D RttService: SCAN_AVAILABLE : 3
07-15 15:22:27.979   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-15 15:22:27.979   788   906 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-15 15:22:27.980   192   653 D CommandListener: Setting iface cfg
,07-15 15:22:27.983   192   653 D CommandListener: Trying to bring up p2p0
,07-15 15:22:27.984   788   891 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-15 15:22:27.985   788   891 D WifiNative-HAL: p2pGetDeviceAddress
07-15 15:22:27.986   788   891 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.181  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:28.182  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:28.183  3491  3549 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-15 15:22:28.183  3491  3549 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-15 15:22:28.184  3491  3549 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4b6f1e Bundle[{}]
07-15 15:22:28.184  3491  3549 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:22:28.184  3491  3549 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-15 15:22:28.185  3491  3549 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-15 15:22:28.185  3491  3549 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-15 15:22:28.185  3491  3549 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-15 15:22:28.186  3491  3549 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-15 15:22:28.190  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-15 15:22:28.190  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-15 15:22:28.190  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-15 15:22:28.190  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-15 15:22:28.190  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-15 15:22:28.190  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-15 15:22:28.193  3491  3549 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 301)
,07-15 15:22:28.193  3491  3549 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 301)
07-15 15:22:28.193  3491  3549 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 301)
07-15 15:22:28.193  3491  3549 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 301)
07-15 15:22:28.195  3491  3549 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 306)
07-15 15:22:28.195  3491  3549 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 306)
07-15 15:22:28.195  3491  3549 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 306)
07-15 15:22:28.195  3491  3549 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 307)
07-15 15:22:28.196  3491  3549 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 309)
,07-15 15:22:28.200  3491  4107 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 315, name: My test thread name)
,07-15 15:22:28.200  3491  4107 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 315, thread name: My test thread name)
07-15 15:22:28.200  3491  4107 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 315, name: My test thread name)
07-15 15:22:28.201  3491  4108 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 317, name: My test thread name)
07-15 15:22:28.201  3491  4108 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 317, thread name: My test thread name)
07-15 15:22:28.201  3491  4108 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 317, name: My test thread name)
,07-15 15:22:28.202  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-15 15:22:28.202  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88dced6 added. We now have 2 listener(s)
,07-15 15:22:28.203  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-15 15:22:28.203  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.204  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.204  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.204  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ea7557 added. We now have 9 listener(s)
07-15 15:22:28.204  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.205  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:22:28.205  3491  3549 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-15 15:22:28.208  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.210  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:28.212  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:28.212  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.212  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.212  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5aa8d2d added. We now have 3 listener(s)
07-15 15:22:28.214  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-15 15:22:28.214  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.214  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.214  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.214  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e700262 added. We now have 10 listener(s)
07-15 15:22:28.214  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.214  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.214  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.214  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.215  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.215  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.215  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.215  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.215  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88dced6 removed from the list
07-15 15:22:28.215  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.215  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ea7557 removed from the list
07-15 15:22:28.216  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.216  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.216  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.217  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.217  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.217  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.217  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.217  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ea7557 not in the list
07-15 15:22:28.217  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.217  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:22:28.217  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.217  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e700262 removed from the list
07-15 15:22:28.217  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.217  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.218  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.218  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.218  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5aa8d2d removed from the list
07-15 15:22:28.218  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.218  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370ff3 added. We now have 2 listener(s)
07-15 15:22:28.220  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-15 15:22:28.220  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.220  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:22:28.220  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.220  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74004b0 added. We now have 9 listener(s)
07-15 15:22:28.220  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.223  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:22:28.223  3491  3549 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-15 15:22:28.226  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.228  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:28.229  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:28.229  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.230  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.230  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74fe2ae added. We now have 3 listener(s)
07-15 15:22:28.231  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-15 15:22:28.231  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.231  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.231  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.231  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a8b84f added. We now have 10 listener(s)
07-15 15:22:28.231  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.231  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:28.231  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:28.231  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.231  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:28.234  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:28.235  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:28.236  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:22:28.236  3491  3549 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-15 15:22:28.236  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.237  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.238  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.238  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.238  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.238  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.238  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.238  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:28.238  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.238  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370ff3 removed from the list
07-15 15:22:28.238  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.238  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74004b0 removed from the list
07-15 15:22:28.238  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.238  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.239  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.239  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-15 15:22:28.239  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.239  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.239  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.239  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74004b0 not in the list
07-15 15:22:28.239  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:28.239  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.239  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.240  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a8b84f removed from the list
07-15 15:22:28.240  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.240  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.240  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.240  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.240  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74fe2ae removed from the list
07-15 15:22:28.240  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.240  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bed34e5 added. We now have 2 listener(s)
07-15 15:22:28.242  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-15 15:22:28.242  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.242  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.242  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.242  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83b7bba added. We now have 9 listener(s)
07-15 15:22:28.242  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.244  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:22:28.244  3491  3549 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:22:28.247  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.250  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:28.251  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:28.251  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.252  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.252  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c63b9c8 added. We now have 3 listener(s)
07-15 15:22:28.252  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.253  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:28.255  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-15 15:22:28.255  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.255  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:22:28.255  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.255  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c13a61 added. We now have 10 listener(s)
07-15 15:22:28.255  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.255  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:28.256  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:28.256  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:28.256  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.256  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-15 15:22:28.260  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:22:28.260  3491  3549 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:22:28.260  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.260  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.260  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.260  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.260  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.260  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:28.260  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.260  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bed34e5 removed from the list
07-15 15:22:28.260  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.260  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83b7bba removed from the list
,07-15 15:22:28.260  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.260  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.261  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.261  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-15 15:22:28.261  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.261  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.261  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.261  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83b7bba not in the list
07-15 15:22:28.261  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-15 15:22:28.262  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.262  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.262  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c13a61 removed from the list
07-15 15:22:28.262  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.262  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.262  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.262  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.262  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c63b9c8 removed from the list
07-15 15:22:28.263  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.263  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9d6247 added. We now have 2 listener(s)
,07-15 15:22:28.264  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-15 15:22:28.264  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:22:28.264  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.265  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.265  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdeaa74 added. We now have 9 listener(s)
07-15 15:22:28.265  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.266  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-15 15:22:28.266  3491  3549 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:22:28.270  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.272  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:28.274  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:28.274  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.274  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.274  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@321c812 added. We now have 3 listener(s)
07-15 15:22:28.275  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-15 15:22:28.275  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.275  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.275  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.275  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43dbe3 added. We now have 10 listener(s)
,07-15 15:22:28.275  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.275  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:28.275  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:28.275  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:28.275  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:28.277  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.279  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.279  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:22:28.279  3491  3549 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-15 15:22:28.281  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:28.281  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.281  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.281  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.281  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.281  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:28.281  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.281  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9d6247 removed from the list
07-15 15:22:28.281  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.281  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdeaa74 removed from the list
07-15 15:22:28.281  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.281  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.282  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.282  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-15 15:22:28.282  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.282  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.282  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.282  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdeaa74 not in the list
07-15 15:22:28.282  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:28.282  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.282  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.282  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43dbe3 removed from the list
07-15 15:22:28.282  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.282  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.282  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.282  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.282  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@321c812 removed from the list
,07-15 15:22:28.283  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.283  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9dd499 added. We now have 2 listener(s)
07-15 15:22:28.285  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-15 15:22:28.285  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.285  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.285  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.285  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a50535e added. We now have 9 listener(s)
07-15 15:22:28.285  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.287  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-15 15:22:28.287  3491  3549 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-15 15:22:28.289  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.292  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:28.293  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-15 15:22:28.293  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.294  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.294  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e70d40c added. We now have 3 listener(s)
07-15 15:22:28.294  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:28.295  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:22:28.296  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-15 15:22:28.296  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.296  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.297  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.297  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ee2155 added. We now have 10 listener(s)
07-15 15:22:28.297  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.297  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.297  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.297  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.297  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.297  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.297  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.297  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.297  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9dd499 removed from the list
,07-15 15:22:28.297  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.297  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a50535e removed from the list
07-15 15:22:28.297  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.297  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-15 15:22:28.298  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.298  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.298  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:28.298  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a50535e not in the list
,07-15 15:22:28.298  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.298  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.298  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.298  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ee2155 removed from the list
07-15 15:22:28.298  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.298  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.298  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.298  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:22:28.298  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e70d40c removed from the list
07-15 15:22:28.298  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-15 15:22:28.298  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a added. We now have 2 listener(s)
07-15 15:22:28.299  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-15 15:22:28.299  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:22:28.299  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-15 15:22:28.299  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-15 15:22:28.299  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b added. We now have 9 listener(s)
07-15 15:22:28.299  3491  3549 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-15 15:22:28.301  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-15 15:22:28.301  3491  3549 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-15 15:22:28.302  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.304  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:28.305  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:28.305  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.305  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:22:28.305  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:22:28.306  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:22:28.306  3491  3549 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-15 15:22:28.306  3491  3549 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-15 15:22:28.306  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:22:28.306  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:28.306  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:28.306  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.306  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.306  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.306  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-15 15:22:28.306  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.306  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.306  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:28.306  3491  3549 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a removed from the list
07-15 15:22:28.306  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.306  3491  3549 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b removed from the list
07-15 15:22:28.306  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.306  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.307  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.307  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.307  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.308  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:28.308  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.308  3491  3549 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-15 15:22:28.308  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.308  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.308  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.309  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.309  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.309  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.309  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
,07-15 15:22:28.309  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.309  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.309  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.309  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.309  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.309  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.309  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.309  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-15 15:22:28.309  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
,07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-15 15:22:28.310  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-15 15:22:28.311  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.311  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.311  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.311  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.311  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.311  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.311  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.311  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.311  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.311  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.311  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:28.311  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.311  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.311  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.311  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.311  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.312  3491  3549 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:22:28.313  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.315  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-15 15:22:28.316  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:28.316  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.316  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.316  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:28.317  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:28.317  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.317  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:28.317  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.320  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
,07-15 15:22:28.320  3491  3549 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:22:28.320  3491  3549 I io.jxcore.node.ConnectionHelper: start: OK
07-15 15:22:28.321  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.321  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.321  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.321  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.321  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.321  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:28.321  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.321  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.321  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.321  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.321  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.321  3491  3549 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:22:28.322  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.325  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:28.326  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:28.326  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.326  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:28.326  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:28.328  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.328  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:22:28.328  3491  3549 E io.jxcore.node.StartStopOperationHandler: executeCu,rrentOperation: Failed to start the discovery manager
07-15 15:22:28.328  3491  3549 I io.jxcore.node.ConnectionHelper: start: OK
07-15 15:22:28.329  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.329  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.329  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.330  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.330  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.330  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.330  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:28.330  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.330  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.330  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.330  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.330  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.330  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:28.330  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.330  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.330  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.331  3491  3549 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-15 15:22:28.332  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:22:28.334  3491  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:22:28.335  3491  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-15 15:22:28.335  3491  3549 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:22:28.335  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-15 15:22:28.335  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-15 15:22:28.335  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.335  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:28.337  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.338  3491  3491 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:22:28.348  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:22:28.348  3491  3549 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-15 15:22:28.348  3491  3549 I io.jxcore.node.ConnectionHelper: start: OK
07-15 15:22:28.348  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.348  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.348  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.348  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.348  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.348  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.348  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.348  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.348  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-15 15:22:28.348  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.349  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.349  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.349  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.349  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.349  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:28.349  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.349  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.349  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.350  3491  3549 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-15 15:22:28.350  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.350  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.350  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.350  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.350  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.350  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.350  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.350  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.350  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.350  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.350  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.350  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.350  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.350  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.350  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.350  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.351  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-15 15:22:28.351  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.351  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.351  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.351  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.351  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.351  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.351  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.351  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.351  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.351  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.351  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.351  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.351  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.351  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.351  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.351  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.351  3491  3549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-15 15:22:28.351  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.352  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.352  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.352  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.352  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.352  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.352  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.352  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.352  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.352  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.352  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.352  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.352  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.352  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.352  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.352  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.352  3491  3549 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-15 15:22:28.352  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-15 15:22:28.352  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.352  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.352  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.352  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.352  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.352  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.352  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.352  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.352  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.352  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.352  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.352  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.353  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.353  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.353  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.353  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:22:28.354  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:22:28.354  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:22:28.354  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:28.355  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:22:28.355  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-15 15:22:28.355  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.355  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.355  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.355  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.355  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.355  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.355  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.355  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.355  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.355  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.355  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.355  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.355  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.355  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.355  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.355  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.356  3491  3549 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:28.356  3491  3549 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-15 15:22:28.356  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:28.357  3491  3549 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:28.357  3491  3549 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-15 15:22:28.357  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-15 15:22:28.358  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-15 15:22:28.358  3491  3549 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-15 15:22:28.358  3491  3549 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:22:28.359  3491  3549 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-15 15:22:28.359  3491  3549 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:28.359  3491  3549 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:22:28.359  3491  3549 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-15 15:22:28.359  3491  3549 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:28.359  3491  3549 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-15 15:22:28.359  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:28.363  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-15 15:22:28.363  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-15 15:22:28.364  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-15 15:22:28.366  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-15 15:22:28.366  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-15 15:22:28.367  3491  3549 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-15 15:22:28.367  3491  3549 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-15 15:22:28.367  3491  3549 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-15 15:22:28.367  3491  4122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 383)
07-15 15:22:28.368  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.368  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.368  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.368  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.368  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.368  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.368  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.368  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.368  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.368  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.368  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.369  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.369  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.369  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.369  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.369  3491  4122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-15 15:22:28.369  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.369  3491  3549 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-15 15:22:28.369  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.370  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.370  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.370  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.370  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.370  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.370  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.370  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.370  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.370  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.370  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.370  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.370  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.370  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.370  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.370  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.370  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.370  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.370  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.370  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.370  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.370  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.371  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.371  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.371  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.371  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.371  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.371  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.371  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.372  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.372  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.372  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.372  3491  3549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-15 15:22:28.372  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.372  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.372  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.372  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.372  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.372  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.372  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.372  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.372  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.372  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.372  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.372  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.372  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.373  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.373  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.373  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.373  3491  3549 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-15 15:22:28.373  3491  3549 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-15 15:22:28.373  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-15 15:22:28.373  3491  3549 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-15 15:22:28.373  3491  3549 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-15 15:22:28.373  3491  3549 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-15 15:22:28.373  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:22:28.373  3491  3549 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-15 15:22:28.373  3491  3549 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-15 15:22:28.373  3491  3549 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-15 15:22:28.373  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-15 15:22:28.373  3491  3549 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-15 15:22:28.373  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.373  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.373  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.373  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.373  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.373  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.373  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.373  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.373  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.373  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.373  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.373  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.373  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.374  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.374  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.374  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.374  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.374  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.374  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.374  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.374  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.374  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.374  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.374  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.374  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.374  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.374  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.374  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.374  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.374  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.374  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.374  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.374  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.375  3491  3549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-15 15:22:28.375  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.376  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-15 15:22:28.376  3491  3549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-15 15:22:28.376  3491  3549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-15 15:22:28.377  3491  3491 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-15 15:22:28.377  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-15 15:22:28.377  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.377  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-15 15:22:28.377  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-15 15:22:28.377  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-15 15:22:28.377  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-15 15:22:28.377  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.377  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.377  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.377  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-15 15:22:28.377  3491  3549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-15 15:22:28.377  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-15 15:22:28.377  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.378  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.378  3491  3549 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:28.378  3491  4124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-15 15:22:28.378  3491  4124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-15 15:22:28.378  3491  3491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:28.378  3491  3491 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.378  3491  3491 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:28.378  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.379  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.379  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.379  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-15 15:22:28.379  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.379  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.380  3491  3491 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:22:28.380  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:28.380  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.380  3491  3491 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-15 15:22:28.380  3491  3491 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:22:28.380  3491  3491 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-15 15:22:28.381  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.381  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-15 15:22:28.381  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.381  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.381  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.381  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.381  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.381  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.381  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.381  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-15 15:22:28.383  3491  3491 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because the device does not support Bluetooth LE multi advertisement
07-15 15:22:28.383  3491  3549 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-15 15:22:28.383  3491  3491 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-15 15:22:28.383  3491  3491 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-15 15:22:28.383  3491  3491 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-15 15:22:28.383  3491  3491 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-15 15:22:28.383  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.383  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.383  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.384  3491  3549 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-15 15:22:28.384  3491  3549 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-15 15:22:28.384  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-15 15:22:28.384  3491  3549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-15 15:22:28.384  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.384  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.384  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.384  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.384  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.384  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.385  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.385  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.385  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.385  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.385  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.385  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.385  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.385  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.385  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.385  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.387  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.387  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.387  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.387  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.387  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.387  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.387  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.387  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.387  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.387  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.387  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.387  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.387  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.387  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.388  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.388  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.388  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.388  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.388  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.388  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.388  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.388  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.388  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.388  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.388  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.388  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.388  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.389  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.389  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.389  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.389  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.389  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.389  3491  3549 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:28.389  3491  3549 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
,07-15 15:22:28.389  3491  3491 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-15 15:22:28.390  3491  3549 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-15 15:22:28.390  3491  3549 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-15 15:22:28.390  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.390  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.390  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.390  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.390  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.390  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.390  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.390  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.390  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.390  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.390  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.390  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.390  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.390  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.391  3491  3549 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-15 15:22:28.391  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.391  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.391  3491  3549 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-15 15:22:28.391  3491  3549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-15 15:22:28.391  3491  3549 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-15 15:22:28.391  3491  3549 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:28.391  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.391  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.391  3491  3549 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74a476a not in the list
07-15 15:22:28.391  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.391  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.391  3491  3549 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:28.391  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.391  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.391  3491  3549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:22:28.391  3491  3549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:28.391  3491  3549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:28.391  3491  3549 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25ee45b not in the list
07-15 15:22:28.392  3491  3549 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 85
07-15 15:22:28.392  3491  3549 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 85
07-15 15:22:28.392  3491  3549 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-15 15:22:28.392  3491  3549 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-15 15:22:28.392  3491  3549 D com.test.thalitest.ThaliTestRunner: Total duration: 22467 ms
07-15 15:22:28.395  3491  3549 I jxcore-log: true
07-15 15:22:28.395  3491  3549 I jxcore-log: 
07-15 15:22:28.395  3491  3549 I jxcore-log: Total number of executed tests:  85
07-15 15:22:28.395  3491  3549 I jxcore-log: 
07-15 15:22:28.395  3491  3549 I jxcore-log: Number of passed tests:  85
07-15 15:22:28.395  3491  3549 I jxcore-log: 
07-15 15:22:28.396  3491  3549 I jxcore-log: Number of failed tests:  0
07-15 15:22:28.396  3491  3549 I jxcore-log: 
07-15 15:22:28.396  3491  3549 I jxcore-log: Number of ignored tests:  0
07-15 15:22:28.396  3491  3549 I jxcore-log: 
07-15 15:22:28.400  3491  3549 I jxcore-log: Total duration:  22467
07-15 15:22:28.400  3491  3549 I jxcore-log: 
07-15 15:22:28.401  3491  3549 I jxcore-log: My device name is: LGE-Nexus 5
07-15 15:22:28.401  3491  3549 I jxcore-log: 
,07-15 15:22:32.376  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-15 15:22:32.376  3491  3549 I jxcore-log: 
,07-15 15:22:32.768  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-15 15:22:32.768  3491  3549 I jxcore-log: 
,07-15 15:22:32.791  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-15 15:22:32.791  3491  3549 I jxcore-log: 
07-15 15:22:32.795  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-15 15:22:32.795  3491  3549 I jxcore-log: 
,07-15 15:22:32.811  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-15 15:22:32.811  3491  3549 I jxcore-log: 
,07-15 15:22:32.814  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-15 15:22:32.814  3491  3549 I jxcore-log: 
,07-15 15:22:33.500  3956  4008 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,07-15 15:22:33.500  3491  4122 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 383)
07-15 15:22:33.500  3491  4122 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 383)
07-15 15:22:33.500  3491  4122 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 383)
07-15 15:22:33.500  3491  3491 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,07-15 15:22:33.501  3491  3491 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
07-15 15:22:33.501  3491  3491 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-15 15:22:33.501  3491  3491 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-15 15:22:33.501  3956  4011 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
07-15 15:22:33.501  3491  4122 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 383
07-15 15:22:33.501  3491  4122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 383)
07-15 15:22:33.501  3491  4123 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 383
07-15 15:22:33.502  3491  4123 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 383)
07-15 15:22:33.503  3491  4123 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 383)
,07-15 15:22:34.743  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-15 15:22:34.743  3491  3549 I jxcore-log: 
,07-15 15:22:34.755  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-15 15:22:34.755  3491  3549 I jxcore-log: 
,07-15 15:22:34.762  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-15 15:22:34.762  3491  3549 I jxcore-log: 
,07-15 15:22:34.914  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-15 15:22:34.914  3491  3549 I jxcore-log: 
,07-15 15:22:35.622  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-15 15:22:35.622  3491  3549 I jxcore-log: 
,07-15 15:22:35.676  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-15 15:22:35.676  3491  3549 I jxcore-log: 
,07-15 15:22:35.682  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-15 15:22:35.682  3491  3549 I jxcore-log: 
,07-15 15:22:35.877  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-15 15:22:35.877  3491  3549 I jxcore-log: 
,07-15 15:22:35.898  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-15 15:22:35.898  3491  3549 I jxcore-log: 
,07-15 15:22:35.902  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-15 15:22:35.902  3491  3549 I jxcore-log: 
,07-15 15:22:35.907  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-15 15:22:35.907  3491  3549 I jxcore-log: 
,07-15 15:22:35.922  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-15 15:22:35.922  3491  3549 I jxcore-log: 
,07-15 15:22:35.941  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-15 15:22:35.941  3491  3549 I jxcore-log: 
,07-15 15:22:36.026  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-15 15:22:36.026  3491  3549 I jxcore-log: 
,07-15 15:22:36.031  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-15 15:22:36.031  3491  3549 I jxcore-log: 
,07-15 15:22:36.055  3491  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-15 15:22:36.055  3491  3549 I jxcore-log: 
,07-15 15:22:36.064  3491  3549 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-15 15:22:36.065  3491  3549 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-15 15:22:36.065  3491  3549 I jxcore-log: 
,07-15 15:22:36.109  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:36.109  3491  3549 I jxcore-log: 
,07-15 15:22:36.109  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-15 15:22:36.109  3491  3549 I jxcore-log: 
07-15 15:22:36.110  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.110  3491  3549 I jxcore-log: 
07-15 15:22:36.111  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.111  3491  3549 I jxcore-log: 
07-15 15:22:36.112  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.112  3491  3549 I jxcore-log: 
07-15 15:22:36.113  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.113  3491  3549 I jxcore-log: 
07-15 15:22:36.114  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.114  3491  3549 I jxcore-log: 
07-15 15:22:36.114  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.114  3491  3549 I jxcore-log: 
07-15 15:22:36.114  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.114  3491  3549 I jxcore-log: 
,07-15 15:22:36.115  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.115  3491  3549 I jxcore-log: 
07-15 15:22:36.116  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.116  3491  3549 I jxcore-log: 
07-15 15:22:36.116  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.116  3491  3549 I jxcore-log: 
,07-15 15:22:36.117  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.117  3491  3549 I jxcore-log: 
,07-15 15:22:36.117  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-15 15:22:36.117  3491  3549 I jxcore-log: 
07-15 15:22:36.118  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.118  3491  3549 I jxcore-log: 
07-15 15:22:36.118  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.118  3491  3549 I jxcore-log: 
07-15 15:22:36.118  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.118  3491  3549 I jxcore-log: 
07-15 15:22:36.119  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.119  3491  3549 I jxcore-log: 
07-15 15:22:36.119  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.119  3491  3549 I jxcore-log: 
07-15 15:22:36.120  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.120  3491  3549 I jxcore-log: 
,07-15 15:22:36.120  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.120  3491  3549 I jxcore-log: 
07-15 15:22:36.120  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.120  3491  3549 I jxcore-log: 
07-15 15:22:36.121  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.121  3491  3549 I jxcore-log: 
07-15 15:22:36.121  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.121  3491  3549 I jxcore-log: 
07-15 15:22:36.122  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-15 15:22:36.122  3491  3549 I jxcore-log: 
07-15 15:22:36.122  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-15 15:22:36.122  3491  3549 I jxcore-log: 
07-15 15:22:36.123  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-15 15:22:36.123  3491  3549 I jxcore-log: 
07-15 15:22:36.123  3491  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-15 15:22:36.123  3491  3549 I jxcore-log: 
,07-15 15:22:45.496  1636  3004 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-15 15:22:54.348  1230  1360 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-15 15:22:54.348  1230  1360 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-15 15:22:59.923   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:22:59.944   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:23:06.180   788   894 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-15 15:23:41.013  1744  1919 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-15 15:24:01.593   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:24:01.621   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:25:03.288   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:25:03.316   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:25:35.465  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:35.500  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-15 15:25:35.503  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:25:44.428  1744  2966 V NativeCrypto: SSL shutdown failed: ssl=0x9b138400: I/O error during system call, Connection timed out
,07-15 15:26:41.014  1744  2966 V NativeCrypto: SSL shutdown failed: ssl=0x99965e00: I/O error during system call, Connection timed out
,07-15 15:26:42.848  1744  2966 V NativeCrypto: SSL shutdown failed: ssl=0xaeef7200: I/O error during system call, Connection timed out
,07-15 15:31:04.975   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:31:05.000   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:36:09.667  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:36:09.700  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:36:09.701  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:37:06.618   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:37:06.645   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:40:20.459   788   800 I UsageStatsService: User[0] Flushing usage stats to disk
,07-15 15:41:09.758  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:41:09.792  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:41:09.793  1744  1744 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-15 15:43:08.284   788   892 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:43:08.311   788   892 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-15 15:43:08.392  1636  4227 I EventLogChimeraService: Aggregate from 1468587689759 (log), 1468587689759 (data)
,07-15 15:43:08.613  1636  4241 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-15 15:43:08.628  1636  4241 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,TIME-OUT KILL (timeout was 1400000ms)
```
