#### Test 7578926821ef376_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,07-07 20:30:01.998   875  2110 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268385, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
07-07 20:30:02.733  3822  3822 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-07 20:30:02.738  3822  3822 D AndroidRuntime: CheckJNI is OFF
07-07 20:30:02.780  3822  3822 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-07 20:30:02.829  3822  3822 I Radio-JNI: register_android_hardware_Radio DONE
07-07 20:30:02.850  3822  3822 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-07 20:30:02.858   875   885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-07 20:30:02.920   875   885 I ActivityManager: Start proc 3831:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-07 20:30:02.925  3822  3822 D AndroidRuntime: Shutting down VM
07-07 20:30:03.088  3831  3831 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-07 20:30:03.115  3831  3831 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-07 20:30:03.123  3831  3831 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9507-9510)
07-07 20:30:03.123  3831  3831 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:30:03.155  3831  3831 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {79e4540}
07-07 20:30:03.155  3831  3831 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:30:03.156  3831  3831 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 20:30:03.162  3831  3831 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-07 20:30:03.163  3831  3831 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:30:03.190  3831  3831 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-07 20:30:03.201  3831  3831 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:30:03.201  3831  3831 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-07 20:30:03.201  3831  3831 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-07 20:30:03.201  3831  3831 I Adreno  : Build Date                       : 10/20/15
07-07 20:30:03.201  3831  3831 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-07 20:30:03.201  3831  3831 I Adreno  : Local Branch                     : M14
07-07 20:30:03.201  3831  3831 I Adreno  : Remote Branch                    : 
07-07 20:30:03.201  3831  3831 I Adreno  : Remote Branch                    : 
07-07 20:30:03.201  3831  3831 I Adreno  : Reconstruct Branch               : 
,07-07 20:30:03.262   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a000e55:true
,07-07 20:30:03.305  3831  3831 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 20:30:03.317  3831  3831 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-07 20:30:03.371  3831  3869 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-07 20:30:03.382  3831  3855 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-07 20:30:03.417  3831  3869 I OpenGLRenderer: Initialized EGL, version 1.4
,07-07 20:30:03.459  1658  1658 I Keyboard.Facilitator: onFinishInput()
,07-07 20:30:03.473   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +447ms (total +589ms)
,07-07 20:30:03.536  3831  3831 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3831
,07-07 20:30:03.691  3831  3831 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:30:03.832  3831  3871 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1682704080
,07-07 20:30:03.842  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 20:30:03.842  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:30:03.842  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:30:03.842  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:30:03.842  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-07 20:30:03.842  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@428cdd7 added. We now have 1 listener(s)
,07-07 20:30:03.846  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-07 20:30:03.848  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-07 20:30:03.850  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:30:03.850  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-07 20:30:03.855  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10294e2 added. We now have 1 listener(s)
07-07 20:30:03.855  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:03.863   875  1313 D WifiService: New client listening to asynchronous messages
,07-07 20:30:03.866  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-07 20:30:03.871  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 20:30:03.872  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-07 20:30:03.873  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 20:30:03.873  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-07 20:30:03.881  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:03.882  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:30:03.893  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:30:03.893  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-07 20:30:03.893  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:30:03.894  3831  3871 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 20:30:03.899  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:03.902  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:03.935  3831  3831 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:30:04.910  3831  3877 W jxcore-log: Initializing JXcore engine
,07-07 20:30:04.911  3831  3877 W jxcore-log: JXcore engine is ready
,07-07 20:30:04.948  3877  3877 W Thread-349: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-07 20:30:04.948  3877  3877 W Thread-349: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11781]" dev="sockfs" ino=11781 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-07 20:30:04.948  3877  3877 W Thread-349: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-07 20:30:04.948  3877  3877 W Thread-349: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[24939]" dev="sockfs" ino=24939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-07 20:30:04.964  3831  3877 W jxcore-log: Starting JXcore engine
,07-07 20:30:05.047  3831  3877 W jxcore-log: Platform android
07-07 20:30:05.047  3831  3877 W jxcore-log: 
,07-07 20:30:05.048  3831  3877 W jxcore-log: Process ARCH arm
07-07 20:30:05.048  3831  3877 W jxcore-log: 
,07-07 20:30:05.245  3831  3877 I jxcore-log: JXcore Cordova bridge is ready!
07-07 20:30:05.245  3831  3877 I jxcore-log: 
,07-07 20:30:05.246  3831  3877 W jxcore-log: JXcore engine is started
,07-07 20:30:05.253  3831  3871 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 20:30:05.258  3831  3831 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 20:30:15.212  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-07 20:30:15.212  3831  3877 I jxcore-log: 
,07-07 20:30:15.215  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-07 20:30:15.215  3831  3877 I jxcore-log: 
,07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:30:15.228  3831  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:30:15.234  3831  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:30:15.236  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-07 20:30:15.236  3831  3877 I jxcore-log: 
,07-07 20:30:15.238  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-07 20:30:15.238  3831  3877 I jxcore-log: 
,07-07 20:30:15.608  3831  3877 I jxcore-log: Unit Test app is loaded
07-07 20:30:15.608  3831  3877 I jxcore-log: 
,07-07 20:30:15.620  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:30:15.620  3831  3877 I jxcore-log: 
,07-07 20:30:15.626  3831  3831 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-07 20:30:15.626  3831  3871 D JX-Cordova: Running tests
,07-07 20:30:15.640  3831  3877 I jxcore-log: My device name is: motorola-Nexus 6
07-07 20:30:15.640  3831  3877 I jxcore-log: 
07-07 20:30:15.648  3831  3877 I jxcore-log: WARN testUtils: myNameCallback not set!
07-07 20:30:15.648  3831  3877 I jxcore-log: 
,07-07 20:30:15.720  3831  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-07 20:30:15.720  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-07 20:30:15.720  3831  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,07-07 20:30:15.720  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-07 20:30:15.720  3831  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,07-07 20:30:15.721  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-07 20:30:15.722  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-07 20:30:15.722  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-07 20:30:15.723  3831  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-07 20:30:15.723  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-07 20:30:15.724  3831  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-07 20:30:15.724  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-07 20:30:15.724  3831  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-07 20:30:15.724  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-07 20:30:15.725  3831  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-07 20:30:15.725  3831  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-07 20:30:15.725  3831  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-07 20:30:15.725  3831  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,07-07 20:30:15.726  3831  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-07 20:30:15.726  3831  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-07 20:30:15.727  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:30:15.727  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5645120 added. We now have 2 listener(s)
07-07 20:30:15.727  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:15.730  3831  3871 D BluetoothAdapter: enable(): BT is already enabled..!
,07-07 20:30:15.730   875  1692 D WifiService: setWifiEnabled: true pid=3831, uid=10000
07-07 20:30:15.730   875  1692 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-07 20:30:15.731  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:30:15.731  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b2e7ad9 added. We now have 3 listener(s)
07-07 20:30:15.731  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:15.739  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:30:15.740  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90e9c9e added. We now have 4 listener(s)
07-07 20:30:15.740  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:15.741  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:15.742  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f25037f added. We now have 5 listener(s)
,07-07 20:30:15.742  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:15.754   875  1681 D WifiService: setWifiEnabled: false pid=3831, uid=10000
07-07 20:30:15.754   875  1681 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:30:15.759  2698  2749 D BluetoothAdapterState: Current state: ON, message: 23
,07-07 20:30:15.759  2698  2749 D BluetoothAdapterProperties: Setting state to 13
,07-07 20:30:15.759  2698  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:30:15.760  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:15.760  2698  2749 D BluetoothAdapterProperties: onBluetoothDisable()
,07-07 20:30:15.765  2698  2755 D BluetoothAdapterProperties: Scan Mode:20
,07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:30:15.764  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:30:15.765  2698  2749 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:30:15.766  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:30:15.766  2698  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:30:15.766  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:30:15.771  2698  2698 D HeadsetService: Received stop request...Stopping profile...
07-07 20:30:15.772  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-07 20:30:15.774  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:15.776   875  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-07 20:30:15.776   875  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,07-07 20:30:15.776   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-07 20:30:15.776   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-07 20:30:15.777  2698  2698 D A2dpService: Received stop request...Stopping profile...
07-07 20:30:15.776  1368  1849 D BluetoothHeadset: Proxy object disconnected
,07-07 20:30:15.778  2698  2902 D A2dpStateMachine: Exit Disconnected: -1
07-07 20:30:15.778  1368  1368 D HeadsetProfile: Bluetooth service disconnected
07-07 20:30:15.778   875   875 D BluetoothHeadset: Proxy object disconnected
,07-07 20:30:15.779   875   875 D BluetoothHeadset: Proxy object disconnected
,07-07 20:30:15.779  1368  1368 D BluetoothA2dp: Proxy object disconnected
,07-07 20:30:15.779  2698  2698 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:15.779  2698  2698 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:15.779  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:15.779  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:15.780  1742  1756 D BluetoothHeadset: Proxy object disconnected
,07-07 20:30:15.781  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:15.781   875   875 D BluetoothHeadset: Proxy object disconnected
,07-07 20:30:15.782   875   875 D BluetoothA2dp: Proxy object disconnected
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:30:15.784  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:30:15.786  2698  2698 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-07 20:30:15.786  2698  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,07-07 20:30:15.786  2698  2698 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-07 20:30:15.786  2698  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:15.786  2698  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:15.786  2698  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-07 20:30:15.786  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:15.787  2698  2755 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-07 20:30:15.789  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:15.790  2698  2698 V BluetoothAdapterState: isTurningOff()=true
,07-07 20:30:15.790  2698  2698 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:15.790  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:15.790  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:15.791  2698  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:15.792  2698  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:15.792  2698  2879 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:30:15.792  2698  2879 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-07 20:30:15.792  2698  2879 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-07 20:30:15.792  2698  2879 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:30:15.792  2698  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-07 20:30:15.792  2698  2698 D HidService: Received stop request...Stopping profile...
07-07 20:30:15.792  2698  2698 D HidService: Stopping Bluetooth HidService
07-07 20:30:15.793  1368  1368 D BluetoothInputDevice: Proxy object disconnected
07-07 20:30:15.793  1368  1368 D HidProfile: Bluetooth service disconnected
07-07 20:30:15.794  2698  2698 D HealthService: Received stop request...Stopping profile...
07-07 20:30:15.794   875  1312 E native  : do suspend true
07-07 20:30:15.795  2698  2698 D PanService: Received stop request...Stopping profile...
07-07 20:30:15.797  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:30:15.797  1368  1368 D PanProfile: Bluetooth service disconnected
07-07 20:30:15.797  2698  2698 D BluetoothMapService: Received stop request...Stopping profile...
07-07 20:30:15.797  2698  2698 D BluetoothMapService: stop()
07-07 20:30:15.798  2698  2698 D BluetoothMapAppObserver: deinitObservers()
07-07 20:30:15.798  2698  2698 D BluetoothMapAppObserver: removeReceiver()
07-07 20:30:15.799  1368  1368 D BluetoothMap: Proxy object disconnected
07-07 20:30:15.799  1368  1368 D MapProfile: Bluetooth service disconnected
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:15.800  2698  2698 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-07 20:30:15.800  2698  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-07 20:30:15.800  2698  2698 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:15.800  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:15.801  2698  2698 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:30:15.801  2698  2755 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-07 20:30:15.801  2698  2698 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:30:15.801  2698  2698 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:15.801  2698  2698 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:15.801  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:15.801  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:15.802  2698  2698 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-07 20:30:15.802  2698  2698 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-07 20:30:15.803  2698  2698 D BluetoothMapService: MAP Service closeService in
07-07 20:30:15.803  2698  2698 D BluetoothMapMasInstance0: MAP Service shutdown
07-07 20:30:15.803  2698  2698 D ObexServerSockets0: shutdown(block = true)
07-07 20:30:15.803  2698  2909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-07 20:30:15.803  2698  2698 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:30:15.804  2698  2910 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-07 20:30:15.804  2698  2890 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-07 20:30:15.804  2698  2698 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:30:15.804  2698  2698 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:15.804  2698  2698 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:,15.804  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:15.804  2698  2698 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:15.805  2698  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-07 20:30:15.805  2698  2749 D BluetoothAdapterProperties: Setting state to 15
07-07 20:30:15.805  2698  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:30:15.805  2698  2749 I BluetoothAdapterState: Entering BleOnState
07-07 20:30:15.805  2698  2698 D BluetoothMapService: cleanup()
07-07 20:30:15.805  2698  2698 D BluetoothMapService: MAP Service closeService in
07-07 20:30:15.807   875  2111 D DhcpClient: Clearing IP address
07-07 20:30:15.807   374   873 D CommandListener: Setting iface cfg
07-07 20:30:15.809   374   873 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:30:15.810  1368  1850 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:30:15.811  1368  1849 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:30:15.812   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:15.812   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:15.812  1368  1380 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:30:15.812   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:30:15.812  1368  1382 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:30:15.813  1742  1913 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:15.813   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:15.813  1368  1849 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:15.814  1368  1382 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:30:15.815  2698  2698 I BtOppRfcommListener: stopping Accept Thread
07-07 20:30:15.815  2698  3452 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-07 20:30:15.815  2698  3452 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-07 20:30:15.817  1511  2295 V NativeCrypto: Read error: ssl=0x9b475000: I/O error during system call, Connection timed out
07-07 20:30:15.818  1511  2295 V NativeCrypto: SSL shutdown failed: ssl=0x9b475000: I/O error during system call, Broken pipe
07-07 20:30:15.820   875  3212 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
07-07 20:30:15.820   875  2109 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
07-07 20:30:15.822   875  2109 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
07-07 20:30:15.823   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
07-07 20:30:15.823   875  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-07 20:30:15.824   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-07 20:30:15.828   875   888 I ActivityManager: Start proc 3882:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-07 20:30:15.829  2698  2749 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-07 20:30:15.830  2698  2749 D BluetoothAdapterProperties: Setting state to 16
07-07 20:30:15.830  2698  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-07 20:30:15.830  2698  2749 D BluetoothAdapterProperties: onBleDisable
07-07 20:30:15.830  2698  2749 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:30:15.831  2698  2750 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:30:15.831  2698  2755 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:30:15.832   397   397 E Parcel  : Reading a NULL string not supported here.
07-07 20:30:15.832   875  1314 D ConnectivityService: Netwo,rkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-07 20:30:15.832   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-07 20:30:15.833   875  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
07-07 20:30:15.834   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:30:15.834   875  1312 E native  : do suspend true
07-07 20:30:15.834   875  2112 D DhcpClient: Receive thread stopped
07-07 20:30:15.834  2698  2879 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-07 20:30:15.834  2698  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:15.844  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:30:15.844   875  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-07 20:30:15.844  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:15.845   374   873 D CommandListener: Clearing all IP addresses on wlan0
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:15.846  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:30:15.846  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:15.847   875  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-07 20:30:15.863   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:15.865  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:15.866  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:15.866   875  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:15.867  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:15.868  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:15.870  1836  2057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:30:15.881   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-07 20:30:15.893  3882  3882 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-07 20:30:15.897   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-07 20:30:15.898   875  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-07 20:30:15.898   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-07 20:30:15.900   875   892 D Tethering: MasterInitialState.processMessage what=3
07-07 20:30:15.904  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:15.904  3400  3400 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4b0be8a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-07 20:30:15.905  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:15.914  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:30:15.919  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:30:15.921   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9975b35:true
07-07 20:30:15.931   875  1681 I ActivityManager: Start proc 3900:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
07-07 20:30:15.957  3882  3882 D LocalBluetoothProfileManager: Adding local MAP profile
07-07 20:30:15.960  3882  3882 D BluetoothMap: Create BluetoothMap proxy object
07-07 20:30:15.965  3900  3900 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-07 20:30:15.969  3882  3882 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-07 20:30:15.970   374   873 E Netd    : netlink response contains error (No such file or directory)
,07-07 20:30:15.971   875  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-07 20:30:15.971   875  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-07 20:30:15.988  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:30:15.990   875  1741 I ActivityManager: Killing 3187:com.google.android.gm/u0a78 (adj 15): empty #17
,07-07 20:30:16.035  2698  2755 I bt_hci  : shut_down
,07-07 20:30:16.035  2698  2773 D bt_hwcfg: hw_epilog_process
07-07 20:30:16.036  2698  2773 I bt_vendor: low_power_mode_cb
,07-07 20:30:16.063  2698  2773 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-07 20:30:16.064  2698  2773 I bt_vendor: epilog_cb
,07-07 20:30:16.064  2698  2773 I bt_hci  : epilog_finished_callback
,07-07 20:30:16.073  2698  2755 I bt_hci_h4: hal_close
,07-07 20:30:16.073  2698  2755 I bt_userial_vendor: device fd = 51 close
,07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:170)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.k.d(PG:583)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:170)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.File.exists(File.java:361)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:30:16.143  3900  3900 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-07 20:30:16.143  3900  3900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-07 20:30:16.155  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:30:16.165  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:30:16.187   875  1741 I ActivityManager: Start proc 3932:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
07-07 20:30:16.196  3882  3882 D DockEventReceiver: finishStartingService: stopping service
07-07 20:30:16.199   875  1381 I ActivityManager: Killing 3400:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-07 20:30:16.305  2698  2750 D bt_stack_manager: event_shut_down_stack finished.
,07-07 20:30:16.306  2698  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-07 20:30:16.309  2698  2698 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:30:16.309  2698  2749 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-07 20:30:16.313  2698  2698 D BtGatt.GattService: Received stop request...Stopping profile...
,07-07 20:30:16.313  2698  2698 D BtGatt.GattService: stop()
07-07 20:30:16.314  2698  2698 D BtGatt.AdvertiseManager: advertise clients cleared
,07-07 20:30:16.322  2698  2698 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:16.322  2698  2698 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:16.322  2698  2698 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:30:16.322  2698  2698 V BluetoothAdapterState: isBleTurningOff()=true
07-07 20:30:16.323  2698  2749 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-07 20:30:16.323  2698  2749 D BluetoothAdapterProperties: Setting state to 10
,07-07 20:30:16.323  2698  2749 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-07 20:30:16.323  2698  2749 I BluetoothAdapterState: Entering OffState
07-07 20:30:16.326   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-07 20:30:16.338  2698  2698 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-07 20:30:16.338  2698  2698 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-07 20:30:16.338  2698  2750 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-07 20:30:16.340  2698  2750 D bt_stack_manager: event_clean_up_stack finished.
07-07 20:30:16.340  2698  2698 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-07 20:30:16.345  3932  3932 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-07 20:30:16.350  2698  2698 I art     : System.exit called, status: 0
,07-07 20:30:16.350  2698  2698 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-07 20:30:16.417  3900  3922 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-07 20:30:16.419   875  1768 I ActivityManager: Process com.android.bluetooth (pid 2698) has died
,07-07 20:30:16.421  3932  3932 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-07 20:30:16.456  1868  1868 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-07 20:30:16.460  1868  2375 I iu.UploadsManager: num queued entries: 0
,07-07 20:30:16.461  1868  1868 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-07 20:30:16.462  1868  1868 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-07 20:30:16.463  1868  2375 I iu.UploadsManager: num updated entries: 0
,07-07 20:30:16.464   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c33572a:true
,07-07 20:30:16.464  1868  2375 I iu.SyncManager: NEXT; no task
,07-07 20:30:16.473   875  1381 I ActivityManager: Start proc 3961:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-07 20:30:16.507  3961  3961 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-07 20:30:16.510  3961  3961 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-07 20:30:16.517  3961  3961 D SprintDMHelper: simOperator: 
,07-07 20:30:16.517  3961  3961 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-07 20:30:16.529   875  1615 I ActivityManager: Start proc 3973:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-07 20:30:16.530   875  1615 I ActivityManager: Killing 3280:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-07 20:30:16.660  2400  3987 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-07 20:30:16.665   875  1748 I ActivityManager: Start proc 3988:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-07 20:30:16.668   875  1768 I ActivityManager: Killing 3038:android.process.acore/u0a5 (adj 15): empty #17
,07-07 20:30:16.739  3988  3988 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
07-07 20:30:16.787  3988  3988 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-07 20:30:16.787  3988  3988 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-07 20:30:16.787  3988  3988 I GAv4    :   adb logcat -s GAv4
,07-07 20:30:16.801  3988  3988 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:16.809  3988  3988 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,07-07 20:30:16.833  3988  4005 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:16.925  3988  3988 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-07 20:30:16.964  3988  3988 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-07 20:30:16.971  3988  3988 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3356-3358)
,07-07 20:30:16.971  3988  3988 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:30:16.979  3988  3988 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7a9f8f4}
,07-07 20:30:16.980  3988  3988 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:30:16.980  3988  3988 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 20:30:16.986  3988  3988 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:30:16.988  3988  3988 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:30:17.002  3988  3988 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-07 20:30:17.015  3988  3988 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-07 20:30:17.015  3988  3988 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-07 20:30:17.015  3988  3988 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-07 20:30:17.015  3988  3988 I Adreno  : Build Date                       : 10/20/15
07-07 20:30:17.015  3988  3988 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-07 20:30:17.015  3988  3988 I Adreno  : Local Branch                     : M14
07-07 20:30:17.015  3988  3988 I Adreno  : Remote Branch                    : 
07-07 20:30:17.015  3988  3988 I Adreno  : Remote Branch                    : 
07-07 20:30:17.015  3988  3988 I Adreno  : Reconstruct Branch               : 
,07-07 20:30:17.082  3988  3988 I NSApplication: Starting up...
,07-07 20:30:17.085  3988  4034 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-07 20:30:17.113   875  1692 I ActivityManager: Start proc 4039:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-07 20:30:17.113   875  1692 I ActivityManager: Killing 3669:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-07 20:30:17.207  4039  4039 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-07 20:30:17.361   875  1768 I ActivityManager: Killing 3683:com.android.musicfx/u0a18 (adj 15): empty #17
,07-07 20:30:18.768   875  1741 D WifiService: setWifiEnabled: true pid=3831, uid=10000
,07-07 20:30:18.769   875  1741 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:30:18.782   875  1312 D WifiConfigStore: Loading config and enabling all networks 
,07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:18.791  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:18.791  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:18.793  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:18.794  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:18.815   875  1312 D WifiConfigStore: loaded 0 passpoint configs
,07-07 20:30:18.815   875  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-07 20:30:18.815   875  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-07 20:30:18.816   875  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000,
,07-07 20:30:18.817   875  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-07 20:30:18.817   875  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-07 20:30:18.817   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-07 20:30:18.817   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-07 20:30:18.835   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-07 20:30:18.835   875  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:30:18.836   374   873 D CommandListener: Setting iface cfg
,07-07 20:30:18.837   875  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-07 20:30:18.837   875  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-07 20:30:18.846   875  1312 E native  : do suspend true
,07-07 20:30:18.854   875  1311 D WifiNative-HAL: p2pGetDeviceAddress
,07-07 20:30:18.858   875  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-07 20:30:18.859   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:30:19.058   875  1381 I ActivityManager: Start proc 4062:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-07 20:30:19.108  4062  4062 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-07 20:30:19.140  4062  4062 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-07 20:30:19.140  4062  4062 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-07 20:30:19.140  4062  4062 I GAv4    :   adb logcat -s GAv4
,07-07 20:30:19.155  4062  4062 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:19.161  4062  4062 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:19.174  4062  4077 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-07 20:30:19.192   875  1741 I ActivityManager: Killing 3470:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-07 20:30:19.775  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-07 20:30:19.775  3831  3877 I jxcore-log: 
,07-07 20:30:20.188  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-07 20:30:20.188  3831  3877 I jxcore-log: 
,07-07 20:30:20.216  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-07 20:30:20.216  3831  3877 I jxcore-log: 
,07-07 20:30:20.221  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-07 20:30:20.221  3831  3877 I jxcore-log: 
,07-07 20:30:20.229   875  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:30:20.242  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-07 20:30:20.242  3831  3877 I jxcore-log: 
,07-07 20:30:20.247  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-07 20:30:20.247  3831  3877 I jxcore-log: 
,07-07 20:30:20.283   875  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.31 rxSuccessRate=13.44 delta 1000 -> 994
,07-07 20:30:20.287   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-07 20:30:20.287   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:30:20.298   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-07 20:30:20.341   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-07 20:30:20.347  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-07 20:30:20.796  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-07 20:30:20.836  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-07 20:30:20.836  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-07 20:30:20.843   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:30:20.856   875  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-07 20:30:20.856   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-07 20:30:20.856   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-07 20:30:20.875   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:30:20.895   374   873 D CommandListener: Setting iface cfg
,07-07 20:30:20.895   875  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,07-07 20:30:20.905   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-07 20:30:20.925   875  4084 D DhcpClient: Receive thread started
,07-07 20:30:21.010   875  1312 E native  : do suspend false
,07-07 20:30:21.020   875  2111 D DhcpClient: Broadcasting DHCPDISCOVER
,07-07 20:30:21.035   875  4084 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172536, domain null
07-07 20:30:21.035   875  2111 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172536 seconds
,07-07 20:30:21.036   875  2111 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-07 20:30:21.053   875  4084 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-07 20:30:21.054   875  2111 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-07 20:30:21.055   374   873 D CommandListener: Setting iface cfg
,07-07 20:30:21.058   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-07 20:30:21.059   875  2111 D DhcpClient: Scheduling renewal in 86399s
07-07 20:30:21.059   875  1312 E native  : do suspend true
,07-07 20:30:21.076   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-07 20:30:21.077   875  1312 D WifiConfigStore: No blacklist allowed without epno enabled
07-07 20:30:21.077   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-07 20:30:21.078   875  1314 D ConnectivityService: Adding iface wlan0 to network 101
07-07 20:30:21.081   875  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-07 20:30:21.126   875  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-07 20:30:21.126   875  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-07 20:30:21.127   875  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-07 20:30:21.127   875  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-07 20:30:21.128   875  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-07 20:30:21.135   875  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-07 20:30:21.139   875  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-07 20:30:21.139   875  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,07-07 20:30:21.139   875  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-07 20:30:21.140   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:30:21.140   875  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-07 20:30:21.140   875  1314 D ConnectivityService:    accepting network in place of null
07-07 20:30:21.141   875  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-07 20:30:21.153   875  4083 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287540, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:30:21.164   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:30:21.190   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:30:21.193   875  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-07 20:30:21.194   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-07 20:30:21.200   875   892 D Tethering: MasterInitialState.processMessage what=3
,07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:30:21.201  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 20:30:21.201  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:30:21.203  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:30:21.203  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:21.202   875  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-07 20:30:21.231   875  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:815::200e
,07-07 20:30:21.241  1868  1868 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-07 20:30:21.249  1868  2375 I iu.UploadsManager: num queued entries: 0
07-07 20:30:21.250  1868  2375 I iu.UploadsManager: num updated entries: 0
07-07 20:30:21.251  1868  2375 I iu.SyncManager: NEXT; no task
,07-07 20:30:21.252  1868  1868 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-07 20:30:21.254  1868  1868 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-07 20:30:21.258  3961  3961 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
07-07 20:30:21.261  1868  4100 I MDM     : [217] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-07 20:30:21.261  1868  4100 W BaseAppContext: Using Auth Proxy for data requests.
07-07 20:30:21.262  1868  4100 V GoogleAuthProtoRequest: [217] a.<init>: mAccountName set to: thalitester@gmail.com
07-07 20:30:21.267  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-07 20:30:21.269  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:21.282  3961  3961 D SprintDMHelper: simOperator: 
07-07 20:30:21.282  3961  3961 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-07 20:30:21.304  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-07 20:30:21.304  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-07 20:30:21.304  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:21.304  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-07 20:30:21.308   875  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 07 Jul 2016 18:30:21 GMT], X-Android-Received-Millis=[1467916221308], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467916221272]}
07-07 20:30:21.309   875  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-07 20:30:21.309   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-07 20:30:21.309   875  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-07 20:30:21.310   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-07 20:30:21.325  1868  4100 E MDM     : [217] SitrepService.a: Error sending sitrep.
07-07 20:30:21.349  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-07 20:30:21.349  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:30:21.349  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:21.349  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-07 20:30:21.361  3006  4095 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-07 20:30:21.361  3006  4095 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at blb.a(PG:3937)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at czp.a(PG:18188)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:30:21.361  3006  4095 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	... 12 more
07-07 20:30:21.361  3006  4095 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at fal.a(PG:38)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:30:21.361  3006  4095 E HttpOperation: 	... 14 more
,07-07 20:30:21.404  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:30:21.404  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:30:21.404  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:21.405  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:30:21.417  3006  4095 E HttpOperation: [getmobileexperiments] Unexpected exception
07-07 20:30:21.417  3006  4095 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at jcs.o(PG:406),
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at hec.a(PG:42)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at hee.a(PG:102)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at czr.a(PG:65)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at kka.a(PG:108)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at czp.a(PG:19176)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:30:21.417  3006  4095 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	... 15 more
07-07 20:30:21.417  3006  4095 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:30:21.417  3006  4095 E HttpOperation: 	at fal.a(PG:38)
07-07 20:3,0:21.417  3006  4095 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:30:21.417  3006  4095 E HttpOperation: 	... 17 more
07-07 20:30:21.417  3006  4095 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-07 20:30:21.417  3006  4095 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jdm.a(PG:82)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jcs.o(PG:406)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jcn.a(PG:1379)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jcs.i(PG:143)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at hec.a(PG:42)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at hee.a(PG:102)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at czr.a(PG:65)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at kka.a(PG:108)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at czp.a(PG:19176)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at czp.a(PG:9081)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at czq.run(PG:1686)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jdj.a(PG:4091)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jdj.a(PG:1125)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jdm.a(PG:77)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	... 15 more
07-07 20:30:21.417  3006  4095 E ExperimentLoader: Caused by: faj: BadAuthentication
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at fal.a(PG:38)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	at jdj.a(PG:4089)
07-07 20:30:21.417  3006  4095 E ExperimentLoader: 	... 17 more
,07-07 20:30:21.468  2400  4102 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-07 20:30:21.523   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 285845, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:30:21.523   875   886 I ActivityManager: Killing 3707:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-07 20:30:21.779   875  1381 D WifiService: setWifiEnabled: false pid=3831, uid=10000
,07-07 20:30:21.779   875  1381 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:30:21.805  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-07 20:30:21.812   875  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-07 20:30:21.812   875  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-07 20:30:21.813   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:30:21.813   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:30:21.826   875  1312 E native  : do suspend true
,07-07 20:30:21.838   374   873 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:30:21.838   875  2111 D DhcpClient: Clearing IP address
07-07 20:30:21.840   374   873 D CommandListener: Setting iface cfg
,07-07 20:30:21.846  1511  4107 V NativeCrypto: Read error: ssl=0x9aeb6e00: I/O error during system call, Connection timed out
,07-07 20:30:21.848  1511  4107 V NativeCrypto: SSL shutdown failed: ssl=0x9aeb6e00: I/O error during system call, Broken pipe
,07-07 20:30:21.852   875  1738 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,07-07 20:30:21.852   875  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,07-07 20:30:21.852   875  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:815::200e
,07-07 20:30:21.853   875  4084 D DhcpClient: Receive thread stopped
07-07 20:30:21.855   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-07 20:30:21.855   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
07-07 20:30:21.857   875  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
,07-07 20:30:21.858   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-07 20:30:21.858   875  1312 E native  : do suspend true
07-07 20:30:21.859   875  4082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:815::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
07-07 20:30:21.859   397   397 E Parcel  : Reading a NULL string not supported here.
07-07 20:30:21.868   374   873 D CommandListener: Clearing all IP addresses on wlan0
,07-07 20:30:21.871   875  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-07 20:30:21.872   875  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-07 20:30:21.886   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:21.889  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:21.889  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:21.889  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:21.891  1836  2057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-07 20:30:21.891   875  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-07 20:30:21.907   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:30:21.934   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:30:21.934   875  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-07 20:30:21.934   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-07 20:30:21.936   875   892 D Tethering: MasterInitialState.processMessage what=3
07-07 20:30:21.938  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:21.939  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:21.957  1868  1868 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-07 20:30:21.963  1868  2375 I iu.UploadsManager: num queued entries: 0
,07-07 20:30:21.963  1868  2375 I iu.UploadsManager: num updated entries: 0
,07-07 20:30:21.965  1868  1868 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-07 20:30:21.966  1868  1868 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-07 20:30:21.968  3961  3961 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-07 20:30:21.973  3961  3961 D SprintDMHelper: simOperator: 
07-07 20:30:21.973  3961  3961 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-07 20:30:21.977  1868  2375 I iu.SyncManager: NEXT; no task
,07-07 20:30:22.003  2400  4122 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-07 20:30:22.008   374   873 E Netd    : netlink response contains error (No such file or directory)
,07-07 20:30:22.010   875  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-07 20:30:22.010   875  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-07 20:30:22.194   875  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-07 20:30:22.464  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-07 20:30:22.464  3831  3877 I jxcore-log: 
,07-07 20:30:22.476  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-07 20:30:22.476  3831  3877 I jxcore-log: 
,07-07 20:30:22.485  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-07 20:30:22.485  3831  3877 I jxcore-log: 
,07-07 20:30:22.644  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-07 20:30:22.644  3831  3877 I jxcore-log: 
,07-07 20:30:22.727  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-07 20:30:22.727  3831  3877 I jxcore-log: 
,07-07 20:30:22.783  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-07 20:30:22.783  3831  3877 I jxcore-log: 
,07-07 20:30:22.790  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
07-07 20:30:22.790  3831  3877 I jxcore-log: 
,07-07 20:30:22.986  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-07 20:30:22.986  3831  3877 I jxcore-log: 
,07-07 20:30:23.007  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-07 20:30:23.007  3831  3877 I jxcore-log: 
,07-07 20:30:23.013  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-07 20:30:23.013  3831  3877 I jxcore-log: 
,07-07 20:30:23.019  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-07 20:30:23.019  3831  3877 I jxcore-log: 
,07-07 20:30:23.035  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-07 20:30:23.035  3831  3877 I jxcore-log: 
,07-07 20:30:23.055  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,07-07 20:30:23.055  3831  3877 I jxcore-log: 
,07-07 20:30:23.146  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
07-07 20:30:23.146  3831  3877 I jxcore-log: 
07-07 20:30:23.153  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-07 20:30:23.153  3831  3877 I jxcore-log: 
,07-07 20:30:23.215  3831  3877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-07 20:30:23.215  3831  3877 I jxcore-log: 
,07-07 20:30:23.227  3831  3877 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-07 20:30:23.229  3831  3877 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-07 20:30:23.229  3831  3877 I jxcore-log: 
,07-07 20:30:23.281  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:30:23.281  3831  3877 I jxcore-log: 
,07-07 20:30:23.282  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:30:23.282  3831  3877 I jxcore-log: 
07-07 20:30:23.283  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:30:23.283  3831  3877 I jxcore-log: 
,07-07 20:30:23.285  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:30:23.285  3831  3877 I jxcore-log: 
,07-07 20:30:23.286  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:30:23.286  3831  3877 I jxcore-log: 
,07-07 20:30:23.286  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:30:23.286  3831  3877 I jxcore-log: 
07-07 20:30:23.287  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:30:23.287  3831  3877 I jxcore-log: 
07-07 20:30:23.288  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-07 20:30:23.288  3831  3877 I jxcore-log: 
,07-07 20:30:23.288  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:30:23.288  3831  3877 I jxcore-log: 
07-07 20:30:23.289  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:30:23.289  3831  3877 I jxcore-log: 
,07-07 20:30:23.290  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:30:23.290  3831  3877 I jxcore-log: 
07-07 20:30:23.290  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:30:23.290  3831  3877 I jxcore-log: 
,07-07 20:30:24.832   875   892 I ActivityManager: Start proc 4124:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-07 20:30:24.970  4124  4124 D AdapterServiceConfig: Adding HeadsetService
,07-07 20:30:24.970  4124  4124 D AdapterServiceConfig: Adding A2dpService
,07-07 20:30:24.970  4124  4124 D AdapterServiceConfig: Adding HidService
,07-07 20:30:24.970  4124  4124 D AdapterServiceConfig: Adding HealthService
,07-07 20:30:24.970  4124  4124 D AdapterServiceConfig: Adding PanService
07-07 20:30:24.971  4124  4124 D AdapterServiceConfig: Adding GattService
,07-07 20:30:24.971  4124  4124 D AdapterServiceConfig: Adding BluetoothMapService
,07-07 20:30:24.983   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5fe0bf0:true
07-07 20:30:24.984  4124  4124 D BluetoothAdapterState: make() - Creating AdapterState
07-07 20:30:24.987  4124  4124 I bt_bluedroid: init
07-07 20:30:24.987  4124  4136 I BluetoothAdapterState: Entering OffState
,07-07 20:30:24.993  4124  4137 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-07 20:30:24.993  4124  4137 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-07 20:30:24.994  4124  4137 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-07 20:30:24.994  4124  4137 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-07 20:30:24.997  4124  4124 I bt_bluedroid: get_profile_interface socket
,07-07 20:30:24.998  4124  4124 I bt_bluedroid: get_profile_interface sdp
,07-07 20:30:25.002  4124  4135 I bt_bluedroid: config_hci_snoop_log
,07-07 20:30:25.003  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-07 20:30:25.006   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-07 20:30:25.013  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,07-07 20:30:25.016  4124  4136 D BluetoothAdapterState: Current state: OFF, message: 0
07-07 20:30:25.016  4124  4136 D BluetoothAdapterProperties: Setting state to 14
07-07 20:30:25.016  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-07 20:30:25.017  4124  4136 D BluetoothBondStateMachine: make
,07-07 20:30:25.019  4124  4141 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-07 20:30:25.022  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:30:25.023  4124  4124 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-07 20:30:25.026  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:25.027  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
07-07 20:30:25.028  4124  4124 D BtGatt.GattService: Received start request. Starting profile...
07-07 20:30:25.028  4124  4124 D BtGatt.GattService: start()
07-07 20:30:25.028  4124  4124 I bt_bluedroid: get_profile_interface gatt
07-07 20:30:25.029  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
07-07 20:30:25.029  4124  4124 D BtGatt.AdvertiseManager: advertise manager created
,07-07 20:30:25.036  4124  4124 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:25.036  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:25.036  4124  4124 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:30:25.036  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:25.036  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-07 20:30:25.036  4124  4136 I bt_bluedroid: enable
07-07 20:30:25.037  4124  4137 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-07 20:30:25.037  4124  4137 I bt_hci  : start_up
,07-07 20:30:25.051  4124  4137 I bt_vendor: alloc value 0xb3a15189
07-07 20:30:25.051  4124  4137 I bt_vendor: init
,07-07 20:30:25.051  4124  4137 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-07 20:30:25.051  4124  4137 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-07 20:30:25.157  4124  4137 D bt_hci  : start_up starting async portion
,07-07 20:30:25.158  4124  4144 I bt_hci  : event_finish_startup
07-07 20:30:25.158  4124  4144 I bt_hci_h4: hal_open
07-07 20:30:25.159  4124  4144 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-07 20:30:25.167  4124  4144 I bt_userial_vendor: device fd = 51 open
,07-07 20:30:25.200  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-07 20:30:25.232  4124  4144 D bt_hwcfg: Chipset BCM4354A2
,07-07 20:30:25.232  4124  4144 D bt_hwcfg: Target name = [BCM4354A2]
,07-07 20:30:25.233  4124  4144 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-07 20:30:25.890  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-07 20:30:25.892  4124  4144 D bt_hwcfg: Settlement delay -- 100 ms
07-07 20:30:25.892  4124  4144 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:30:26.009  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-07 20:30:26.010  4124  4144 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-07 20:30:26.039  4124  4144 I bt_hwcfg: vendor lib fwcfg completed
,07-07 20:30:26.040  4124  4144 I bt_vendor: firmware callback
,07-07 20:30:26.040  4124  4144 I bt_hci  : firmware_config_callback
,07-07 20:30:26.051  4124  4146 I bt_btu  : btu_task pending for preload complete event,
07-07 20:30:26.051  4124  4146 I bt_btu_task: Bluetooth chip preload is complete
,07-07 20:30:26.052  4124  4146 I bt_btu  : btu_task received preload complete event
,07-07 20:30:26.065  4124  4146 I         : BTE_InitTraceLevels -- TRC_HCI
07-07 20:30:26.065  4124  4146 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-07 20:30:26.065  4124  4146 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-07 20:30:26.065  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-07 20:30:26.066  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-07 20:30:26.066  4124  4146 I         : BTE_InitTraceLevels -- TRC_A2D
07-07 20:30:26.066  4124  4146 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-07 20:30:26.067  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTM
07-07 20:30:26.067  4124  4146 I         : BTE_InitTraceLevels -- TRC_GAP
,07-07 20:30:26.067  4124  4146 I         : BTE_InitTraceLevels -- TRC_PAN
07-07 20:30:26.067  4124  4146 I         : BTE_InitTraceLevels -- TRC_SDP
07-07 20:30:26.068  4124  4146 I         : BTE_InitTraceLevels -- TRC_GATT
,07-07 20:30:26.068  4124  4146 I         : BTE_InitTraceLevels -- TRC_SMP
07-07 20:30:26.068  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-07 20:30:26.068  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:30:26.202  4124  4146 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3992d9d
,07-07 20:30:26.203  4124  4146 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3992d9d 
,07-07 20:30:26.214  4124  4140 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-07 20:30:26.215  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:30:26.216  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-07 20:30:26.220  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,07-07 20:30:26.223  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
,07-07 20:30:26.224  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-07 20:30:26.224  4124  4140 D bt_hci  : do_postload posting postload work item
,07-07 20:30:26.224  4124  4144 I bt_hci  : event_postload
,07-07 20:30:26.224  4124  4144 I bt_vendor: sco_config_cb
07-07 20:30:26.224  4124  4144 I bt_hci  : sco_config_callback postload finished.
07-07 20:30:26.228  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:26.230  4124  4140 D bt_bte_conf: Device ID record 1 : primary
,07-07 20:30:26.231  4124  4140 D bt_bte_conf:   vendorId            = 000f
07-07 20:30:26.231  4124  4140 D bt_bte_conf:   vendorIdSource      = 0001
07-07 20:30:26.231  4124  4140 D bt_bte_conf:   product             = 1200
07-07 20:30:26.231  4124  4140 D bt_bte_conf:   version             = 1436
,07-07 20:30:26.231  4124  4140 D bt_bte_conf:   clientExecutableURL = 
07-07 20:30:26.232  4124  4140 D bt_bte_conf:   serviceDescription  = 
07-07 20:30:26.232  4124  4140 D bt_bte_conf:   documentationURL    = 
07-07 20:30:26.232  4124  4140 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-07 20:30:26.234  4124  4144 I bt_vendor: low_power_mode_cb
07-07 20:30:26.234  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:26.235  4124  4137 D bt_stack_manager: event_start_up_stack finished
07-07 20:30:26.236  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-07 20:30:26.237  4124  4136 D BluetoothAdapterProperties: Setting state to 15
07-07 20:30:26.237  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-07 20:30:26.239  4124  4136 I BluetoothAdapterState: Entering BleOnState
,07-07 20:30:26.244  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-07 20:30:26.244  4124  4136 D BluetoothAdapterProperties: Setting state to 11
07-07 20:30:26.244  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-07 20:30:26.251  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:26.252  4124  4124 D HeadsetService: Received start request. Starting profile...
07-07 20:30:26.255  4124  4124 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-07 20:30:26.257  4124  4124 D HeadsetStateMachine: make
,07-07 20:30:26.263  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:30:26.267  4124  4124 D HeadsetStateMachine: max_hf_connections = 1
,07-07 20:30:26.267  4124  4124 I bt_bluedroid: get_profile_interface handsfree
,07-07 20:30:26.268  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-07 20:30:26.268  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,07-07 20:30:26.272  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:26.273  4124  4124 D A2dpService: Received start request. Starting profile...
07-07 20:30:26.273  4124  4124 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-07 20:30:26.274  4124  4124 I bt_bluedroid: get_profile_interface avrcp
,07-07 20:30:26.279  4124  4124 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-07 20:30:26.279  4124  4124 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-07 20:30:26.279  4124  4124 D A2dpStateMachine: make
,07-07 20:30:26.280  4124  4124 I bt_bluedroid: get_profile_interface a2dp
,07-07 20:30:26.281  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-07 20:30:26.282  4124  4124 I BluetoothHidServiceJni: classInitNative: succeeds
07-07 20:30:26.282  4124  4155 D A2dpStateMachine: Enter Disconnected: -2
07-07 20:30:26.283  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:26.285  4124  4124 D HidService: Received start request. Starting profile...
07-07 20:30:26.285  4124  4124 I bt_bluedroid: get_profile_interface hidhost
,07-07 20:30:26.285  4124  4140 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39743e5
07-07 20:30:26.285  4124  4124 D HidService: setHidService(): set to: null
07-07 20:30:26.286  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-07 20:30:26.287  4124  4124 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-07 20:30:26.288  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:26.289  4124  4124 D HealthService: Received start request. Starting profile...
,07-07 20:30:26.290  3882  3882 D BluetoothInputDevice: Proxy object connected
07-07 20:30:26.290  4124  4124 I bt_bluedroid: get_profile_interface health
07-07 20:30:26.291  4124  4124 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-07 20:30:26.291  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
07-07 20:30:26.292  3882  3882 D HidProfile: Bluetooth service connected
07-07 20:30:26.292  4124  4124 D PanService: Received start request. Starting profile...
07-07 20:30:26.293  4124  4124 D BluetoothPanServiceJni: initializeNative(L110): pan
07-07 20:30:26.293  4124  4124 I bt_bluedroid: get_profile_interface pan
07-07 20:30:26.293  4124  4140 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:30:26.295  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:26.296  4124  4124 D BluetoothMapService: Received start request. Starting profile...
,07-07 20:30:26.296  4124  4124 D BluetoothMapService: start()
,07-07 20:30:26.296  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
07-07 20:30:26.297  3882  3882 D PanProfile: Bluetooth service connected
,07-07 20:30:26.297  3882  3882 D BluetoothMap: Proxy object connected
07-07 20:30:26.297  3882  3882 D MapProfile: Bluetooth service connected
,07-07 20:30:26.298  3882  3882 D BluetoothMap: getConnectedDevices()
07-07 20:30:26.298  3882  3882 D BluetoothMap: Bluetooth is Not enabled
07-07 20:30:26.299  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-07 20:30:26.300  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-07 20:30:26.300  4124  4124 D BluetoothMapAppObserver: createReceiver()
07-07 20:30:26.301  4124  4124 D BluetoothMapAppObserver: initObservers()
07-07 20:30:26.301  4124  4124 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-07 20:30:26.316  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:30:26.318  4124  4124 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:26.318  4124  4153 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-07 20:30:26.318  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:30:26.318  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:26.319  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:30:26.321  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:30:26.321  4124  4124 V BluetoothAdapterState: isTurningOn()=true
07-07 20:30:26.322  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:26.322  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:26.322  4124  4124 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:26.322  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:30:26.322  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:26.322  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:26.323  4124  4124 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:26.323  4124  4124 V BluetoothAdapterState: isTurningOn()=true
07-07 20:30:26.323  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:30:26.323  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:26.323  4124  4124 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:26.324  4124  4124 V BluetoothAdapterState: isTurningOn()=true
07-07 20:30:26.324  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:26.324  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:30:26.324  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:30:26.324  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:30:26.324  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:26.325  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:26.325  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-07 20:30:26.325  4124  4136 D BluetoothAdapterProperties: ScanMode =  20
07-07 20:30:26.325  4124  4136 D BluetoothAdapterProperties: State =  11
07-07 20:30:26.327  4124  4136 D BluetoothAdapterProperties: Setting state to 12
07-07 20:30:26.327  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:30:26.328  4124  4136 I BluetoothAdapterState: Entering OnState
,07-07 20:30:26.328  1368  1380 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:30:26.329  4124  4140 D BluetoothAdapterProperties: Scan Mode:21
07-07 20:30:26.329  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:30:26.331  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected,
07-07 20:30:26.331  1368  1368 D PanProfile: Bluetooth service connected
07-07 20:30:26.331  1368  1382 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:30:26.333   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:26.333  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-07 20:30:26.333  3882  3893 D BluetoothPbap: onBluetoothStateChange: up=true
,07-07 20:30:26.334  4124  4124 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-07 20:30:26.336   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:30:26.336  1368  1850 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-07 20:30:26.337  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:30:26.339   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-07 20:30:26.339  1368  1368 D BluetoothInputDevice: Proxy object connected
07-07 20:30:26.339  3882  3894 D BluetoothMap: onBluetoothStateChange: up=true
,07-07 20:30:26.340  1368  1368 D HidProfile: Bluetooth service connected
07-07 20:30:26.340  1368  1380 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:26.340  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:26.342  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-07 20:30:26.343  3882  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:30:26.344  1368  1368 D BluetoothMap: Proxy object connected
07-07 20:30:26.344  1368  1368 D MapProfile: Bluetooth service connected
,07-07 20:30:26.344  1368  1368 D BluetoothMap: getConnectedDevices()
07-07 20:30:26.344  1742  1757 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:26.345  3882  3894 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:30:26.345   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:26.345  1368  1849 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:26.345  4124  4124 D ObexServerSockets: Succeed to create listening sockets 
07-07 20:30:26.345  4124  4124 D ObexServerSockets0: startAccept()
07-07 20:30:26.345  4124  4124 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:30:26.346  1368  1850 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:30:26.347  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:26.348  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:30:26.348  3831  3877 I jxcore-log: 
07-07 20:30:26.350   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:26.350  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:26.353  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:26.354  4124  4124 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-07 20:30:26.354  4124  4124 D BluetoothSdpJni: SDP Create record success - handle: 0
07-07 20:30:26.355  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:30:26.355  3831  3877 I jxcore-log: 
07-07 20:30:26.355  4124  4162 D ObexServerSockets0: Accepting socket connection...
07-07 20:30:26.355  4124  4124 D BluetoothMapService: onReceive
07-07 20:30:26.355  1368  1368 D BluetoothA2dp: Proxy object connected
07-07 20:30:26.355  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:30:26.355   875   875 D BluetoothA2dp: Proxy object connected
07-07 20:30:26.356  4124  4124 D BluetoothMapService: STATE_ON
07-07 20:30:26.354  3882  3882 D LocalBluetoothProfileManager: Adding local A2DP profile
07-07 20:30:26.357  4124  4163 D ObexServerSockets0: Accepting socket connection...
07-07 20:30:26.364  3882  3882 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-07 20:30:26.371  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:30:26.373  3882  3882 D BluetoothA2dp: Proxy object connected
,07-07 20:30:26.376  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-07 20:30:26.376  4124  4124 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:30:26.378  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:30:26.383  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:30:26.386  1368  1368 D BluetoothPbap: Proxy object connected
,07-07 20:30:26.386  3882  3882 D BluetoothPbap: Proxy object connected
07-07 20:30:26.386  1368  1368 D PbapServerProfile: Bluetooth service connected
07-07 20:30:26.386  3882  3882 D PbapServerProfile: Bluetooth service connected
,07-07 20:30:26.392  4124  4167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:30:26.408  4124  4171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:30:26.409  4124  4171 I BtOppRfcommListener: Accept thread started.
,07-07 20:30:26.435  1368  1382 D BluetoothHeadset: Proxy object connected
,07-07 20:30:26.435  1368  1368 D HeadsetProfile: Bluetooth service connected
07-07 20:30:26.435   875   875 D BluetoothHeadset: Proxy object connected
07-07 20:30:26.435   875   875 D BluetoothHeadset: Proxy object connected
07-07 20:30:26.435  1742  1756 D BluetoothHeadset: Proxy object connected
,07-07 20:30:26.435   875   875 D BluetoothHeadset: Proxy object connected
07-07 20:30:26.436   875   892 D BluetoothHeadset: Proxy object connected
,07-07 20:30:26.445  1742  1913 D BluetoothHeadset: Proxy object connected
,07-07 20:30:26.445   875   892 D BluetoothHeadset: Proxy object connected
,07-07 20:30:26.447  1368  1380 D BluetoothHeadset: Proxy object connected
,07-07 20:30:26.447  1368  1368 D HeadsetProfile: Bluetooth service connected
,07-07 20:30:26.468  3882  3893 D BluetoothHeadset: Proxy object connected
,07-07 20:30:26.469  3882  3882 D HeadsetProfile: Bluetooth service connected
,07-07 20:30:27.795  4124  4136 D BluetoothAdapterState: Current state: ON, message: 23
,07-07 20:30:27.796  4124  4136 D BluetoothAdapterProperties: Setting state to 13
,07-07 20:30:27.796  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-07 20:30:27.799  4124  4136 D BluetoothAdapterProperties: onBluetoothDisable()
,07-07 20:30:27.801  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:30:27.807  4124  4124 D BluetoothMapService: onReceive
,07-07 20:30:27.809  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-07 20:30:27.809  4124  4124 D BluetoothMapService: STATE_TURNING_OFF
,07-07 20:30:27.810  4124  4124 D BluetoothMapService: MAP Service closeService in
,07-07 20:30:27.811  4124  4124 D BluetoothMapMasInstance0: MAP Service shutdown
07-07 20:30:27.811  4124  4124 D ObexServerSockets0: shutdown(block = true)
07-07 20:30:27.813  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:30:27.813  4124  4162 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-07 20:30:27.813  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
07-07 20:30:27.813  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-07 20:30:27.814  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-07 20:30:27.814  4124  4163 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-07 20:30:27.815  4124  4149 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,07-07 20:30:27.817  4124  4124 I BtOppRfcommListener: stopping Accept Thread
07-07 20:30:27.818  4124  4171 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-07 20:30:27.818  4124  4171 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:27.827  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:27.828  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:30:27.829  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:27.831  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:27.832  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:27.833  4124  4124 D HeadsetService: Received stop request...Stopping profile...
07-07 20:30:27.833  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:30:27.833  3831  3877 I jxcore-log: 
07-07 20:30:27.836  1368  1380 D BluetoothHeadset: Proxy object disconnected
07-07 20:30:27.836   875   875 D BluetoothHeadset: Proxy object disconnected
07-07 20:30:27.836  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-07 20:30:27.836  3831  3877 I jxcore-log: 
07-07 20:30:27.836   875   875 D BluetoothHeadset: Proxy object disconnected
07-07 20:30:27.837  3882  3893 D BluetoothHeadset: Proxy object disconnected
07-07 20:30:27.837  1742  2029 D BluetoothHeadset: Proxy object disconnected
07-07 20:30:27.837   875   875 D BluetoothHeadset: Proxy object disconnected
07-07 20:30:27.838  4124  4124 D A2dpService: Received stop request...Stopping profile...
07-07 20:30:27.838  1368  1368 D HeadsetProfile: Bluetooth service disconnected
,07-07 20:30:27.838  4124  4155 D A2dpStateMachine: Exit Disconnected: -1
07-07 20:30:27.840   875   875 D BluetoothA2dp: Proxy object disconnected
07-07 20:30:27.840  1368  1368 D BluetoothA2dp: Proxy object disconnected
07-07 20:30:27.840  4124  4124 D HidService: Received stop request...Stopping profile...
07-07 20:30:27.841  4124  4124 D HidService: Stopping Bluetooth HidService
07-07 20:30:27.841  3882  3882 D DockEventReceiver: finishStartingService: stopping service
07-07 20:30:27.841  1368  1368 D BluetoothInputDevice: Proxy object disconnected
07-07 20:30:27.842  1368  1368 D HidProfile: Bluetooth service disconnected
07-07 20:30:27.842  3882  3882 D HeadsetProfile: Bluetooth service disconnected
,07-07 20:30:27.843  3882  3882 D BluetoothA2dp: Proxy object disconnected
07-07 20:30:27.843  3882  3882 D BluetoothInputDevice: Proxy object disconnected
07-07 20:30:27.843  3882  3882 D HidProfile: Bluetooth service disconnected
07-07 20:30:27.845  4124  4124 D HealthService: Received stop request...Stopping profile...
07-07 20:30:27.847  4124  4124 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:27.847  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:27.847  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:27.847  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-07 20:30:27.847  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:30:27.847  4124  4124 D PanService: Received stop request...Stopping profile...
07-07 20:30:27.850  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:30:27.851  1368  1368 D PanProfile: Bluetooth service disconnected
,07-07 20:30:27.851  3882  3882 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-07 20:30:27.851  3882  3882 D PanProfile: Bluetooth service disconnected
,07-07 20:30:27.852  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-07 20:30:27.853  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-07 20:30:27.853  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:27.853  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-07 20:30:27.853  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:27.852  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-07 20:30:27.853  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
07-07 20:30:27.854  4124  4124 D BluetoothMapService: Received stop request...Stopping profile...
07-07 20:30:27.854  4124  4124 D BluetoothMapService: stop()
07-07 20:30:27.854  4124  4124 D BluetoothMapAppObserver: deinitObservers()
07-07 20:30:27.854  4124  4124 D BluetoothMapAppObserver: removeReceiver()
,07-07 20:30:27.856  1368  1368 D BluetoothMap: Proxy object disconnected
07-07 20:30:27.856  1368  1368 D MapProfile: Bluetooth service disconnected
,07-07 20:30:27.856  4124  4124 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:27.856  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:27.856  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:27.856  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:27.856  3882  3882 D BluetoothMap: Proxy object disconnected
07-07 20:30:27.857  3882  3882 D MapProfile: Bluetooth service disconnected
,07-07 20:30:27.857  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-07 20:30:27.857  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:27.857  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:27.858  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:30:27.858  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-07 20:30:27.858  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-07 20:30:27.858  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-07 20:30:27.860  4124  4124 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:27.860  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:27.860  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,07-07 20:30:27.860  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:27.860  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-07 20:30:27.861  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-07 20:30:27.861  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:30:27.863  3882  3882 D BluetoothPbap: Proxy object disconnected
,07-07 20:30:27.863  3882  3882 D PbapServerProfile: Bluetooth service disconnected
07-07 20:30:27.863  1368  1368 D BluetoothPbap: Proxy object disconnected
07-07 20:30:27.863  1368  1368 D PbapServerProfile: Bluetooth service disconnected
07-07 20:30:27.864  4124  4124 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:27.864  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:27.864  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:27.864  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:27.864  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-07 20:30:27.864  4124  4140 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-07 20:30:27.864  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-07 20:30:27.865  4124  4124 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:27.865  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:27.865  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:27.865  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:30:27.867  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-07 20:30:27.868  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-07 20:30:27.868  4124  4124 D BluetoothMapService: MAP Service closeService in
07-07 20:30:27.869  4124  4124 V BluetoothAdapterState: isTurningOff()=true
07-07 20:30:27.869  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:27.869  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:27.869  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:27.869  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-07 20:30:27.869  4124  4124 D BluetoothMapService: cleanup()
07-07 20:30:27.869  4124  4136 D BluetoothAdapterProperties: Setting state to 15
07-07 20:30:27.869  4124  4124 D BluetoothMapService: MAP Service closeService in
07-07 20:30:27.869  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-07 20:30:27.870  4124  4136 I BluetoothAdapterState: Entering BleOnState
,07-07 20:30:27.870  1368  1382 D BluetoothPan: onBluetoothStateChange on: false
07-07 20:30:27.871  1368  1380 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:30:27.871   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:27.871  3882  3894 D BluetoothPbap: onBluetoothStateChange: up=false
07-07 20:30:27.873   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:27.873  1368  1849 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-07 20:30:27.873   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:30:27.874  3882  3893 D BluetoothMap: onBluetoothStateChange: up=false
07-07 20:30:27.874  1368  1850 D BluetoothMap: onBluetoothStateChange: up=false
,07-07 20:30:27.875  3882  3894 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-07 20:30:27.876  1742  1757 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:27.876  3882  3893 D BluetoothPan: onBluetoothStateChange on: false
,07-07 20:30:27.877   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:27.877  1368  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
07-07 20:30:27.877  1368  1380 D BluetoothPbap: onBluetoothStateChange: up=false
,07-07 20:30:27.878  3882  3894 D BluetoothA2dp: onBluetoothStateChange: up=false
07-07 20:30:27.879  3882  3893 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-07 20:30:27.879  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-07 20:30:27.879  4124  4136 D BluetoothAdapterProperties: Setting state to 16
,07-07 20:30:27.879  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-07 20:30:27.880  4124  4136 D BluetoothAdapterProperties: onBleDisable
07-07 20:30:27.882  4124  4137 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-07 20:30:27.882  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
07-07 20:30:27.883  4124  4146 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-07 20:30:27.883  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-07 20:30:27.884  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
,07-07 20:30:27.885  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-07 20:30:27.886  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:27.888  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:27.891  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:30:27.895  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:30:28.084  4124  4140 I bt_hci  : shut_down
,07-07 20:30:28.085  4124  4144 D bt_hwcfg: hw_epilog_process
,07-07 20:30:28.097  4124  4144 I bt_vendor: low_power_mode_cb
,07-07 20:30:28.120  4124  4144 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-07 20:30:28.120  4124  4144 I bt_vendor: epilog_cb
07-07 20:30:28.121  4124  4144 I bt_hci  : epilog_finished_callback
,07-07 20:30:28.128  4124  4140 I bt_hci_h4: hal_close
,07-07 20:30:28.130  4124  4140 I bt_userial_vendor: device fd = 51 close
,07-07 20:30:28.251  4124  4137 D bt_stack_manager: event_shut_down_stack finished.
,07-07 20:30:28.253  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-07 20:30:28.258  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:30:28.259  4124  4136 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-07 20:30:28.260  4124  4124 D BtGatt.GattService: Received stop request...Stopping profile...
07-07 20:30:28.260  4124  4124 D BtGatt.GattService: stop()
,07-07 20:30:28.260  4124  4124 D BtGatt.AdvertiseManager: advertise clients cleared
,07-07 20:30:28.265  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:30:28.265  4124  4124 V BluetoothAdapterState: isTurningOn()=false
07-07 20:30:28.266  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:28.266  4124  4124 V BluetoothAdapterState: isBleTurningOff()=true
07-07 20:30:28.267  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-07 20:30:28.268  4124  4136 D BluetoothAdapterProperties: Setting state to 10
07-07 20:30:28.268  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-07 20:30:28.270  4124  4136 I BluetoothAdapterState: Entering OffState
07-07 20:30:28.271   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-07 20:30:28.298  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-07 20:30:28.299  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-07 20:30:28.299  4124  4137 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-07 20:30:28.308  4124  4137 D bt_stack_manager: event_clean_up_stack finished.
,07-07 20:30:28.308  4124  4124 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-07 20:30:28.315  4124  4124 I art     : System.exit called, status: 0
,07-07 20:30:28.316  4124  4124 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-07 20:30:28.380   875  1741 I ActivityManager: Process com.android.bluetooth (pid 4124) has died
,07-07 20:30:29.140   875  1314 D ConnectivityService: handlePromptUnvalidated 101
,07-07 20:30:30.793  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:30.793  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:30:30.800  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:30:30.800  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@282eb95 added. We now have 6 listener(s)
07-07 20:30:30.801  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:30.805  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
07-07 20:30:30.805  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc3e4aa added. We now have 7 listener(s)
07-07 20:30:30.805  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:30.807  3831  3871 I System.out: IsBluetoothEnabled
,07-07 20:30:30.816  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,07-07 20:30:30.856   875   892 I ActivityManager: Start proc 4179:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-07 20:30:30.997  4179  4179 D AdapterServiceConfig: Adding HeadsetService
07-07 20:30:30.997  4179  4179 D AdapterServiceConfig: Adding A2dpService
07-07 20:30:30.998  4179  4179 D AdapterServiceConfig: Adding HidService
,07-07 20:30:30.998  4179  4179 D AdapterServiceConfig: Adding HealthService
07-07 20:30:30.998  4179  4179 D AdapterServiceConfig: Adding PanService
07-07 20:30:30.999  4179  4179 D AdapterServiceConfig: Adding GattService
,07-07 20:30:30.999  4179  4179 D AdapterServiceConfig: Adding BluetoothMapService
,07-07 20:30:31.014   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@939a12d:true
,07-07 20:30:31.015  4179  4179 D BluetoothAdapterState: make() - Creating AdapterState
,07-07 20:30:31.020  4179  4179 I bt_bluedroid: init
,07-07 20:30:31.020  4179  4191 I BluetoothAdapterState: Entering OffState
,07-07 20:30:31.025  4179  4192 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-07 20:30:31.026  4179  4192 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-07 20:30:31.026  4179  4192 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-07 20:30:31.026  4179  4192 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-07 20:30:31.028  4179  4179 I bt_bluedroid: get_profile_interface socket
07-07 20:30:31.031  4179  4195 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-07 20:30:31.033  4179  4195 D BluetoothAdapterProperties: Name is: Nexus 6
,07-07 20:30:31.033  4179  4179 I bt_bluedroid: get_profile_interface sdp
,07-07 20:30:31.039  4179  4190 I bt_bluedroid: config_hci_snoop_log
,07-07 20:30:31.043   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-07 20:30:31.050  4179  4191 D BluetoothAdapterState: Current state: OFF, message: 0
,07-07 20:30:31.050  4179  4191 D BluetoothAdapterProperties: Setting state to 14
07-07 20:30:31.051  4179  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-07 20:30:31.055  4179  4191 D BluetoothBondStateMachine: make
,07-07 20:30:31.060  4179  4196 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-07 20:30:31.067  4179  4191 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:30:31.070  4179  4179 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-07 20:30:31.078  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:31.080  4179  4179 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-07 20:30:31.082  4179  4179 D BtGatt.GattService: Received start request. Starting profile...
07-07 20:30:31.082  4179  4179 D BtGatt.GattService: start()
07-07 20:30:31.082  4179  4179 I bt_bluedroid: get_profile_interface gatt
,07-07 20:30:31.084  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:31.085  4179  4179 D BtGatt.AdvertiseManager: advertise manager created
,07-07 20:30:31.100  4179  4179 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:30:31.100  4179  4179 V BluetoothAdapterState: isTurningOn()=false
,07-07 20:30:31.101  4179  4179 V BluetoothAdapterState: isBleTurningOn()=true
07-07 20:30:31.101  4179  4179 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:31.102  4179  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-07 20:30:31.103  4179  4191 I bt_bluedroid: enable
07-07 20:30:31.103  4179  4192 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-07 20:30:31.105  4179  4192 I bt_hci  : start_up
,07-07 20:30:31.134  4179  4192 I bt_vendor: alloc value 0xb3a15189
,07-07 20:30:31.134  4179  4192 I bt_vendor: init
07-07 20:30:31.134  4179  4192 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-07 20:30:31.134  4179  4192 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-07 20:30:31.241  4179  4192 D bt_hci  : start_up starting async portion
,07-07 20:30:31.241  4179  4199 I bt_hci  : event_finish_startup
07-07 20:30:31.242  4179  4199 I bt_hci_h4: hal_open
,07-07 20:30:31.242  4179  4199 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-07 20:30:31.251  4179  4199 I bt_userial_vendor: device fd = 51 open
,07-07 20:30:31.283  4179  4199 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-07 20:30:31.315  4179  4199 D bt_hwcfg: Chipset BCM4354A2
,07-07 20:30:31.315  4179  4199 D bt_hwcfg: Target name = [BCM4354A2]
07-07 20:30:31.316  4179  4199 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-07 20:30:31.976  4179  4199 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-07 20:30:31.978  4179  4199 D bt_hwcfg: Settlement delay -- 100 ms
07-07 20:30:31.978  4179  4199 I bt_hwcfg: Setting fw settlement delay to 100 
,07-07 20:30:32.094  4179  4199 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-07 20:30:32.096  4179  4199 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-07 20:30:32.125  4179  4199 I bt_hwcfg: vendor lib fwcfg completed
,07-07 20:30:32.125  4179  4199 I bt_vendor: firmware callback
07-07 20:30:32.125  4179  4199 I bt_hci  : firmware_config_callback
,07-07 20:30:32.137  4179  4203 I bt_btu  : btu_task pending for preload complete event
,07-07 20:30:32.137  4179  4203 I bt_btu_task: Bluetooth chip preload is complete
07-07 20:30:32.137  4179  4203 I bt_btu  : btu_task received preload complete event
,07-07 20:30:32.150  4179  4203 I         : BTE_InitTraceLevels -- TRC_HCI
,07-07 20:30:32.150  4179  4203 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-07 20:30:32.150  4179  4203 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-07 20:30:32.151  4179  4203 I         : BTE_InitTraceLevels -- TRC_AVDT
07-07 20:30:32.151  4179  4203 I         : BTE_InitTraceLevels -- TRC_AVRC
07-07 20:30:32.151  4179  4203 I         : BTE_InitTraceLevels -- TRC_A2D
,07-07 20:30:32.151  4179  4203 I         : BTE_InitTraceLevels -- TRC_BNEP
07-07 20:30:32.152  4179  4203 I         : BTE_InitTraceLevels -- TRC_BTM
07-07 20:30:32.152  4179  4203 I         : BTE_InitTraceLevels -- TRC_GAP
07-07 20:30:32.153  4179  4203 I         : BTE_InitTraceLevels -- TRC_PAN
,07-07 20:30:32.153  4179  4203 I         : BTE_InitTraceLevels -- TRC_SDP
07-07 20:30:32.153  4179  4203 I         : BTE_InitTraceLevels -- TRC_GATT
07-07 20:30:32.153  4179  4203 I         : BTE_InitTraceLevels -- TRC_SMP
,07-07 20:30:32.154  4179  4203 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-07 20:30:32.154  4179  4203 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-07 20:30:32.289  4179  4203 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3992d9d
,07-07 20:30:32.289  4179  4203 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3992d9d 
,07-07 20:30:32.301  4179  4195 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-07 20:30:32.304  4179  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-07 20:30:32.305  4179  4195 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-07 20:30:32.310  4179  4195 D BluetoothAdapterProperties: Name is: Nexus 6
,07-07 20:30:32.315  4179  4195 D BluetoothAdapterProperties: Scan Mode:20
,07-07 20:30:32.315  4179  4195 D BluetoothAdapterProperties: Discoverable Timeout:120
07-07 20:30:32.317  4179  4195 D bt_hci  : do_postload posting postload work item
07-07 20:30:32.317  4179  4199 I bt_hci  : event_postload
07-07 20:30:32.317  4179  4199 I bt_vendor: sco_config_cb
07-07 20:30:32.317  4179  4199 I bt_hci  : sco_config_callback postload finished.
,07-07 20:30:32.321  4179  4195 D bt_bte_conf: Device ID record 1 : primary
07-07 20:30:32.321  4179  4195 D bt_bte_conf:   vendorId            = 000f
,07-07 20:30:32.321  4179  4195 D bt_bte_conf:   vendorIdSource      = 0001
07-07 20:30:32.321  4179  4195 D bt_bte_conf:   product             = 1200
07-07 20:30:32.322  4179  4195 D bt_bte_conf:   version             = 1436
07-07 20:30:32.322  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:32.322  4179  4195 D bt_bte_conf:   clientExecutableURL = 
07-07 20:30:32.322  4179  4195 D bt_bte_conf:   serviceDescription  = 
07-07 20:30:32.323  4179  4195 D bt_bte_conf:   documentationURL    = 
,07-07 20:30:32.323  4179  4195 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-07 20:30:32.324  4179  4192 D bt_stack_manager: event_start_up_stack finished
07-07 20:30:32.325  4179  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-07 20:30:32.325  4179  4191 D BluetoothAdapterProperties: Setting state to 15
,07-07 20:30:32.325  4179  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-07 20:30:32.326  4179  4199 I bt_vendor: low_power_mode_cb
07-07 20:30:32.327  4179  4191 I BluetoothAdapterState: Entering BleOnState
,07-07 20:30:32.331  4179  4191 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-07 20:30:32.332  4179  4191 D BluetoothAdapterProperties: Setting state to 11
,07-07 20:30:32.332  4179  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-07 20:30:32.336  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:32.337  4179  4179 D HeadsetService: Received start request. Starting profile...
07-07 20:30:32.345  4179  4179 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-07 20:30:32.345  4179  4179 D HeadsetStateMachine: make
07-07 20:30:32.349  4179  4191 I BluetoothAdapterState: Entering PendingCommandState
,07-07 20:30:32.358  4179  4179 D HeadsetStateMachine: max_hf_connections = 1
,07-07 20:30:32.358  4179  4179 I bt_bluedroid: get_profile_interface handsfree
,07-07 20:30:32.358  4179  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-07 20:30:32.359  4179  4195 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-07 20:30:32.364  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:32.366  4179  4179 D A2dpService: Received start request. Starting profile...
,07-07 20:30:32.367  4179  4179 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-07 20:30:32.368  4179  4179 I bt_bluedroid: get_profile_interface avrcp
,07-07 20:30:32.375  4179  4179 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-07 20:30:32.375  4179  4179 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-07 20:30:32.376  4179  4179 D A2dpStateMachine: make
,07-07 20:30:32.378  4179  4179 I bt_bluedroid: get_profile_interface a2dp
,07-07 20:30:32.379  4179  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-07 20:30:32.381  4179  4212 D A2dpStateMachine: Enter Disconnected: -2
,07-07 20:30:32.382  4179  4179 I BluetoothHidServiceJni: classInitNative: succeeds
,07-07 20:30:32.384  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:32.385  4179  4179 D HidService: Received start request. Starting profile...
,07-07 20:30:32.385  4179  4179 I bt_bluedroid: get_profile_interface hidhost
,07-07 20:30:32.385  4179  4179 D HidService: setHidService(): set to: null
,07-07 20:30:32.386  4179  4195 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39743e5
07-07 20:30:32.386  4179  4195 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-07 20:30:32.387  4179  4179 I BluetoothHealthServiceJni: classInitNative: succeeds
07-07 20:30:32.388  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
07-07 20:30:32.389  4179  4179 D HealthService: Received start request. Starting profile...
,07-07 20:30:32.391  4179  4179 I bt_bluedroid: get_profile_interface health
,07-07 20:30:32.392  4179  4179 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-07 20:30:32.393  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
07-07 20:30:32.393  4179  4179 D PanService: Received start request. Starting profile...
07-07 20:30:32.393  4179  4179 D BluetoothPanServiceJni: initializeNative(L110): pan
07-07 20:30:32.393  4179  4179 I bt_bluedroid: get_profile_interface pan
07-07 20:30:32.394  4179  4195 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-07 20:30:32.397  4179  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
07-07 20:30:32.398  4179  4179 D BluetoothMapService: Received start request. Starting profile...
07-07 20:30:32.398  4179  4179 D BluetoothMapService: start()
,07-07 20:30:32.402  4179  4179 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-07 20:30:32.403  4179  4179 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-07 20:30:32.403  4179  4179 D BluetoothMapAppObserver: createReceiver()
,07-07 20:30:32.405  4179  4179 D BluetoothMapAppObserver: initObservers()
07-07 20:30:32.405  4179  4179 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-07 20:30:32.416  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:30:32.417  4179  4179 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:32.417  4179  4179 V BluetoothAdapterState: isTurningOn()=true
07-07 20:30:32.417  4179  4179 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:32.417  4179  4179 V BluetoothAdapterState: isBleTurningOff()=false
,07-07 20:30:32.420  4179  4179 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:30:32.420  4179  4179 V BluetoothAdapterState: isTurningOn()=true
07-07 20:30:32.420  4179  4179 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:32.420  4179  4210 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-07 20:30:32.420  4179  4179 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:32.420  4179  4179 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:32.420  4179  4179 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isTurningOn()=true
07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isTurningOff()=false
07-07 20:30:32.421  4179  4179 V BluetoothAdapterState: isTurningOn()=true
07-07 20:30:32.422  4179  4179 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:32.422  4179  4179 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:32.422  4179  4179 V BluetoothAdapterState: isTurningOff()=false
,07-07 20:30:32.422  4179  4179 V BluetoothAdapterState: isTurningOn()=true
,07-07 20:30:32.422  4179  4179 V BluetoothAdapterState: isBleTurningOn()=false
07-07 20:30:32.422  4179  4179 V BluetoothAdapterState: isBleTurningOff()=false
07-07 20:30:32.423  4179  4191 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-07 20:30:32.423  4179  4191 D BluetoothAdapterProperties: ScanMode =  20
07-07 20:30:32.423  4179  4191 D BluetoothAdapterProperties: State =  11
,07-07 20:30:32.424  4179  4191 D BluetoothAdapterProperties: Setting state to 12
07-07 20:30:32.424  4179  4191 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-07 20:30:32.425  1368  1849 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:30:32.426  4179  4191 I BluetoothAdapterState: Entering OnState
07-07 20:30:32.426  4179  4195 D BluetoothAdapterProperties: Scan Mode:21
07-07 20:30:32.427  4179  4195 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-07 20:30:32.432  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected
,07-07 20:30:32.432  1368  1368 D PanProfile: Bluetooth service connected
07-07 20:30:32.432  1368  1382 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:30:32.434   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:32.435  3882  3893 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:30:32.436  4179  4179 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-07 20:30:32.437  4179  4179 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:32.437  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:32.438   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:30:32.438  1368  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-07 20:30:32.440  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:32.441   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
07-07 20:30:32.441  4179  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:30:32.442  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:30:32.442  3831  3877 I jxcore-log: 
07-07 20:30:32.443  3882  3894 D BluetoothMap: onBluetoothStateChange: up=true
,07-07 20:30:32.444  4179  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:30:32.445  1368  1850 D BluetoothMap: onBluetoothStateChange: up=true
07-07 20:30:32.446  4179  4179 D ObexServerSockets: Succeed to create listening sockets 
07-07 20:30:32.446  4179  4179 D ObexServerSockets0: startAccept()
,07-07 20:30:32.446  4179  4179 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:30:32.447  3882  3893 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-07 20:30:32.448  4179  4179 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-07 20:30:32.448  4179  4179 D BluetoothSdpJni: SDP Create record success - handle: 0
07-07 20:30:32.448  1742  1756 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:32.449   875   875 D BluetoothA2dp: Proxy object connected
07-07 20:30:32.449  3882  3894 D BluetoothPan: onBluetoothStateChange on: true
07-07 20:30:32.449  1368  1368 D BluetoothA2dp: Proxy object connected
07-07 20:30:32.451  4179  4218 D ObexServerSockets0: Accepting socket connection...
07-07 20:30:32.452  1368  1368 D BluetoothInputDevice: Proxy object connected
07-07 20:30:32.452  1368  1368 D HidProfile: Bluetooth service connected
07-07 20:30:32.452   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:32.452  3882  3882 D BluetoothInputDevice: Proxy object connected
07-07 20:30:32.452  1368  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
07-07 20:30:32.453  1368  1849 D BluetoothPbap: onBluetoothStateChange: up=true
07-07 20:30:32.453  4179  4219 D ObexServerSockets0: Accepting socket connection...
,07-07 20:30:32.454  1368  1368 D BluetoothMap: Proxy object connected
07-07 20:30:32.457  1368  1368 D MapProfile: Bluetooth service connected
07-07 20:30:32.458  1368  1368 D BluetoothMap: getConnectedDevices()
07-07 20:30:32.458  3882  3894 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-07 20:30:32.460  3882  3893 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-07 20:30:32.461   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,07-07 20:30:32.462  4179  4179 D BluetoothMapService: onReceive
07-07 20:30:32.462  4179  4179 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-07 20:30:32.462  4179  4179 D BluetoothMapService: STATE_ON
,07-07 20:30:32.452  3882  3882 D HidProfile: Bluetooth service connected
,07-07 20:30:32.466  3882  3882 D BluetoothMap: Proxy object connected
,07-07 20:30:32.466  3882  3882 D MapProfile: Bluetooth service connected
07-07 20:30:32.466  3882  3882 D BluetoothMap: getConnectedDevices()
,07-07 20:30:32.468  3882  3882 D BluetoothPan: BluetoothPAN Proxy object connected
,07-07 20:30:32.469  3882  3882 D PanProfile: Bluetooth service connected
07-07 20:30:32.469  3882  3882 D BluetoothA2dp: Proxy object connected
,07-07 20:30:32.475  3882  3882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-07 20:30:32.482  3882  3882 D DockEventReceiver: finishStartingService: stopping service
,07-07 20:30:32.483  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-07 20:30:32.492  3882  3882 D BluetoothPbap: Proxy object connected
07-07 20:30:32.492  3882  3882 D PbapServerProfile: Bluetooth service connected
,07-07 20:30:32.492  1368  1368 D BluetoothPbap: Proxy object connected
07-07 20:30:32.492  1368  1368 D PbapServerProfile: Bluetooth service connected
07-07 20:30:32.492  4179  4179 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-07 20:30:32.492  4179  4179 D ObexServerSockets0: prepareForNewConnect()
,07-07 20:30:32.501  4179  4225 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:30:32.518  4179  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-07 20:30:32.519  4179  4229 I BtOppRfcommListener: Accept thread started.
,07-07 20:30:32.537  1368  1849 D BluetoothHeadset: Proxy object connected
,07-07 20:30:32.537  1368  1368 D HeadsetProfile: Bluetooth service connected
,07-07 20:30:32.537   875   875 D BluetoothHeadset: Proxy object connected
07-07 20:30:32.537   875   875 D BluetoothHeadset: Proxy object connected
07-07 20:30:32.537  3882  3894 D BluetoothHeadset: Proxy object connected
07-07 20:30:32.537  3882  3882 D HeadsetProfile: Bluetooth service connected
07-07 20:30:32.538  1742  1913 D BluetoothHeadset: Proxy object connected
07-07 20:30:32.538   875   892 D BluetoothHeadset: Proxy object connected
07-07 20:30:32.538   875   875 D BluetoothHeadset: Proxy object connected
,07-07 20:30:32.549  1742  2029 D BluetoothHeadset: Proxy object connected
,07-07 20:30:32.552   875   892 D BluetoothHeadset: Proxy object connected
,07-07 20:30:32.553  1368  1380 D BluetoothHeadset: Proxy object connected
,07-07 20:30:32.553  1368  1368 D HeadsetProfile: Bluetooth service connected
,07-07 20:30:32.561  3882  3893 D BluetoothHeadset: Proxy object connected
,07-07 20:30:32.561  3882  3882 D HeadsetProfile: Bluetooth service connected
,07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:32.840  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:32.848  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:32.852  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-07 20:30:32.852  3831  3877 I jxcore-log: 
,07-07 20:30:32.853  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:30:32.853  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b90589b added. We now have 8 listener(s)
,07-07 20:30:32.853  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:32.860   875  1692 D WifiService: setWifiEnabled: false pid=3831, uid=10000
,07-07 20:30:32.861   875  1692 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:30:32.873  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:32.874   875  3211 D WifiService: setWifiEnabled: true pid=3831, uid=10000
07-07 20:30:32.874   875  3211 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-07 20:30:32.883   875  1312 D WifiConfigStore: Loading config and enabling all networks 
,07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:32.895  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:32.901  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:32.904  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:32.904  3831  3877 I jxcore-log: 
,07-07 20:30:32.905   875  1312 D WifiConfigStore: loaded 0 passpoint configs
07-07 20:30:32.906   875  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:30:32.906   875  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-07 20:30:32.907   875  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-07 20:30:32.908   875  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-07 20:30:32.908   875  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-07 20:30:32.908   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-07 20:30:32.909   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-07 20:30:32.923   875  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-07 20:30:32.923   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-07 20:30:32.925   374   873 D CommandListener: Setting iface cfg
,07-07 20:30:32.975   875  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,07-07 20:30:32.976   875  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-07 20:30:32.984   875  1312 E native  : do suspend true
,07-07 20:30:32.988   875  1311 D WifiNative-HAL: p2pGetDeviceAddress
,07-07 20:30:33.001   875  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-07 20:30:33.016   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:33.894  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:33.902  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:33.906  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:33.906  3831  3877 I jxcore-log: 
,07-07 20:30:33.909  3831  3871 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-07 20:30:33.911  3831  3871 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-07 20:30:33.924  3831  3871 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4fb0696 Bundle[{}]
,07-07 20:30:33.926  3831  3871 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 20:30:33.927  3831  3871 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-07 20:30:33.929  3831  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-07 20:30:33.931  3831  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-07 20:30:33.933  3831  3871 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-07 20:30:33.937  3831  3871 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-07 20:30:33.943  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-07 20:30:33.943  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-07 20:30:33.944  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-07 20:30:33.944  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-07 20:30:33.944  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,07-07 20:30:33.944  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:33.950  3831  3871 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 376)
,07-07 20:30:33.950  3831  3871 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 376)
07-07 20:30:33.950  3831  3871 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 376)
07-07 20:30:33.951  3831  3871 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 376)
,07-07 20:30:33.954  3831  3871 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 382)
07-07 20:30:33.954  3831  3871 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 382)
,07-07 20:30:33.954  3831  3871 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 382)
07-07 20:30:33.955  3831  3871 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 383)
07-07 20:30:33.956  3831  3871 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 385)
,07-07 20:30:33.958  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-07 20:30:33.958  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a572438 added. We now have 2 listener(s)
07-07 20:30:33.960  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-07 20:30:33.960  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:30:33.960  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:33.960  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:33.960  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73ac11 added. We now have 9 listener(s)
,07-07 20:30:33.960  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:33.965  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 20:30:33.968  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:33.975  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:33.979  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:33.979  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:30:33.979  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:33.979  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@491e377 added. We now have 3 listener(s)
,07-07 20:30:33.982  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:33.982  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:30:33.982  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:33.982  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:33.982  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a764be4 added. We now have 10 listener(s)
,07-07 20:30:33.982  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:33.982  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:33.983  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:33.983  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:33.983  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:33.984  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:33.984  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:33.984  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-07 20:30:33.984  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:33.985  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a572438 removed from the list
07-07 20:30:33.985  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:33.985  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73ac11 removed from the list
07-07 20:30:33.986  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:33.986  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:33.986  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-07 20:30:33.987  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:33.989  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:33.989  3831  3877 I jxcore-log: 
07-07 20:30:33.987  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:30:33.989  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:33.989  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73ac11 not in the list
07-07 20:30:33.989  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:33.989  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:30:33.989  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:33.990  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a764be4 removed from the list
,07-07 20:30:33.990  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:33.990  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:33.990  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:30:33.990  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-07 20:30:33.990  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@491e377 removed from the list
07-07 20:30:33.991  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:33.991  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5f84d added. We now have 2 listener(s)
07-07 20:30:33.994  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:33.994  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:30:33.994  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:33.995  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:33.995  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6505f02 added. We now have 9 listener(s)
07-07 20:30:33.995  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:33.999  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 20:30:34.003  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.007  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:34.010  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:34.011  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:30:34.011  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-07 20:30:34.012  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73e4250 added. We now have 3 listener(s)
07-07 20:30:34.012  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:34.014  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:34.015  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.015  3831  3877 I jxcore-log: 
,07-07 20:30:34.017  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:34.018  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:30:34.018  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:34.019  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:34.019  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@796cc49 added. We now have 10 listener(s)
07-07 20:30:34.019  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:30:34.020  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.020  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:30:34.021  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.021  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:30:34.029  3831  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-07 20:30:34.029  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:30:34.035  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-07 20:30:34.037  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-07 20:30:34.037  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-07 20:30:34.037  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:30:34.038  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:30:34.038  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-07 20:30:34.039  3831  3871 D BluetoothAdapter: STATE_ON
,07-07 20:30:34.045  4179  4190 D BtGatt.GattService: registerClient() - UUID=54d0c14d-ee73-4229-9b6a-1317f673289e
,07-07 20:30:34.046  4179  4195 D BtGatt.GattService: onClientRegistered() - UUID=54d0c14d-ee73-4229-9b6a-1317f673289e, clientIf=5
,07-07 20:30:34.047  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-07 20:30:34.049  4179  4189 D BtGatt.GattService: start scan with filters
,07-07 20:30:34.055  4179  4198 D BtGatt.ScanManager: handling starting scan
,07-07 20:30:34.055  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:30:34.056  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-07 20:30:34.056  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:30:34.057  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-07 20:30:34.057  4179  4198 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@79937ca
,07-07 20:30:34.057  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:30:34.058  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-07 20:30:34.058  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:30:34.059  4179  4195 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
07-07 20:30:34.059  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.060  4179  4198 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:30:34.061  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:30:34.061  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.062  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.062  3831  3877 I jxcore-log: 
,07-07 20:30:34.062  4179  4198 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:30:34.062  4179  4198 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:30:34.063  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.063  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:30:34.063  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.064  3831  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-07 20:30:34.064  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.064  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.064  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.064  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:30:34.064  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:30:34.064  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:30:34.065  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:30:34.065  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:30:34.066  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.066  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.066  3831  3877 I jxcore-log: 
,07-07 20:30:34.067  4179  4209 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:30:34.068  4179  4221 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:30:34.068  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.068  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:30:34.068  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:30:34.068  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:30:34.068  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:30:34.068  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.069  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.069  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:30:34.069  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:30:34.070  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:30:34.070  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.070  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.070  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.070  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.072  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:30:34.072  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.072  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.072  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.073  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.073  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.073  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:34.073  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5f84d removed from the list
07-07 20:30:34.073  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.073  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6505f02 removed from the list
07-07 20:30:34.073  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.073  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:30:34.075  4179  4195 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:30:34.075  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.075  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.075  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:30:34.075  3831  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:30:34.075  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.075  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.075  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-07 20:30:34.075  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.075  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6505f02 not in the list
07-07 20:30:34.077  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:30:34.077  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.080  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:30:34.080  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.080  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-07 20:30:34.080  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.080  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-07 20:30:34.081  4179  4198 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:30:34.081  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.083  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:30:34.083  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.083  4179  4198 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:30:34.083  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.084  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-07 20:30:34.084  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.084  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.084  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:30:34.085  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.085  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.085  3831  3877 I jxcore-log: 
07-07 20:30:34.085  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.085  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.085  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.085  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.085  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@796cc49 removed from the list
07-07 20:30:34.086  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.086  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.086  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:30:34.086  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:34.086  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73e4250 removed from the list
07-07 20:30:34.086  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.086  3831  3877 I jxcore-log: 
,07-07 20:30:34.086  4179  4195 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:30:34.086  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.087  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:34.087  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f80b68 added. We now have 2 listener(s)
07-07 20:30:34.088  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:34.089  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:30:34.089  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:34.089  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:34.089  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@586bb81 added. We now have 9 listener(s)
07-07 20:30:34.089  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:34.091  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:30:34.093  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.096  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:34.098  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:34.098  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:30:34.098  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:34.098  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8c9867 added. We now have 3 listener(s)
07-07 20:30:34.099  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.100  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:34.100  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:30:34.100  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:34.100  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:30:34.100  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef67614 added. We now have 10 listener(s)
07-07 20:30:34.100  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.100  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:34.101  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.101  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.102  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:30:34.102  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.102  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:30:34.102  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.102  3831  3877 I jxcore-log: 
07-07 20:30:34.106  3831  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.106  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:30:34.110  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-07 20:30:34.111  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.111  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:30:34.111  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:30:34.111  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-07 20:30:34.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-07 20:30:34.112  3831  3871 D BluetoothAdapter: STATE_ON
,07-07 20:30:34.114  4179  4217 D BtGatt.GattService: registerClient() - UUID=34950ad3-8612-443c-a923-5c6223ec4441
,07-07 20:30:34.115  4179  4195 D BtGatt.GattService: onClientRegistered() - UUID=34950ad3-8612-443c-a923-5c6223ec4441, clientIf=5
07-07 20:30:34.115  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:30:34.115  4179  4190 D BtGatt.GattService: start scan with filters
,07-07 20:30:34.117  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-07 20:30:34.118  4179  4198 D BtGatt.ScanManager: handling starting scan
,07-07 20:30:34.118  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:30:34.118  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:30:34.118  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:30:34.118  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.118  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-07 20:30:34.118  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.119  4179  4195 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:30:34.119  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.119  4179  4198 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:30:34.120  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
07-07 20:30:34.120  3831  3877 I jxcore-log: 
07-07 20:30:34.120  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.120  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:30:34.120  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:30:34.120  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.120  3831  3871 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-07 20:30:34.121  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.121  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:34.121  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:30:34.121  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.121  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.121  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.121  4179  4198 D BtGatt.ScanManager: Starting BLE batch scan
,07-07 20:30:34.121  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.121  4179  4198 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:30:34.121  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.121  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-07 20:30:34.121  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f80b68 removed from the list
07-07 20:30:34.121  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.121  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@586bb81 removed from the list
,07-07 20:30:34.121  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.121  3831  3877 I jxcore-log: 
07-07 20:30:34.121  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.121  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-07 20:30:34.122  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.123  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:30:34.123  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.123  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-07 20:30:34.123  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.123  4179  4195 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:30:34.123  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@586bb81 not in the list
07-07 20:30:34.123  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.123  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:30:34.123  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-07 20:30:34.123  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:30:34.123  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:30:34.123  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-07 20:30:34.124  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:30:34.124  3831  3871 D BluetoothAdapter: STATE_ON
,07-07 20:30:34.124  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.125  4179  4221 D BtGatt.GattService: stopScan() - queue size =1
,07-07 20:30:34.125  4179  4189 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:30:34.126  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.126  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:30:34.126  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:30:34.126  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-07 20:30:34.126  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:30:34.126  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.126  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.127  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:30:34.127  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-07 20:30:34.127  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:30:34.127  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.127  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-07 20:30:34.127  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.128  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef67614 removed from the list
07-07 20:30:34.128  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.128  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.128  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.128  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:30:34.128  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:34.128  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.127  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.128  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.128  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8c9867 removed from the list
07-07 20:30:34.128  4179  4198 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:30:34.129  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:34.129  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2e59b9 added. We now have 2 listener(s)
07-07 20:30:34.131  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-07 20:30:34.131  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.131  4179  4198 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:30:34.132  4179  4195 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:30:34.132  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.133  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.133  3831  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:30:34.133  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:34.133  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:30:34.134  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:30:34.134  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:34.134  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@728c1fe added. We now have 9 listener(s)
07-07 20:30:34.134  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:34.136  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:30:34.137  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:30:34.138  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.138  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:30:34.138  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.139  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:34.141  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.141  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.141  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.143  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:34.144  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.144  3831  3877 I jxcore-log: 
07-07 20:30:34.145  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.145  3831  3877 I jxcore-log: 
07-07 20:30:34.145  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:34.145  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:30:34.146  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:34.146  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70273ac added. We now have 3 listener(s)
07-07 20:30:34.148  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.148  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:34.148  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:30:34.148  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:34.148  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-07 20:30:34.148  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e51d875 added. We now have 10 listener(s)
07-07 20:30:34.149  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:34.149  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.149  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:30:34.149  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.149  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:30:34.151  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.152  3831  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.152  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:30:34.153  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.153  3831  3877 I jxcore-log: 
,07-07 20:30:34.155  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-07 20:30:34.156  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.156  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-07 20:30:34.156  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:30:34.156  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:30:34.156  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-07 20:30:34.157  3831  3871 D BluetoothAdapter: STATE_ON
,07-07 20:30:34.159  4179  4190 D BtGatt.GattService: registerClient() - UUID=24cf1114-a36d-411c-a33d-001156299634
,07-07 20:30:34.159  4179  4195 D BtGatt.GattService: onClientRegistered() - UUID=24cf1114-a36d-411c-a33d-001156299634, clientIf=5
07-07 20:30:34.160  3831  3841 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-07 20:30:34.160  4179  4189 D BtGatt.GattService: start scan with filters
,07-07 20:30:34.162  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:30:34.163  4179  4198 D BtGatt.ScanManager: handling starting scan
07-07 20:30:34.163  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:30:34.163  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:30:34.163  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-07 20:30:34.163  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:30:34.163  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.164  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-07 20:30:34.165  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.165  3831  3877 I jxcore-log: 
07-07 20:30:34.167  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:30:34.167  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-07 20:30:34.167  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:30:34.168  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.168  3831  3877 I jxcore-log: 
,07-07 20:30:34.170  4179  4195 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-07 20:30:34.170  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.170  4179  4198 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:30:34.171  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.171  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:34.171  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.171  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.171  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.171  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.171  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-07 20:30:34.171  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2e59b9 removed from the list
07-07 20:30:34.171  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.172  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@728c1fe removed from the list
07-07 20:30:34.172  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.172  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.172  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.172  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.172  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.172  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.172  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.173  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@728c1fe not in the list
07-07 20:30:34.173  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:30:34.173  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:30:34.173  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:30:34.173  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:30:34.173  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:30:34.174  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.174  4179  4209 D BtGatt.GattService: stopScan() - queue size =1
,07-07 20:30:34.175  4179  4217 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:30:34.175  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.175  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:30:34.176  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:30:34.176  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-07 20:30:34.176  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:30:34.176  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.176  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.176  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:30:34.176  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-07 20:30:34.176  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-07 20:30:34.177  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.177  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.177  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.177  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:30:34.178  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:30:34.178  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.178  4179  4198 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:30:34.178  4179  4198 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-07 20:30:34.182  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-07 20:30:34.182  3831  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:30:34.186  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-07 20:30:34.187  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.187  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-07 20:30:34.187  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-07 20:30:34.190  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-07 20:30:34.190  4179  4195 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-07 20:30:34.190  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.190  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.190  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.191  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.191  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.191  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:30:34.191  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.191  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.191  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e51d875 removed from the list
07-07 20:30:34.191  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.191  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.191  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.191  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:34.191  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70273ac removed from the list
07-07 20:30:34.192  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.192  3831  3877 I jxcore-log: 
,07-07 20:30:34.192  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:34.192  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a112d6 added. We now have 2 listener(s)
07-07 20:30:34.193  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.193  3831  3877 I jxcore-log: 
07-07 20:30:34.194  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-07 20:30:34.194  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:30:34.194  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:34.194  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:34.195  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d66957 added. We now have 9 listener(s)
07-07 20:30:34.195  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:34.196  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:30:34.196  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.197  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 20:30:34.201  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:34.204  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-07 20:30:34.204  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.204  4179  4198 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.205  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:34.207  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:34.207  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:30:34.208  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-07 20:30:34.209  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:34.209  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@939a12d added. We now have 3 listener(s)
,07-07 20:30:34.210  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.211  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:34.211  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:30:34.211  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:30:34.211  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:34.211  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2738662 added. We now have 10 listener(s)
07-07 20:30:34.211  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:34.212  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.212  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.212  3831  3877 I jxcore-log: 
07-07 20:30:34.212  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.212  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:30:34.212  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:30:34.212  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.212  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.212  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.212  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.212  4179  4198 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:30:34.212  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:34.212  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a112d6 removed from the list
,07-07 20:30:34.212  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.213  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d66957 removed from the list
07-07 20:30:34.213  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.213  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.214  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.214  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.214  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.214  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.214  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.214  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d66957 not in the list
07-07 20:30:34.214  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.214  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.214  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.214  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.215  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.215  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2738662 removed from the list
07-07 20:30:34.215  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:30:34.215  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.215  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.215  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:34.215  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@939a12d removed from the list
,07-07 20:30:34.215  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-07 20:30:34.216  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 added. We now have 2 listener(s)
07-07 20:30:34.217  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-07 20:30:34.217  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:30:34.218  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-07 20:30:34.218  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-07 20:30:34.218  4179  4195 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:30:34.218  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 added. We now have 9 listener(s)
07-07 20:30:34.218  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.218  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-07 20:30:34.220  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 20:30:34.222  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.225  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-07 20:30:34.226  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-07 20:30:34.227  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:30:34.227  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-07 20:30:34.228  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-07 20:30:34.228  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:30:34.228  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.228  3831  3871 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-07 20:30:34.228  3831  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-07 20:30:34.228  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:30:34.229  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:30:34.229  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:30:34.229  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:30:34.229  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.229  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.229  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.229  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.229  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.229  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:30:34.229  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 removed from the list
,07-07 20:30:34.229  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.229  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.230  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 removed from the list
,07-07 20:30:34.230  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.230  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.230  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.230  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.230  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.230  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.230  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.230  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.231  3831  3871 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-07 20:30:34.232  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.232  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.232  3831  3877 I jxcore-log: 
07-07 20:30:34.232  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:34.232  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.232  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.232  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.232  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.232  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.232  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.232  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.233  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.233  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.233  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.233  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.233  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.233  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.233  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.233  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.233  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.236  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.236  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:30:34.236  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:30:34.236  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:30:34.236  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:30:34.237  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:30:34.238  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:30:34.239  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:30:34.239  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-07 20:30:34.239  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:30:34.239  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:30:34.239  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.239  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.239  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.239  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.240  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.240  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.240  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.240  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.240  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.240  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.240  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.240  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.240  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.240  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.241  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.241  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.241  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.242  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.242  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.242  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.242  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.242  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.242  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.242  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.243  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.243  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.243  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.243  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.243  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.243  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.243  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.243  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.243  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.243  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.243  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.244  3831  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:30:34.245  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.248  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:34.250  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:34.250  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:30:34.251  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.251  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:30:34.251  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.251  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.251  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.254  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.254  3831  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.254  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:30:34.255  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.255  3831  3877 I jxcore-log: 
07-07 20:30:34.257  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:30:34.258  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.258  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:30:34.258  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:30:34.258  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:30:34.258  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-07 20:30:34.259  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.261  4179  4189 D BtGatt.GattService: registerClient() - UUID=f9d289c3-7d30-42a0-a401-c6d9eb886f22
07-07 20:30:34.261  4179  4195 D BtGatt.GattService: onClientRegistered() - UUID=f9d289c3-7d30-42a0-a401-c6d9eb886f22, clientIf=5
07-07 20:30:34.261  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:30:34.262  4179  4209 D BtGatt.GattService: start scan with filters
07-07 20:30:34.264  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:30:34.264  4179  4198 D BtGatt.ScanManager: handling starting scan
07-07 20:30:34.264  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:30:34.264  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:30:34.264  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:30:34.265  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.265  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.270  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-07 20:30:34.271  4179  4195 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:30:34.271  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.271  4179  4198 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-07 20:30:34.272  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.272  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:30:34.272  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.272  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-07 20:30:34.272  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
07-07 20:30:34.274  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.274  3831  3877 I jxcore-log: 
07-07 20:30:34.275  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.275  3831  3877 I jxcore-log: 
07-07 20:30:34.275  3831  3871 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:30:34.278  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.278  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.278  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.278  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:30:34.278  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:30:34.279  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:30:34.279  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:30:34.279  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:30:34.279  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.279  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:30:34.279  4179  4198 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:30:34.279  4179  4198 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:30:34.279  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:30:34.280  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.281  4179  4209 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:30:34.282  4179  4221 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:30:34.282  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.282  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:30:34.282  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:30:34.282  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:30:34.283  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:30:34.283  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.283  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.283  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:30:34.283  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.283  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.283  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.283  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.283  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.284  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.285  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.285  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.285  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:30:34.286  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.286  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.286  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.286  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.286  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.287  3831  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:30:34.287  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.287  3831  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:30:34.289  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.291  4179  4195 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:30:34.291  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.294  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.294  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:34.295  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.295  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:30:34.295  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.297  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:30:34.297  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.298  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.298  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.298  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.300  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:34.300  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:30:34.300  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.300  3831  3877 I jxcore-log: 
07-07 20:30:34.301  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.302  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.302  3831  3877 I jxcore-log: 
07-07 20:30:34.302  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.302  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:30:34.303  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.303  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-07 20:30:34.303  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.304  4179  4198 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:30:34.304  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.304  3831  3877 I jxcore-log: 
07-07 20:30:34.306  3831  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.306  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-07 20:30:34.306  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-07 20:30:34.306  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-07 20:30:34.307  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.308  4179  4209 D BtGatt.GattService: registerClient() - UUID=32481204-6529-4e70-a172-e18161306a93
07-07 20:30:34.309  4179  4195 D BtGatt.GattService: onClientRegistered() - UUID=32481204-6529-4e70-a172-e18161306a93, clientIf=5
07-07 20:30:34.309  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:30:34.309  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-07 20:30:34.309  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.309  4179  4198 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:30:34.309  4179  4189 D BtGatt.GattService: start scan with filters
07-07 20:30:34.312  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-07 20:30:34.312  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:30:34.312  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:30:34.312  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:30:34.312  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.312  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.312  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-07 20:30:34.314  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.314  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:30:34.314  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-07 20:30:34.314  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-07 20:30:34.314  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.315  3831  3871 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:30:34.315  4179  4195 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:30:34.315  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.316  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.316  3831  3877 I jxcore-log: 
,07-07 20:30:34.316  4179  4198 D BtGatt.ScanManager: handling starting scan
07-07 20:30:34.317  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.317  3831  3877 I jxcore-log: 
07-07 20:30:34.317  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.317  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.317  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.317  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:30:34.317  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-07 20:30:34.317  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:30:34.317  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:30:34.318  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:30:34.318  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:30:34.318  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.319  4179  4189 D BtGatt.GattService: stopScan() - queue size =1
07-07 20:30:34.319  4179  4217 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:30:34.320  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:30:34.320  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.320  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.320  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.321  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.321  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-07 20:30:34.322  4179  4195 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:30:34.323  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.323  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.323  3831  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:30:34.324  4179  4198 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-07 20:30:34.325  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:30:34.325  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.325  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:30:34.325  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.325  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.325  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.325  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:30:34.325  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-07 20:30:34.326  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:30:34.327  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.327  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:30:34.327  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.327  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.327  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.328  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.328  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.328  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.328  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.328  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.328  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.328  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.328  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.329  3831  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-07 20:30:34.329  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:30:34.329  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.330  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.330  4179  4198 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:30:34.330  4179  4198 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:30:34.331  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.331  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.331  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:30:34.333  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:30:34.333  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.333  3831  3877 I jxcore-log: 
,07-07 20:30:34.334  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.334  3831  3877 I jxcore-log: 
07-07 20:30:34.335  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-07 20:30:34.335  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:30:34.336  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-07 20:30:34.336  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-07 20:30:34.336  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:30:34.338  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-07 20:30:34.339  3831  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.339  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-07 20:30:34.339  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-07 20:30:34.339  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-07 20:30:34.339  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.340  4179  4195 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:30:34.340  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.341  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-07 20:30:34.341  3831  3877 I jxcore-log: 
07-07 20:30:34.341  4179  4209 D BtGatt.GattService: registerClient() - UUID=31ef158f-3186-46fe-aafb-7fa2577d8b44
07-07 20:30:34.342  4179  4195 D BtGatt.GattService: onClientRegistered() - UUID=31ef158f-3186-46fe-aafb-7fa2577d8b44, clientIf=5
07-07 20:30:34.342  3831  3841 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-07 20:30:34.342  4179  4221 D BtGatt.GattService: start scan with filters
,07-07 20:30:34.345  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-07 20:30:34.345  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-07 20:30:34.345  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-07 20:30:34.345  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-07 20:30:34.345  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.345  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-07 20:30:34.345  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-07 20:30:34.345  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-07 20:30:34.345  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-07 20:30:34.347  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.347  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-07 20:30:34.347  3831  3871 I io.jxcore.node.ConnectionHelper: start: OK
07-07 20:30:34.347  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.347  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-07 20:30:34.347  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-07 20:30:34.347  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:34.347  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-07 20:30:34.347  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.347  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,07-07 20:30:34.348  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:30:34.348  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:30:34.348  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:30:34.348  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:30:34.348  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-07 20:30:34.348  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.348  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.348  3831  3877 I jxcore-log: 
07-07 20:30:34.349  4179  4190 D BtGatt.GattService: stopScan() - queue size =0
,07-07 20:30:34.349  4179  4189 D BtGatt.GattService: unregisterClient() - clientIf=5
07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-07 20:30:34.350  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-07 20:30:34.350  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.350  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.351  3831  3831 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.351  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:30:34.351  3831  3831 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-07 20:30:34.351  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.351  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.351  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-07 20:30:34.351  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:30:34.351  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.351  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.351  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.351  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-07 20:30:34.351  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.351  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.351  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.351  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.351  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.353  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-07 20:30:34.353  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.353  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-07 20:30:34.353  3831  3877 I jxcore-log: 
07-07 20:30:34.353  4179  4198 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:30:34.354  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.354  3831  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-07 20:30:34.357  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:30:34.358  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-07 20:30:34.358  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:30:34.358  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.359  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:30:34.359  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.359  4179  4198 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-07 20:30:34.360  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.360  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.360  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-07 20:30:34.360  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.360  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.360  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.361  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.361  3831  3871 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:30:34.361  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.361  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.361  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
,07-07 20:30:34.361  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.361  3831  3877 I jxcore-log: 
07-07 20:30:34.362  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.362  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:34.362  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:30:34.362  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.362  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.362  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.362  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
07-07 20:30:34.362  3831  3877 I jxcore-log: 
,07-07 20:30:34.362  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.362  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.362  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
,07-07 20:30:34.362  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.362  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.362  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.363  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.363  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:30:34.363  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.363  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.363  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.363  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.363  3831  3871 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:30:34.363  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.363  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.364  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.364  3831  3871 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-07 20:30:34.364  4179  4195 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-07 20:30:34.364  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.365  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.365  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.365  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-07 20:30:34.365  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.365  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.365  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.365  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.365  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.365  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.365  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:30:34.365  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.366  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.366  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.366  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.366  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.366  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.366  4179  4198 D BtGatt.ScanManager: handling starting scan
07-07 20:30:34.366  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.366  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.366  3831  3871 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:30:34.366  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,07-07 20:30:34.367  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.367  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
,07-07 20:30:34.367  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-07 20:30:34.367  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:30:34.367  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.367  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.368  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:30:34.368  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.368  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.368  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
,07-07 20:30:34.368  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.368  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.368  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:30:34.368  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.368  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.368  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.368  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.368  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.369  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.369  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
07-07 20:30:34.369  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.369  3831  3871 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:30:34.369  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.369  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.369  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.370  3831  3871 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-07 20:30:34.370  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.370  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:34.370  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.370  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:30:34.370  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.370  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.370  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.370  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.370  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
,07-07 20:30:34.371  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.371  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.371  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.371  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.371  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.371  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.371  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.371  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.371  4179  4195 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-07 20:30:34.371  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.371  4179  4198 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-07 20:30:34.372  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.372  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.372  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:30:34.372  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.372  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
,07-07 20:30:34.372  3831  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.373  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.373  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.373  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.373  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
07-07 20:30:34.373  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.373  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.373  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.373  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.373  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.373  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.373  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.373  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.373  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.373  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:30:34.374  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.374  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.374  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.374  3831  3871 D BluetoothAdapter: STATE_ON
,07-07 20:30:34.374  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.374  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.374  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.375  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.375  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-07 20:30:34.375  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:30:34.375  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-07 20:30:34.375  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:30:34.375  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-07 20:30:34.376  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-07 20:30:34.376  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.376  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.376  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.376  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
07-07 20:30:34.376  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.376  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.376  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.376  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.376  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.376  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-07 20:30:34.377  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.376  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:30:34.377  4179  4198 D BtGatt.ScanManager: Starting BLE batch scan
07-07 20:30:34.377  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.377  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.377  4179  4198 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-07 20:30:34.377  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.377  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:30:34.377  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.377  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.377  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.378  3831  3871 D BluetoothAdapter: STATE_ON
,07-07 20:30:34.378  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.378  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-07 20:30:34.378  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.378  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.379  3831  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:30:34.379  3831  3871 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:30:34.379  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-07 20:30:34.380  3831  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:30:34.380  3831  3871 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-07 20:30:34.380  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-07 20:30:34.380  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-07 20:30:34.380  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-07 20:30:34.380  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-07 20:30:34.380  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-07 20:30:34.381  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-07 20:30:34.382  3831  3871 D ,io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-07 20:30:34.382  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-07 20:30:34.383  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-07 20:30:34.383  3831  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-07 20:30:34.383  3831  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-07 20:30:34.383  3831  3871 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-07 20:30:34.383  3831  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-07 20:30:34.383  3831  3871 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-07 20:30:34.384  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.384  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.384  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.384  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
07-07 20:30:34.384  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.384  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.384  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.384  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.385  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.385  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.385  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.385  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.385  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.385  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.385  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.385  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.385  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.386  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.386  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.386  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
07-07 20:30:34.386  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.386  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.387  3831  3871 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-07 20:30:34.387  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.387  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.387  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.388  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.388  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.388  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.388  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.388  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.388  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.388  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.388  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-07 20:30:34.388  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.388  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.388  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.388  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.388  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.388  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.389  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.389  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.389  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.389  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.389  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.390  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.390  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.390  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.390  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.390  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.390  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.390  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.390  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.391  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.391  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop,
07-07 20:30:34.391  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.391  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.391  4179  4195 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-07 20:30:34.391  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.391  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.391  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.391  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.391  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.391  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.392  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.392  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.392  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.392  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.393  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.393  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.393  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.393  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.394  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.394  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.394  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
07-07 20:30:34.394  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.394  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.394  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.394  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.394  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.394  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.394  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.394  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.394  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.394  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.395  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.395  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.395  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.395  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.395  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.395  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-07 20:30:34.395  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.395  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.396  3831  3871 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-07 20:30:34.397  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:30:34.397  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.397  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.398  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-07 20:30:34.398  3831  3877 I jxcore-log: 
07-07 20:30:34.398  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.398  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.398  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.398  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.398  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.398  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.398  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:30:34.398  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-07 20:30:34.398  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.399  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
07-07 20:30:34.399  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.399  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.399  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.399  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.403  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.403  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.403  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.403  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
07-07 20:30:34.403  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.403  3831  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-07 20:30:34.403  3831  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-07 20:30:34.404  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-07 20:30:34.404  3831  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-07 20:30:34.404  3831  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:30:34.404  3831  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,07-07 20:30:34.404  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:30:34.404  3831  3871 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-07 20:30:34.404  3831  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-07 20:30:34.404  3831  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-07 20:30:34.404  3831  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-07 20:30:34.404  3831  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-07 20:30:34.404  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.404  4179  4195 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-07 20:30:34.404  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-07 20:30:34.404  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.404  4179  4198 D BtGatt.ScanManager: stopping BLe Batch
07-07 20:30:34.405  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.405  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.405  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.405  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.405  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.405  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.405  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
,07-07 20:30:34.405  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.405  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.405  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.405  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.405  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.405  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.405  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.405  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.406  3831  3871 D BluetoothAdapter: STATE_ON
,07-07 20:30:34.406  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.406  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.406  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.406  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.407  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.407  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.407  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.407  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.407  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.407  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.407  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.407  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.407  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.407  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.407  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.407  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.407  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.407  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.407  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.408  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.408  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.408  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.408  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.408  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.408  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.408  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.408  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.408  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.408  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.408  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.408  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.408  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.408  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.408  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.409  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.409  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.409  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.410  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.410  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.410   875  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-07 20:30:34.411  4179  4195 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-07 20:30:34.411  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.410  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.411  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.411  4179  4198 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-07 20:30:34.416  3831  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-07 20:30:34.416  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.416  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-07 20:30:34.417  3831  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-07 20:30:34.417  3831  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-07 20:30:34.418  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-07 20:30:34.418  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
07-07 20:30:34.418  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.418  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:30:34.418  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-07 20:30:34.418  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-07 20:30:34.418  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-07 20:30:34.418  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.418  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
,07-07 20:30:34.418  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.418  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-07 20:30:34.418  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-07 20:30:34.418  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-07 20:30:34.419  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-07 20:30:34.419  3831  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-07 20:30:34.419  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.419  3831  3871 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:30:34.419  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.419  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.420  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-07 20:30:34.420  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.420  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.420  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.420  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.420  3831  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.420  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-07 20:30:34.420  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.420  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.420  4179  4195 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-07 20:30:34.420  4179  4195 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-07 20:30:34.420  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.421  3831  4235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-07 20:30:34.421  3831  4235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-07 20:30:34.421  3831  4235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,07-07 20:30:34.422  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.422  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.422  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:30:34.422  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.422  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-07 20:30:34.422  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.422  3831  3831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-07 20:30:34.425  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-07 20:30:34.426  3831  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-07 20:30:34.426  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-07 20:30:34.426  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.426  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.426  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-07 20:30:34.426  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.426  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:30:34.426  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-07 20:30:34.426  3831  3831 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-07 20:30:34.426  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.426  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.426  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.426  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.427  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.427  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.427  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.427  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-07 20:30:34.428  3831  3831 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-07 20:30:34.428  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-07 20:30:34.428  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.428  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.428  3831  3831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-07 20:30:34.428  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.428  3831  3831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-07 20:30:34.428  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-07 20:30:34.429  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.429  3831  3871 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:30:34.429  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.429  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.429  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.430  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-07 20:30:34.430  3831  3877 I jxcore-log: 
07-07 20:30:34.430  3831  3871 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-07 20:30:34.430  3831  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-07 20:30:34.430  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-07 20:30:34.431  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-07 20:30:34.431  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.431  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.431  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.431  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.431  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.431  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.431  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.431  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-07 20:30:34.431  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.431  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.431  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.431  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.431  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.432  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.432  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.432  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.432  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.432  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.432  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.432  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.433  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.433  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.435  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.435  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.435  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.436  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:30:34.436  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.436  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.436  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.436  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.436  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.436  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.436  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.436  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.436  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.436  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-07 20:30:34.436  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.436  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.437  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.437  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.437  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.437  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.437  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.437  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.438  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:30:34.438  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.438  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.438  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.438  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.438  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.438  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.438  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
07-07 20:30:34.438  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.438  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:30:34.439  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.439  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.439  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.439  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.439  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.439  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.439  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-07 20:30:34.439  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.440  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.440  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.440  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.440  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.440  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.440  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:34.440  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.441  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.441  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.441  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.441  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.441  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.441  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.441  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
,07-07 20:30:34.441  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.441  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.441  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.441  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.441  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.441  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.441  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.442  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.442  3831  3871 D BluetoothLeScanner: could not find callback wrapper
,07-07 20:30:34.442  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.442  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.442  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.443  3831  3871 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-07 20:30:34.443  3831  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-07 20:30:34.443  3831  3831 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-07 20:30:34.443  3831  3871 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-07 20:30:34.444  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-07 20:30:34.444  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.444  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.444  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.444  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.444  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.444  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.444  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.444  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
,07-07 20:30:34.444  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.444  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.445  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.445  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.445  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-07 20:30:34.445  3831  3877 I jxcore-log: 
07-07 20:30:34.445  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.445  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.445  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.445  3831  3871 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-07 20:30:34.445  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.446  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.446  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.446  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.446  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.446  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.446  3831  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-07 20:30:34.446  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-07 20:30:34.446  3831  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-07 20:30:34.446  3831  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:30:34.446  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.447  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-07 20:30:34.447  3831  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fee43f3 not in the list
07-07 20:30:34.447  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.447  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.447  3831  3871 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:30:34.447  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.447  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.447  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-07 20:30:34.447  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-07 20:30:34.447  3831  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-07 20:30:34.447  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-07 20:30:34.447  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-07 20:30:34.448  3831  3871 D BluetoothAdapter: STATE_ON
07-07 20:30:34.448  3831  3871 D BluetoothLeScanner: could not find callback wrapper
07-07 20:30:34.448  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-07 20:30:34.448  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:30:34.448  3831  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21928b0 not in the list
07-07 20:30:34.449  3831  3871 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-07 20:30:34.449  3831  3871 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
,07-07 20:30:34.449  3831  3871 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-07 20:30:34.449  3831  3871 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-07 20:30:34.449  3831  3871 E com.test.thalitest.ThaliTestRunner: Total duration: 18733 ms
07-07 20:30:34.449  3831  3871 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 18823ms. Plugin should use CordovaInterface.getThreadPool().
,07-07 20:30:34.474   875  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=15.06 delta 1000 -> 994
,07-07 20:30:34.475   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-07 20:30:34.475   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:30:34.480   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-07 20:30:34.542   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1,
,07-07 20:30:34.543  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-07 20:30:34.983  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-07 20:30:35.030  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-07 20:30:35.031  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-07 20:30:35.041   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,07-07 20:30:35.058   875  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-07 20:30:35.059   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-07 20:30:35.060   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:30:35.087   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-07 20:30:35.108   374   873 D CommandListener: Setting iface cfg
,07-07 20:30:35.110   875  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,07-07 20:30:35.127   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-07 20:30:35.157   875  4238 D DhcpClient: Receive thread started
,07-07 20:30:35.238   875  1312 E native  : do suspend false
,07-07 20:30:35.261   875  2111 D DhcpClient: Broadcasting DHCPDISCOVER
,07-07 20:30:35.274   875  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172785, domain null
,07-07 20:30:35.276   875  2111 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172785 seconds
,07-07 20:30:35.279   875  2111 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-07 20:30:35.292   875  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-07 20:30:35.293   875  2111 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-07 20:30:35.298   374   873 D CommandListener: Setting iface cfg
,07-07 20:30:35.309   875  2111 D DhcpClient: Scheduling renewal in 86399s
,07-07 20:30:35.309   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-07 20:30:35.312   875  1312 E native  : do suspend true
,07-07 20:30:35.330   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-07 20:30:35.333   875  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,07-07 20:30:35.334   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-07 20:30:35.336   875  1314 D ConnectivityService: Adding iface wlan0 to network 102
,07-07 20:30:35.345   875  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-07 20:30:35.411   875  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-07 20:30:35.411   875  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-07 20:30:35.412   875  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-07 20:30:35.414   875  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-07 20:30:35.415   875  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-07 20:30:35.429   875  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-07 20:30:35.436   875  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-07 20:30:35.436   875  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,07-07 20:30:35.436   875  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,07-07 20:30:35.436   875  1314 D ConnectivityService:    accepting network in place of null
,07-07 20:30:35.436   875  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-07 20:30:35.437   875  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-07 20:30:35.438   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-07 20:30:35.444   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=301831, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:30:35.484   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:30:35.517   875  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:80b::200e
,07-07 20:30:35.566   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-07 20:30:35.574   875  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-07 20:30:35.574   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-07 20:30:35.581   875  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,07-07 20:30:35.586   875   892 D Tethering: MasterInitialState.processMessage what=3
07-07 20:30:35.600   875  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 07 Jul 2016 18:30:35 GMT], X-Android-Received-Millis=[1467916235596], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467916235566]}
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:30:35.607  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:30:35.608   875  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-07 20:30:35.608   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-07 20:30:35.608   875  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-07 20:30:35.609   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-07 20:30:35.610  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-07 20:30:35.611  3831  3877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-07 20:30:35.611  3831  3877 I jxcore-log: 
,07-07 20:30:35.642  1868  1868 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-07 20:30:35.649  1868  2375 I iu.UploadsManager: num queued entries: 0
,07-07 20:30:35.651  1868  1868 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-07 20:30:35.652  1868  2375 I iu.UploadsManager: num updated entries: 0
,07-07 20:30:35.654  1868  1868 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-07 20:30:35.655  1868  2375 I iu.SyncManager: NEXT; no task
,07-07 20:30:35.659  3961  3961 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-07 20:30:35.664  1868  4249 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-07 20:30:35.664  1868  4249 W BaseAppContext: Using Auth Proxy for data requests.
,07-07 20:30:35.667  3961  3961 D SprintDMHelper: simOperator: 
,07-07 20:30:35.667  3961  3961 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-07 20:30:35.676  1868  4249 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:30:35.691  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:35.697  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:30:35.742  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-07 20:30:35.742  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-07 20:30:35.742  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:30:35.742  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:30:35.772  1868  4249 E MDM     : [220] SitrepService.a: Error sending sitrep.
,07-07 20:30:35.784  2400  4252 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-07 20:30:37.073  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-07 20:30:37.074  3831  3871 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,07-07 20:30:37.168  3831  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-07 20:30:37.169  3831  3871 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,07-07 20:30:43.444   875  1314 D ConnectivityService: handlePromptUnvalidated 102
,07-07 20:31:03.500  1658  1698 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-07 20:31:03.500  1658  1698 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-07 20:31:03.548  1511  1511 I ConfigService: onCreate
,07-07 20:31:05.702  3592  4264 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:31:05.794  3592  4265 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-07 20:31:05.807  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:05.810  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:05.843  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-07 20:31:05.844  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-07 20:31:05.844  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:31:05.844  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:05.868  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:05.870  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:05.895  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:31:05.895  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:31:05.895  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:31:05.895  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:05.923  3592  4265 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:31:05.923  3592  4264 E BooksSync: Soft error
07-07 20:31:05.923  3592  4264 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:31:05.923  3592  4264 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:31:05.923  3592  4264 E BooksSync: Sync error
07-07 20:31:05.923  3592  4264 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:31:05.923  3592  4264 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:31:05.923  3592  4264 I BooksSync: Finished books sync
,07-07 20:31:05.934   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 320186, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:31:05.943  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:31:05.943  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-07 20:31:05.943  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:31:05.943  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:05.962  3006  4263 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-07 20:31:05.962  3006  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at blb.a(PG:3937)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at czp.a(PG:18188)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:31:05.962  3006  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	... 12 more
07-07 20:31:05.962  3006  4263 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at fal.a(PG:38)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:31:05.962  3006  4263 E HttpOperation: 	... 14 more
,07-07 20:31:05.990  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:31:05.991  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:31:05.991  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:31:05.991  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:06.015  3006  4263 E HttpOperation: [getmobileexperiments] Unexpected exception
07-07 20:31:06.015  3006  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at hec.a(PG:42)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at hee.a(PG:102)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at czr.a(PG:65)
,07-07 20:31:06.015  3006  4263 E HttpOperation: 	at kka.a(PG:108)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at czp.a(PG:19176)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:31:06.015  3006  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	... 15 more
07-07 20:31:06.015  3006  4263 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at fal.a(PG:38)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:31:06.015  3006  4263 E HttpOperation: 	... 17 more
,07-07 20:31:06.015  3006  4263 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-07 20:31:06.015  3006  4263 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jdm.a(PG:82)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jcs.o(PG:406)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jcn.a(PG:1379)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jcs.i(PG:143)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at hec.a(PG:42)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at hee.a(PG:102)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at czr.a(PG:65)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at kka.a(PG:108)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at czp.a(PG:19176)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at czp.a(PG:9081)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at czq.run(PG:1686)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jdj.a(PG:4091)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jdj.a(PG:1125)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jdm.a(PG:77)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	... 15 more
07-07 20:31:06.015  3006  4263 E ExperimentLoader: Caused by: faj: BadAuthentication
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at fal.a(PG:38)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	at jdj.a(PG:4089)
07-07 20:31:06.015  3006  4263 E ExperimentLoader: 	... 17 more
,07-07 20:31:06.131   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 319187, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:31:08.620  1511  1511 I ConfigService: onDestroy
,07-07 20:31:11.123   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=337510, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:31:15.104  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:15.124  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:15.127  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:15.186  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-07 20:31:15.186  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-07 20:31:15.189  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:31:15.189  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:15.216  1511  1896 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-07 20:31:15.216  1511  1896 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-07 20:31:15.216  1511  1896 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-07 20:31:15.216  1511  1896 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-07 20:31:15.216  1511  1896 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-07 20:31:15.216  1511  1896 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-07 20:31:15.216  1511  1896 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-07 20:31:15.227  3521  3551 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-07 20:31:15.227  3521  3551 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-07 20:31:15.227  3521  3551 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-07 20:31:15.227  3521  3551 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-07 20:31:15.227  3521  3551 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-07 20:31:15.227  3521  3551 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-07 20:31:15.227  3521  3551 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-07 20:31:20.264   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=346650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:31:36.836  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:36.837  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:31:36.872  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:31:36.872  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:31:36.872  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:31:36.872  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:36.890  3006  4274 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-07 20:31:36.890  3006  4274 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at blb.a(PG:3937)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at czp.a(PG:18188)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:31:36.890  3006  4274 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	... 12 more
07-07 20:31:36.890  3006  4274 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at fal.a(PG:38)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:31:36.890  3006  4274 E HttpOperation: 	... 14 more
,07-07 20:31:36.953  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-07 20:31:36.953  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:31:36.954  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:31:36.954  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:31:36.971  3006  4274 E HttpOperation: [getmobileexperiments] Unexpected exception
07-07 20:31:36.971  3006  4274 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at hec.a(PG:42)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at hee.a(PG:102)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at czr.a(PG:65)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at kka.a(PG:108)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at czp.a(PG:19176)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:31:36.971  3006  4274 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	... 15 more
07-07 20:31:36.971  3006  4274 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at fal.a(PG:38)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:31:36.971  3006  4274 E HttpOperation: 	... 17 more
07-07 20:31:36.971  3006  4274 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-07 20:31:36.971  3006  4274 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jdm.a(PG:82)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jcs.o(PG:406)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jcn.a(PG:1379)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jcs.i(PG:143)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at hec.a(PG:42)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at hee.a(PG:102)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at czr.a(PG:65)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at kka.a(PG:108)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at czp.a(PG:19176)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at czp.a(PG:9081)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at czq.run(PG:1686)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jdj.a(PG:4091)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jdm.a(PG:77)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	... 15 more
07-07 20:31:36.971  3006  4274 E ExperimentLoader: Caused by: faj: BadAuthentication
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at fal.a(PG:38)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	at jdj.a(PG:4089)
07-07 20:31:36.971  3006  4274 E ExperimentLoader: 	... 17 more
,07-07 20:31:37.087   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 362906, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:31:50.730   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=377117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:32:07.323  3592  4278 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:32:07.342  3592  4279 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-07 20:32:07.359  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:07.360  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:07.392  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:32:07.392  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:32:07.392  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:32:07.392  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:07.426  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-07 20:32:07.427  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:07.454  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-07 20:32:07.454  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:32:07.454  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:32:07.454  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:07.477  3592  4279 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
07-07 20:32:07.477  3592  4278 E BooksSync: Soft error
07-07 20:32:07.477  3592  4278 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:32:07.477  3592  4278 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:32:07.478  3592  4278 E BooksSync: Sync error
07-07 20:32:07.478  3592  4278 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:32:07.478  3592  4278 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:32:07.478  3592  4278 I BooksSync: Finished books sync
,07-07 20:32:07.483   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 364617, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:32:21.321  1511  1991 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:32:22.650   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:32:38.148  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:38.152  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:32:38.201  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:32:38.201  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:32:38.202  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:32:38.202  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:38.217  3006  4282 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-07 20:32:38.217  3006  4282 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at blb.a(PG:3937)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at czp.a(PG:18188)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:32:38.217  3006  4282 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	... 12 more
07-07 20:32:38.217  3006  4282 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at fal.a(PG:38)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:32:38.217  3006  4282 E HttpOperation: 	... 14 more
,07-07 20:32:38.255  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:32:38.255  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:32:38.255  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:32:38.255  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:32:38.270  3006  4282 E HttpOperation: [getmobileexperiments] Unexpected exception
07-07 20:32:38.270  3006  4282 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at hec.a(PG:42)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at hee.a(PG:102)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at czr.a(PG:65)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at kka.a(PG:108)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at czp.a(PG:19176)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:32:38.270  3006  4282 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	... 15 more
07-07 20:32:38.270  3006  4282 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at fal.a(PG:38)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:32:38.270  3006  4282 E HttpOperation: 	... 17 more
07-07 20:32:38.270  3006  4282 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-07 20:32:38.270  3006  4282 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jdm.a(PG:82)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jcs.o(PG:406)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jcn.a(PG:1379)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jcs.i(PG:143)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at hec.a(PG:42)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at hee.a(PG:102)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at czr.a(PG:65)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at kka.a(PG:108)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at czp.a(PG:19176)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at czp.a(PG:9081)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at czq.run(PG:1686)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jdj.a(PG:4091)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jdm.a(PG:77)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	... 15 more
07-07 20:32:38.270  3006  4282 E ExperimentLoader: Caused by: faj: BadAuthentication
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at fal.a(PG:38)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	at jdj.a(PG:4089)
07-07 20:32:38.270  3006  4282 E ExperimentLoader: 	... 17 more
,07-07 20:32:38.438   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 424250, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:32:57.824   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=444210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:33:12.216  3592  4286 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:33:12.260  3592  4287 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-07 20:33:12.281  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:33:12.286  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:33:12.340  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:33:12.340  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-07 20:33:12.341  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:33:12.341  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:33:12.374  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:33:12.379  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:33:12.415  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:33:12.415  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:33:12.416  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:33:12.416  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:33:12.445  3592  4287 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:33:12.447  3592  4286 E BooksSync: Soft error
07-07 20:33:12.447  3592  4286 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:33:12.447  3592  4286 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:33:12.447  3592  4286 E BooksSync: Sync error
07-07 20:33:12.447  3592  4286 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:33:12.447  3592  4286 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:33:12.447  3592  4286 I BooksSync: Finished books sync
,07-07 20:33:12.463   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 458461, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:33:46.450  3137  4289 V KeepSync: Connecting to GoogleApiClient
,07-07 20:33:46.450   875   886 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-07 20:33:46.495  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:33:46.500  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:33:46.533  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-07 20:33:46.533  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:33:46.534  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:33:46.534  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:33:46.558  1868  4290 V BaseAuthAsyncOperation: access token request failed
,07-07 20:33:46.559  3137  4289 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:33:46.618  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-07 20:33:46.619  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:33:46.619  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:33:46.619  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:33:46.635  3137  4289 E KeepSync: IOException
07-07 20:33:46.635  3137  4289 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:33:46.635  3137  4289 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:33:46.635  3137  4289 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:33:46.635  3137  4289 E KeepSync: 	... 10 more
07-07 20:33:46.635  3137  4289 W KeepSync: Sync result 2
,07-07 20:33:46.647   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 492696, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:34:18.198  3137  4292 V KeepSync: Connecting to GoogleApiClient
,07-07 20:34:18.199   875  1381 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-07 20:34:18.266  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:34:18.271  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:34:18.326  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-07 20:34:18.326  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-07 20:34:18.326  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:34:18.327  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:34:18.363  1868  4293 V BaseAuthAsyncOperation: access token request failed
07-07 20:34:18.365  3137  4292 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:34:18.425  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-07 20:34:18.425  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-07 20:34:18.425  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:34:18.425  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:34:18.439  3137  4292 E KeepSync: IOException
07-07 20:34:18.439  3137  4292 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:34:18.439  3137  4292 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:34:18.439  3137  4292 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:34:18.439  3137  4292 E KeepSync: 	... 10 more
07-07 20:34:18.439  3137  4292 W KeepSync: Sync result 2
,07-07 20:34:18.455   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 524446, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:34:18.473   875   884 I art     : Background partial concurrent mark sweep GC freed 38683(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.795ms total 109.116ms
,07-07 20:34:26.464   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=532851, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:34:48.854  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:34:48.855  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:34:48.896  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:34:48.896  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:34:48.896  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:34:48.896  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:34:48.917  3006  4296 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-07 20:34:48.917  3006  4296 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at blb.a(PG:3937)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at czp.a(PG:18188)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:34:48.917  3006  4296 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	... 12 more
07-07 20:34:48.917  3006  4296 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at fal.a(PG:38)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:34:48.917  3006  4296 E HttpOperation: 	... 14 more
,07-07 20:34:49.002  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:34:49.002  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:34:49.002  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:34:49.002  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:34:49.017  3006  4296 E HttpOperation: [getmobileexperiments] Unexpected exception
07-07 20:34:49.017  3006  4296 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at hec.a(PG:42)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at hee.a(PG:102)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at czr.a(PG:65)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at kka.a(PG:108)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at czp.a(PG:19176)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:34:49.017  3006  4296 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	... 15 more
07-07 20:34:49.017  3006  4296 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at fal.a(PG:38)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:34:49.017  3006  4296 E HttpOperation: 	... 17 more
,07-07 20:34:49.018  3006  4296 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-07 20:34:49.018  3006  4296 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jdm.a(PG:82)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jcs.o(PG:406)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jcn.a(PG:1379)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jcs.i(PG:143)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at hec.a(PG:42)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at hee.a(PG:102)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at czr.a(PG:65)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at kka.a(PG:108)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at czp.a(PG:19176)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at czp.a(PG:9081)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at czq.run(PG:1686)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jdj.a(PG:4091)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jdj.a(PG:1125)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jdm.a(PG:77)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	... 15 more
07-07 20:34:49.018  3006  4296 E ExperimentLoader: Caused by: faj: BadAuthentication
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at fal.a(PG:38)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	at jdj.a(PG:4089)
07-07 20:34:49.018  3006  4296 E ExperimentLoader: 	... 17 more
,07-07 20:34:49.189   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 546377, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:35:01.664   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=568051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:35:20.770   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:35:21.426  3137  4299 V KeepSync: Connecting to GoogleApiClient
,07-07 20:35:21.427   875  3211 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-07 20:35:21.490  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:21.494  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:21.530  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:35:21.530  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:35:21.531  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:21.531  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:21.556  1868  4300 V BaseAuthAsyncOperation: access token request failed
,07-07 20:35:21.558  3137  4299 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:35:21.632  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:35:21.632  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-07 20:35:21.632  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:21.633  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:21.655  3137  4299 E KeepSync: IOException
07-07 20:35:21.655  3137  4299 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:35:21.655  3137  4299 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:35:21.655  3137  4299 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:35:21.655  3137  4299 E KeepSync: 	... 10 more
,07-07 20:35:21.657  3137  4299 W KeepSync: Sync result 2
,07-07 20:35:21.670   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 587666, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:35:21.786  3592  4301 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:35:21.819  3592  4302 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-07 20:35:21.851  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:35:21.851  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:35:21.852  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:21.852  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:21.918  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:35:21.918  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-07 20:35:21.918  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:21.918  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:21.950  3592  4302 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:35:21.951  3592  4301 E BooksSync: Soft error
07-07 20:35:21.951  3592  4301 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:35:21.951  3592  4301 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:35:21.951  3592  4301 E BooksSync: Sync error
07-07 20:35:21.951  3592  4301 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:35:21.951  3592  4301 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:35:21.951  3592  4301 I BooksSync: Finished books sync
,07-07 20:35:21.974   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 588030, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:35:23.867  3521  3521 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-07 20:35:23.899  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:23.981  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-07 20:35:23.982  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-07 20:35:23.982  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:23.983  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:24.053  3521  3521 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-07 20:35:24.078  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:24.141  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-07 20:35:24.141  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-07 20:35:24.142  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:24.142  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:24.205  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:24.244  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-07 20:35:24.244  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-07 20:35:24.245  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:24.245  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:24.291  3521  3521 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-07 20:35:24.766  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:24.856  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-07 20:35:24.856  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-07 20:35:24.857  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:24.857  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:24.930  3521  3521 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-07 20:35:24.934  3521  3521 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-07 20:35:24.939  3521  3521 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-07 20:35:24.950  3521  3521 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,07-07 20:35:24.951  3521  3567 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-07 20:35:39.639  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:39.649  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:39.651  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:39.692  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-07 20:35:39.693  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-07 20:35:39.693  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:39.693  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:39.730  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:35:39.730  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-07 20:35:39.731  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-07 20:35:55.957   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=622343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:35:59.912  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:59.922  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:59.924  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:35:59.951  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-07 20:35:59.951  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-07 20:35:59.951  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:35:59.952  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:35:59.973  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:35:59.973  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:35:59.974  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-07 20:36:10.783   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=637170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-07 20:36:20.281  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:20.289  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:20.292  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:20.337  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-07 20:36:20.337  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-07 20:36:20.337  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:36:20.338  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:36:20.368  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:36:20.369  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:36:20.369  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-07 20:36:40.540  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:40.547  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:40.550  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:36:40.598  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-07 20:36:40.598  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-07 20:36:40.599  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:36:40.599  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:36:40.647  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-07 20:36:40.647  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:36:40.648  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-07 20:36:45.983   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=672370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:37:00.953  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:00.965  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:00.967  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:01.008  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-07 20:37:01.008  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-07 20:37:01.008  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:37:01.008  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:37:01.047  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-07 20:37:01.048  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:37:01.048  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-07 20:37:21.267  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:21.284  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:21.289  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:21.358  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-07 20:37:21.359  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-07 20:37:21.359  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:37:21.359  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:37:21.405  3521  3521 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-07 20:37:21.406  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-07 20:37:21.406  3521  3521 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-07 20:37:27.422  3137  4314 V KeepSync: Connecting to GoogleApiClient
,07-07 20:37:27.423   875   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-07 20:37:27.492  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:27.497  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:37:27.520  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:37:27.520  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-07 20:37:27.520  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:37:27.520  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:37:27.536  1868  4315 V BaseAuthAsyncOperation: access token request failed
,07-07 20:37:27.537  3137  4314 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:37:27.579  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:37:27.579  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:37:27.579  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:37:27.579  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:37:27.597  3137  4314 E KeepSync: IOException
07-07 20:37:27.597  3137  4314 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:37:27.597  3137  4314 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:37:27.597  3137  4314 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:37:27.597  3137  4314 E KeepSync: 	... 10 more
,07-07 20:37:27.597  3137  4314 W KeepSync: Sync result 2
,07-07 20:37:27.614   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 713705, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:38:52.663  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:38:52.664  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:38:52.705  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:38:52.705  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-07 20:38:52.705  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:38:52.705  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:38:52.729  3006  4320 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-07 20:38:52.729  3006  4320 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at blb.a(PG:3937)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at czp.a(PG:18188)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:38:52.729  3006  4320 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	... 12 more
07-07 20:38:52.729  3006  4320 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at fal.a(PG:38)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:38:52.729  3006  4320 E HttpOperation: 	... 14 more
,07-07 20:38:52.802  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:38:52.802  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:38:52.802  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:38:52.802  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:38:52.823  3006  4320 E HttpOperation: [getmobileexperiments] Unexpected exception
07-07 20:38:52.823  3006  4320 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at hec.a(PG:42)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at hee.a(PG:102)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at czr.a(PG:65)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at kka.a(PG:108)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at czp.a(PG:19176)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:38:52.823  3006  4320 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	... 15 more
07-07 20:38:52.823  3006  4320 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at fal.a(PG:38)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:38:52.823  3006  4320 E HttpOperation: 	... 17 more
,07-07 20:38:52.823  3006  4320 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-07 20:38:52.823  3006  4320 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jdm.a(PG:82)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jcs.o(PG:406)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jcn.a(PG:1379)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jcs.i(PG:143)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at hec.a(PG:42)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at hee.a(PG:102)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at czr.a(PG:65)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at kka.a(PG:108)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at czp.a(PG:19176)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at czp.a(PG:9081)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at czq.run(PG:1686)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jdj.a(PG:4091)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jdj.a(PG:1125)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jdm.a(PG:77)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	... 15 more
07-07 20:38:52.823  3006  4320 E ExperimentLoader: Caused by: faj: BadAuthentication
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at fal.a(PG:38)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	at jdj.a(PG:4089)
07-07 20:38:52.823  3006  4320 E ExperimentLoader: 	... 17 more
,07-07 20:38:52.945   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 798681, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:39:40.609  3592  4324 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:39:40.656  3592  4325 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-07 20:39:40.682  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:39:40.690  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:39:40.782  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-07 20:39:40.783  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-07 20:39:40.783  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:39:40.784  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:39:40.852  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:39:40.856  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:39:40.894  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-07 20:39:40.895  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-07 20:39:40.895  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:39:40.895  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:39:40.931  3592  4325 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:39:40.933  3592  4324 E BooksSync: Soft error
07-07 20:39:40.933  3592  4324 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:39:40.933  3592  4324 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:39:40.933  3592  4324 E BooksSync: Sync error
07-07 20:39:40.933  3592  4324 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:39:40.933  3592  4324 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:39:40.933  3592  4324 I BooksSync: Finished books sync
,07-07 20:39:40.945   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 846721, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:41:39.103  3137  4330 V KeepSync: Connecting to GoogleApiClient
,07-07 20:41:39.104   875  1748 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-07 20:41:39.155  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:41:39.158  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:41:39.209  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-07 20:41:39.209  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-07 20:41:39.209  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-07 20:41:39.209  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:41:39.238  1868  4331 V BaseAuthAsyncOperation: access token request failed
,07-07 20:41:39.239  3137  4330 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:41:39.318  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:41:39.318  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-07 20:41:39.318  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:41:39.318  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:41:39.336  3137  4330 E KeepSync: IOException
07-07 20:41:39.336  3137  4330 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:41:39.336  3137  4330 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:41:39.336  3137  4330 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:41:39.336  3137  4330 E KeepSync: 	... 10 more
,07-07 20:41:39.336  3137  4330 W KeepSync: Sync result 2
,07-07 20:41:39.345   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 965297, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:41:40.961  1511  1991 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-07 20:45:32.336  4179  4194 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-07 20:45:36.147   875  1755 I ActivityManager: Start proc 4343:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-07 20:45:36.209  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:36.211  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:45:36.246  4343  4343 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-07 20:45:36.256  3932  4353 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:45:36.340  4343  4356 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-07 20:45:36.406  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:45:36.407  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-07 20:45:36.407  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:45:36.407  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:45:36.494  4343  4356 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-07 20:45:36.501  3932  4353 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:45:36.502  3932  4353 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:45:36.621  4343  4356 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-07 20:45:36.670  4343  4343 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-07 20:45:36.883  4343  4343 W InstanceID/Rpc: Found 10011
,07-07 20:45:37.010  4380  4380 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-947227941.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-947227941.dex
,07-07 20:45:37.070  4380  4380 I dex2oat : dex2oat took 60.305ms (threads: 4) arena alloc=171KB java alloc=29KB native alloc=1386KB free=1429KB
,07-07 20:45:37.107   875  1741 I ActivityManager: Killing 3634:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-07 20:45:41.211   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1207597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-07 20:45:51.423   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1217810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-07 20:45:51.490   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,07-07 20:46:07.057  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:46:07.060  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:46:07.076  3932  4430 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:46:07.123  1511  1896 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:46:07.123  1511  1896 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-07 20:46:07.123  1511  1896 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:46:07.123  1511  1896 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:46:07.138  3932  4430 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:46:59.559  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:46:59.560  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:46:59.601  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-07 20:46:59.601  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:46:59.601  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:46:59.601  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:46:59.633  3006  4435 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-07 20:46:59.633  3006  4435 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at blb.a(PG:3937)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at czp.a(PG:18188)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:46:59.633  3006  4435 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	... 12 more
07-07 20:46:59.633  3006  4435 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at fal.a(PG:38)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:46:59.633  3006  4435 E HttpOperation: 	... 14 more
,07-07 20:46:59.703  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-07 20:46:59.703  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-07 20:46:59.703  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:46:59.703  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:46:59.721  3006  4435 E HttpOperation: [getmobileexperiments] Unexpected exception
07-07 20:46:59.721  3006  4435 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jdm.a(PG:82)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jcs.o(PG:406)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jcn.a(PG:1379)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jcs.i(PG:143)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at hec.a(PG:42)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at hee.a(PG:102)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at czr.a(PG:65)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at kka.a(PG:108)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at czp.a(PG:19176)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at czp.a(PG:9081)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at czq.run(PG:1686)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:46:59.721  3006  4435 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jdj.a(PG:4091)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jdj.a(PG:1125)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jdm.a(PG:77)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	... 15 more
07-07 20:46:59.721  3006  4435 E HttpOperation: Caused by: faj: BadAuthentication
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at fal.a(PG:38)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	at jdj.a(PG:4089)
07-07 20:46:59.721  3006  4435 E HttpOperation: 	... 17 more
,07-07 20:46:59.721  3006  4435 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-07 20:46:59.721  3006  4435 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jdm.a(PG:82)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jcs.o(PG:406)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jcn.a(PG:1379)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jcs.i(PG:143)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at hec.a(PG:42)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at hee.a(PG:102)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at czr.a(PG:65)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at kka.a(PG:108)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at czp.a(PG:19176)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at czp.a(PG:9081)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at czq.run(PG:1686)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jdj.a(PG:4091)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jdj.a(PG:1125)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jdm.a(PG:77)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	... 15 more
07-07 20:46:59.721  3006  4435 E ExperimentLoader: Caused by: faj: BadAuthentication
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at fal.a(PG:38)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	at jdj.a(PG:4089)
07-07 20:46:59.721  3006  4435 E ExperimentLoader: 	... 17 more
,07-07 20:46:59.886   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1285540, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:47:07.252  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:47:07.254  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:47:07.271  3932  4438 V GoogleAuthProtoRequest: [352] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:47:07.300  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-07 20:47:07.300  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-07 20:47:07.300  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:47:07.300  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: [352] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: [352] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:47:07.343  3932  4438 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:48:17.837  3592  4443 I BooksSync: Starting books sync for 61035162, extras: ade
,07-07 20:48:17.890  3592  4444 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-07 20:48:17.912  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:48:17.918  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:48:17.977  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-07 20:48:17.977  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-07 20:48:17.977  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:48:17.977  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:48:18.006  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:48:18.011  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:48:18.056  1511  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-07 20:48:18.056  1511  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-07 20:48:18.056  1511  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:48:18.057  1511  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:48:18.090  3592  4444 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-07 20:48:18.091  3592  4443 E BooksSync: Soft error
07-07 20:48:18.091  3592  4443 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:48:18.091  3592  4443 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-07 20:48:18.091  3592  4443 E BooksSync: Sync error
07-07 20:48:18.091  3592  4443 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-07 20:48:18.091  3592  4443 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-07 20:48:18.091  3592  4443 I BooksSync: Finished books sync
,07-07 20:48:18.104   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1364053, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-07 20:49:07.428  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:49:07.430  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:49:07.443  3932  4447 V GoogleAuthProtoRequest: [353] a.<init>: mAccountName set to: thalitester@gmail.com
,07-07 20:49:07.464  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-07 20:49:07.464  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-07 20:49:07.464  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:49:07.464  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:49:07.484  3932  4447 W ExperimentUpdateService: [353] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: [353] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-07 20:49:07.485  3932  4447 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-07 20:50:02.106  3137  4450 V KeepSync: Connecting to GoogleApiClient
07-07 20:50:02.106   875  3211 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-07 20:50:02.175  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:50:02.178  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-07 20:50:02.217  1511  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-07 20:50:02.217  1511  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-07 20:50:02.217  1511  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
07-07 20:50:02.218  1511  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:50:02.241  1868  4451 V BaseAuthAsyncOperation: access token request failed
,07-07 20:50:02.243  3137  4450 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-07 20:50:02.313  1511  2213 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-07 20:50:02.314  1511  2213 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-07 20:50:02.314  1511  2213 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-07 20:50:02.314  1511  2213 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-07 20:50:02.338  3137  4450 E KeepSync: IOException
07-07 20:50:02.338  3137  4450 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-07 20:50:02.338  3137  4450 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-07 20:50:02.338  3137  4450 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-07 20:50:02.338  3137  4450 E KeepSync: 	... 10 more
,07-07 20:50:02.338  3137  4450 W KeepSync: Sync result 2
,07-07 20:50:02.351   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1468325, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms)
```
