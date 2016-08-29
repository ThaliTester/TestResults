#### Test 82912030d0e406f_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
,08-29 10:12:14.035   929  5319 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287860, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
08-29 10:12:14.504  5637  5637 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 10:12:14.510  5637  5637 D AndroidRuntime: CheckJNI is OFF
08-29 10:12:14.538  5637  5637 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 10:12:14.573  5637  5637 I Radio-JNI: register_android_hardware_Radio DONE
08-29 10:12:14.589  5637  5637 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 10:12:14.595   929   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 10:12:14.639   929   940 I ActivityManager: Start proc 5646:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 10:12:14.644  5637  5637 D AndroidRuntime: Shutting down VM
08-29 10:12:14.737  5646  5646 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 10:12:14.769  5646  5646 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 10:12:14.792  5646  5646 I LibraryLoader: Time to load native libraries: 16 ms (timestamps 8601-8617)
08-29 10:12:14.792  5646  5646 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:12:14.811  5646  5646 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fddc549}
08-29 10:12:14.811  5646  5646 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 10:12:14.811  5646  5646 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 10:12:14.817  5646  5646 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 10:12:14.818  5646  5646 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 10:12:14.851  5646  5646 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 10:12:14.863  5646  5646 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 10:12:14.864  5646  5646 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 10:12:14.864  5646  5646 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 10:12:14.864  5646  5646 I Adreno  : Build Date                       : 10/21/15
08-29 10:12:14.864  5646  5646 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 10:12:14.864  5646  5646 I Adreno  : Local Branch                     : 
08-29 10:12:14.864  5646  5646 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 10:12:14.864  5646  5646 I Adreno  : Remote Branch                    : NONE
08-29 10:12:14.864  5646  5646 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 10:12:14.914   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d97ae7:true
,08-29 10:12:14.950  5646  5646 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 10:12:14.959  5646  5646 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 10:12:14.983  5646  5683 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 10:12:14.990  5646  5670 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 10:12:15.027  5646  5683 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 10:12:15.110   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +426ms (total +495ms)
,08-29 10:12:15.138  5646  5646 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5646
,08-29 10:12:15.222  5646  5646 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 10:12:15.339  5646  5686 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -580122320
,08-29 10:12:15.345  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 10:12:15.345  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 10:12:15.345  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 10:12:15.345  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 10:12:15.345  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 10:12:15.345  5646  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@156c527 added. We now have 1 listener(s)
,08-29 10:12:15.348  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 10:12:15.349  5646  5686 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 10:12:15.349  5646  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:12:15.350  5646  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 10:12:15.353  5646  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6313072 added. We now have 1 listener(s)
08-29 10:12:15.353  5646  5686 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:12:15.357   929  3068 D WifiService: New client listening to asynchronous messages
,08-29 10:12:15.357  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:12:15.357  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 10:12:15.358  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 10:12:15.358  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 10:12:15.358  5646  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 10:12:15.362  5646  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:12:15.362  5646  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 10:12:15.370  5646  5686 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:15.370  5646  5686 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:15.371  5646  5686 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 10:12:15.371  5646  5686 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:12:15.371  5646  5686 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 10:12:15.375  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:15.378  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:15.397  5646  5646 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 10:12:15.683  5646  5692 W jxcore-log: Initializing JXcore engine
08-29 10:12:15.683  5646  5692 W jxcore-log: JXcore engine is ready
,08-29 10:12:15.701  5646  5655 I art     : Background sticky concurrent mark sweep GC freed 85204(8MB) AllocSpace objects, 18(1892KB) LOS objects, 25% free, 24MB/32MB, paused 1.867ms total 103.147ms
,08-29 10:12:15.698  5692  5692 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12615 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 10:12:15.698  5692  5692 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[15521]" dev="sockfs" ino=15521 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 10:12:15.698  5692  5692 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5905 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 10:12:15.698  5692  5692 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[29492]" dev="sockfs" ino=29492 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 10:12:15.717  5646  5692 W jxcore-log: Starting JXcore engine
,08-29 10:12:15.766  5646  5692 W jxcore-log: Platform android
08-29 10:12:15.766  5646  5692 W jxcore-log: 
08-29 10:12:15.766  5646  5692 W jxcore-log: Process ARCH arm
08-29 10:12:15.766  5646  5692 W jxcore-log: 
,08-29 10:12:15.864  5646  5692 I jxcore-log: JXcore Cordova bridge is ready!
08-29 10:12:15.864  5646  5692 I jxcore-log: 
,08-29 10:12:15.865  5646  5692 W jxcore-log: JXcore engine is started
,08-29 10:12:15.868  5646  5686 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 10:12:15.871  5646  5646 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 10:12:25.317  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 10:12:25.317  5646  5692 I jxcore-log: 
,08-29 10:12:25.320  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 10:12:25.320  5646  5692 I jxcore-log: 
,08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:25.324  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:25.326  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:12:25.327  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 10:12:25.327  5646  5692 I jxcore-log: 
,08-29 10:12:25.329  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 10:12:25.329  5646  5692 I jxcore-log: 
,08-29 10:12:25.576  5646  5692 I jxcore-log: Running unit tests
08-29 10:12:25.576  5646  5692 I jxcore-log: 
,08-29 10:12:25.576  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:12:25.576  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f35b67 added. We now have 2 listener(s)
,08-29 10:12:25.577  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 10:12:25.577  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:12:25.578  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:12:25.578  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:12:25.578  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e217d14 added. We now have 2 listener(s)
08-29 10:12:25.578  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:12:25.578  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:12:25.583  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:25.592  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:25.595  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:25.596  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:12:25.596  5646  5692 D executeNativeTests: Running unit tests
08-29 10:12:25.599  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:25.602  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:25.636  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:12:25.636  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 added. We now have 3 listener(s)
08-29 10:12:25.637  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:12:25.637  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:12:25.637  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:12:25.637  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:12:25.637  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 added. We now have 3 listener(s)
08-29 10:12:25.637  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:12:25.638  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:12:25.639  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:25.642  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:25.642  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:12:25.642  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:12:25.644  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:12:25.644  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:12:25.644  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 10:12:25.644  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:12:25.645  5646  5692 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 10:12:25.645  5646  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:12:25.645  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:12:25.645  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 10:12:25.645  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:12:25.645  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:12:25.645  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:25.645  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:25.645  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:12:25.646  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:25.646  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:25.646  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:12:25.646  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:12:25.646  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 removed from the list
,08-29 10:12:25.647  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:25.647  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 removed from the list
08-29 10:12:25.648  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:25.653  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:25.654  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:25.654  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:25.654  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:25.654  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:25.655  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:25.655  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:25.655  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:25.655  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:25.656  5646  5692 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 10:12:25.656  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:25.656  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:25.656  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:12:25.656  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:25.656  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:25.656  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:25.656  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:25.656  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:25.656  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:25.656  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:25.656  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:25.656  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:25.656  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:25.656  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:25.657  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:25.657  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:25.657  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:25.657  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
,08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:12:25.659  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:12:25.660  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 10:12:25.660  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:25.660  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:25.661  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:25.661  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:25.661  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:25.661  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:25.661  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:25.661  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:25.661  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:25.661  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:25.661  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:25.661  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:25.661  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:25.661  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:25.661  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:25.661  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:25.661  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:25.662  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:25.662  5646  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:12:25.663  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:25.665  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:12:25.666  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:25.666  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:12:25.666  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:12:25.667  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:12:25.667  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:12:25.667  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:12:25.667  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:12:25.668  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:25.669  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:25.670  5646  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:12:25.671  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:12:25.675  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:12:25.675  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:12:25.676  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:12:25.677  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 10:12:25.678  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 10:12:25.678  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:12:25.678  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:12:25.678  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:12:25.678  5646  5692 D BluetoothAdapter: STATE_ON
08-29 10:12:25.680  4415  4429 D BtGatt.GattService: registerClient() - UUID=e4953815-2a31-45bc-b587-29b8c0b9396f
08-29 10:12:25.681  4415  4502 D BtGatt.GattService: onClientRegistered() - UUID=e4953815-2a31-45bc-b587-29b8c0b9396f, clientIf=5
08-29 10:12:25.682  5646  5657 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 10:12:25.683  4415  4648 D BtGatt.GattService: start scan with filters
08-29 10:12:25.688  4415  4507 D BtGatt.ScanManager: handling starting scan
08-29 10:12:25.688  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:12:25.689  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:12:25.689  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:12:25.689  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:12:25.690  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:12:25.690  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:12:25.690  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:12:25.690  4415  4507 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:12:25.691  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 10:12:25.692  5646  5692 I io.jxcore.node.ConnectionHelper: start: OK
08-29 10:12:25.698  4415  4502 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:12:25.698  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:25.699  4415  4507 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:12:25.705  4415  4502 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 10:12:25.705  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:25.706  4415  4507 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:12:25.706  4415  4507 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 10:12:25.718  4415  4502 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 10:12:25.718  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:25.724  4415  4502 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:12:25.724  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:12:26.175   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:12:26.191  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-29 10:12:26.192  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:12:26.192  5646  5646 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:12:27.176   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:12:28.177   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:12:29.177   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:12:30.178   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:12:30.696  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:12:30.696  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:30.696  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:12:30.696  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:30.696  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:12:30.696  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:12:30.697  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:12:30.697  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:12:30.697  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:12:30.697  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:12:30.698  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:12:30.698  5646  5692 D BluetoothAdapter: STATE_ON
,08-29 10:12:30.699  4415  4429 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:12:30.700  4415  4648 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 10:12:30.701  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:12:30.701  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:12:30.701  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:12:30.701  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:12:30.701  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:12:30.702  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:12:30.703  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:12:30.703  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:12:30.703  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:12:30.704  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:12:30.709  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:30.710  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:30.710  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:12:30.710  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
,08-29 10:12:30.710  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:12:30.710  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:30.710  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:30.710  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:12:30.710  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:30.711  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:12:30.711  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:30.711  4415  4415 D BtGatt.ScanManager: awakened up at time 304537
08-29 10:12:30.719  4415  4502 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,08-29 10:12:30.719  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:30.719  4415  4507 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:12:30.729  4415  4502 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 10:12:30.729  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:30.729  4415  4507 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:12:30.753  4415  4502 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 10:12:30.753  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:30.753  4415  4502 D BtGatt.GattService: current time is 304579123423
,08-29 10:12:30.754  4415  4502 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -82, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -78, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -77, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -78, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -76, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 10:12:30.756  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 10:12:30.757  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-29 10:12:30.757  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 10:12:30.757  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 10:12:30.758  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 10:12:30.758  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 10:12:31.179   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:12:31.212  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:12:35.716  5646  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 10:12:35.721  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:35.731  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:35.735  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:12:35.736  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:12:35.736  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:12:35.736  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:12:35.737  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 10:12:35.737  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:12:35.737  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:12:35.743  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:35.746  5646  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:12:35.746  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:12:35.749  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:35.755  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:12:35.756  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:12:35.756  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:12:35.764  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:12:35.764  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:12:35.765  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:12:35.766  5646  5692 D BluetoothAdapter: STATE_ON
08-29 10:12:35.768  4415  4648 D BtGatt.GattService: registerClient() - UUID=77345eb2-04e6-4a33-9585-e74426475fa4
08-29 10:12:35.769  4415  4502 D BtGatt.GattService: onClientRegistered() - UUID=77345eb2-04e6-4a33-9585-e74426475fa4, clientIf=5
,08-29 10:12:35.769  5646  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:12:35.770  4415  4428 D BtGatt.GattService: start scan with filters
08-29 10:12:35.774  4415  4507 D BtGatt.ScanManager: handling starting scan
08-29 10:12:35.774  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:12:35.774  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:12:35.774  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:12:35.774  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:12:35.777  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:12:35.777  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:12:35.777  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:12:35.778  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:12:35.781  4415  4502 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 10:12:35.781  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:35.782  4415  4507 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 10:12:35.782  5646  5692 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:12:35.785  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:12:35.785  5646  5692 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:12:35.786  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:35.786  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:12:35.786  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:35.786  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:12:35.786  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:12:35.786  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:12:35.786  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:12:35.786  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:12:35.786  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:12:35.786  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:12:35.787  5646  5692 D BluetoothAdapter: STATE_ON
08-29 10:12:35.787  4415  4648 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:12:35.788  4415  4656 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:12:35.788  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:12:35.788  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:12:35.788  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:12:35.789  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:12:35.789  4415  4502 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 10:12:35.789  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:35.789  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:12:35.789  4415  4507 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:12:35.789  4415  4507 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:12:35.790  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:12:35.790  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:12:35.791  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:12:35.791  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:12:35.791  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:12:35.792  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:35.792  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:35.792  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:12:35.792  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:12:35.793  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:35.793  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:12:35.793  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:35.793  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:12:35.793  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:35.793  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:35.793  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:35.795  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:35.795  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:35.796  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:35.796  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:12:35.796  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:35.796  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:35.797  5646  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:12:35.799  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:12:35.802  4415  4502 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 10:12:35.802  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:35.803  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:35.805  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:12:35.805  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:12:35.805  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:12:35.805  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:12:35.805  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:12:35.805  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:12:35.805  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:12:35.808  5646  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:12:35.809  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:12:35.809  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:35.809  4415  4502 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:12:35.809  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:12:35.813  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:35.814  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:12:35.815  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:12:35.815  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:12:35.816  4415  4502 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 10:12:35.816  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:35.816  4415  4507 D BtGatt.ScanManager: stopping BLe Batch
08-29 10:12:35.818  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:12:35.818  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:12:35.818  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:12:35.819  5646  5692 D BluetoothAdapter: STATE_ON
,08-29 10:12:35.822  4415  4502 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 10:12:35.822  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:35.822  4415  4507 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 10:12:35.822  4415  4648 D BtGatt.GattService: registerClient() - UUID=2b1a91fd-01e8-418a-adeb-de6e0b2c01e3
08-29 10:12:35.823  4415  4502 D BtGatt.GattService: onClientRegistered() - UUID=2b1a91fd-01e8-418a-adeb-de6e0b2c01e3, clientIf=5
,08-29 10:12:35.824  5646  5657 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 10:12:35.824  4415  4656 D BtGatt.GattService: start scan with filters
,08-29 10:12:35.828  4415  4502 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 10:12:35.828  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:12:35.830  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:12:35.830  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:12:35.830  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 10:12:35.830  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:12:35.830  4415  4507 D BtGatt.ScanManager: handling starting scan
,08-29 10:12:35.833  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:12:35.833  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:12:35.833  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:12:35.834  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 10:12:35.836  5646  5692 I io.jxcore.node.ConnectionHelper: start: OK
08-29 10:12:35.837  4415  4502 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:12:35.837  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:12:35.837  4415  4507 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:12:35.843  4415  4502 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 10:12:35.844  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:35.844  4415  4507 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:12:35.844  4415  4507 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:12:35.853  4415  4502 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:12:35.853  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:12:35.859  4415  4502 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:12:35.859  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:12:36.334  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 10:12:36.336  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:12:36.336  5646  5646 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:12:40.837  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:12:40.837  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:40.837  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:12:40.838  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:40.838  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 10:12:40.838  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:12:40.838  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:12:40.838  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:12:40.838  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:12:40.839  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:12:40.839  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:12:40.841  5646  5692 D BluetoothAdapter: STATE_ON
,08-29 10:12:40.842  4415  4428 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:12:40.846  4415  4429 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:12:40.847  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:12:40.847  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:12:40.847  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:12:40.847  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 10:12:40.847  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:12:40.850  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:12:40.850  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:12:40.851  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:12:40.851  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:12:40.852  4415  4415 D BtGatt.ScanManager: awakened up at time 314678
,08-29 10:12:40.852  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:12:40.855  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:12:40.855  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:12:40.855  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:12:40.857  4415  4502 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 10:12:40.857  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:40.858  4415  4507 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:12:40.866  4415  4502 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:12:40.866  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:12:40.866  4415  4507 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:12:40.886  4415  4502 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 10:12:40.886  4415  4502 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:12:40.886  4415  4502 D BtGatt.GattService: current time is 314712488575
08-29 10:12:40.887  4415  4502 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -78, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -78, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -78, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -77, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -79, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 10:12:40.887  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 10:12:40.887  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 10:12:40.887  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 10:12:40.888  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 10:12:40.888  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 10:12:40.888  4415  4502 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 10:12:41.356  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:12:41.356  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:41.356  5646  5646 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:12:45.856  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:12:45.856  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:12:45.856  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:12:45.857  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.857  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:45.857  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:12:45.857  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
,08-29 10:12:45.857  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:45.858  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
,08-29 10:12:45.858  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:12:45.858  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:45.859  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:45.859  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.862  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.862  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.862  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.862  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.864  5646  5692 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 10:12:45.866  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.866  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:45.866  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:12:45.866  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.867  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.867  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.867  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.867  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.867  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.867  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.868  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.868  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:45.868  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.868  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.871  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.871  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.871  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.872  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.874  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 10:12:45.874  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.874  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:12:45.875  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:45.875  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.875  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.875  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.875  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.875  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.875  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.876  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.876  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.876  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.876  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.876  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.877  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.877  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.877  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:45.877  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.878  5646  5692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 10:12:45.878  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.878  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:45.878  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:45.879  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.879  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.879  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.879  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.879  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:45.879  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.879  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.879  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.879  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.879  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.879  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.880  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:12:45.880  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.880  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.881  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.881  5646  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 10:12:45.882  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.882  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:45.882  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:12:45.882  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.882  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.882  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.882  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.882  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.882  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.882  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.882  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.882  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.882  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.882  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.884  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.884  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.884  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.884  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
,08-29 10:12:45.885  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:12:45.885  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:12:45.885  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:12:45.885  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:12:45.885  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:12:45.885  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:12:45.885  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:12:45.886  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:12:45.886  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:12:45.886  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:12:45.886  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:45.886  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:45.886  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.886  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.886  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.886  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.886  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.886  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.886  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.886  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.886  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.887  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.887  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.888  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.888  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:12:45.888  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.888  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.889  5646  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:12:45.889  5646  5692 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:12:45.889  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:12:45.893  5646  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:12:45.893  5646  5692 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 10:12:45.893  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:12:45.893  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-29 10:12:45.893  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:12:45.893  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:12:45.893  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:12:45.893  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:12:45.893  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:12:45.894  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:12:45.895  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 10:12:45.895  5646  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 10:12:45.895  5646  5692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:12:45.896  5646  5692 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 10:12:45.896  5646  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:12:45.896  5646  5692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:12:45.896  5646  5692 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-29 10:12:45.896  5646  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:12:45.896  5646  5692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:12:45.896  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 10:12:45.900  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 10:12:45.902  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 10:12:45.902  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 10:12:45.903  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 10:12:45.903  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 10:12:45.903  5646  5692 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 10:12:45.903  5646  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:12:45.903  5646  5692 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 10:12:45.903  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
,08-29 10:12:45.904  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.904  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:45.904  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:12:45.905  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.905  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.905  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.905  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 10:12:45.906  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
,08-29 10:12:45.906  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.906  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.906  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.906  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:45.906  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.906  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.906  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.906  5646  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
08-29 10:12:45.907  5646  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:12:45.908  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:12:45.908  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.908  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.908  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.909  5646  5692 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 10:12:45.909  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.909  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:45.909  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:45.910  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.910  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.910  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.910  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
,08-29 10:12:45.910  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.910  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.910  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.910  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.910  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.910  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.910  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.911  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.911  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.911  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.911  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.912  5646  5692 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 10:12:45.912  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.912  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:12:45.912  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:45.913  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.913  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.913  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.913  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.913  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.913  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.913  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.913  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.913  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:45.913  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.913  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.915  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.915  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.915  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.915  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.916  5646  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 10:12:45.916  5646  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-29 10:12:45.916  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:12:45.916  5646  5692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 10:12:45.916  5646  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:12:45.916  5646  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 10:12:45.916  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:12:45.916  5646  5692 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 10:12:45.916  5646  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:12:45.916  5646  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:12:45.916  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:12:45.916  5646  5692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-29 10:12:45.916  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:45.917  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:45.917  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:45.917  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:45.917  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.917  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.917  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.917  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.917  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.917  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:12:45.917  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.917  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.917  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.917  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.918  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:45.919  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:45.919  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.919  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.919  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:12:45.919  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.919  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:45.919  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:45.919  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:45.920  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:45.920  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:45.920  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:45.920  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:50.920  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:50.921  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.921  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:50.921  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.921  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.921  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
,08-29 10:12:50.922  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:50.922  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:50.922  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:50.922  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:50.923  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:50.923  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.923  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:50.923  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.923  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
,08-29 10:12:50.923  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:50.923  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.924  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.924  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:50.924  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:50.928  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:12:50.928  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:50.929  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.929  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
,08-29 10:12:50.935  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:12:50.936  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:12:50.939  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 10:12:50.940  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 10:12:50.941  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:12:50.941  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:12:50.941  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:12:50.941  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 10:12:50.942  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:50.942  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 10:12:50.942  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:12:50.942  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 10:12:50.942  5646  5695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:12:50.942  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:50.942  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 10:12:50.943  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:50.943  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 10:12:50.943  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.943  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:12:50.943  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:12:50.943  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:12:50.943  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.943  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.946  5646  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 10:12:50.946  5646  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 10:12:50.946  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:12:50.947  5646  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:12:50.947  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.947  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:12:50.947  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:50.947  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:12:50.947  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:50.947  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:12:50.947  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:50.947  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:12:50.947  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:12:50.947  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.947  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.948  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:50.948  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:50.948  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.948  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:50.948  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.948  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:50.949  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:50.949  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:50.952  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:50.952  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:50.952  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.953  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.957  5646  5692 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 10:12:50.957  5646  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:12:50.957  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:12:50.957  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:12:50.958  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:12:50.958  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:50.958  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:50.958  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:12:50.958  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:50.958  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.958  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.958  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:50.958  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.958  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.958  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:50.958  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:50.958  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.959  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.959  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.960  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:50.960  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:50.960  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.961  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
,08-29 10:12:50.967  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:12:50.967  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:50.967  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:50.967  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:12:50.967  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.967  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.967  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:50.967  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:50.967  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.967  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:50.967  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.967  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.968  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.968  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.969  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:50.969  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:12:50.969  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.969  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.970  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:12:50.970  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:12:50.970  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:12:50.971  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:12:50.971  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.971  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.971  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5852562 not in the list
08-29 10:12:50.971  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.971  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
08-29 10:12:50.971  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:50.971  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:50.971  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.971  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:50.971  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:50.973  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:12:50.973  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:12:50.973  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:50.973  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e0f6f3 not in the list
,08-29 10:12:50.975  5646  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-29 10:12:50.975  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:12:50.975  5646  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 10:12:50.975  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:12:50.975  5646  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 10:12:50.975  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:12:50.977  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:12:50.977  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 10:12:50.978  5646  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 10:12:50.978  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:12:50.978  5646  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 10:12:50.978  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:12:50.978  5646  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 10:12:50.978  5646  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 10:12:50.978  5646  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 10:12:50.978  5646  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 10:12:50.979  5646  5692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 10:12:50.979  5646  5692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 10:12:50.979  5646  5692 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 10:12:50.979  5646  5692 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 10:12:50.980  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:12:50.980  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@affaa9d added. We now have 3 listener(s)
08-29 10:12:50.980  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:12:50.981  5646  5692 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 10:12:50.982   929  3218 D WifiService: setWifiEnabled: true pid=5646, uid=10077
08-29 10:12:50.982   929  3218 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:12:51.036  4415  4626 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-29 10:12:51.036  4415  4643 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
08-29 10:12:51.036  5646  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,08-29 10:12:51.448  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:12:55.987  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:12:55.987  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@745ab12 added. We now have 4 listener(s)
08-29 10:12:55.988  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:12:55.999  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:12:56.000  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@745ab12 removed from the list
08-29 10:12:56.000  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:56.000  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:12:56.000  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:12:56.002  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:12:56.002  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b582e3 added. We now have 4 listener(s)
,08-29 10:12:56.002  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:12:56.005  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:12:56.006  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b582e3 removed from the list
,08-29 10:12:56.006  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:12:56.006  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:12:56.006  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:12:56.008  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:12:56.008  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbc14e0 added. We now have 4 listener(s)
,08-29 10:12:56.008  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:12:56.013   929  3218 D WifiService: setWifiEnabled: false pid=5646, uid=10077
08-29 10:12:56.013   929  3218 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:12:56.020   929  3067 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 10:12:56.020   929  3067 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 10:12:56.020   929  3067 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:12:56.020   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:12:56.022  4415  4498 D BluetoothAdapterState: Current state: ON, message: 23
08-29 10:12:56.023  4415  4498 D BluetoothAdapterProperties: Setting state to 13
08-29 10:12:56.023  4415  4498 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 10:12:56.024  4415  4498 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 10:12:56.026  4415  4498 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:12:56.032  4415  4415 D BluetoothMapService: onReceive
08-29 10:12:56.032  4415  4415 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:12:56.032  4415  4415 D BluetoothMapService: STATE_TURNING_OFF
08-29 10:12:56.033  4415  4415 D BluetoothMapService: MAP Service closeService in
08-29 10:12:56.033  4415  4415 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 10:12:56.034  4415  4415 D ObexServerSockets0: shutdown(block = true)
08-29 10:12:56.036  4415  4415 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:12:56.036  4415  4415 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:12:56.036  4415  4658 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-29 10:12:56.036  4415  4643 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 10:12:56.036  4415  4659 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 10:12:56.042  4415  4415 I BtOppRfcommListener: stopping Accept Thread
08-29 10:12:56.043  4415  5234 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 10:12:56.043  4415  5234 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 10:12:56.045   929  3067 E native  : do suspend true
08-29 10:12:56.046  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:56.046  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:12:56.047  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.048  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:56.051  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:56.052  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:56.053  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.053  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:12:56.059   929   942 I ActivityManager: Start proc 5699:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 10:12:56.060  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:12:56.061  4415  4502 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:12:56.062  4415  4498 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 10:12:56.064  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:12:56.064  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:12:56.065  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.065  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:12:56.065  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:12:56.066  4415  4415 D HeadsetService: Received stop request...Stopping profile...
,08-29 10:12:56.073  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:56.071   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 10:12:56.074   929   929 D BluetoothHeadset: Proxy object disconnected
,08-29 10:12:56.074  3589  3607 D BluetoothHeadset: Proxy object disconnected
08-29 10:12:56.075   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 10:12:56.075  3207  3405 D BluetoothHeadset: Proxy object disconnected
,08-29 10:12:56.076  4415  4415 D A2dpService: Received stop request...Stopping profile...
08-29 10:12:56.076  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:56.077  4415  4651 D A2dpStateMachine: Exit Disconnected: -1
08-29 10:12:56.078   929   929 D BluetoothA2dp: Proxy object disconnected
,08-29 10:12:56.079  3207  3207 D HeadsetProfile: Bluetooth service disconnected
08-29 10:12:56.079  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:56.079  3207  3207 D BluetoothA2dp: Proxy object disconnected
,08-29 10:12:56.081  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:56.082   929  5320 D DhcpClient: Clearing IP address
08-29 10:12:56.082   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:12:56.084  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:56.084  4415  4415 D HidService: Received stop request...Stopping profile...
08-29 10:12:56.084  4415  4415 D HidService: Stopping Bluetooth HidService
08-29 10:12:56.085  4415  4415 V BluetoothAdapterState: isTurningOff()=true
08-29 10:12:56.085  4415  4415 V BluetoothAdapterState: isTurningOn()=false
08-29 10:12:56.085  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:12:56.085  4415  4415 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:12:56.086  3207  3207 D BluetoothInputDevice: Proxy object disconnected
08-29 10:12:56.086  3207  3207 D HidProfile: Bluetooth service disconnected
08-29 10:12:56.086  4415  4415 D HealthService: Received stop request...Stopping profile...
,08-29 10:12:56.088  4415  4415 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:12:56.088  4415  4415 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:12:56.088   507   923 D CommandListener: Setting iface cfg
08-29 10:12:56.088  4415  4626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:12:56.088  4415  4626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:12:56.089  4415  4626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:12:56.089  4415  4415 D PanService: Received stop request...Stopping profile...
,08-29 10:12:56.089  4415  4502 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 10:12:56.089  4415  4502 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 10:12:56.091  4415  4415 D BluetoothMapService: Received stop request...Stopping profile...
08-29 10:12:56.091  4415  4415 D BluetoothMapService: stop()
08-29 10:12:56.091  3207  3207 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 10:12:56.092  3207  3207 D PanProfile: Bluetooth service disconnected
08-29 10:12:56.093   929  5322 D DhcpClient: Receive thread stopped
08-29 10:12:56.094  4415  4415 D BluetoothMapAppObserver: deinitObservers()
08-29 10:12:56.094  4415  4415 D BluetoothMapAppObserver: removeReceiver()
08-29 10:12:56.096  3207  3207 D BluetoothMap: Proxy object disconnected
08-29 10:12:56.097  3207  3207 D MapProfile: Bluetooth service disconnected
08-29 10:12:56.097  4415  4415 D SapService: Received stop request...Stopping profile...
08-29 10:12:56.097  4415  4415 V SapService: stop()
08-29 10:12:56.098  4415  4415 V BluetoothAdapterState: isTurningOff()=true
08-29 10:12:56.098  4415  4415 V BluetoothAdapterState: isTurningOn()=false
08-29 10:12:56.098  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:12:56.098  4415  4415 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:12:56.099  4415  4415 V BluetoothAdapterState: isTurningOff()=true
,08-29 10:12:56.099  4415  4415 V BluetoothAdapterState: isTurningOn()=false
08-29 10:12:56.099  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:12:56.100  4415  4415 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:12:56.100  4415  4415 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:12:56.100  4415  4415 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:12:56.100  4415  4415 V BluetoothAdapterState: isTurningOff()=true
08-29 10:12:56.100  4415  4415 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:12:56.100  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:12:56.100  4415  4415 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:12:56.100  4415  4415 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:12:56.101  4415  4415 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:12:56.101  4415  4502 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:12:56.101  4415  4626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:12:56.101  4415  4502 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:12:56.101  4415  4415 V BluetoothAdapterState: isTurningOff()=true
08-29 10:12:56.101  4415  4415 V BluetoothAdapterState: isTurningOn()=false
08-29 10:12:56.101  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:12:56.101  4415  4626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:12:56.101  4415  4415 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:12:56.101  4415  4626 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:12:56.101  4415  4626 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:12:56.101  4415  4415 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:12:56.101  4415  4415 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 10:12:56.101  4415  4626 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 10:12:56.102  4415  4626 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:12:56.102  4415  4502 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 10:12:56.102  3670  5382 V NativeCrypto: Read error: ssl=0x7f7a071000: I/O error during system call, Connection timed out
08-29 10:12:56.104  3670  5382 V NativeCrypto: SSL shutdown failed: ssl=0x7f7a071000: I/O error during system call, Broken pipe
08-29 10:12:56.105  4415  4415 D BluetoothMapService: MAP Service closeService in
,08-29 10:12:56.105  4415  4415 V BluetoothAdapterState: isTurningOff()=true
08-29 10:12:56.105  4415  4415 V BluetoothAdapterState: isTurningOn()=false
08-29 10:12:56.105  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 10:12:56.105  4415  4415 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:12:56.105  4415  4415 D BluetoothMapService: cleanup()
08-29 10:12:56.106  4415  4415 D BluetoothMapService: MAP Service closeService in
08-29 10:12:56.106  4415  4415 V BluetoothAdapterState: isTurningOff()=true
08-29 10:12:56.106  4415  4415 V BluetoothAdapterState: isTurningOn()=false
08-29 10:12:56.106  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:12:56.106  4415  4415 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:12:56.106  4415  4498 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 10:12:56.106  4415  4498 D BluetoothAdapterProperties: Setting state to 15
08-29 10:12:56.106  4415  4498 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 10:12:56.107  4415  4498 I BluetoothAdapterState: Entering BleOnState
,08-29 10:12:56.107   929  4029 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 10:12:56.107  3207  3220 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:12:56.107   929  5318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 10:12:56.109  3207  3219 D BluetoothPan: onBluetoothStateChange on: false
,08-29 10:12:56.110   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:12:56.110   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:12:56.110   929  5318 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 10:12:56.110  3207  3832 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 10:12:56.111   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 10:12:56.111   929  3069 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 10:12:56.112   929  3069 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 10:12:56.113  5699  5699 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 10:12:56.113  3207  3832 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 10:12:56.114   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 10:12:56.114   603   603 E Parcel  : Reading a NULL string not supported here.
,08-29 10:12:56.116   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:12:56.116   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 10:12:56.116  3589  3833 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:12:56.114   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 10:12:56.117  3207  3219 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:12:56.117   929   929 D RttService: SCAN_AVAILABLE : 1
08-29 10:12:56.117   929  3132 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:12:56.118  3207  3832 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:12:56.119  4415  4498 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 10:12:56.119  4415  4498 D BluetoothAdapterProperties: Setting state to 16
08-29 10:12:56.119  4415  4498 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 10:12:56.120  4415  4498 D BluetoothAdapterProperties: onBleDisable
08-29 10:12:56.120  4415  4498 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:12:56.120  4415  4499 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 10:12:56.123  4415  4626 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 10:12:56.123  4415  4626 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:12:56.125  4415  4502 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:12:56.125   929  3069 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 10:12:56.126  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:12:56.126  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:12:56.126  3560  3773 W QCNEJ   : |CORE| network lost: 100
08-29 10:12:56.127  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.127  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:12:56.129   929  3067 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 10:12:56.129  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:12:56.129  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:12:56.130  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.130  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:12:56.133  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.133  3560  3773 ,W QCNEJ   : |CORE| onLost: unbind the process to WIFI
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:12:56.133  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:12:56.134  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.134  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:12:56.134  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 10:12:56.136  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:12:56.136  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:12:56.138  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:56.139  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:56.141  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:12:56.142   929  3067 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:12:56.142   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d4608e:true
08-29 10:12:56.142   929  3067 E native  : do suspend true
,08-29 10:12:56.156   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:12:56.157   929  3521 I ActivityManager: Start proc 5719:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 10:12:56.178   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 10:12:56.178   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:12:56.178   507   923 D TetherController: Setting IP forward enable = 0
,08-29 10:12:56.179  5699  5699 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 10:12:56.179   929  3069 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 10:12:56.180   929  3069 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:12:56.180   605   605 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 10:12:56.180   605   605 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:12:56.182   929   946 D Tethering: MasterInitialState.processMessage what=3
08-29 10:12:56.183   929  3067 D DhcpClient: doQuit
,08-29 10:12:56.183   929  3067 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 10:12:56.184   929  5320 D DhcpClient: onQuitting
08-29 10:12:56.184  3683  3683 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
08-29 10:12:56.184  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:56.187  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:12:56.187  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:12:56.187  4841  4883 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 10:12:56.187  4841  4883 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:12:56.187  4841  4883 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 10:12:56.187  4841  4883 E SarControlService: no key has been found,reset the power
08-29 10:12:56.187  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 10:12:56.187  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,08-29 10:12:56.187  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 10:12:56.187  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.187  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:12:56.188  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:12:56.188  4905  4905 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 10:12:56.189  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:12:56.189  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 10:12:56.189  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 10:12:56.190  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.190  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:12:56.190  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:12:56.190  4905  4905 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 10:12:56.190  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.190  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:12:56.192  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000ea03000000000000ffffffff]
,08-29 10:12:56.192  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:12:56.192  4905  4919 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 10:12:56.192  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:12:56.192  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:12:56.192  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:12:56.193  4841  4858 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 10:12:56.193  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:12:56.193  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:12:56.195  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:56.196  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:56.199  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000eb03000000000000ffffffff]
08-29 10:12:56.199  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:12:56.199  4905  4919 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,08-29 10:12:56.200  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:12:56.200  4841  4856 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 10:12:56.201  5699  5699 D BluetoothMap: Create BluetoothMap proxy object
,08-29 10:12:56.211  5699  5699 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 10:12:56.217  5719  5719 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 10:12:56.226  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:12:56.231   929  3624 I ActivityManager: Killing 5369:com.android.chrome/u0a39 (adj 15): empty #17
,08-29 10:12:56.263  3683  3683 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:12:56.268  3683  3683 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 10:12:56.340  4415  4502 I bt_hci  : shut_down
,08-29 10:12:56.343  4415  4509 D bt_hwcfg: hw_epilog_process
,08-29 10:12:56.343  4415  4509 I bt_vendor: low_power_mode_cb
,08-29 10:12:56.346  4415  4509 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 10:12:56.347  4415  4509 I bt_vendor: epilog_cb
08-29 10:12:56.347  4415  4509 I bt_hci  : epilog_finished_callback
,08-29 10:12:56.349  4415  4502 I bt_hci_h4: hal_close
,08-29 10:12:56.350  4415  4502 I bt_userial_vendor: device fd = 51 close
,08-29 10:12:56.364  3683  3683 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:12:56.400  5719  5719 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 10:12:56.400  5719  5719 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 10:12:56.406  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 10:12:56.413  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:12:56.413  5699  5699 D DockEventReceiver: finishStartingService: stopping service
08-29 10:12:56.425  3683  3683 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 10:12:56.436   929  4965 I ActivityManager: Killing 4802:com.google.android.calendar/u0a36 (adj 15): empty #17
,08-29 10:12:56.495  4415  4499 D bt_stack_manager: event_shut_down_stack finished.
08-29 10:12:56.495  4415  4498 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-29 10:12:56.496  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 10:12:56.497  4415  4415 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:12:56.498  4415  4498 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 10:12:56.498  4415  4415 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:12:56.498  4415  4415 D BtGatt.GattService: stop()
08-29 10:12:56.498  4415  4415 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 10:12:56.500  3924  3924 D SystemUpdateService: onCreate
08-29 10:12:56.502  4415  4415 V BluetoothAdapterState: isTurningOff()=false
08-29 10:12:56.502  4415  4415 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:12:56.502  4415  4415 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:12:56.502  4415  4415 V BluetoothAdapterState: isBleTurningOff()=true
08-29 10:12:56.502  4415  4498 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 10:12:56.502  4415  4498 D BluetoothAdapterProperties: Setting state to 10
08-29 10:12:56.502  4415  4498 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 10:12:56.503   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 10:12:56.504  4415  4498 I BluetoothAdapterState: Entering OffState
08-29 10:12:56.504  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 10:12:56.511  4415  4415 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 10:12:56.511  4415  4415 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 10:12:56.511  4415  4499 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 10:12:56.512  4415  4499 D bt_stack_manager: event_clean_up_stack finished.
08-29 10:12:56.512  4415  4415 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 10:12:56.520  4415  4415 I art     : System.exit called, status: 0
,08-29 10:12:56.520  4415  4415 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 10:12:56.523  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 10:12:56.525  3924  5351 I iu.UploadsManager: num queued entries: 0
08-29 10:12:56.526  3924  5351 I iu.UploadsManager: num updated entries: 0
08-29 10:12:56.526  3924  5351 I iu.SyncManager: NEXT; no task
08-29 10:12:56.529   929  3067 D wifi    : In wifi stop Hal
08-29 10:12:56.529   929  3067 D wifi    : halHandle = 0x7f63db59e0, mVM = 0x7f801cd140, mCls = 0x200ad6
08-29 10:12:56.529   929  3678 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 10:12:56.529   929  3678 D WifiHAL : Got a signal to exit!!!
08-29 10:12:56.529   929  3678 I WifiHAL : Exit wifi_event_loop
08-29 10:12:56.529  4286  4286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:12:56.530   929  3067 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
08-29 10:12:56.530   929  3067 E WifiHAL : Event processing terminated
08-29 10:12:56.530   929  3067 D wifi    : In wifi cleaned up handler
08-29 10:12:56.530   929  3067 I WifiHAL : Internal cleanup completed
08-29 10:12:56.531  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:56.532  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:12:56.532  3704  4038 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:12:56.532  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:12:56.548   929  3678 D wifi    : set interface wlan0 flags (DOWN)
08-29 10:12:56.549   929  3067 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 10:12:56.554  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 10:12:56.556  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 10:12:56.557  3924  5760 I SystemUpdateService: active receiver: enabled
,08-29 10:12:56.585  3924  5760 I SystemUpdateService: showing system update notification
,08-29 10:12:56.607   929  3624 I ActivityManager: Process com.android.bluetooth (pid 4415) has died
,08-29 10:12:56.623   929  3510 I ActivityManager: Start proc 5764:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 10:12:56.641  3924  5760 V SystemUpdateService: retry (wakeup: false) in 3599917 ms
,08-29 10:12:56.644  3924  3924 D SystemUpdateService: onDestroy
,08-29 10:12:56.658  5764  5764 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 10:12:56.660  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:12:56.669  5764  5764 D SprintDMHelper: simOperator: 
08-29 10:12:56.669  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:12:56.681   929  3235 I ActivityManager: Start proc 5776:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 10:12:56.681   929  3235 I ActivityManager: Killing 4969:com.google.android.deskclock/u0a66 (adj 15): empty #17
,08-29 10:12:56.742  5719  5754 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 10:12:56.752   929   946 D Tethering: InitialState.processMessage what=4
,08-29 10:12:56.755   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 10:12:56.793  4286  5790 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 10:12:56.799   929  3517 I ActivityManager: Killing 5403:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-29 10:12:56.815   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42429a2:true
,08-29 10:12:56.844   929  3517 I ActivityManager: Start proc 5792:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 10:12:56.879  5792  5792 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 10:12:56.922  5792  5792 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 10:12:56.929   929   940 I ActivityManager: Killing 4512:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 10:12:57.264   507   923 E Netd    : netlink response contains error (No such file or directory)
,08-29 10:12:57.266   929  3069 E NetdConnector: NDC Command {52 network destroy 100} took too long (1086ms)
,08-29 10:12:57.267   929  3069 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 10:12:57.267   929  3054 E NetdConnector: NDC Command {53 bandwidth setglobalalert 2097152} took too long (1079ms)
08-29 10:12:57.268   507   923 D TetherController: Setting IP forward enable = 0
08-29 10:12:57.268   929  3053 E NetdConnector: NDC Command {54 bandwidth gettetherstats} took too long (512ms)
,08-29 10:13:01.068   929  3521 D WifiService: setWifiEnabled: true pid=5646, uid=10077
,08-29 10:13:01.068   929  3521 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:13:01.077   507   923 D SoftapController: Softap fwReload - Ok
,08-29 10:13:01.083   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:01.083   507   923 D CommandListener: Trying to bring down wlan0
,08-29 10:13:01.085   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:13:01.091   929  3067 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 10:13:01.681   929  3067 D wifi    : set interface wlan0 flags (UP)
,08-29 10:13:01.685   929  3067 I WifiHAL : Initializing wifi
,08-29 10:13:01.685   929  3067 I WifiHAL : Creating socket
08-29 10:13:01.688   929  3067 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,08-29 10:13:01.688   929  3067 D wifi    : Did set static halHandle = 0x7f63db59e0
08-29 10:13:01.688   929  3067 D wifi    : halHandle = 0x7f63db59e0, mVM = 0x7f801cd140, mCls = 0x101752
08-29 10:13:01.689   929  3067 D wifi    : array field set
08-29 10:13:01.689   929  3067 I WifiNative-HAL: interface[0] = wlan0
08-29 10:13:01.692   929  5822 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547136166368
08-29 10:13:01.692   929  5822 D wifi    : waitForHalEvents called, vm = 0x7f801cd140, obj = 0x101752, env = 0x7f64f82c00
08-29 10:13:01.693   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 10:13:01.732  5823  5823 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 10:13:01.750  5823  5823 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:13:01.792   929  3067 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 10:13:01.796  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:01.797  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:01.798  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:01.807  5823  5823 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 10:13:01.807  5823  5823 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 10:13:01.826   929  3067 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:13:01.827  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:01.827  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:01.827  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:01.827  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:01.830  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:01.830  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:01.830  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:01.830  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:01.831  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:01.831  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:01.831  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:01.831  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:13:01.834   929  3067 D WifiConfigStore: loaded 0 passpoint configs
,08-29 10:13:01.834   929  3067 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:13:01.835   929  3067 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 10:13:01.836   929  3067 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:13:01.836   929  3067 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 10:13:01.836   929  3067 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 10:13:01.840   929  3067 D WifiNative-HAL: Setting external_sim to 1
08-29 10:13:01.840  4286  4286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:13:01.841   929  3067 D wifi    : setting dfs flag to true, 0x7f6512f960
,08-29 10:13:01.841   929  3067 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:13:01.841   929  3067 D wifi    : setting scan oui 0x7f6512f960
08-29 10:13:01.841   929  3067 D WifiHAL : Sending mac address OUI
,08-29 10:13:01.855   929  3067 E native  : do suspend true
,08-29 10:13:01.861   929   929 D RttService: SCAN_AVAILABLE : 3
08-29 10:13:01.861   929  3067 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 10:13:01.861   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 10:13:01.861   929  3132 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:13:01.862   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:01.868   929  3055 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,08-29 10:13:01.868   929  3055 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 10:13:01.876   929  3055 D WifiNative-HAL: p2pGetDeviceAddress
08-29 10:13:01.877   929  3055 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
08-29 10:13:01.882   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=335707 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=7 mControllerEnergyUsed=26 }
,08-29 10:13:02.252  3924  5828 I EventLogService: Aggregate from 1472478178949 (log), 1472478178949 (data)
,08-29 10:13:05.113  5823  5823 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 10:13:05.155   929  3067 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 10:13:05.166   929  3067 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
08-29 10:13:05.166   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:13:05.186   929  3067 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 10:13:05.225   929  3067 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 10:13:05.564  5823  5823 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:13:05.612  5823  5823 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 10:13:05.613  5823  5823 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 10:13:05.627   929  3067 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:13:05.627   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:13:05.627   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 10:13:05.646   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:13:05.661   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:05.668   929  3067 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 10:13:05.678   929  3067 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 10:13:05.687   929  5833 D DhcpClient: Receive thread started
,08-29 10:13:05.781   929  3067 E native  : do suspend false
,08-29 10:13:05.800   929  5832 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 10:13:05.814   929  5833 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172502, domain null
,08-29 10:13:05.815   929  5832 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172502 seconds
,08-29 10:13:05.817   929  5832 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 10:13:05.831   929  5833 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 10:13:05.832   929  5832 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 10:13:05.834   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:05.842   929  3067 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 10:13:05.844   929  5832 D DhcpClient: Scheduling renewal in 86399s
,08-29 10:13:05.847   929  3067 E native  : do suspend true
,08-29 10:13:05.876   929  3067 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 10:13:05.880   929  3067 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 10:13:05.881   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 10:13:05.883   929  3069 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 10:13:05.889   929  3067 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 10:13:05.938   929  3069 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 10:13:05.938   929  3069 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 10:13:05.940   929  3069 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 10:13:05.943   929  3069 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 10:13:05.945   929  3069 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 10:13:05.954   929  3069 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 10:13:05.958   929  3069 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 10:13:05.958   929  3069 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-29 10:13:05.958   929  3069 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 10:13:05.958   929  3069 D ConnectivityService:    accepting network in place of null
,08-29 10:13:05.959   929  3067 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 10:13:05.959   929  3069 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:13:05.960   929  3067 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 10:13:05.985   929  5831 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:13:05.988   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:13:06.017   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:13:06.023   929  3069 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 10:13:06.023   929  3069 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:13:06.023  3560  3773 W QCNEJ   : |CORE| network available: 101
08-29 10:13:06.025   929  3069 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 10:13:06.026  3560  3773 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
08-29 10:13:06.027  3560  3773 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,08-29 10:13:06.028   929   946 D Tethering: MasterInitialState.processMessage what=3
08-29 10:13:06.029  3560  3773 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,08-29 10:13:06.032  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:06.033  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:13:06.033  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.033  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:13:06.036  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:06.036  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:13:06.036  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.036  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:06.039  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:06.039  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:13:06.040  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.040  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:13:06.042  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 10:13:06.043  4841  4883 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 10:13:06.044  4841  4883 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:13:06.044  4841  4883 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 10:13:06.044  4841  4883 E SarControlService: no key has been found,reset the power
08-29 10:13:06.044  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 10:13:06.044  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,08-29 10:13:06.044  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,08-29 10:13:06.045  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:13:06.045  4905  4905 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 10:13:06.047  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:13:06.047  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 10:13:06.047  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 10:13:06.048  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:13:06.048  4905  4905 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 10:13:06.052  3924  3924 D SystemUpdateService: onCreate
08-29 10:13:06.053  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000ec03000000000000ffffffff]
08-29 10:13:06.053  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,08-29 10:13:06.053  4905  4919 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
08-29 10:13:06.053  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:13:06.054  4841  4858 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-29 10:13:06.055  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000ed03000000000000ffffffff]
,08-29 10:13:06.055  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:13:06.055  4905  4919 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
08-29 10:13:06.056  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:13:06.056  4841  4856 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 10:13:06.059  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:13:06.071  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-29 10:13:06.073   929  3235 D WifiService: setWifiEnabled: false pid=5646, uid=10077
08-29 10:13:06.073   929  3235 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:13:06.075   929  5830 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
08-29 10:13:06.077   929  3067 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 10:13:06.077   929  3067 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 10:13:06.077   929  3067 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:13:06.077   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:13:06.079  3924  5351 I iu.UploadsManager: num queued entries: 0
,08-29 10:13:06.080  3924  5351 I iu.UploadsManager: num updated entries: 0
08-29 10:13:06.081  3924  5351 I iu.SyncManager: NEXT; no task
,08-29 10:13:06.083  3924  5843 I SystemUpdateService: active receiver: enabled
,08-29 10:13:06.084   929  3067 E native  : do suspend true
,08-29 10:13:06.085  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:13:06.087  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 10:13:06.089  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:13:06.092   929  5832 D DhcpClient: Clearing IP address
08-29 10:13:06.092   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:13:06.094   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:06.094  5764  5764 D SprintDMHelper: simOperator: 
08-29 10:13:06.094  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:13:06.100   929  5830 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-29 10:13:06.100   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-29 10:13:06.102   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 10:13:06.102   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 10:13:06.105   603   603 E Parcel  : Reading a NULL string not supported here.
,08-29 10:13:06.108   929  3069 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 10:13:06.109  3560  3773 W QCNEJ   : |CORE| network lost: 101
08-29 10:13:06.112  3560  3773 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-29 10:13:06.112   929   929 D RttService: SCAN_AVAILABLE : 1
08-29 10:13:06.113   929  3132 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:13:06.115   929  3067 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 10:13:06.120   929  3067 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:13:06.120   929  3067 E native  : do suspend true
,08-29 10:13:06.130  3924  5843 I SystemUpdateService: showing system update notification
,08-29 10:13:06.135   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:13:06.141  3924  5843 V SystemUpdateService: retry (wakeup: false) in 3599943 ms
,08-29 10:13:06.143  3924  3924 D SystemUpdateService: onDestroy
,08-29 10:13:06.146   929  5833 D DhcpClient: Receive thread stopped
,08-29 10:13:06.154   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 10:13:06.154   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:13:06.154   929  3069 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 10:13:06.154   929  3069 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:13:06.158   929  3067 D DhcpClient: doQuit
,08-29 10:13:06.158   929  3067 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 10:13:06.158   929  5832 D DhcpClient: onQuitting
08-29 10:13:06.160   929   946 D Tethering: MasterInitialState.processMessage what=3
08-29 10:13:06.161  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:06.162  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:06.162  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:13:06.162  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:06.163  5823  5823 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 10:13:06.163  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:06.164  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:06.164  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.164  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:06.165  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:06.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:06.165  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:13:06.165  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:06.167  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:06.167  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:06.168  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:06.172  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 10:13:06.172  4841  4883 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 10:13:06.173  4841  4883 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:13:06.173  4841  4883 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 10:13:06.173  4841  4883 E SarControlService: no key has been found,reset the power
08-29 10:13:06.173  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 10:13:06.173  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 10:13:06.173  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 10:13:06.174  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:13:06.174  4905  4905 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,08-29 10:13:06.175  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:13:06.175  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 10:13:06.175  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,08-29 10:13:06.176  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:13:06.176  4905  4905 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 10:13:06.179  3924  3924 D SystemUpdateService: onCreate
,08-29 10:13:06.181  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000ee03000000000000ffffffff]
08-29 10:13:06.181  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:13:06.181  4905  4919 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
08-29 10:13:06.181  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:13:06.181  4841  4856 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-29 10:13:06.184  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000ef03000000000000ffffffff]
08-29 10:13:06.184  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:13:06.184  4905  4919 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
08-29 10:13:06.185  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:13:06.185  4841  4858 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 10:13:06.186  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 10:13:06.189  3924  5858 I SystemUpdateService: active receiver: enabled
,08-29 10:13:06.195  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-29 10:13:06.196  3924  5351 I iu.UploadsManager: num queued entries: 0
,08-29 10:13:06.202  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:13:06.204  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 10:13:06.205   507   923 E Netd    : netlink response contains error (No such file or directory)
08-29 10:13:06.205  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 10:13:06.205   929  3069 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 10:13:06.206   929  3069 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 10:13:06.209  5764  5764 D SprintDMHelper: simOperator: 
08-29 10:13:06.209  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:13:06.216  5823  5823 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:13:06.218  3924  5351 I iu.UploadsManager: num updated entries: 0
,08-29 10:13:06.219  3924  5858 I SystemUpdateService: showing system update notification
,08-29 10:13:06.220  5823  5823 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 10:13:06.228  3924  5351 I iu.SyncManager: NEXT; no task
,08-29 10:13:06.240  3924  5858 V SystemUpdateService: retry (wakeup: false) in 3599950 ms
,08-29 10:13:06.243  3924  3924 D SystemUpdateService: onDestroy
,08-29 10:13:06.265  5823  5823 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 10:13:06.277  5823  5823 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:13:06.382   929  3067 D wifi    : In wifi stop Hal
,08-29 10:13:06.382   929  3067 D wifi    : halHandle = 0x7f63db59e0, mVM = 0x7f801cd140, mCls = 0x101752
08-29 10:13:06.382   929  5822 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 10:13:06.382   929  5822 D WifiHAL : Got a signal to exit!!!
08-29 10:13:06.382   929  5822 I WifiHAL : Exit wifi_event_loop
08-29 10:13:06.382   929  3067 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 10:13:06.382   929  3067 E WifiHAL : Event processing terminated
08-29 10:13:06.383   929  3067 D wifi    : In wifi cleaned up handler
08-29 10:13:06.383   929  3067 I WifiHAL : Internal cleanup completed
,08-29 10:13:06.388  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:06.390  4286  4286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:13:06.390  3704  4038 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:13:06.390  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:06.392  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:06.403   929  5822 D wifi    : set interface wlan0 flags (DOWN)
08-29 10:13:06.404   929  3067 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 10:13:06.612   929   946 D Tethering: InitialState.processMessage what=4
,08-29 10:13:06.619   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 10:13:07.025   929  3069 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 10:13:11.111   929   946 I ActivityManager: Start proc 5864:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 10:13:11.180   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:11.205  5864  5864 D AdapterServiceConfig: Adding HeadsetService
,08-29 10:13:11.206  5864  5864 D AdapterServiceConfig: Adding A2dpService
08-29 10:13:11.206  5864  5864 D AdapterServiceConfig: Adding HidService
08-29 10:13:11.206  5864  5864 D AdapterServiceConfig: Adding HealthService
08-29 10:13:11.206  5864  5864 D AdapterServiceConfig: Adding PanService
08-29 10:13:11.207  5864  5864 D AdapterServiceConfig: Adding GattService
,08-29 10:13:11.207  5864  5864 D AdapterServiceConfig: Adding BluetoothMapService
08-29 10:13:11.207  5864  5864 D AdapterServiceConfig: Adding SapService
,08-29 10:13:11.221   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@78e8074:true
,08-29 10:13:11.221  5864  5864 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 10:13:11.225  5864  5864 I bt_bluedroid: init
,08-29 10:13:11.225  5864  5876 I BluetoothAdapterState: Entering OffState
,08-29 10:13:11.227  5864  5877 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 10:13:11.227  5864  5877 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 10:13:11.227  5864  5877 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 10:13:11.228  5864  5877 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 10:13:11.228  5864  5864 I bt_bluedroid: get_profile_interface socket
,08-29 10:13:11.230  5864  5864 I bt_bluedroid: get_profile_interface sdp
,08-29 10:13:11.230  5864  5880 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 10:13:11.232  5864  5880 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 10:13:11.234  5864  5875 I bt_bluedroid: config_hci_snoop_log
08-29 10:13:11.235   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 10:13:11.240  5864  5876 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 10:13:11.240  5864  5876 D BluetoothAdapterProperties: Setting state to 14
08-29 10:13:11.240  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 10:13:11.242  5864  5876 D BluetoothBondStateMachine: make
,08-29 10:13:11.244  5864  5881 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 10:13:11.247  5864  5876 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:13:11.248  5864  5864 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 10:13:11.250  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:11.251  5864  5864 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:13:11.251  5864  5864 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:13:11.251  5864  5864 D BtGatt.GattService: start()
08-29 10:13:11.251  5864  5864 I bt_bluedroid: get_profile_interface gatt
,08-29 10:13:11.253  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:11.253  5864  5864 D BtGatt.AdvertiseManager: advertise manager created
,08-29 10:13:11.259  5864  5864 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:13:11.259  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:11.259  5864  5864 V BluetoothAdapterState: isBleTurningOn()=true
08-29 10:13:11.259  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:11.259  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 10:13:11.260  5864  5876 I bt_bluedroid: enable
08-29 10:13:11.260  5864  5877 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 10:13:11.260  5864  5877 I bt_hci  : start_up
,08-29 10:13:11.266  5864  5877 I bt_vendor: alloc value 0xf3fc904d
,08-29 10:13:11.266  5864  5877 I bt_vendor: init
08-29 10:13:11.266  5864  5877 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 10:13:11.266  5864  5877 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 10:13:11.388  5864  5877 D bt_hci  : start_up starting async portion
,08-29 10:13:11.389  5864  5884 I bt_hci  : event_finish_startup
,08-29 10:13:11.389  5864  5884 I bt_hci_h4: hal_open
,08-29 10:13:11.389  5864  5884 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-29 10:13:11.391  5864  5884 I bt_userial_vendor: device fd = 51 open
08-29 10:13:11.378  5885  5885 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 10:13:11.405  5864  5884 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:13:11.408  5864  5884 D bt_hwcfg: Chipset BCM4358A3
,08-29 10:13:11.408  5864  5884 D bt_hwcfg: Target name = [BCM4358A3]
,08-29 10:13:11.408  5864  5884 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 10:13:11.805  5864  5884 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 10:13:11.806  5864  5884 D bt_hwcfg: Settlement delay -- 100 ms
08-29 10:13:11.806  5864  5884 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 10:13:11.940  5864  5884 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:13:11.940  5864  5884 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 10:13:11.942  5864  5884 I bt_hwcfg: vendor lib fwcfg completed
08-29 10:13:11.942  5864  5884 I bt_vendor: firmware callback
,08-29 10:13:11.942  5864  5884 I bt_hci  : firmware_config_callback
,08-29 10:13:11.950  5864  5887 I bt_btu  : btu_task pending for preload complete event
,08-29 10:13:11.950  5864  5887 I bt_btu_task: Bluetooth chip preload is complete
,08-29 10:13:11.951  5864  5887 I bt_btu  : btu_task received preload complete event
,08-29 10:13:11.956  5864  5887 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 10:13:11.956  5864  5887 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 10:13:11.956  5864  5887 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 10:13:11.956  5864  5887 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:13:11.956  5864  5887 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 10:13:11.957  5864  5887 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:13:12.038  5864  5887 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f46c99
,08-29 10:13:12.039  5864  5887 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f46c99 
,08-29 10:13:12.061  5864  5880 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 10:13:12.063  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:13:12.063  5864  5880 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 10:13:12.066  5864  5880 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 10:13:12.069  5864  5880 D BluetoothAdapterProperties: Scan Mode:20
,08-29 10:13:12.069  5864  5880 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 10:13:12.070  5864  5880 D bt_hci  : do_postload posting postload work item
,08-29 10:13:12.070  5864  5884 I bt_hci  : event_postload
,08-29 10:13:12.070  5864  5884 I bt_vendor: sco_config_cb
08-29 10:13:12.070  5864  5884 I bt_hci  : sco_config_callback postload finished.
,08-29 10:13:12.073  5864  5880 D bt_bte_conf: Device ID record 1 : primary
08-29 10:13:12.073  5864  5880 D bt_bte_conf:   vendorId            = 000f
08-29 10:13:12.073  5864  5880 D bt_bte_conf:   vendorIdSource      = 0001
08-29 10:13:12.073  5864  5880 D bt_bte_conf:   product             = 1200
08-29 10:13:12.073  5864  5880 D bt_bte_conf:   version             = 1436
08-29 10:13:12.073  5864  5880 D bt_bte_conf:   clientExecutableURL = 
08-29 10:13:12.073  5864  5880 D bt_bte_conf:   serviceDescription  = 
08-29 10:13:12.073  5864  5880 D bt_bte_conf:   documentationURL    = 
08-29 10:13:12.074  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:12.074  5864  5880 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 10:13:12.074  5864  5877 D bt_stack_manager: event_start_up_stack finished
08-29 10:13:12.076  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 10:13:12.077  5864  5876 D BluetoothAdapterProperties: Setting state to 15
08-29 10:13:12.077  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 10:13:12.078  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:12.078  5864  5876 I BluetoothAdapterState: Entering BleOnState
08-29 10:13:12.082  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:12.082  5864  5884 I bt_vendor: low_power_mode_cb
,08-29 10:13:12.083  5864  5876 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 10:13:12.084  5864  5876 D BluetoothAdapterProperties: Setting state to 11
08-29 10:13:12.084  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 10:13:12.090  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:12.092  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:12.092  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:12.093  5864  5864 D HeadsetService: Received start request. Starting profile...
08-29 10:13:12.095  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:12.098  5864  5864 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 10:13:12.098  5864  5864 D HeadsetStateMachine: make
,08-29 10:13:12.102  5864  5876 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:13:12.107  5864  5864 D HeadsetStateMachine: max_hf_connections = 1
,08-29 10:13:12.107  5864  5864 I bt_bluedroid: get_profile_interface handsfree
08-29 10:13:12.107  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 10:13:12.108  5864  5880 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 10:13:12.111  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:12.111  5864  5864 D A2dpService: Received start request. Starting profile...
,08-29 10:13:12.112  5864  5864 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 10:13:12.112  5864  5864 I bt_bluedroid: get_profile_interface avrcp
,08-29 10:13:12.118  5864  5864 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 10:13:12.118  5864  5864 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:13:12.118  5864  5864 D A2dpStateMachine: make
08-29 10:13:12.119  5864  5864 I bt_bluedroid: get_profile_interface a2dp
,08-29 10:13:12.120  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 10:13:12.121  5864  5895 D A2dpStateMachine: Enter Disconnected: -2
,08-29 10:13:12.122  5864  5864 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 10:13:12.123  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:12.123  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:13:12.126  5699  5699 D BluetoothInputDevice: Proxy object connected
,08-29 10:13:12.126  5864  5864 D HidService: Received start request. Starting profile...
08-29 10:13:12.126  5864  5864 I bt_bluedroid: get_profile_interface hidhost
08-29 10:13:12.126  5699  5699 D HidProfile: Bluetooth service connected
08-29 10:13:12.126  5864  5864 D HidService: setHidService(): set to: null
08-29 10:13:12.126  5864  5880 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f282d9
08-29 10:13:12.127  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 10:13:12.127  5864  5864 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 10:13:12.128  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:12.128  5864  5864 D HealthService: Received start request. Starting profile...
,08-29 10:13:12.130  5864  5864 I bt_bluedroid: get_profile_interface health
,08-29 10:13:12.130  5864  5864 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 10:13:12.131  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:12.132  5864  5864 D PanService: Received start request. Starting profile...
08-29 10:13:12.132  5699  5699 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 10:13:12.132  5864  5864 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:13:12.132  5864  5864 I bt_bluedroid: get_profile_interface pan
08-29 10:13:12.133  5864  5880 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 10:13:12.133  5699  5699 D PanProfile: Bluetooth service connected
,08-29 10:13:12.135  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:12.136  5864  5864 D BluetoothMapService: Received start request. Starting profile...
08-29 10:13:12.136  5864  5864 D BluetoothMapService: start()
08-29 10:13:12.136  5699  5699 D BluetoothMap: Proxy object connected
08-29 10:13:12.137  5699  5699 D MapProfile: Bluetooth service connected
08-29 10:13:12.137  5699  5699 D BluetoothMap: getConnectedDevices()
08-29 10:13:12.137  5699  5699 D BluetoothMap: Bluetooth is Not enabled
,08-29 10:13:12.139  5864  5864 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 10:13:12.139  5864  5864 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 10:13:12.140  5864  5864 D BluetoothMapAppObserver: createReceiver()
,08-29 10:13:12.141  5864  5864 D BluetoothMapAppObserver: initObservers()
,08-29 10:13:12.141  5864  5864 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 10:13:12.147  5864  5864 V SapService: SapBinder()
,08-29 10:13:12.147  5864  5864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:12.147  5864  5864 D SapService: Received start request. Starting profile...
08-29 10:13:12.147  5864  5864 V SapService: start()
,08-29 10:13:12.150  5864  5864 V BluetoothAdapterState: isTurningOff()=false
,08-29 10:13:12.150  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:12.150  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:12.150  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:12.151  5864  5893 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isTurningOn()=true
,08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:12.151  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:12.152  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:12.153  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:12.153  5864  5864 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:12.153  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:12.153  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:12.154  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 10:13:12.154  5864  5876 D BluetoothAdapterProperties: ScanMode =  20
,08-29 10:13:12.154  5864  5876 D BluetoothAdapterProperties: State =  11
,08-29 10:13:12.155  5864  5880 D BluetoothAdapterProperties: Scan Mode:21
,08-29 10:13:12.155  5864  5880 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:13:12.156  5864  5876 D BluetoothAdapterProperties: Setting state to 12
08-29 10:13:12.156  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 10:13:12.157  5864  5876 I BluetoothAdapterState: Entering OnState
08-29 10:13:12.157  5699  5709 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:13:12.157  3207  3405 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:12.158  3207  3832 D BluetoothPan: onBluetoothStateChange on: true
,08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:12.158  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:12.159   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:13:12.159  3207  3207 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:13:12.159  3207  3207 D PanProfile: Bluetooth service connected
08-29 10:13:12.160   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:12.160  5699  5710 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:13:12.161   929   929 D BluetoothA2dp: Proxy object connected
08-29 10:13:12.161  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:12.161  3207  3220 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 10:13:12.163  3207  3832 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:13:12.163  3207  3207 D BluetoothMap: Proxy object connected
08-29 10:13:12.163  3207  3207 D MapProfile: Bluetooth service connected
08-29 10:13:12.163  3207  3207 D BluetoothMap: getConnectedDevices()
08-29 10:13:12.165   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:12.165   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:12.165  3589  3606 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:12.165  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:12.165  3207  3219 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 10:13:12.168  5864  5864 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 10:13:12.168  5864  5864 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 10:13:12.169  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:12.170  3207  3207 D BluetoothInputDevice: Proxy object connected
08-29 10:13:12.170  3207  3207 D HidProfile: Bluetooth service connected
08-29 10:13:12.170  5699  5709 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:13:12.170  5864  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:13:12.170  5699  5710 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:13:12.170  3207  3220 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:13:12.173  5864  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:12.173  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:13:12.173  3207  3207 D BluetoothA2dp: Proxy object connected
,08-29 10:13:12.174   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 10:13:12.177  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:13:12.178  5864  5864 D ObexServerSockets: Succeed to create listening sockets 
,08-29 10:13:12.178  5864  5864 D ObexServerSockets0: startAccept()
08-29 10:13:12.178  5864  5864 D ObexServerSockets0: prepareForNewConnect()
,08-29 10:13:12.179  5699  5699 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 10:13:12.179  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:12.180  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:12.181  5864  5864 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 10:13:12.181  5864  5864 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 10:13:12.181   605   605 I ServiceManager: Waiting for service AtCmdFwd...
08-29 10:13:12.181  5864  5864 D BluetoothMapService: onReceive
08-29 10:13:12.181  5864  5904 D ObexServerSockets0: Accepting socket connection...
08-29 10:13:12.181  5864  5864 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:13:12.181  5864  5864 D BluetoothMapService: STATE_ON
,08-29 10:13:12.181  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:12.182  5864  5905 D ObexServerSockets0: Accepting socket connection...
,08-29 10:13:12.184  5864  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:13:12.185  5864  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 10:13:12.185  5864  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 10:13:12.186  5699  5699 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 10:13:12.192  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:13:12.194  5699  5699 D BluetoothA2dp: Proxy object connected
,08-29 10:13:12.197  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 10:13:12.201  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:13:12.204  5699  5699 D BluetoothPbap: Proxy object connected
,08-29 10:13:12.205  5699  5699 D PbapServerProfile: Bluetooth service connected
,08-29 10:13:12.209  3207  3207 D BluetoothPbap: Proxy object connected
,08-29 10:13:12.209  3207  3207 D PbapServerProfile: Bluetooth service connected
,08-29 10:13:12.209  5864  5864 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 10:13:12.209  5864  5864 D ObexServerSockets0: prepareForNewConnect()
08-29 10:13:12.210  5864  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:13:12.224  5864  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:13:12.225  5864  5914 I BtOppRfcommListener: Accept thread started.
,08-29 10:13:12.259   929   929 D BluetoothHeadset: Proxy object connected
,08-29 10:13:12.259   929   929 D BluetoothHeadset: Proxy object connected
08-29 10:13:12.259   929   946 D BluetoothHeadset: Proxy object connected
08-29 10:13:12.259  3589  3607 D BluetoothHeadset: Proxy object connected
08-29 10:13:12.259   929   929 D BluetoothHeadset: Proxy object connected
,08-29 10:13:12.260  3207  3832 D BluetoothHeadset: Proxy object connected
08-29 10:13:12.260  3207  3207 D HeadsetProfile: Bluetooth service connected
,08-29 10:13:12.264   929   946 D BluetoothHeadset: Proxy object connected
,08-29 10:13:12.264   929   946 D BluetoothHeadset: Proxy object connected
,08-29 10:13:12.266  3589  3833 D BluetoothHeadset: Proxy object connected
,08-29 10:13:12.289  5699  5710 D BluetoothHeadset: Proxy object connected
,08-29 10:13:12.289  5699  5699 D HeadsetProfile: Bluetooth service connected
,08-29 10:13:13.182   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:13.966   929  3069 D ConnectivityService: handlePromptUnvalidated 101
,08-29 10:13:14.182   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:15.183   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:16.089  5864  5876 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 10:13:16.089  5864  5876 D BluetoothAdapterProperties: Setting state to 13
,08-29 10:13:16.089  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 10:13:16.091  5864  5876 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 10:13:16.092  5864  5876 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:13:16.095  5864  5864 D BluetoothMapService: onReceive
,08-29 10:13:16.095  5864  5864 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:13:16.095  5864  5864 D BluetoothMapService: STATE_TURNING_OFF
,08-29 10:13:16.096  5864  5864 D BluetoothMapService: MAP Service closeService in
08-29 10:13:16.096  5864  5864 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 10:13:16.096  5864  5864 D ObexServerSockets0: shutdown(block = true)
08-29 10:13:16.097  5864  5864 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:13:16.097  5864  5904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 10:13:16.097  5864  5864 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 10:13:16.097  5864  5905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 10:13:16.097  5864  5889 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 10:13:16.100  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:16.100  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:16.101  5864  5864 I BtOppRfcommListener: stopping Accept Thread
08-29 10:13:16.102  5864  5914 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:13:16.102  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:13:16.102  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:16.103  5864  5914 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 10:13:16.103  5864  5880 D BluetoothAdapterProperties: Scan Mode:20
,08-29 10:13:16.103  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 10:13:16.105  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:16.105  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:16.106  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:16.106  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:16.107  5864  5864 D HeadsetService: Received stop request...Stopping profile...
08-29 10:13:16.107  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:13:16.110  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:16.110  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:16.111  5646  5646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:13:16.112  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:16.113  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.115  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.115   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 10:13:16.115   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 10:13:16.115  5699  5709 D BluetoothHeadset: Proxy object disconnected
08-29 10:13:16.116  3589  3606 D BluetoothHeadset: Proxy object disconnected
,08-29 10:13:16.116  5864  5864 D A2dpService: Received stop request...Stopping profile...
08-29 10:13:16.116  5864  5895 D A2dpStateMachine: Exit Disconnected: -1
08-29 10:13:16.116  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.117   929   929 D BluetoothHeadset: Proxy object disconnected
08-29 10:13:16.117  3207  3832 D BluetoothHeadset: Proxy object disconnected
08-29 10:13:16.118   929   929 D BluetoothA2dp: Proxy object disconnected
08-29 10:13:16.119  5864  5864 D HidService: Received stop request...Stopping profile...
08-29 10:13:16.119  5864  5864 D HidService: Stopping Bluetooth HidService
08-29 10:13:16.120  5864  5864 D HealthService: Received stop request...Stopping profile...
08-29 10:13:16.121  3207  3207 D HeadsetProfile: Bluetooth service disconnected
08-29 10:13:16.121  3207  3207 D BluetoothA2dp: Proxy object disconnected
08-29 10:13:16.121  3207  3207 D BluetoothInputDevice: Proxy object disconnected
08-29 10:13:16.121  3207  3207 D HidProfile: Bluetooth service disconnected
08-29 10:13:16.122  5864  5864 D PanService: Received stop request...Stopping profile...
08-29 10:13:16.122  3207  3207 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 10:13:16.122  3207  3207 D PanProfile: Bluetooth service disconnected
08-29 10:13:16.123  5864  5864 D BluetoothMapService: Received stop request...Stopping profile...
08-29 10:13:16.123  5864  5864 D BluetoothMapService: stop()
08-29 10:13:16.123  5864  5864 D BluetoothMapAppObserver: deinitObservers()
08-29 10:13:16.123  5699  5699 D DockEventReceiver: finishStartingService: stopping service
08-29 10:13:16.123  5864  5864 D BluetoothMapAppObserver: removeReceiver()
08-29 10:13:16.124  5699  5699 D HeadsetProfile: Bluetooth service disconnected
08-29 10:13:16.125  5699  5699 D BluetoothA2dp: Proxy object disconnected
08-29 10:13:16.125  3207  3207 D BluetoothMap: Proxy object disconnected
08-29 10:13:16.125  3207  3207 D MapProfile: Bluetooth service disconnected
08-29 10:13:16.125  5699  5699 D BluetoothInputDevice: Proxy object disconnected
08-29 10:13:16.125  5699  5699 D HidProfile: Bluetooth service disconnected
08-29 10:13:16.125  5864  5864 D SapService: Received stop request...Stopping profile...
08-29 10:13:16.125  5864  5864 V SapService: stop()
,08-29 10:13:16.125  5699  5699 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:13:16.125  5699  5699 D PanProfile: Bluetooth service disconnected
08-29 10:13:16.125  5699  5699 D BluetoothMap: Proxy object disconnected
08-29 10:13:16.126  5699  5699 D MapProfile: Bluetooth service disconnected
08-29 10:13:16.127  5864  5864 V BluetoothAdapterState: isTurningOff()=true
08-29 10:13:16.128  5864  5864 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:13:16.128  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.128  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:16.129  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:13:16.130  5864  5864 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:13:16.130  5864  5864 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 10:13:16.130  5864  5887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:13:16.130  5864  5887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:13:16.130  5864  5864 V BluetoothAdapterState: isTurningOff()=true
08-29 10:13:16.130  5864  5887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:13:16.130  5864  5864 V BluetoothAdapterState: isTurningOn()=false
,08-29 10:13:16.131  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.131  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:16.131  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 10:13:16.131  5864  5880 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 10:13:16.132  5864  5887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:13:16.132  5864  5864 V BluetoothAdapterState: isTurningOff()=true
08-29 10:13:16.132  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:16.132  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.132  5864  5887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:13:16.132  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:16.132  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 10:13:16.132  5864  5864 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 10:13:16.132  5864  5887 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:13:16.132  5864  5887 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:13:16.132  5864  5864 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:13:16.132  5864  5887 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:13:16.132  5864  5880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 10:13:16.132  5864  5887 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:13:16.132  5864  5864 V BluetoothAdapterState: isTurningOff()=true
08-29 10:13:16.133  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:16.133  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.133  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:16.133  5864  5864 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:13:16.133  5864  5880 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 10:13:16.133  5864  5864 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:13:16.133  5864  5864 V BluetoothAdapterState: isTurningOff()=true
,08-29 10:13:16.133  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:16.134  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.134  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:16.134  5864  5864 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:13:16.134  5864  5864 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 10:13:16.135  5864  5864 D BluetoothMapService: MAP Service closeService in
08-29 10:13:16.135  5864  5864 V BluetoothAdapterState: isTurningOff()=true
08-29 10:13:16.135  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:16.135  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.135  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:16.135  5864  5864 D BluetoothMapService: cleanup()
08-29 10:13:16.135  5864  5864 D BluetoothMapService: MAP Service closeService in
08-29 10:13:16.135  5864  5864 V BluetoothAdapterState: isTurningOff()=true
08-29 10:13:16.136  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:16.136  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.136  5864  5864 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:16.136  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 10:13:16.136  5864  5876 D BluetoothAdapterProperties: Setting state to 15
08-29 10:13:16.136  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 10:13:16.137  5864  5876 I BluetoothAdapterState: Entering BleOnState
,08-29 10:13:16.137  5699  5699 D BluetoothPbap: Proxy object disconnected
08-29 10:13:16.137  5699  5710 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:13:16.138  3207  3207 D BluetoothPbap: Proxy object disconnected
,08-29 10:13:16.138  3207  3207 D PbapServerProfile: Bluetooth service disconnected
08-29 10:13:16.138  3207  3220 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:13:16.139  3207  3832 D BluetoothPan: onBluetoothStateChange on: false
08-29 10:13:16.140  5699  5709 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:13:16.140   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:13:16.140   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:13:16.140  5699  5710 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:13:16.141  3207  3219 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:13:16.141  3207  3405 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:13:16.142   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:13:16.142   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:13:16.142  3589  5735 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 10:13:16.142  3207  3220 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:13:16.143  5699  5709 D BluetoothPan: onBluetoothStateChange on: false
08-29 10:13:16.143  5699  5710 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:13:16.144  5699  5709 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:13:16.145  3207  3832 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:13:16.146  5864  5876 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 10:13:16.146  5864  5876 D BluetoothAdapterProperties: Setting state to 16
08-29 10:13:16.146  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 10:13:16.146  5864  5876 D BluetoothAdapterProperties: onBleDisable
08-29 10:13:16.146  5864  5876 I BluetoothAdapterState: Entering PendingCommandState
08-29 10:13:16.146  5864  5877 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 10:13:16.137  5699  5699 D PbapServerProfile: Bluetooth service disconnected
08-29 10:13:16.147  5864  5887 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 10:13:16.148  5864  5887 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 10:13:16.149  5864  5880 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:13:16.149  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.149  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 10:13:16.152  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.155  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:13:16.156  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.157  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.157  5699  5699 D DockEventReceiver: finishStartingService: stopping service
08-29 10:13:16.158  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:16.159  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:16.184   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:13:16.357  5864  5880 I bt_hci  : shut_down
,08-29 10:13:16.362  5864  5884 D bt_hwcfg: hw_epilog_process
,08-29 10:13:16.362  5864  5884 I bt_vendor: low_power_mode_cb
,08-29 10:13:16.364  5864  5884 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 10:13:16.364  5864  5884 I bt_vendor: epilog_cb
08-29 10:13:16.364  5864  5884 I bt_hci  : epilog_finished_callback
,08-29 10:13:16.366  5864  5880 I bt_hci_h4: hal_close
08-29 10:13:16.366  5864  5880 I bt_userial_vendor: device fd = 51 close
,08-29 10:13:16.481  5864  5877 D bt_stack_manager: event_shut_down_stack finished.
,08-29 10:13:16.482  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 10:13:16.486  5864  5876 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 10:13:16.486  5864  5864 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:13:16.487  5864  5864 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:13:16.487  5864  5864 D BtGatt.GattService: stop()
,08-29 10:13:16.488  5864  5864 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 10:13:16.491  5864  5864 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:16.491  5864  5864 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:16.491  5864  5864 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:16.491  5864  5864 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 10:13:16.492  5864  5876 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 10:13:16.492  5864  5876 D BluetoothAdapterProperties: Setting state to 10
08-29 10:13:16.493  5864  5876 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 10:13:16.494  5864  5876 I BluetoothAdapterState: Entering OffState
08-29 10:13:16.495   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 10:13:16.511  5864  5864 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 10:13:16.511  5864  5864 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 10:13:16.511  5864  5877 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 10:13:16.514  5864  5864 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 10:13:16.518  5864  5877 D bt_stack_manager: event_clean_up_stack finished.
,08-29 10:13:16.520  5864  5864 I art     : System.exit called, status: 0
,08-29 10:13:16.520  5864  5864 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 10:13:16.557   929  3517 I ActivityManager: Process com.android.bluetooth (pid 5864) has died
,08-29 10:13:21.086  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:13:21.087  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:21.091  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:21.091  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbc14e0 removed from the list
08-29 10:13:21.091  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:13:21.091  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:21.091  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:21.093  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:13:21.094  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f665e added. We now have 4 listener(s)
08-29 10:13:21.095  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:13:21.096  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:21.097  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f665e removed from the list
08-29 10:13:21.097  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:13:21.097  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:21.097  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:21.099  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:13:21.099  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db36a3f added. We now have 4 listener(s)
08-29 10:13:21.099  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:13:21.184   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:22.186   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:23.187   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:24.188   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:25.189   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:26.109  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:26.144   929   946 I ActivityManager: Start proc 5922:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 10:13:26.190   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:13:26.237  5922  5922 D AdapterServiceConfig: Adding HeadsetService
,08-29 10:13:26.237  5922  5922 D AdapterServiceConfig: Adding A2dpService
08-29 10:13:26.237  5922  5922 D AdapterServiceConfig: Adding HidService
08-29 10:13:26.238  5922  5922 D AdapterServiceConfig: Adding HealthService
08-29 10:13:26.238  5922  5922 D AdapterServiceConfig: Adding PanService
08-29 10:13:26.238  5922  5922 D AdapterServiceConfig: Adding GattService
08-29 10:13:26.238  5922  5922 D AdapterServiceConfig: Adding BluetoothMapService
08-29 10:13:26.238  5922  5922 D AdapterServiceConfig: Adding SapService
,08-29 10:13:26.249   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75f4b5d:true
,08-29 10:13:26.249  5922  5922 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 10:13:26.252  5922  5922 I bt_bluedroid: init
,08-29 10:13:26.252  5922  5934 I BluetoothAdapterState: Entering OffState
,08-29 10:13:26.255  5922  5935 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 10:13:26.255  5922  5935 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:13:26.255  5922  5935 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 10:13:26.255  5922  5935 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 10:13:26.256  5922  5922 I bt_bluedroid: get_profile_interface socket
,08-29 10:13:26.258  5922  5938 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 10:13:26.259  5922  5922 I bt_bluedroid: get_profile_interface sdp
08-29 10:13:26.260  5922  5938 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 10:13:26.262  5922  5933 I bt_bluedroid: config_hci_snoop_log
08-29 10:13:26.263   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 10:13:26.268  5922  5934 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 10:13:26.268  5922  5934 D BluetoothAdapterProperties: Setting state to 14
08-29 10:13:26.268  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 10:13:26.269  5922  5934 D BluetoothBondStateMachine: make
,08-29 10:13:26.272  5922  5939 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 10:13:26.274  5922  5934 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:13:26.275  5922  5922 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 10:13:26.278  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:26.279  5922  5922 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:13:26.279  5922  5922 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:13:26.279  5922  5922 D BtGatt.GattService: start()
08-29 10:13:26.279  5922  5922 I bt_bluedroid: get_profile_interface gatt
,08-29 10:13:26.280  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:26.281  5922  5922 D BtGatt.AdvertiseManager: advertise manager created
,08-29 10:13:26.286  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:26.287  5922  5922 V BluetoothAdapterState: isTurningOn()=false
08-29 10:13:26.287  5922  5922 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 10:13:26.287  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:26.287  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 10:13:26.287  5922  5934 I bt_bluedroid: enable
08-29 10:13:26.288  5922  5935 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 10:13:26.288  5922  5935 I bt_hci  : start_up
,08-29 10:13:26.294  5922  5935 I bt_vendor: alloc value 0xf3fc904d
08-29 10:13:26.294  5922  5935 I bt_vendor: init
08-29 10:13:26.294  5922  5935 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 10:13:26.294  5922  5935 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 10:13:26.416  5922  5935 D bt_hci  : start_up starting async portion
,08-29 10:13:26.417  5922  5942 I bt_hci  : event_finish_startup
,08-29 10:13:26.417  5922  5942 I bt_hci_h4: hal_open
08-29 10:13:26.417  5922  5942 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 10:13:26.408  5943  5943 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 10:13:26.422  5922  5942 I bt_userial_vendor: device fd = 51 open
,08-29 10:13:26.438  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 10:13:26.442  5922  5942 D bt_hwcfg: Chipset BCM4358A3
,08-29 10:13:26.443  5922  5942 D bt_hwcfg: Target name = [BCM4358A3]
08-29 10:13:26.443  5922  5942 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 10:13:26.953  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 10:13:26.954  5922  5942 D bt_hwcfg: Settlement delay -- 100 ms
08-29 10:13:26.954  5922  5942 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 10:13:27.088  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
08-29 10:13:27.089  5922  5942 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 10:13:27.090  5922  5942 I bt_hwcfg: vendor lib fwcfg completed
,08-29 10:13:27.090  5922  5942 I bt_vendor: firmware callback
08-29 10:13:27.090  5922  5942 I bt_hci  : firmware_config_callback
,08-29 10:13:27.100  5922  5945 I bt_btu  : btu_task pending for preload complete event
08-29 10:13:27.100  5922  5945 I bt_btu_task: Bluetooth chip preload is complete
,08-29 10:13:27.100  5922  5945 I bt_btu  : btu_task received preload complete event
08-29 10:13:27.106  5922  5945 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 10:13:27.107  5922  5945 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 10:13:27.107  5922  5945 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 10:13:27.107  5922  5945 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:13:27.107  5922  5945 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 10:13:27.107  5922  5945 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 10:13:27.107  5922  5945 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 10:13:27.107  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:13:27.108  5922  5945 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 10:13:27.108  5922  5945 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:13:27.108  5922  5945 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 10:13:27.108  5922  5945 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:13:27.108  5922  5945 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:13:27.108  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 10:13:27.108  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 10:13:27.202  5922  5945 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f46c99
,08-29 10:13:27.202  5922  5945 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f46c99 
,08-29 10:13:27.235  5922  5938 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 10:13:27.238  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 10:13:27.238  5922  5938 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 10:13:27.240  5922  5938 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 10:13:27.243  5922  5938 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:13:27.243  5922  5938 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:13:27.244  5922  5938 D bt_hci  : do_postload posting postload work item
08-29 10:13:27.244  5922  5942 I bt_hci  : event_postload
08-29 10:13:27.244  5922  5942 I bt_vendor: sco_config_cb
08-29 10:13:27.244  5922  5942 I bt_hci  : sco_config_callback postload finished.
,08-29 10:13:27.245  5922  5938 D bt_bte_conf: Device ID record 1 : primary
08-29 10:13:27.245  5922  5938 D bt_bte_conf:   vendorId            = 000f
,08-29 10:13:27.245  5922  5938 D bt_bte_conf:   vendorIdSource      = 0001
08-29 10:13:27.245  5922  5938 D bt_bte_conf:   product             = 1200
08-29 10:13:27.245  5922  5938 D bt_bte_conf:   version             = 1436
08-29 10:13:27.245  5922  5938 D bt_bte_conf:   clientExecutableURL = 
08-29 10:13:27.246  5922  5938 D bt_bte_conf:   serviceDescription  = 
08-29 10:13:27.246  5922  5938 D bt_bte_conf:   documentationURL    = 
08-29 10:13:27.246  5922  5938 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 10:13:27.246  5922  5935 D bt_stack_manager: event_start_up_stack finished
,08-29 10:13:27.246  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 10:13:27.247  5922  5934 D BluetoothAdapterProperties: Setting state to 15
08-29 10:13:27.247  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 10:13:27.248  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:27.248  5922  5934 I BluetoothAdapterState: Entering BleOnState
,08-29 10:13:27.251  5922  5934 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 10:13:27.252  5922  5942 I bt_vendor: low_power_mode_cb
08-29 10:13:27.252  5922  5934 D BluetoothAdapterProperties: Setting state to 11
08-29 10:13:27.252  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 10:13:27.252  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:27.257  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:27.259  5922  5922 D HeadsetService: Received start request. Starting profile...
,08-29 10:13:27.261  5922  5922 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:13:27.262  5922  5922 D HeadsetStateMachine: make
,08-29 10:13:27.267  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:27.269  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:27.271  5922  5922 D HeadsetStateMachine: max_hf_connections = 1
08-29 10:13:27.271  5922  5922 I bt_bluedroid: get_profile_interface handsfree
08-29 10:13:27.271  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 10:13:27.272  5922  5934 I BluetoothAdapterState: Entering PendingCommandState
,08-29 10:13:27.276  5922  5938 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 10:13:27.277  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:27.277  5922  5922 D A2dpService: Received start request. Starting profile...
08-29 10:13:27.278  5922  5922 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 10:13:27.278  5922  5922 I bt_bluedroid: get_profile_interface avrcp
,08-29 10:13:27.283  5922  5922 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 10:13:27.284  5922  5922 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:13:27.284  5922  5922 D A2dpStateMachine: make
,08-29 10:13:27.285  5922  5922 I bt_bluedroid: get_profile_interface a2dp
,08-29 10:13:27.286  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 10:13:27.287  5922  5954 D A2dpStateMachine: Enter Disconnected: -2
08-29 10:13:27.287  5922  5922 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 10:13:27.288  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:27.289  5922  5922 D HidService: Received start request. Starting profile...
08-29 10:13:27.289  5922  5922 I bt_bluedroid: get_profile_interface hidhost
08-29 10:13:27.289  5922  5922 D HidService: setHidService(): set to: null
08-29 10:13:27.289  5922  5938 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f282d9
08-29 10:13:27.289  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 10:13:27.290  5922  5922 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 10:13:27.290  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:27.291  5922  5922 D HealthService: Received start request. Starting profile...
,08-29 10:13:27.292  5922  5922 I bt_bluedroid: get_profile_interface health
08-29 10:13:27.293  5922  5922 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 10:13:27.294  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:27.294  5922  5922 D PanService: Received start request. Starting profile...
08-29 10:13:27.295  5922  5922 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:13:27.295  5922  5922 I bt_bluedroid: get_profile_interface pan
08-29 10:13:27.295  5922  5938 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 10:13:27.298  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
08-29 10:13:27.298  5922  5922 D BluetoothMapService: Received start request. Starting profile...
08-29 10:13:27.299  5922  5922 D BluetoothMapService: start()
,08-29 10:13:27.301  5922  5922 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 10:13:27.302  5922  5922 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 10:13:27.302  5922  5922 D BluetoothMapAppObserver: createReceiver()
,08-29 10:13:27.304  5922  5922 D BluetoothMapAppObserver: initObservers()
08-29 10:13:27.304  5922  5922 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 10:13:27.311  5922  5922 V SapService: SapBinder()
08-29 10:13:27.311  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:27.312  5922  5922 D SapService: Received start request. Starting profile...
08-29 10:13:27.312  5922  5922 V SapService: start()
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:27.315  5922  5951 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:27.315  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:27.316  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
08-29 10:13:27.317  5922  5922 V BluetoothAdapterState: isTurningOff()=false
08-29 10:13:27.317  5922  5922 V BluetoothAdapterState: isTurningOn()=true
08-29 10:13:27.317  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
08-29 10:13:27.317  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 10:13:27.317  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:13:27.317  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 10:13:27.317  5922  5934 D BluetoothAdapterProperties: ScanMode =  20
08-29 10:13:27.317  5922  5934 D BluetoothAdapterProperties: State =  11
08-29 10:13:27.318  5922  5934 D BluetoothAdapterProperties: Setting state to 12
08-29 10:13:27.318  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 10:13:27.318  5699  5710 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:13:27.318  5922  5934 I BluetoothAdapterState: Entering OnState
,08-29 10:13:27.322  3207  3405 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 10:13:27.324  3207  3219 D BluetoothPan: onBluetoothStateChange on: true
08-29 10:13:27.325  5922  5938 D BluetoothAdapterProperties: Scan Mode:21
08-29 10:13:27.325  5922  5938 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:13:27.326  5699  5710 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:27.326   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:13:27.327   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:27.327  5699  5709 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:13:27.327  3207  3207 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:13:27.328  3207  3207 D PanProfile: Bluetooth service connected
08-29 10:13:27.328   929   929 D BluetoothA2dp: Proxy object connected
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:27.329  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:27.329  3207  3220 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:13:27.331  5922  5922 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 10:13:27.331  3207  3405 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 10:13:27.331  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:27.331  5922  5922 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 10:13:27.332  5699  5699 D BluetoothInputDevice: Proxy object connected
08-29 10:13:27.332  5699  5699 D HidProfile: Bluetooth service connected
,08-29 10:13:27.334  5922  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:13:27.335   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:27.335   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:27.335  3589  5735 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 10:13:27.335  3207  3219 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 10:13:27.337  5699  5710 D BluetoothPan: onBluetoothStateChange on: true
,08-29 10:13:27.337  3207  3207 D BluetoothInputDevice: Proxy object connected
08-29 10:13:27.337  5922  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:13:27.337  3207  3207 D HidProfile: Bluetooth service connected
,08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:27.338  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:27.338  5922  5922 D ObexServerSockets: Succeed to create listening sockets 
08-29 10:13:27.339  5922  5922 D ObexServerSockets0: startAccept()
08-29 10:13:27.339  5922  5922 D ObexServerSockets0: prepareForNewConnect()
08-29 10:13:27.339  5699  5709 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:13:27.340  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:13:27.341  5922  5922 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 10:13:27.341  5922  5922 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 10:13:27.342  5922  5960 D ObexServerSockets0: Accepting socket connection...
08-29 10:13:27.342  5922  5961 D ObexServerSockets0: Accepting socket connection...
08-29 10:13:27.343  5699  5710 D BluetoothMap: onBluetoothStateChange: up=true
08-29 10:13:27.343  3207  3207 D BluetoothMap: Proxy object connected
08-29 10:13:27.343  3207  3207 D MapProfile: Bluetooth service connected
08-29 10:13:27.343  3207  3207 D BluetoothMap: getConnectedDevices()
08-29 10:13:27.345  3207  3405 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:13:27.347  3207  3207 D BluetoothA2dp: Proxy object connected
08-29 10:13:27.347  5699  5699 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:13:27.347  5699  5699 D PanProfile: Bluetooth service connected
,08-29 10:13:27.347  5699  5699 D BluetoothA2dp: Proxy object connected
08-29 10:13:27.348  5922  5922 D BluetoothMapService: onReceive
08-29 10:13:27.348  5922  5922 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:13:27.348  5922  5922 D BluetoothMapService: STATE_ON
08-29 10:13:27.349   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 10:13:27.350  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:27.351  5699  5699 D BluetoothMap: Proxy object connected
08-29 10:13:27.351  5699  5699 D MapProfile: Bluetooth service connected
08-29 10:13:27.352  5699  5699 D BluetoothMap: getConnectedDevices()
08-29 10:13:27.353  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:27.354  5922  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:13:27.355  5922  5963 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 10:13:27.355  5922  5963 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 10:13:27.358  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:13:27.364  3670  3670 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 10:13:27.364  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:13:27.371  5699  5699 D BluetoothPbap: Proxy object connected
,08-29 10:13:27.372  5699  5699 D PbapServerProfile: Bluetooth service connected
,08-29 10:13:27.375  5922  5922 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 10:13:27.375  5922  5922 D ObexServerSockets0: prepareForNewConnect()
08-29 10:13:27.376  5922  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:13:27.378  3207  3207 D BluetoothPbap: Proxy object connected
08-29 10:13:27.378  3207  3207 D PbapServerProfile: Bluetooth service connected
,08-29 10:13:27.392  5922  5971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:13:27.394  5922  5971 I BtOppRfcommListener: Accept thread started.
,08-29 10:13:27.424   929   929 D BluetoothHeadset: Proxy object connected
08-29 10:13:27.424   929   929 D BluetoothHeadset: Proxy object connected
,08-29 10:13:27.425  5699  5710 D BluetoothHeadset: Proxy object connected
08-29 10:13:27.425  3589  3607 D BluetoothHeadset: Proxy object connected
08-29 10:13:27.425   929   929 D BluetoothHeadset: Proxy object connected
,08-29 10:13:27.426  3207  3219 D BluetoothHeadset: Proxy object connected
08-29 10:13:27.426  3207  3207 D HeadsetProfile: Bluetooth service connected
08-29 10:13:27.427  5699  5959 D BluetoothHeadset: Proxy object connected
08-29 10:13:27.427   929   946 D BluetoothHeadset: Proxy object connected
08-29 10:13:27.427  5699  5699 D HeadsetProfile: Bluetooth service connected
,08-29 10:13:27.429  5699  5699 D HeadsetProfile: Bluetooth service connected
,08-29 10:13:27.434   929   946 D BluetoothHeadset: Proxy object connected
,08-29 10:13:27.434   929   946 D BluetoothHeadset: Proxy object connected
,08-29 10:13:27.436  3589  3833 D BluetoothHeadset: Proxy object connected
,08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:31.124  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:13:31.131  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:13:31.131  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:13:31.132  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db36a3f removed from the list
08-29 10:13:31.132  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:13:31.132  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:31.132  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:13:31.134  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:13:31.134  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7d9f0c added. We now have 4 listener(s)
08-29 10:13:31.134  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:13:31.136   929  3218 D WifiService: setWifiEnabled: false pid=5646, uid=10077
08-29 10:13:31.137   929  3218 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:13:36.145  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:36.147   929  3235 D WifiService: setWifiEnabled: true pid=5646, uid=10077
08-29 10:13:36.147   929  3235 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 10:13:36.158   507   923 D SoftapController: Softap fwReload - Ok
,08-29 10:13:36.162   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:36.162   507   923 D CommandListener: Trying to bring down wlan0
08-29 10:13:36.164   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:13:36.170   929  3067 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 10:13:36.191   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:36.835   929  3067 D wifi    : set interface wlan0 flags (UP)
08-29 10:13:36.841   929  3067 I WifiHAL : Initializing wifi
08-29 10:13:36.841   929  3067 I WifiHAL : Creating socket
08-29 10:13:36.842   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 10:13:36.846   929  3067 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 10:13:36.847   929  3067 D wifi    : Did set static halHandle = 0x7f63db59e0
08-29 10:13:36.847   929  3067 D wifi    : halHandle = 0x7f63db59e0, mVM = 0x7f801cd140, mCls = 0x14be
08-29 10:13:36.847   929  3067 D wifi    : array field set
08-29 10:13:36.847   929  3067 I WifiNative-HAL: interface[0] = wlan0
,08-29 10:13:36.851   929  5976 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547136166368
,08-29 10:13:36.851   929  5976 D wifi    : waitForHalEvents called, vm = 0x7f801cd140, obj = 0x14be, env = 0x7f64f847c0
,08-29 10:13:36.896  5977  5977 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 10:13:36.916  5977  5977 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:13:36.950   929  3067 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 10:13:36.958  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:36.960  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:37.007  5977  5977 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 10:13:37.007  5977  5977 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 10:13:37.027   929  3067 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:37.034  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:13:37.034   929  3067 D WifiConfigStore: loaded 0 passpoint configs
,08-29 10:13:37.035   929  3067 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:13:37.035   929  3067 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 10:13:37.036   929  3067 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 10:13:37.037   929  3067 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 10:13:37.037  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:13:37.037   929  3067 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 10:13:37.040   929  3067 D WifiNative-HAL: Setting external_sim to 1
08-29 10:13:37.041   929  3067 D wifi    : setting dfs flag to true, 0x7f6512ffc0
,08-29 10:13:37.041  4286  4286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:13:37.041  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:13:37.041   929  3067 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:13:37.042   929  3067 D wifi    : setting scan oui 0x7f6512ffc0
08-29 10:13:37.042   929  3067 D WifiHAL : Sending mac address OUI
,08-29 10:13:37.043  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:13:37.062   929  3067 E native  : do suspend true
,08-29 10:13:37.072   929  3067 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 10:13:37.072   929   929 D RttService: SCAN_AVAILABLE : 3
08-29 10:13:37.072   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 10:13:37.072   929  3132 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:13:37.073   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:37.080   929  3055 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,08-29 10:13:37.080   929  3055 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 10:13:37.089   929  3055 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 10:13:37.089   929  3055 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 10:13:37.096   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=370921 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=9 mControllerEnergyUsed=34 }
,08-29 10:13:37.192   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:38.193   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:39.194   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:40.195   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:40.309  5977  5977 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 10:13:40.340   929  3067 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-29 10:13:40.351   929  3067 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,08-29 10:13:40.351   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:13:40.367   929  3067 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,08-29 10:13:40.413   929  3067 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,08-29 10:13:40.756  5977  5977 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 10:13:40.790  5977  5977 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 10:13:40.792  5977  5977 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-29 10:13:40.803   929  3067 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:13:40.803   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:13:40.803   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 10:13:40.818   929  3067 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:13:40.830   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:40.836   929  3067 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 10:13:40.844   929  3067 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 10:13:40.856   929  5982 D DhcpClient: Receive thread started
,08-29 10:13:40.939   929  3067 E native  : do suspend false
,08-29 10:13:40.951   929  5981 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 10:13:40.964   929  5982 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-29 10:13:40.965   929  5981 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-29 10:13:40.967   929  5981 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,08-29 10:13:40.980   929  5982 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 10:13:40.981   929  5981 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 10:13:40.983   507   923 D CommandListener: Setting iface cfg
,08-29 10:13:40.992   929  3067 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 10:13:40.997   929  5981 D DhcpClient: Scheduling renewal in 86399s
,08-29 10:13:40.997   929  3067 E native  : do suspend true
,08-29 10:13:41.013   929  3067 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 10:13:41.015   929  3067 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 10:13:41.016   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 10:13:41.018   929  3069 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 10:13:41.026   929  3067 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 10:13:41.059   929  3069 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 10:13:41.060   929  3069 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 10:13:41.061   929  3069 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 10:13:41.062   929  3069 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 10:13:41.064   929  3069 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 10:13:41.070   929  3069 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 10:13:41.074   929  3069 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 10:13:41.075   929  3069 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 10:13:41.075   929  3069 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 10:13:41.075   929  3067 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 10:13:41.075   929  3069 D ConnectivityService:    accepting network in place of null
08-29 10:13:41.075   929  3067 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 10:13:41.075   929  3069 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 10:13:41.099   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:13:41.109   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=374934, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:13:41.120   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 10:13:41.123   929  3069 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 10:13:41.123   929  3069 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 10:13:41.124  3560  3773 W QCNEJ   : |CORE| network available: 102
,08-29 10:13:41.125   929  3069 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-29 10:13:41.126   929   946 D Tethering: MasterInitialState.processMessage what=3
08-29 10:13:41.128  3560  3773 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,08-29 10:13:41.129  3560  3773 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
08-29 10:13:41.130  3560  3773 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:41.135  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:13:41.138  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:41.142  5646  5646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:13:41.143  5646  5646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:41.144  4841  4883 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 10:13:41.144  4841  4883 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 10:13:41.144  4841  4883 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
08-29 10:13:41.145  4841  4883 E SarControlService: no key has been found,reset the power
,08-29 10:13:41.145  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 10:13:41.146  3924  3924 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 10:13:41.147  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 10:13:41.147  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 10:13:41.148  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:13:41.148  4905  4905 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 10:13:41.149  4841  4917 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 10:13:41.149  4841  4917 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
08-29 10:13:41.149  4841  4917 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 10:13:41.150  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 10:13:41.150  4905  4905 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 10:13:41.153  3924  3924 D SystemUpdateService: onCreate
08-29 10:13:41.155  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000f003000000000000ffffffff]
08-29 10:13:41.155  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 10:13:41.155  4905  4919 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,08-29 10:13:41.156  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:13:41.156  4841  4856 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
08-29 10:13:41.158  4905  4919 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d17f50 HexData = [00000000f103000000000000ffffffff]
08-29 10:13:41.158  4905  4919 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,08-29 10:13:41.159  4905  4919 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
08-29 10:13:41.159  4905  4905 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 10:13:41.159  4841  4858 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
08-29 10:13:41.159  3924  3924 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:41.160  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:13:41.162  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:41.162  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:41.163  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7d9f0c removed from the list
08-29 10:13:41.163  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:13:41.163  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:41.163  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:13:41.166  5646  5993 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-29 10:13:41.166  5646  5993 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 10:13:41.171  3924  3924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 10:13:41.177  3924  5992 I SystemUpdateService: active receiver: enabled
,08-29 10:13:41.178  3924  5351 I iu.UploadsManager: num queued entries: 0
,08-29 10:13:41.179  3924  5351 I iu.UploadsManager: num updated entries: 0
08-29 10:13:41.180  3924  5351 I iu.SyncManager: NEXT; no task
,08-29 10:13:41.182  3924  3924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 10:13:41.183  3924  3924 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 10:13:41.185  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 10:13:41.189  5764  5764 D SprintDMHelper: simOperator: 
08-29 10:13:41.189  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 10:13:41.196   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:13:41.217  3924  5992 I SystemUpdateService: showing system update notification
,08-29 10:13:41.228  3924  5992 V SystemUpdateService: retry (wakeup: false) in 3599950 ms
,08-29 10:13:41.231  3924  3924 D SystemUpdateService: onDestroy
,08-29 10:13:41.238   929  5979 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:812::200e
,08-29 10:13:41.319   929  5979 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:13:41 GMT], X-Android-Received-Millis=[1472480021319], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472480021287]}
,08-29 10:13:41.320   929  3069 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 10:13:41.320   929  3069 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 10:13:41.320   929  3069 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 10:13:41.321   929  3069 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 10:13:41.336  4286  5999 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 10:13:44.176  5646  6006 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-29 10:13:44.176  5646  5993 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-29 10:13:44.177  5646  5993 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 10:13:44.177  5646  6006 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 10:13:44.179  5646  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 10:13:44.179  5646  6006 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:13:44.180  5646  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:13:44.180  5646  6006 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:13:44.183  5646  6008 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Sender)
,08-29 10:13:44.184  5646  5993 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 10:13:44.187  5646  6006 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 10:13:44.189  5646  6009 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: IncomingSocketThread/Sender)
,08-29 10:13:44.191  5646  6010 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: OutgoingSocketThread/Receiver)
,08-29 10:13:44.192  5646  6011 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver)
08-29 10:13:44.193  5646  6011 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver)
,08-29 10:13:44.193  5646  6011 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-29 10:13:44.193  5646  6011 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-29 10:13:44.194  5646  6010 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: OutgoingSocketThread/Receiver)
,08-29 10:13:44.194  5646  6010 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 10:13:44.194  5646  6010 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-29 10:13:47.173  5646  5692 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 10:13:47.175  5646  5692 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 10:13:47.180  5646  5692 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7f5d967 Bundle[{}]
,08-29 10:13:47.182  5646  5692 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 10:13:47.182  5646  5692 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 10:13:47.183  5646  5692 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 10:13:47.185  5646  5692 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 10:13:47.186  5646  5692 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 10:13:47.187  5646  5692 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 10:13:47.192  5646  5692 I System.out: Running OutgoingSocketThread
,08-29 10:13:47.213  5646  6012 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-29 10:13:47.213  5646  6012 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 10:13:49.083   929  3069 D ConnectivityService: handlePromptUnvalidated 102
,08-29 10:13:50.223  5646  6012 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-29 10:13:50.223  5646  6012 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-29 10:13:50.224  5646  6012 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:13:50.225  5646  6012 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 10:13:50.226  5646  6012 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-29 10:13:50.227  5646  6013 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-29 10:13:50.227  5646  6013 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 10:13:50.227  5646  6015 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
,08-29 10:13:50.229  5646  6016 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Receiver)
08-29 10:13:50.230  5646  6016 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: OutgoingSocketThread/Receiver)
08-29 10:13:50.230  5646  6016 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 10:13:50.230  5646  6016 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-29 10:13:50.230  5646  6013 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:13:50.232  5646  6013 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 10:13:50.233  5646  6017 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
08-29 10:13:50.234  5646  6013 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-29 10:13:50.235  5646  6018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
,08-29 10:13:50.238  5646  6018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
08-29 10:13:50.239  5646  6018 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 10:13:50.239  5646  6018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-29 10:13:53.222  5646  5692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,08-29 10:13:53.223  5646  5692 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 10:13:53.223  5646  5692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,08-29 10:13:53.228  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:13:53.228  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a9055 added. We now have 3 listener(s)
08-29 10:13:53.231  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 10:13:53.231  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:13:53.231  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:13:53.231  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:13:53.231  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a78a6a added. We now have 4 listener(s)
,08-29 10:13:53.231  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:13:53.232  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:13:53.237  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:53.244  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:13:53.247  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:13:53.247  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:13:53.248  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:13:53.248  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:13:53.248  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:13:53.248  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:13:53.248  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:53.248  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:13:53.248  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:13:53.248  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a9055 removed from the list
08-29 10:13:53.248  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:53.248  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a78a6a removed from the list
,08-29 10:13:53.250  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:53.253  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:53.253  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:13:53.253  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:13:53.254  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:53.254  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:53.255  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:13:53.255  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:13:53.256  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:53.256  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a78a6a not in the list
08-29 10:13:53.256  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:53.256  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:53.257  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:13:53.257  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:13:53.257  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:53.257  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a78a6a not in the list
08-29 10:13:53.257  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:13:53.257  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:13:53.257  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:53.257  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3a9055 not in the list
08-29 10:13:53.258  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:13:53.258  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@deb9ff8 added. We now have 3 listener(s)
08-29 10:13:53.259  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:13:53.259  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:13:53.259  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:13:53.259  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:13:53.260  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e0dcd1 added. We now have 4 listener(s)
,08-29 10:13:53.260  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:13:53.260  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:13:53.264  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:53.268  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:13:53.270  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:53.270  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:13:53.270  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:13:53.270  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:13:53.270  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:13:53.270  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:13:53.270  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:13:53.273  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:53.275  5646  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:13:53.275  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:13:53.276  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:53.278  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:13:53.279  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:13:53.279  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:13:53.281  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:13:53.281  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:13:53.281  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:13:53.281  5646  5692 D BluetoothAdapter: STATE_ON
08-29 10:13:53.283  5922  5933 D BtGatt.GattService: registerClient() - UUID=4418a764-2ebe-4400-b2bf-aab9f9631c7c
08-29 10:13:53.284  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=4418a764-2ebe-4400-b2bf-aab9f9631c7c, clientIf=5
,08-29 10:13:53.285  5646  5657 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:13:53.286  5922  5932 D BtGatt.GattService: start scan with filters
08-29 10:13:53.289  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:13:53.290  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:13:53.290  5922  5941 D BtGatt.ScanManager: handling starting scan
08-29 10:13:53.290  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:13:53.290  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:13:53.291  5922  5941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@49bcf8b
,08-29 10:13:53.292  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:13:53.292  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:13:53.292  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:13:53.293  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:13:53.296  5646  5692 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:13:53.296  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:13:53.296  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:13:53.296  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:53.296  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:13:53.296  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:13:53.296  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:13:53.296  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:13:53.296  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:13:53.296  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:13:53.296  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:13:53.297  5646  5692 D BluetoothAdapter: STATE_ON
08-29 10:13:53.298  5922  5933 D BtGatt.GattService: stopScan() - queue size =1
08-29 10:13:53.298  5922  5932 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:13:53.299  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:13:53.299  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:13:53.299  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:13:53.299  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:13:53.299  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:13:53.299  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:13:53.299  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:13:53.299  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 10:13:53.300  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:13:53.300  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:13:53.300  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:13:53.300  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:13:53.301  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:13:53.305  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:13:53.305  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:13:53.305  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:13:53.306  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 10:13:53.306  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:13:53.306  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:13:53.306  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:13:53.316  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 10:13:53.316  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:13:53.322  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:13:53.322  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:13:53.329  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 10:13:53.329  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:13:53.330  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:13:53.335  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:13:53.335  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:13:53.335  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 10:13:53.341  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 10:13:53.341  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:13:53.806  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:13:53.807  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:13:53.807  5646  5646 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:13:56.196   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:56.305  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:13:56.306  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:13:56.306  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:13:56.306  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:13:56.306  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:13:56.306  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:13:56.306  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:13:56.307  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@deb9ff8 removed from the list
08-29 10:13:56.307  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:13:56.307  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e0dcd1 removed from the list
08-29 10:13:56.307  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:13:56.307  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:56.309  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:13:56.309  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:56.311  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:13:56.312  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:13:56.312  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:13:56.312  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e0dcd1 not in the list
08-29 10:13:56.312  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:56.312  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:56.315  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:13:56.316  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:13:56.316  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:56.316  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e0dcd1 not in the list
,08-29 10:13:56.316  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:13:56.317  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:56.317  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:56.317  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@deb9ff8 not in the list
,08-29 10:13:56.319  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:13:56.319  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cafcc2 added. We now have 3 listener(s)
08-29 10:13:56.323  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:13:56.324  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:13:56.324  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:13:56.325  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:13:56.325  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7cead3 added. We now have 4 listener(s)
08-29 10:13:56.325  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:13:56.327  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:13:56.332  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:56.336  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:13:56.339  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:56.339  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:13:56.339  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 10:13:56.340  5646  5692 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-29 10:13:56.340  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-29 10:13:56.340  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 10:13:56.340  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 10:13:56.341  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:13:56.341  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:13:56.341  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 10:13:56.342  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 10:13:56.342  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:13:56.342  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:13:56.342  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 10:13:56.342  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:13:56.342  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:13:56.343  5646  6019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:13:56.343  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:56.347  5646  6019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 10:13:56.347  5646  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 10:13:56.347  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:13:56.347  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:13:56.348  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 10:13:56.351  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:13:56.352  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 10:13:56.352  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:13:56.354  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 10:13:56.355  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:13:56.355  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,08-29 10:13:56.356  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 10:13:56.356  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 10:13:56.356  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 10:13:56.358  5646  5692 D BluetoothAdapter: STATE_ON
,08-29 10:13:56.363  5922  5962 D BtGatt.GattService: registerClient() - UUID=4bda3d13-d2c6-4703-ae74-67a28f9d2cbd
,08-29 10:13:56.364  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=4bda3d13-d2c6-4703-ae74-67a28f9d2cbd, clientIf=5
08-29 10:13:56.365  5646  5656 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 10:13:56.367  5922  5940 D BtGatt.AdvertiseManager: message : 0
,08-29 10:13:56.369  5922  5940 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 10:13:56.380  5922  5938 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 10:13:56.386  5922  5938 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 10:13:56.387  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 10:13:56.387  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:13:56.389  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 10:13:56.390  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 10:13:56.390  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 10:13:56.390  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 10:13:56.390  5646  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 10:13:56.390  5646  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 10:13:56.390  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-29 10:13:56.391  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 10:13:56.393  5646  5646 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 10:13:56.393  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 10:13:56.894  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 10:13:56.894  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 10:13:56.895  5646  5646 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:13:57.197   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:58.198   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:59.199   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:13:59.393  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:13:59.393  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 10:13:59.393  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:13:59.393  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 10:13:59.394  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:13:59.394  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 10:13:59.395  5646  6019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 10:13:59.395  5646  6019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 10:13:59.395  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 10:13:59.395  5646  6019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:13:59.395  5646  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 10:13:59.395  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 10:13:59.395  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:13:59.396  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:13:59.396  5646  5646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:13:59.396  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:13:59.396  5646  5646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 10:13:59.396  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:13:59.398  5646  5692 D BluetoothAdapter: STATE_ON
08-29 10:13:59.399  5646  5692 D BluetoothLeScanner: could not find callback wrapper
08-29 10:13:59.399  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:13:59.399  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 10:13:59.402  5922  5940 D BtGatt.AdvertiseManager: message : 1
08-29 10:13:59.404  5922  5940 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 10:13:59.416  5922  5938 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 10:13:59.417  5922  5938 D BtGatt.GattService: Client app is not null!
,08-29 10:13:59.418  5922  5933 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 10:13:59.419  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:13:59.420  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 10:13:59.420  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-29 10:13:59.420  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 10:13:59.420  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-29 10:13:59.423  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:13:59.423  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:13:59.423  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:13:59.424  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 10:13:59.425  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:13:59.425  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:13:59.425  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:59.425  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:13:59.425  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:13:59.425  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:13:59.425  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:13:59.425  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cafcc2 removed from the list
08-29 10:13:59.426  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:59.426  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7cead3 removed from the list
,08-29 10:13:59.426  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:13:59.426  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:59.427  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:59.427  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:13:59.431  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:13:59.431  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:13:59.432  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:59.432  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7cead3 not in the list
08-29 10:13:59.432  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:59.432  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:59.433  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:13:59.433  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:13:59.433  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:13:59.433  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7cead3 not in the list
08-29 10:13:59.433  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:13:59.433  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:13:59.433  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:13:59.433  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cafcc2 not in the list
,08-29 10:13:59.434  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:13:59.434  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ce33c added. We now have 3 listener(s)
08-29 10:13:59.436  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:13:59.436  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:13:59.436  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:13:59.436  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:13:59.436  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc138c5 added. We now have 4 listener(s)
08-29 10:13:59.436  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:13:59.437  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:13:59.440  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:13:59.443  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:13:59.445  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:13:59.445  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:13:59.446  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:13:59.446  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:13:59.446  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:13:59.446  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:13:59.446  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:13:59.449  5646  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 10:13:59.449  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:13:59.450  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:59.453  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:13:59.453  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:13:59.454  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 10:13:59.454  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:13:59.457  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:13:59.457  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:13:59.457  5646  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:13:59.458  5646  5692 D BluetoothAdapter: STATE_ON
,08-29 10:13:59.460  5922  5933 D BtGatt.GattService: registerClient() - UUID=fd98937f-4f89-4840-b2a1-629b4c0dcdb9
08-29 10:13:59.461  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=fd98937f-4f89-4840-b2a1-629b4c0dcdb9, clientIf=5
08-29 10:13:59.461  5646  5657 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 10:13:59.461  5922  5962 D BtGatt.GattService: start scan with filters
,08-29 10:13:59.463  5922  5941 D BtGatt.ScanManager: handling starting scan
08-29 10:13:59.463  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:13:59.463  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:13:59.463  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:13:59.463  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:13:59.465  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:13:59.466  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:13:59.466  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:13:59.467  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 10:13:59.469  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 10:13:59.469  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:13:59.469  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 10:13:59.474  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 10:13:59.474  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:13:59.474  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:13:59.474  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 10:13:59.482  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 10:13:59.482  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:13:59.487  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 10:13:59.487  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 10:13:59.927  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:13:59.966  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 10:13:59.966  5646  5646 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:13:59.966  5646  5646 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 10:14:00.200   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:14:01.200   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:14:02.477  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:14:02.477  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:14:02.478  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:14:02.478  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:14:02.478  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 10:14:02.478  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:14:02.478  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:14:02.478  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:14:02.479  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:14:02.479  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:14:02.479  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 10:14:02.481  5646  5692 D BluetoothAdapter: STATE_ON
08-29 10:14:02.484  5922  5949 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:14:02.486  5922  5932 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 10:14:02.486  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:14:02.487  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:14:02.487  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:14:02.487  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:14:02.487  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:14:02.489  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:14:02.490  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 10:14:02.490  5646  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:14:02.490  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:14:02.492  5922  5922 D BtGatt.ScanManager: awakened up at time 396318
,08-29 10:14:02.497  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:14:02.498  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 10:14:02.499  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:14:02.499  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:14:02.501  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:14:02.501  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:14:02.501  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.501  5646  5646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:14:02.501  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:14:02.501  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:14:02.501  5646  5646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:14:02.501  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ce33c removed from the list
08-29 10:14:02.502  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:14:02.502  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc138c5 removed from the list
08-29 10:14:02.502  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:14:02.502  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:14:02.502  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.502  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:14:02.504  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:14:02.504  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:14:02.504  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:14:02.504  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc138c5 not in the list
08-29 10:14:02.504  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.504  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:14:02.506  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:14:02.506  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:14:02.506  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:14:02.506  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc138c5 not in the list
08-29 10:14:02.506  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:14:02.506  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.506  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:14:02.506  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ce33c not in the list
08-29 10:14:02.507  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:14:02.507  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9185e6 added. We now have 3 listener(s)
08-29 10:14:02.508  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 10:14:02.509  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:14:02.509  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 10:14:02.509  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:14:02.509  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 10:14:02.509  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:14:02.509  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:14:02.509  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca64727 added. We now have 4 listener(s)
08-29 10:14:02.509  5646  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:14:02.510  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:14:02.512  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:14:02.517  5646  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:14:02.520  5646  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:14:02.520  5646  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:14:02.520  5646  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:14:02.521  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:14:02.521  5646  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:14:02.521  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:14:02.521  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.521  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:14:02.521  5646  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:14:02.521  5646  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9185e6 removed from the list
08-29 10:14:02.521  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:14:02.521  5646  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca64727 removed from the list
08-29 10:14:02.523  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:14:02.523  5646  5692 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:14:02.524  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:14:02.525  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.525  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:14:02.526  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:14:02.526  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:14:02.526  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:14:02.526  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca64727 not in the list
08-29 10:14:02.526  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.526  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:14:02.527  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 10:14:02.527  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 10:14:02.527  5922  5938 D BtGatt.GattService: current time is 396353541617
08-29 10:14:02.528  5922  5938 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -78, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 10:14:02.528  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:14:02.528  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:14:02.528  5646  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:14:02.528  5646  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca64727 not in the list
08-29 10:14:02.528  5646  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:14:02.528  5646  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:14:02.528  5646  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:14:02.528  5646  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9185e6 not in the list
,08-29 10:14:02.529  5922  5938 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 10:14:02.529  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 10:14:02.529  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 10:14:02.529  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 10:14:02.529  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:14:02.529  5646  5646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:14:02.529  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 10:14:02.529  5646  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:14:02.529  5922  5938 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 10:14:02.529  5922  5938 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 10:14:02.530  5922  5938 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 10:14:02.530  5922  5938 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 10:14:02.530  5922  5938 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 10:14:03.002  5646  5646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:14:04.541  5646  6020 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,08-29 10:14:06.541  5646  5692 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
,08-29 10:14:06.541  5646  5692 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,08-29 10:14:06.545  5646  6021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
,08-29 10:14:06.546  5646  6021 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
08-29 10:14:06.546  5646  6021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-29 10:14:06.552  5646  5692 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 10:14:06.557  5646  6022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,08-29 10:14:06.557  5646  6022 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
08-29 10:14:06.557  5646  6022 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-29 10:14:06.562  5646  5692 I jxcore-log: Total number of executed tests:  82
08-29 10:14:06.562  5646  5692 I jxcore-log: 
,08-29 10:14:06.563  5646  5692 I jxcore-log: Number of passed tests:  82
08-29 10:14:06.563  5646  5692 I jxcore-log: 
08-29 10:14:06.563  5646  5692 I jxcore-log: Number of failed tests:  0
08-29 10:14:06.563  5646  5692 I jxcore-log: 
08-29 10:14:06.563  5646  5692 I jxcore-log: Number of ignored tests:  0
08-29 10:14:06.563  5646  5692 I jxcore-log: 
08-29 10:14:06.563  5646  5692 I jxcore-log: Total duration:  100924
08-29 10:14:06.563  5646  5692 I jxcore-log: 
,08-29 10:14:06.568  5646  5692 I jxcore-log: Unit Test app is loaded
08-29 10:14:06.568  5646  5692 I jxcore-log: 
,08-29 10:14:06.579  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.579  5646  5692 I jxcore-log: 
,08-29 10:14:06.586  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.586  5646  5692 I jxcore-log: 
,08-29 10:14:06.587  5646  6020 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
08-29 10:14:06.588  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.588  5646  5692 I jxcore-log: 
08-29 10:14:06.588  5646  5646 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 10:14:06.590  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.590  5646  5692 I jxcore-log: 
,08-29 10:14:06.592  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 10:14:06.592  5646  5692 I jxcore-log: 
,08-29 10:14:06.595  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:14:06.595  5646  5692 I jxcore-log: 
,08-29 10:14:06.599  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.599  5646  5692 I jxcore-log: 
08-29 10:14:06.601  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.601  5646  5692 I jxcore-log: 
08-29 10:14:06.602  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 10:14:06.602  5646  5692 I jxcore-log: 
08-29 10:14:06.603  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:14:06.603  5646  5692 I jxcore-log: 
08-29 10:14:06.603  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:14:06.603  5646  5692 I jxcore-log: 
,08-29 10:14:06.604  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.604  5646  5692 I jxcore-log: 
08-29 10:14:06.606  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.606  5646  5692 I jxcore-log: 
,08-29 10:14:06.607  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.607  5646  5692 I jxcore-log: 
08-29 10:14:06.608  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.608  5646  5692 I jxcore-log: 
08-29 10:14:06.610  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.610  5646  5692 I jxcore-log: 
08-29 10:14:06.611  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.611  5646  5692 I jxcore-log: 
08-29 10:14:06.612  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.612  5646  5692 I jxcore-log: 
08-29 10:14:06.613  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.613  5646  5692 I jxcore-log: 
,08-29 10:14:06.615  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.615  5646  5692 I jxcore-log: 
,08-29 10:14:06.616  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.616  5646  5692 I jxcore-log: 
08-29 10:14:06.617  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.617  5646  5692 I jxcore-log: 
08-29 10:14:06.618  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.618  5646  5692 I jxcore-log: 
08-29 10:14:06.619  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.619  5646  5692 I jxcore-log: 
08-29 10:14:06.620  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.620  5646  5692 I jxcore-log: 
08-29 10:14:06.620  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.620  5646  5692 I jxcore-log: 
08-29 10:14:06.621  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.621  5646  5692 I jxcore-log: 
08-29 10:14:06.621  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.621  5646  5692 I jxcore-log: 
08-29 10:14:06.622  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.622  5646  5692 I jxcore-log: 
08-29 10:14:06.622  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.622  5646  5692 I jxcore-log: 
08-29 10:14:06.623  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.623  5646  5692 I jxcore-log: 
08-29 10:14:06.623  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.623  5646  5692 I jxcore-log: 
08-29 10:14:06.624  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.624  5646  5692 I jxcore-log: 
,08-29 10:14:06.625  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.625  5646  5692 I jxcore-log: 
08-29 10:14:06.626  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.626  5646  5692 I jxcore-log: 
,08-29 10:14:06.627  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.627  5646  5692 I jxcore-log: 
08-29 10:14:06.628  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.628  5646  5692 I jxcore-log: 
,08-29 10:14:06.629  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:14:06.629  5646  5692 I jxcore-log: 
,08-29 10:14:06.630  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.630  5646  5692 I jxcore-log: 
08-29 10:14:06.631  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:14:06.631  5646  5692 I jxcore-log: 
,08-29 10:14:06.632  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.632  5646  5692 I jxcore-log: 
,08-29 10:14:06.633  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.633  5646  5692 I jxcore-log: 
08-29 10:14:06.635  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.635  5646  5692 I jxcore-log: 
,08-29 10:14:06.636  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.636  5646  5692 I jxcore-log: 
,08-29 10:14:06.637  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.637  5646  5692 I jxcore-log: 
08-29 10:14:06.638  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:14:06.638  5646  5692 I jxcore-log: 
,08-29 10:14:06.639  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.639  5646  5692 I jxcore-log: 
,08-29 10:14:06.640  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 10:14:06.640  5646  5692 I jxcore-log: 
,08-29 10:14:06.641  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.641  5646  5692 I jxcore-log: 
,08-29 10:14:06.642  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:14:06.642  5646  5692 I jxcore-log: 
08-29 10:14:06.643  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 10:14:06.643  5646  5692 I jxcore-log: 
08-29 10:14:06.644  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:14:06.644  5646  5692 I jxcore-log: 
,08-29 10:14:06.645  5646  5692 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:14:06.645  5646  5692 I jxcore-log: 
,08-29 10:14:06.648  5646  5692 I jxcore-log: My device name is: Huawei-Nexus 6P
08-29 10:14:06.648  5646  5692 I jxcore-log: 
,08-29 10:14:06.649  5646  5692 I jxcore-log: WARN testUtils: myNameCallback not set!
08-29 10:14:06.649  5646  5692 I jxcore-log: 
,08-29 10:14:06.650  5646  5692 I jxcore-log: Running for NATIVE network type
08-29 10:14:06.650  5646  5692 I jxcore-log: 
,08-29 10:14:06.993  5646  5692 W jxcore-log: !!! js_ReportOverRecursed called !!!
,08-29 10:14:07.069  6023  5692 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
08-29 10:14:07.070  6023  5692 W google-breakpad: O A arm 08 armv8l 3.10.73-g9741316 #1 SMP PREEMPT Thu Nov 5 02:17:00 UTC 2015
08-29 10:14:07.070  6023  5692 W google-breakpad: S 0 D9E57378 D9E57000 00008000
,08-29 10:14:07.095  6023  5692 W google-breakpad: S D9E57000 00000000000000000000000000000000000000000000000000000000001CDFD500000000000000000100000002000000E06F91D800838AD9254C9ADE0000000000000000EA54A99B00000000C0DE28F700000000A09FC7DEC8CA54DA7070E5D9EC73E5D9A87662DA00000000000000009074E5D900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-29 10:14:07.096  6023  5692 W google-breakpad: S D9E57180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99BC0DE28F79072E5D9A09FC7DE4073E5D9A072E5D908CBEED8FC72E5D9E47A62DA00000000000000000000000040B082D9A072E5D901000000807FE5D9F6FFFFFFAC9FC7DE00000000A09FC7DE9072E5D90300000008000000603F87D988FFFFFF40B082D988FFFFFFD03E28D885FFFFFF88CA9FDE00CBEED800E0B5DBC073E5D90C6329F780CA9FDE949528F788CA9FDE00CBEED87FB626F700000000E472E5D901000000A09FC7DEFC72E5D9941153DA0C76E5D9247FE5D9A09FC7DE000000002C73E5D95C6552DA
08-29 10:14:07.097  6023  5692 W google-breakpad: S D9E57300 00CBEED84873E5D940B082D96909000090E2CBEA107091965473E5D9105433DA00000000C073E5D92C0000007073E5D94873E5D90700000058EBA2DA74278DDAA09FC7DE0000000085FFFFFF0030B6DBAC73E5D9205933DA000000007073E5D9A09FC7DE000000006C278DDAC073E5D974278DDAAC73E5D907000000000000000000000090B8E0E6003F28D885FFFFFFE01D91D9A09FC7DE3074E5D9DC73E5D9B473E5D985FFFFFFD473E5D9203E52DA00000000E01D91D922000000A074E5D9DC73E5D93074E5D974278DDA003F28D8FC73E5D958E773DA4C71B1D8000000000000000082FFFFFF3074E5D9A074E5D92074E5D9A09FC7DE6474E5D91C7B6CDAE4E88CDA50EC8CDA58EBA2DA220000004C71B1D87CC4F0D7000000003474E5D9003F28D885FFFFFFA09FC7DE00000000003F28D885FFFFFFE874E5D9B875E5D918D1A3DAB074E5D90000000001000000A074E5D99074E5D922000000A09FC7DEF475E5D928A46FDAF0CAEED8F00FECD40000000000100000F00FECD4C874E5D9
08-29 10:14:07.098  6023  5692 W google-breakpad: S D9E57480 D074E5D9E874E5D9F00FECD4E40134F50000000082FFFFFF00000000000100000000000082FFFFFFA09FC7DE00000000001164D7A09FC7DE010000001876E5D92876E5D901FFFFFFF0CAEED8070000000700000001000000703D28D800000000A09FC7DE0000000000000000060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF00000000F8CAEED822000000783D28D8070000000000000001000000180090D9509083D781FFFFFF5475E5D9E0BA5CDA07000000703D28D8A09FC7DE00000000100090D96075E5D99475E5D9E8FC5CDA0000000000000000000000000CB2F8D5C875E5D90100000000000000F0742DD8E01B91D9703D28D800000000FFFFFFFF509083D781FFFFFF3076E5D9B0B2F8D58876E5D9A475E5D9F075E5D9000000000000000078B2F8D54003000001000000FFFFFFFF81FFFFFF703D28D885FFFFFF100090D985FFFFFF00000000604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D781FFFFFF3076E5D9388F5BDD000000000476E5D9
08-29 10:14:07.098  6023  5692 W google-breakpad: S D9E57600 8C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFF703D28D885FFFFFF8C76E5D9C09083D788FCFAD501050000703D28D885FFFFFF00EA82D988FFFFFF604986D988FFFFFF0000000082FFFFFF0000000028017DD440020000000000005000000030BD82D9F0D991D985FFFFFFBC76E5D9D476E5D900000000B076E5D98C995BDD82010000808686D9010000000000000082FFFFFF703D28D885FFFFFF5C77E5D9C08C13D82CACF9D5010A0000703D28D885FFFFFF0000000082FFFFFF808686D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF300790D985FFFFFFF0D991D985FFFFFF82FFFFFF5828ACDAF0FB91D9DC9E00DCA000000030BD82D90000000083FFFFFFD89F00DC02000000000000008877E5D98C995BDD02020000C04C86D902000000A0C685D988FFFFFF703D28D885FFFFFF
08-29 10:14:07.099  6023  5692 W google-breakpad: S D9E57780 805029D888FFFFFFFC77E5D9803839E0ACE000DC81060000F0D991D985FFFFFF703D28D885FFFFFFA0C685D988FFFFFFC04C86D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000E077E5D90000000083FFFFFF6800000040906AD5783D28D8010000003000000040906AD5000000002078E5D98C995BDD8201000020917BD8010000000000000082FFFFFF703D28D885FFFFFFA478E5D9703139E0ECD800DC81070000703D28D885FFFFFF0000000082FFFFFF20917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC078E5D9B878E5D9B078E5D92479E5D97800000040906AD50000000016A075D958EBA2DAA09FC7DE00000000C878E5D98C995BDD8201000060917BD8010000000000000082FFFFFF703D28D885FFFFFF3479E5D9988791DECCCE00DC01060000703D28D885FFFFFF0000000,082FFFFFF60917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 10:14:07.100  6023  5692 W google-breakpad: S D9E57900 0000000082FFFFFF000000004079E5D95879E5D9040000006000000040906AD5E0C78DDE81FFFFFFC479E5D9F84F5BDD000000005879E5D98C995BDD8201000080917BD8010000000000000082FFFFFF703D28D885FFFFFFC479E5D9988191DED0C500DC01060000703D28D885FFFFFF0000000082FFFFFF80917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000090742DD800000000306D0DD860000000C0742DD804000000D89F00DCD479E5D978143FDA04000000E879E5D98C995BDD82010000A0917BD8010000000000000082FFFFFF90742DD888FFFFFF647AE5D990C68DDEE4BC00DC0107000090742DD888FFFFFF0000000082FFFFFFA0917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF801391D985FFFFFF703D28D885FFFFFF00000000587AE5D9547AE5D988FFFFFF7000000060742DD8F08B20D884F151DA000000000000000004000000887AE5D98C995BDD8201000020927BD801000000B0F2D7D888FFFFFF
08-29 10:14:07.100  6023  5692 W google-breakpad: S D9E57A80 D0702DD888FFFFFFE47AE5D9608C8ADE50B600DC01050000D0702DD888FFFFFFB0F2D7D888FFFFFF20927BD888FFFFFFC0D391D985FFFFFFF08B20D801000000147BE5D92C7BE5D950000000C034CED702000000705AFED6047BE5D9C8133FDA00000000187BE5D9DC6D96DE82020000206FC4D8030000000000000082FFFFFFD0702DD888FFFFFF0000000081FFFFFFF08B20D888FFFFFFB47BE5D9D051FED6E83236D501090000F08B20D888FFFFFF0000000081FFFFFFD0702DD888FFFFFF0000000082FFFFFF206FC4D888FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF00220ED788FFFFFF0000000082FFFFFF0900000081FFFFFFF08B20D888FFFFFF408C20D800000000E47BE5D9C0D682D99000000020C082D9D89F00DC0200000070838ADE81FFFFFF00000000D87BE5D98C995BDD82010000B00283D901000000F08B20D888FFFFFF206FC4D888FFFFFF5C7CE5D928888ADEC0AF00DC81070000206FC4D888FFFFFFF08B20D888FFFFFFB00283D988FFFFFF
08-29 10:14:07.101  6023  5692 W google-breakpad: S D9E57C00 408C20D888FFFFFFC0D682D988FFFFFFC0D082D988FFFFFF0000000082FFFFFF408C20D888FFFFFF0000000082FFFFFF807CE5D9388F5BDD00000000447CE5D978000000C034CED70000000014A600DC420300000300000000000000887CE5D98C995BDD02020000406FC4D80200000040EC8DD488FFFFFFE08CA3D888FFFFFFF08B20D888FFFFFFF47CE5D9788DC1DBE0AA00DC01060000F08B20D888FFFFFFE08CA3D888FFFFFF40EC8DD488FFFFFF406FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFFB87CE5D9A03584D9A03E28D8401191D960000000C034CED785FFFFFF2C447DD485FFFFFFF47CE5D900000000003784D9384F7DD4800B0000806FC4D802000000003784D988FFFFFFE08CA3D888FFFFFF008620D888FFFFFFB03E28D885FFFFFFA08B20D888FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFF0712DD8008620D8A03584D9B0A924D88A000000A0732DD8B03E28D8A08B20D8008620D8A03584D9A03E28D8801890D910AA24D8
08-29 10:14:07.102  6023  5692 W google-breakpad: S D9E57D80 09000000205029D8D0B082D9D0B082D9008620D888FFFFFF09000000401191D909000000003784D9E08CA3D8A0702DD8205029D888FFFFFF000000007CDB95DE20DD95DE00040000803684D901000000003784D988FFFFFFE08CA3D888FFFFFF0000000082FFFFFFF03AACDAE08CA3D870702DD840702DD80000000087FFFFFFA00F83D910702DD840702DD8E06F91D8E0BBF8D580020000C03684D9020000000000000082FFFFFFA00F83D988FFFFFF10702DD888FFFFFF707EE5D910702DD8A05F2FD8D05F2FD8FCDEF8D580020000003784D900000000A05F2FD888FFFFFF30852AD88A0000000700000040852AD8A09FC7DE40B082D9A0A924D8003784D920C85ADD03020000603F87D90100000040B082D988FFFFFFA0A924D885FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000A09FC7DEC0DE28F74880E5D90100000081FFFFFFA07FE5D9
08-29 10:14:07.103  6023  5692 W google-breakpad: S D9E57F00 0C80E5D914D444DA603F87D90000000000000000707FE5D9247FE5D938C75ADD58EBA2DAA09FC7DE00D578D98C90E5D9000000000000000000000000010000007487E5D9A09FC7DE0001000000000000B0DDF8D500000000603F87D90084E5D9020000000100000000000000000000000100000081FFFFFF0000000000000000D883E5D9F6FFFFFFAC9FC7DE01000000A09FC7DEA07FE5D90000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000004880E5D9A09FC7DE784BACDA00828AD900000000E8CAEED80C80E5D9EA54A99B00000000A09FC7DE4880E5D91080E5D9603F87D900828AD900000000E8CAEED83480E5D92C7562DA000000000000000000000000C0DE28F701000000A09FC7DE0884E5D94080E5D9BC83E5D9247662DA5224DFD5FB25DFD50884E5D90100,0000E81CA2DA0100000000828AD94080E5D9000000000026DFD50200000002000000010000000000000080CAA1DA5C0000000600000000000000
08-29 10:14:07.103  6023  5692 W google-breakpad: S D9E58080 788FE5D900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001CDFD500000000000000000100000002000000406F91D800838AD9254C9ADE0000000000000000EA54A99B00000000C0DE28F700000000A09FC7DEC8CA54DAD881E5D95485E5D9A87662DA0000000000000000F885E5D9000000000000000000000000000000000000000000000000000000000000000000000000
,08-29 10:14:07.105  6023  5692 W google-breakpad: S D9E58200 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-29 10:14:07.105  6023  5692 W google-breakpad: S D9E58380 00000000000000000000000000000000000000000000000000000000EA54A99BC0DE28F7F883E5D9A09FC7DEA884E5D90884E5D9E8CAEED86484E5D9E47A62DA00000000000000000000000040B082D90884E5D901000000E890E5D9F6FFFFFFAC9FC7DE00000000A09FC7DEF883E5D90300000008000000603F87D988FFFFFF40B082D988FFFFFFA0A924D885FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99B00000000A09FC7DEB884E5D9A884E5D9B084E5D9A484E5D982FFFFFFE0CAEED89484E5D9386552DAE0CAEED8B084E5D940B082D988FFFFFF1885E5D92885E5D90886E5D901000000C084E5D900000000F484E5D920FB73DAB084E5D9000000001800000040B082D9603F87D988FFFFFF0000000082FFFFFF01000000E0CAEED80000000082FFFFFFA09FC7DE000000006C278DDA2885E5D91885E5D9805AB3DB185DB3DBA09FC7DE0886E5D96C278DDA6485E5D9B80A6BDA2885E5D97C85E5D9
08-29 10:14:07.106  6023  5692 W google-breakpad: S D9E58500 070000004F0000004C1FF6D7AC70B1D800000000A070B1D840B082D988FFFFFFA09FC7DE00000000A0A924D885FFFFFFA09FC7DE000000007885E5D918808EDACD70B1D89885E5D90886E5D98885E5D9A09FC7DE7C85E5D922000000805AB3DBCC85E5D9EC7A6CDAE4E88CDA50EC8CDA58EBA2DA22000000AC70B1D84CC4F0D7000000009C85E5D922000000000000002087E5D900000000B485E5D914452ADA5086E5D92087E5D918D1A3DA1886E5D900000000010000000886E5D9F885E5D922000000A09FC7DE5C87E5D928A46FDAD0CAEED800000000A09FC7DEE885E5D9020000003086E5D9908CA3D85086E5D9F05A2FD888FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000A09FC7DE010000008087E5D99087E5D901000000D0CAEED807000000070000000100000040A824D800000000A09FC7DE0000000000000000060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF00000000D8CAEED82200000048A824D8
08-29 10:14:07.106  6023  5692 W google-breakpad: S D9E58680 070000000000000001000000180090D9509083D781FFFFFFBC86E5D9E0BA5CDA0700000040A824D8A09FC7DE00000000100090D9C886E5D9FC86E5D9E8FC5CDA0000000000000000000000000CB2F8D53087E5D90100000000000000705F2FD8E01B91D940A824D800000000FFFFFFFF509083D781FFFFFF9887E5D9B0B2F8D5F087E5D90C87E5D95887E5D9000000000000000078B2F8D54003000001000000FFFFFFFF81FFFFFF40A824D885FFFFFF100090D985FFFFFF00000000604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D781FFFFFF9887E5D9388F5BDD000000006C87E5D98C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFF40A824D885FFFFFFF487E5D9C09083D788FCFAD50105000040A824D885FFFFFF00EA82D988FFFFFF604986D988FFFFFF0000000082FFFFFF0000000028017DD440020000000000005000000030BD82D9F0D991D985FFFFFF2488E5D93C88E5D9000000001888E5D98C995BDD82010000
08-29 10:14:07.107  6023  5692 W google-breakpad: S D9E58800 808686D9010000000000000082FFFFFF40A824D885FFFFFFC488E5D9C08C13D82CACF9D5010A000040A824D885FFFFFF0000000082FFFFFF808686D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF300790D985FFFFFFF0D991D985FFFFFF82FFFFFF5828ACDAF0FB91D9DC9E00DCA000000030BD82D90000000083FFFFFFD89F00DC0200000000000000F088E5D98C995BDD02020000C04C86D902000000A0C685D988FFFFFF40A824D885FFFFFFC06F91D888FFFFFF6489E5D9803839E0ACE000DC81060000F0D991D985FFFFFF40A824D885FFFFFFA0C685D988FFFFFFC04C86D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300004889E5D90000000083FFFFFF6800000040906AD548A824D8010000003000000040906AD5000000008889E5D98C995BDD8201000020917BD8010000000000000082FFFFFF
08-29 10:14:07.107  6023  5692 W google-breakpad: S D9E58980 40A824D885FFFFFF0C8AE5D9703139E0ECD800DC8107000040A824D885FFFFFF0000000082FFFFFF20917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF288AE5D9208AE5D9188AE5D98C8AE5D97800000040906AD50000000016A075D958EBA2DAA09FC7DE00000000308AE5D98C995BDD8201000060917BD8010000000000000082FFFFFF40A824D885FFFFFF9C8AE5D9988791DECCCE00DC0106000040A824D885FFFFFF0000000082FFFFFF60917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A88AE5D9C08AE5D9040000006000000040906AD5E0C78DDE81FFFFFF2C8BE5D9F84F5BDD00000000C08AE5D98C995BDD8201000080917BD8010000000000000082FFFFFF40A824D885FFFFFF2C8BE5D9988191DED0C500DC0106000040A824D885FFFFFF0000000082FFFFFF80917BD,888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 10:14:07.108  6023  5692 W google-breakpad: S D9E58B00 00000000105F2FD800000000306D0DD860000000405F2FD804000000D89F00DC3C8BE5D978143FDA04000000508BE5D98C995BDD82010000A0917BD8010000000000000082FFFFFF105F2FD888FFFFFFCC8BE5D990C68DDEE4BC00DC01070000105F2FD888FFFFFF0000000082FFFFFFA0917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF801391D985FFFFFF40A824D885FFFFFF00000000C08BE5D9BC8BE5D988FFFFFF70000000E05E2FD8608520D884F151DA000000000000000004000000F08BE5D98C995BDD8201000020927BD801000000B0F2D7D888FFFFFF505B2FD888FFFFFF4C8CE5D9608C8ADE50B600DC01050000505B2FD888FFFFFFB0F2D7D888FFFFFF20927BD888FFFFFFC0D391D985FFFFFF608520D8010000007C8CE5D9948CE5D950000000C034CED702000000705AFED66C8CE5D9C8133FDA00000000808CE5D9DC6D96DE82020000206FC4D8030000000000000082FFFFFF505B2FD888FFFFFF0000000081FFFFFF608520D888FFFFFF
08-29 10:14:07.109  6023  5692 W google-breakpad: S D9E58C80 1C8DE5D9D051FED6E83236D501090000608520D888FFFFFF0000000081FFFFFF505B2FD888FFFFFF0000000082FFFFFF206FC4D888FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF90210ED788FFFFFF0000000082FFFFFF0900000081FFFFFF608520D888FFFFFFB08520D8000000004C8DE5D9C0D682D99000000020C082D9D89F00DC0200000070838ADE81FFFFFF00000000408DE5D98C995BDD82010000B00283D901000000608520D888FFFFFF206FC4D888FFFFFFC48DE5D928888ADEC0AF00DC81070000206FC4D888FFFFFF608520D888FFFFFFB00283D988FFFFFFB08520D888FFFFFFC0D682D988FFFFFFC0D082D988FFFFFF0000000082FFFFFFB08520D888FFFFFF0000000082FFFFFFE88DE5D9388F5BDD00000000AC8DE5D978000000C034CED70000000014A600DC420300000300000000000000F08DE5D98C995BDD02020000406FC4D80200000040EC8DD488FFFFFF908CA3D888FFFFFF608520D888FFFFFF5C8EE5D9788DC1DBE0AA00DC01060000
08-29 10:14:07.109  6023  5692 W google-breakpad: S D9E58E00 608520D888FFFFFF908CA3D888FFFFFF40EC8DD488FFFFFF406FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFF208EE5D9A03584D970A924D8401191D960000000C034CED785FFFFFF2C447DD485FFFFFF5C8EE5D900000000003784D9384F7DD4800B0000806FC4D802000000003784D988FFFFFF908CA3D888FFFFFF604F25D888FFFFFF80A924D885FFFFFF108520D888FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF705C2FD8604F25D8A03584D930852AD88A000000205E2FD880A924D8108520D8604F25D8A03584D970A924D8801890D990852AD809000000606F91D8D0B082D9D0B082D9604F25D888FFFFFF09000000401191D909000000003784D9908CA3D8205B2FD8606F91D888FFFFFF000000007CDB95DE20DD95DE00040000803684D901000000003784D988FFFFFF908CA3D888FFFFFF0000000082FFFFFFF03AACDA908CA3D8F05A2FD8C05A2FD80000000087FFFFFFA00F83D9905A2FD8C05A2FD8406F91D8E0BBF8D580020000
08-29 10:14:07.110  6023  5692 W google-breakpad: S D9E58F80 C03684D9020000000000000082FFFFFFA00F83D988FFFFFF905A2FD888FFFFFFD88FE5D9905A2FD8305A2FD8605A2FD8FCDEF8D580020000003784D900000000305A2FD888FFFFFF60812FD88A0000000700000070812FD8A09FC7DE40B082D920852AD8003784D920C85ADD03020000603F87D90100000040B082D988FFFFFF20852AD885FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000A09FC7DEC0DE28F7B091E5D90100000081FFFFFF0891E5D97491E5D914D444DA603F87D90000000000000000D890E5D98C90E5D938C75ADD58EBA2DAA09FC7DE00D578D9F4A1E5D900000000000000000000000001000000DC98E5D9A09FC7DE0001000000000000B0DDF8D500000000603F87D96895E5D9020000000100000000000000000000000100000081FFFFFF00000000000000004095E5D9F6FFFFFFAC9FC7DE01000000A09FC7DE0891E5D9
08-29 10:14:07.110  6023  5692 W google-breakpad: S D9E59100 000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000B091E5D9A09FC7DE784BACDA00828AD900000000C8CAEED87491E5D9EA54A99B00000000A09FC7DEB091E5D97891E5D9603F87D900828AD900000000C8CAEED89C91E5D92C7562DA000000000000000000000000C0DE28F701000000A09FC7DE7095E5D9A891E5D92495E5D9247662DA5224DFD5FB25DFD57095E5D901000000E81CA2DA0100000000828AD9A891E5D9000000000026DFD50200000002000000010000000000000080CAA1DA5C0000000600000000000000E0A0E5D9000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000,00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.111  6023  5692 W google-breakpad: S D9E59280 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001CDFD500000000000000000100000002000000A06E91D800838AD9254C9ADE0000000000000000EA54A99B00000000C0DE28F700000000A09FC7DEC8CA54DA4093E5D9BC96E5D9A87662DA00000000000000006097E5D90000000000000000000000000000000000000000000000000000000000000000000000000000000000000000040B58D9FFFFFFFF340934F501000000340934F500000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.111  6023  5692 W google-breakpad: S D9E59400 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99BC0DE28F76095E5D9A09FC7DE1096E5D97095E5D9C8CAEED8CC95E5D9E47A62DA00000000000000000000000040B082D97095E5D90100000050A2E5D9F6FFFFFFAC9FC7DE00000000A09FC7DE6095E5D90300000008000000603F87D988FFFFFF40B082D988FFFFFF20852AD885FFFFFF1808B0D8400134F5
08-29 10:14:07.112  6023  5692 W google-breakpad: S D9E59580 08000000FBC225F7A800000000000000280934F52DE125F704000000280934F504000000EA54A99B04000000A09FC7DE2096E5D91096E5D91896E5D90C96E5D982FFFFFFC0CAEED8FC95E5D9386552DAC0CAEED81896E5D940B082D988FFFFFF8096E5D99096E5D97097E5D9010000002896E5D9000000005C96E5D920FB73DA1896E5D9000000001800000040B082D9603F87D988FFFFFF0000000082FFFFFF01000000C0CAEED80000000082FFFFFFA09FC7DE000000006C278DDA9096E5D98096E5D9805AB3DB185DB3DBA09FC7DE7097E5D96C278DDACC96E5D9B80A6BDA9096E5D9E496E5D9070000004F0000004C1FF6D70C70B1D8000000000070B1D840B082D988FFFFFFA09FC7DE0000000020852AD885FFFFFFA09FC7DE00000000E096E5D918808EDA2D70B1D80097E5D97097E5D9F096E5D9A09FC7DEE496E5D922000000805AB3DB3497E5D9EC7A6CDAE4E88CDA50EC8CDA58EBA2DA220000000C70B1D81CC4F0D7000000000497E5D922000000000000008898E5D900000000
08-29 10:14:07.112  6023  5692 W google-breakpad: S D9E59700 1C97E5D914452ADAB897E5D98898E5D918D1A3DA8097E5D900000000010000007097E5D96097E5D922000000A09FC7DEC498E5D928A46FDAB0CAEED800000000A09FC7DE5097E5D9020000009897E5D9408CA3D8B897E5D980552FD888FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000A09FC7DE01000000E898E5D9F898E5D901000000B0CAEED8070000000700000001000000C0832AD800000000A09FC7DE0000000000000000060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF00000000B8CAEED822000000C8832AD8070000000000000001000000180090D9509083D781FFFFFF2498E5D9E0BA5CDA07000000C0832AD8A09FC7DE00000000100090D93098E5D96498E5D9E8FC5CDA0000000000000000000000000CB2F8D59898E5D90100000000000000005A2FD8E01B91D9C0832AD800000000FFFFFFFF509083D781FFFFFF0099E5D9B0B2F8D55899E5D97498E5D9C098E5D9000000000000000078B2F8D5
08-29 10:14:07.113  6023  5692 W google-breakpad: S D9E59880 4003000001000000FFFFFFFF81FFFFFFC0832AD885FFFFFF100090D985FFFFFF00000000604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D781FFFFFF0099E5D9388F5BDD00000000D498E5D98C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFFC0832AD885FFFFFF5C99E5D9C09083D788FCFAD501050000C0832AD885FFFFFF00EA82D988FFFFFF604986D988FFFFFF0000000082FFFFFF0000000028017DD440020000000000005000000030BD82D9F0D991D985FFFFFF8C99E5D9A499E5D9000000008099E5D98C995BDD82010000808686D9010000000000000082FFFFFFC0832AD885FFFFFF2C9AE5D9C08C13D82CACF9D5010A0000C0832AD885FFFFFF0000000082FFFFFF808686D988FFFFFF0,000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF300790D985FFFFFFF0D991D985FFFFFF
08-29 10:14:07.114  6023  5692 W google-breakpad: S D9E59A00 82FFFFFF5828ACDAF0FB91D9DC9E00DCA000000030BD82D90000000083FFFFFFD89F00DC0200000000000000589AE5D98C995BDD02020000C04C86D902000000A0C685D988FFFFFFC0832AD885FFFFFF206F91D888FFFFFFCC9AE5D9803839E0ACE000DC81060000F0D991D985FFFFFFC0832AD885FFFFFFA0C685D988FFFFFFC04C86D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000B09AE5D90000000083FFFFFF6800000040906AD5C8832AD8010000003000000040906AD500000000F09AE5D98C995BDD8201000020917BD8010000000000000082FFFFFFC0832AD885FFFFFF749BE5D9703139E0ECD800DC81070000C0832AD885FFFFFF0000000082FFFFFF20917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF909BE5D9889BE5D9809BE5D9F49BE5D97800000040906AD50000000016A075D958EBA2DAA09FC7DE00000000989BE5D98C995BDD82010000
,08-29 10:14:07.115  6023  5692 W google-breakpad: S D9E59B80 60917BD8010000000000000082FFFFFFC0832AD885FFFFFF049CE5D9988791DECCCE00DC01060000C0832AD885FFFFFF0000000082FFFFFF60917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000109CE5D9289CE5D9040000006000000040906AD5E0C78DDE81FFFFFF949CE5D9F84F5BDD00000000289CE5D98C995BDD8201000080917BD8010000000000000082FFFFFFC0832AD885FFFFFF949CE5D9988191DED0C500DC01060000C0832AD885FFFFFF0000000082FFFFFF80917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A0592FD800000000306D0DD860000000D0592FD804000000D89F00DCA49CE5D978143FDA04000000B89CE5D98C995BDD82010000A0917BD8010000000000000082FFFFFFA0592FD888FFFFFF349DE5D990C68DDEE4BC00DC01070000A0592FD888FFFFFF0000000082FFFFFFA0917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF801391D985FFFFFF
08-29 10:14:07.116  6023  5692 W google-breakpad: S D9E59D00 C0832AD885FFFFFF00000000289DE5D9249DE5D988FFFFFF7000000070592FD8C04E25D884F151DA000000000000000004000000589DE5D98C995BDD8201000020927BD801000000B0F2D7D888FFFFFFE0552FD888FFFFFFB49DE5D9608C8ADE50B600DC01050000E0552FD888FFFFFFB0F2D7D888FFFFFF20927BD888FFFFFFC0D391D985FFFFFFC04E25D801000000E49DE5D9FC9DE5D950000000C034CED702000000705AFED6D49DE5D9C8133FDA00000000E89DE5D9DC6D96DE82020000206FC4D8030000000000000082FFFFFFE0552FD888FFFFFF0000000081FFFFFFC04E25D888FFFFFF849EE5D9D051FED6E83236D501090000C04E25D888FFFFFF0000000081FFFFFFE0552FD888FFFFFF0000000082FFFFFF206FC4D888FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF20210ED788FFFFFF0000000082FFFFFF0900000081FFFFFFC04E25D888FFFFFF104F25D800000000B49EE5D9C0D682D99000000020C082D9D89F00DC0200000070838ADE81FFFFFF
,08-29 10:14:07.116  6023  5692 W google-breakpad: S D9E59E80 00000000A89EE5D98C995BDD82010000B00283D901000000C04E25D888FFFFFF206FC4D888FFFFFF2C9FE5D928888ADEC0AF00DC81070000206FC4D888FFFFFFC04E25D888FFFFFFB00283D988FFFFFF104F25D888FFFFFFC0D682D988FFFFFFC0D082D988FFFFFF0000000082FFFFFF104F25D888FFFFFF0000000082FFFFFF509FE5D9388F5BDD00000000149FE5D978000000C034CED70000000014A600DC420300000300000000000000589FE5D98C995BDD02020000406FC4D80200000040EC8DD488FFFFFF408CA3D888FFFFFFC04E25D888FFFFFFC49FE5D9788DC1DBE0AA00DC01060000C04E25D888FFFFFF408CA3D888FFFFFF40EC8DD488FFFFFF406FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFF889FE5D9A03584D9F0842AD8401191D960000000C034CED785FFFFFF2C447DD485FFFFFFC49FE5D900000000003784D9384F7DD4800B0000806FC4D802000000003784D988FFFFFF408CA3D888FFFFFFD04825D888FFFFFF00852AD885FFFFFF704E25D888FFFFFF
08-29 10:14:07.117  6023  5692 W google-breakpad: S D9E5A000 0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF00572FD8D04825D8A03584D960812FD88A000000B0582FD800852AD8704E25D8D04825D8A03584D9F0842AD8801890D9C0812FD809000000C06E91D8D0B082D9D0B082D9D04825D888FFFFFF09000000401191D909000000003784D9408CA3D8B0552FD8C06E91D888FFFFFF000000007CDB95DE20DD95DE00040000803684D901000000003784D988FFFFFF408CA3D888FFFFFF0000000082FFFFFFF03AACDA408CA3D880552FD850552FD80000000087FFFFFFA00F83D920552FD850552FD8A06E91D8E0BBF8D580020000C03684D9020000000000000082FFFFFFA00F83D988FFFFFF20552FD888FFFFFF40A1E5D920552FD8C0542FD8F0542FD8FCDEF8D580020000003784D900000000C0542FD888FFFFFF304E21D88A00000007000000404E21D8A09FC7DE40B082D950812FD8003784D920C85ADD03020000603F87D90100000040B082D988FFFFFF50812FD885FFFFFF00000000000000000000000000000000
08-29 10:14:07.118  6023  5692 W google-breakpad: S D9E5A180 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000A09FC7DEC0DE28F718A3E5D90100000081FFFFFF70A2E5D9DCA2E5D914D444DA603F87D9000000000000000040A2E5D9F4A1E5D938C75ADD58EBA2DAA09FC7DE00D578D95CB3E5D90000000000000000000000000100000044AAE5D9A09FC7DE0001E5D900000000B0DDF8D500000000603F87D9D0A6E5D9020000000100000064A2E5D9000000000100000081FFFFFF00A5E5D900000005A8A6E5D9F6FFFFFFAC9FC7DE01000000A09FC7DE70A2E5D9000000000800000094A2E5D914B468DA000080002000000018A5E5D9F87B8AD90000100000000000E4A2E5D90100000018A3E5D9A09FC7DE784BACDA00828AD900000000A8CAEED8DCA2E5D9EA54A99B00000000A09FC7DE18A3E5D9E0A2E5D9603F87D900828AD900000000A8CAEED804A3E5D92C7562DA00000000B4186ADA02000000C0DE28F701000000A09FC7DED8A6E5D910A3E5D9
08-29 10:14:07.118  6023  5692 W google-breakpad: S D9E5A300 8CA6E5D9247662DA1CA3E5D90C196ADAD8A6E5D901000000E81CA2DA0100000000828AD910A3E5D90000000000AB68DA0200000038000000C490B4D62CAA68DA11A3E5D93800000010A7E5D911A5E5D93C000000000000E0C0DE28F718A5E5D9B0A3E5D9F87B8AD9F08BA3D8000000009490B4D6F0C768DAD890B4D68CA3E5D9010000009CA3E5D99CA3E5D9FFFFFF0001000000ACA3E5D908000000DC90B4D6B090B4D63CEC00DC48EC00DC209068DA20EC00DCF0FFFFFFFFFFFFFF00000000040000000000101588CA9FDE0090B4D600E0B5DB30A7E5D988CA9FDE90CAEED800E0B5DB18A5E5D90C6329F780CA9FDE949528F788CA9FDE90CAEED87FB626F748A4E5D9C4A4E5D90021DDD448A4E5D93CA4E5D9481848DA3CEC00DC4CEC00DC782562D4782562D44CA4E5D930A7E5D901000000782562D4A09FC7DE18A5E5D901000000782562D4A09FC7DEF08BA3D8F08BA3D8000000006CA4E5D92CD334DA48ACE5D918A5E5D97CA4E5D9247B43DA00000000C0DE28F704B0E5D95C4D48DA
08-29 10:14:07.119  6023  5692 W google-breakpad: S D9E5A480 001862D4BCD08DDA0D0000007C44B7D703000000000000000000000000BB48DA001862D464D38DDA68627DD418A5E5D901000000001862D4D0A4E5D9F87B8AD9F08BA3D828DBA0DA41B082D9584E7DD410000000280000001C0000002C00000000000000782562D40D0000007C44B7D703000000000000000D000000CC8A68DA020000000100000018A5E5D900000000000000000000000028A5E5D9000000000000000000000000000000000000000040A5E5D9000000000000000000000000000000000000000058A5E5D9000000000000000000000000000000000000000070A5E5D900000000000000000000000080A5E5D900000000010000000000000090A5E5D90000000000000000000000000800000000000000A8A5E5D9000000000800000000000000B8A5E5D9000000000800000000000000C8A5E5D9000000000800000000000000D8A5E5D9000000000000000000000000E8A5E5D9000000000000000,005000000F8A5E5D90000000000000000020000000200000000000000
08-29 10:14:07.119  6023  5692 W google-breakpad: S D9E5A600 90CAEED8010000000100000000000000000000000000000028A6E5D9000000000000000000000000200000000000000040A6E5D900000000200000000000000001A6E5D90000000058A6E5D905000000010000000500000068A6E5D90200000001000000D000000078A6E5D9EA54A99BC0DE28F7C8A6E5D9A09FC7DE78A7E5D9D8A6E5D9A8CAEED834A7E5D9E47A62DAA0A6E5D9000000000100000040B082D9D8A6E5D901000000B8B3E5D9F6FFFFFFAC9FC7DE00000000A09FC7DEC8A6E5D90300000008000000603F87D988FFFFFF40B082D988FFFFFF50812FD885FFFFFF200000000000000001A6E5D900000000703AA0DAB090B4D60194B4D60000B4D6703AA0DAB090B4D60194B4D6EA54A99B703AA0DAA09FC7DE88A7E5D978A7E5D980A7E5D974A7E5D982FFFFFFA0CAEED864A7E5D9386552DAA0CAEED880A7E5D940B082D988FFFFFFE8A7E5D9F8A7E5D9D8A8E5D90100000090A7E5D900000000C4A7E5D920FB73DA80A7E5D9080000001800000040B082D9603F87D988FFFFFF
08-29 10:14:07.120  6023  5692 W google-breakpad: S D9E5A780 0000000082FFFFFF01000000A0CAEED80000000082FFFFFFA09FC7DE000000006C278DDAF8A7E5D9E8A7E5D9805AB3DB185DB3DBA09FC7DED8A8E5D96C278DDA34A8E5D9B80A6BDAF8A7E5D94CA8E5D9070000004F0000004C1FF6D7BCBF1DD800000000B0BF1DD840B082D988FFFFFFA09FC7DE0000000050812FD885FFFFFFA09FC7DE0000000048A8E5D918808EDADDBF1DD868A8E5D9D8A8E5D958A8E5D9A09FC7DE4CA8E5D922000000805AB3DB9CA8E5D9EC7A6CDAE4E88CDA50EC8CDA58EBA2DA22000000BCBF1DD8ECC3F0D7000000006CA8E5D92200000000000000F0A9E5D90000000084A8E5D914452ADA20A9E5D9F0A9E5D918D1A3DAE8A8E5D90000000001000000D8A8E5D9C8A8E5D922000000A09FC7DE2CAAE5D928A46FDA90CAEED800000000A09FC7DEB8A8E5D90200000000A9E5D9F08BA3D820A9E5D910502FD888FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000A09FC7DE0100000050AAE5D960AAE5D901000000
08-29 10:14:07.120  6023  5692 W google-breakpad: S D9E5A900 90CAEED8070000000700000001000000E09F21D800000000A09FC7DE0000000000000000060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF0000000098CAEED822000000E89F21D8070000000000000001000000180090D9509083D781FFFFFF8CA9E5D9E0BA5CDA07000000E09F21D8A09FC7DE00000000100090D998A9E5D9CCA9E5D9E8FC5CDAF46229F7E3C825F70C0918D70CB2F8D500AAE5D901000000FC0C60D690542FD8E01B91D9E09F21D800000000FFFFFFFF509083D781FFFFFF68AAE5D9B0B2F8D5C0AAE5D9DCA9E5D928AAE5D9000000000000000078B2F8D54003000001000000FFFFFFFF81FFFFFFE09F21D885FFFFFF100090D985FFFFFFE40134F5604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D781FFFFFF68AAE5D9388F5BDD000000003CAAE5D98C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFFE09F21D885FFFFFFC4AAE5D9C09083D788FCFAD501050000E09F21D885FFFFFF
08-29 10:14:07.121  6023  5692 W google-breakpad: S D9E5AA80 00EA82D988FFFFFF604986D988FFFFFF0000000082FFFFFF0000000028017DD440020000000000005000000030BD82D9F0D991D985FFFFFFF4AAE5D90CABE5D900000000E8AAE5D98C995BDD82010000808686D9010000000000000082FFFFFFE09F21D885FFFFFF94ABE5D9C08C13D82CACF9D5010A0000E09F21D885FFFFFF0000000082FFFFFF808686D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF300790D985FFFFFFF0D991D985FFFFFF82FFFFFF5828ACDAF0FB91D9DC9E00DCA000000030BD82D90000000083FFFFFFD89F00DC0200000000000000C0ABE5D98C995BDD02020000C04C86D902000000A0C685D988FFFFFFE09F21D885FFFFFF806E91D888FFFFFF34ACE5D9803839E0ACE000DC81060000F0D991D985FFFFFFE09F21D885FFFFFFA0C685D988FFFFFFC04C86D988FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 10:14:07.122  6023  5692 W google-breakpad: S D9E5AC00 0000000082FFFFFFC103000018ACE5D90000000083FFFFFF6800000040906AD5E89F21D8010000003000000040906AD50000000058ACE5D98C995BDD8201000020917BD8010000000000000082FFFFFFE09F21D885FFFFFFDCACE5D9703139E0ECD800DC81070000E09F21D885FFFFFF0000000082FFFFFF20917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFF8ACE5D9F0ACE5D9E8ACE5D95CADE5D97800000040906AD50000000016A075D958EBA2DAA09FC7DE0000000000ADE5D98C995BDD8201000060917BD8010000000000000082FFFFFFE09F21D885FFFFFF6CADE5D9988791DECCCE00DC01060000E09F21D885FFFFFF0000000082FFFFFF60917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000078AD,E5D990ADE5D9040000006000000040906AD5E0C78DDE81FFFFFFFCADE5D9F84F5BDD0000000090ADE5D98C995BDD8201000080917BD801000000
08-29 10:14:07.122  6023  5692 W google-breakpad: S D9E5AD80 0000000082FFFFFFE09F21D885FFFFFFFCADE5D9988191DED0C500DC01060000E09F21D885FFFFFF0000000082FFFFFF80917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000030542FD800000000306D0DD86000000060542FD804000000D89F00DC0CAEE5D978143FDA0400000020AEE5D98C995BDD82010000A0917BD8010000000000000082FFFFFF30542FD888FFFFFF9CAEE5D990C68DDEE4BC00DC0107000030542FD888FFFFFF0000000082FFFFFFA0917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF801391D985FFFFFFE09F21D885FFFFFF0000000090AEE5D98CAEE5D988FFFFFF7000000000542FD8304825D884F151DA000000000000000004000000C0AEE5D98C995BDD8201000020927BD801000000B0F2D7D888FFFFFF70502FD888FFFFFF1CAFE5D9608C8ADE50B600DC0105000070502FD888FFFFFFB0F2D7D888FFFFFF20927BD888FFFFFFC0D391D985FFFFFF304825D8010000004CAFE5D964AFE5D9
08-29 10:14:07.123  6023  5692 W google-breakpad: S D9E5AF00 50000000C034CED702000000705AFED63CAFE5D9C8133FDA0000000050AFE5D9DC6D96DE82020000206FC4D8030000000000000082FFFFFF70502FD888FFFFFF0000000081FFFFFF304825D888FFFFFFECAFE5D9D051FED6E83236D501090000304825D888FFFFFF0000000081FFFFFF70502FD888FFFFFF0000000082FFFFFF206FC4D888FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFB0200ED788FFFFFF0000000082FFFFFF0900000081FFFFFF304825D888FFFFFF804825D8000000001CB0E5D9C0D682D99000000020C082D9D89F00DC0200000070838ADE81FFFFFF0000000010B0E5D98C995BDD82010000B00283D901000000304825D888FFFFFF206FC4D888FFFFFF94B0E5D928888ADEC0AF00DC81070000206FC4D888FFFFFF304825D888FFFFFFB00283D988FFFFFF804825D888FFFFFFC0D682D988FFFFFFC0D082D988FFFFFF0000000082FFFFFF804825D888FFFFFF0000000082FFFFFFB8B0E5D9388F5BDD000000007CB0E5D978000000C034CED7
08-29 10:14:07.123  6023  5692 W google-breakpad: S D9E5B080 0000000014A600DC420300000300000000000000C0B0E5D98C995BDD02020000406FC4D80200000040EC8DD488FFFFFFF08BA3D888FFFFFF304825D888FFFFFF2CB1E5D9788DC1DBE0AA00DC01060000304825D888FFFFFFF08BA3D888FFFFFF40EC8DD488FFFFFF406FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFFF0B0E5D9A03584D920812FD8401191D960000000C034CED785FFFFFF2C447DD485FFFFFF2CB1E5D900000000003784D9384F7DD4800B0000806FC4D802000000003784D988FFFFFFF08BA3D888FFFFFF404225D888FFFFFF30812FD885FFFFFFE04725D888FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF90512FD8404225D8A03584D9304E21D88A00000040532FD830812FD8E04725D8404225D8A03584D920812FD8801890D9904E21D809000000206E91D8D0B082D9D0B082D9404225D888FFFFFF09000000401191D909000000003784D9F08BA3D840502FD8206E91D888FFFFFF000000007CDB95DE20DD95DE00040000
,08-29 10:14:07.125  6023  5692 W google-breakpad: S D9E5B200 803684D901000000003784D988FFFFFFF08BA3D888FFFFFF0000000082FFFFFFF03AACDAF08BA3D810502FD8D07F27D80000000087FFFFFFA00F83D9A07F27D8D07F27D8006E91D8E0BBF8D580020000C03684D9020000000000000082FFFFFFA00F83D988FFFFFFA07F27D888FFFFFF00000000A07F27D8407F27D8707F27D8FCDEF8D580020000003784D900000000407F27D888FFFFFF70BCE5D948000000B4B2E5D980BAE5D94800000040B082D9204E21D8003784D920C85ADD03020000603F87D90100000040B082D988FFFFFF204E21D885FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000A09FC7DEC0DE28F780B4E5D90100000081FFFFFFD8B3E5D944B4E5D914D444DA603F87D90000000000000000A8B3E5D95CB3E5D938C75ADD58EBA2DAA09FC7DE00D578D9C4C4E5D900000000000000000000000001000000ACBBE5D9A09FC7DE
08-29 10:14:07.125  6023  5692 W google-breakpad: S D9E5B380 0001FDD700000000B0DDF8D500000000603F87D938B8E5D902000000010000007089BFD7000000000100000081FFFFFF00E0B5DB986C4ED710B8E5D9F6FFFFFFAC9FC7DE01000000A09FC7DED8B3E5D9000000000800000020A0FDD700A0FDD7C089BFD79A010000B07FBFD700A0FDD770A0FDD71804000048E170D90100000080B4E5D9A09FC7DE784BACDA00828AD90000000088CAEED844B4E5D9EA54A99B00000000A09FC7DE80B4E5D948B4E5D9603F87D900828AD90000000088CAEED86CB4E5D92C7562DA00000000F84FB7D700000000C0DE28F701000000A09FC7DE40B8E5D978B4E5D9F4B7E5D9247662DA5224DFD5FB25DFD540B8E5D901000000E81CA2DA0100000000828AD978B4E5D9000000000026DFD50200000002000000010000000000000080CAA1DA5C0000000600000000000000B0C3E5D90000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.125  6023  5692 W google-breakpad: S D9E5B500 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001CDFD500000000000000000100000002000000606D91D800838AD9254C9ADE0000000000000000EA54A99B00000000C0DE28F700000000A09FC7DEC8CA54DA10B6E5D98CB9E5D9A87662DA000000000000000030BAE5D9000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.126  6023  5692 W google-breakpad: S D9E5B680 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000CC0018D7E81118D70000000000800000E81118D7BFC725F7A0B7E5D970B7E5D9E81118D7E40134F5E80134F5E81118D700000000EBC925F70C0918D7FFFFFFFFDC14FCD7010000002C0158D901000000280288DE01000000C4051CD601000000600978D901000000E80134F501000000E80134F5FFFFFFFF18066CD6FFFFFFFF680714D5FFFFFFFF68070CD5FFFFFFFF3414C4D4FFFFFFFF3414C4D4EA54A99BC0DE28F730B8E5D9A09FC7DEE0B8E5D940B8E5D988CAEED89CB8E5D9E47A62DA0000000000000000
08-29 10:14:07.126  6023  5692 W google-breakpad: S D9E5B800 0000000040B082D940B8E5D90100000020C5E5D9F6FFFFFFAC9FC7DE00000000A09FC7DE30B8E5D90300000008000000603F87D988FFFFFF40B082D988FFFFFF204E21D885FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99B00000000A09FC7DEF0B8E5D9E0B8E5D9E8B8E5D9DCB8E5D982FFFFFF80CAEED8CCB8E5D9386552DA80CAEED8E8B8E5D940B082D988FFFFFF50B9E5D960B9E5D940BAE5D901000000F8B8E5D9000000002CB9E5D920FB73DAE8B8E5D9000000001800000040B082D9603F87D988FFFFFF0000000082FFFFFF0100000080CAEED80000000082FFFFFFA09FC7DE000000006C278DDA60B9E5D950B9E5D9805AB3DB185DB3DBA09FC7DE40BAE5D96C278DDA9CB9E5D9B80A6BDA60B9E5D9B4B9E5D9070000004F0000004C1FF6D76CBF1DD80000000060BF1DD840B082D988FFFFFFA09FC7DE00000000204E21D,885FFFFFFA09FC7DE00000000B0B9E5D918808EDA8DBF1DD8D0B9E5D9
08-29 10:14:07.127  6023  5692 W google-breakpad: S D9E5B980 40BAE5D9C0B9E5D9A09FC7DEB4B9E5D922000000805AB3DB04BAE5D9EC7A6CDAE4E88CDA50EC8CDA58EBA2DA220000006CBF1DD8BCC3F0D700B232D8D4B9E5D9220000000000000058BBE5D900000000ECB9E5D914452ADA88BAE5D958BBE5D918D1A3DA50BAE5D9000000000100000040BAE5D930BAE5D922000000A09FC7DE94BBE5D928A46FDA70CAEED80000000038501BD7000000000000000068BAE5D984BAE5D988BAE5D9A0BAE5D9000000000000000082FFFFFF00000000000100002200000000000000000000000000000000BAE5D9A09FC7DE01000000B8BBE5D9C8BBE5D90130000070CAEED8070000000700000001000000C04C21D800000020A09FC7DE34B4E5D9986C4ED7060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF0000000068CAEED822000000C84C21D8070000000000000001000000180090D9509083D701000000F4BAE5D9E0BA5CDA07000000C04C21D8A09FC7DE00000000100090D900BBE5D934BBE5D9E8FC5CDA9810F0D601000000
08-29 10:14:07.127  6023  5692 W google-breakpad: S D9E5BB00 7005F8D60CB2F8D568BBE5D901000000040BDCD6107F27D8E01B91D9C04C21D800000000FFFFFFFF509083D701000000D0BBE5D9B0B2F8D528BCE5D944BBE5D990BBE5D9000000000000000078B2F8D54003000001000000FFFFFFFF81FFFFFFC04C21D885FFFFFF100090D985FFFFFFB0F2BAD7604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D701000000D0BBE5D9388F5BDD00000000A4BBE5D98C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFFC04C21D885FFFFFF2CBCE5D9C09083D788FCFAD501050000C04C21D885FFFFFF00EA82D988FFFFFF604986D988FFFFFF0000000082FFFFFF0000000028017DD440020000000000005000000030BD82D9F0D991D985FFFFFF5CBCE5D974BCE5D90000000050BCE5D98C995BDD82010000808686D9010000000000000082FFFFFFC04C21D885FFFFFFFCBCE5D9C08C13D82CACF9D5010A0000C04C21D885FFFFFF0000000082FFFFFF808686D988FFFFFF0000000082FFFFFF
08-29 10:14:07.128  6023  5692 W google-breakpad: S D9E5BC80 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF300790D985FFFFFFF0D991D985FFFFFF82FFFFFF5828ACDAF0FB91D9DC9E00DCA000000030BD82D90000000083FFFFFFC07D27D8030200000000000028BDE5D98C995BDD02020000C04C86D902000000A0C685D988FFFFFFC04C21D885FFFFFFE06D91D888FFFFFF9CBDE5D9803839E0ACE000DC81060000F0D991D985FFFFFFC04C21D885FFFFFFA0C685D988FFFFFFC04C86D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000080BDE5D90000000083FFFFFF6800000040906AD5C84C21D8010000003000000040906AD500000000C0BDE5D98C995BDD8201000020917BD8010000000000000082FFFFFFC04C21D885FFFFFF44BEE5D9703139E0ECD800DC81070000C04C21D885FFFFFF0000000082FFFFFF20917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 10:14:07.128  6023  5692 W google-breakpad: S D9E5BE00 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF60BEE5D958BEE5D950BEE5D9C4BEE5D97800000040906AD50000000016A075D958EBA2DAA09FC7DE0000000068BEE5D98C995BDD8201000060917BD8010000000000000082FFFFFFC04C21D885FFFFFFD4BEE5D9988791DECCCE00DC01060000C04C21D885FFFFFF0000000082FFFFFF60917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E0BEE5D9F8BEE5D9040000006000000040906AD5E0C78DDE0100000064BFE5D9F84F5BDD00000000F8BEE5D98C995BDD8201000080917BD8010000000000000082FFFFFFC04C21D885FFFFFF64BFE5D9988191DED0C500DC01060000C04C21D885FFFFFF0000000082FFFFFF80917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000B07E27D800000000306D0DD860000000E07E27D804000000C07D27D874BFE5D978143FDA0400000088BFE5D98C995BDD82010000A0917BD8010000000000000082FFFFFF
08-29 10:14:07.129  6023  5692 W google-breakpad: S D9E5BF80 B07E27D888FFFFFF04C0E5D990C68DDEE4BC00DC01070000B07E27D888FFFFFF0000000082FFFFFFA0917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF801391D985FFFFFFC04C21D885FFFFFF00000000F8BFE5D9F4BFE5D988FFFFFF70000000807E27D8A04125D884F151DA00000000000000000400000028C0E5D98C995BDD8201000020927BD801000000B0F2D7D888FFFFFFF07A27D888FFFFFF84C0E5D9608C8ADE50B600DC01050000F07A27D888FFFFFFB0F2D7D888FFFFFF20927BD888FFFFFFC0D391D985FFFFFFA04125D801000000B4C0E5D9CCC0E5D950000000C034CED703020000705AFED6A4C0E5D9C8133FDA00000000B8C0E5D9DC6D96DE82020000206FC4D8030000000000000082FFFFFFF07A27D888FFFFFF0000000081FFFFFFA04125D888FFFFFF54C1E5D9D051FED6E83236D50109,0000A04125D888FFFFFF0000000081FFFFFFF07A27D888FFFFFF0000000082FFFFFF206FC4D888FFFFFF0900000084FFFFFF0000000082FFFFFF
08-29 10:14:07.129  6023  5692 W google-breakpad: S D9E5C100 0000000081FFFFFF40200ED788FFFFFF0000000082FFFFFF0900000081FFFFFFA04125D888FFFFFFF04125D80000000084C1E5D9C0D682D99000000020C082D9C07D27D80302000070838ADE010000000000000078C1E5D98C995BDD82010000B00283D901000000A04125D888FFFFFF206FC4D888FFFFFFFCC1E5D928888ADEC0AF00DC81070000206FC4D888FFFFFFA04125D888FFFFFFB00283D988FFFFFFF04125D888FFFFFFC0D682D988FFFFFFC0D082D988FFFFFF0000000082FFFFFFF04125D888FFFFFF0000000082FFFFFF20C2E5D9388F5BDD00000000E4C1E5D978000000C034CED70000000014A600DC42030000030000000000000028C2E5D98C995BDD02020000406FC4D80200000040EC8DD488FFFFFFA08BA3D888FFFFFFA04125D888FFFFFF94C2E5D9788DC1DBE0AA00DC01060000A04125D888FFFFFFA08BA3D888FFFFFF40EC8DD488FFFFFF406FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFFCCB15BDDDCC2E5D9E0C2E5D90000000060000000C034CED7
08-29 10:14:07.130  6023  5692 W google-breakpad: S D9E5C280 C8C2E5D900000000C07D27D80302000000000000C0C2E5D98C995BDD02020000806FC4D802000000003784D988FFFFFFA08BA3D888FFFFFFA02B2AD888FFFFFF5CC3E5D95881DAD9FC34FAD501090000A02B2AD888FFFFFFA08BA3D888FFFFFF003784D988FFFFFF806FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFF004E21D885FFFFFF504125D888FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF806D91D888FFFFFFC07D27D888FFFFFF603F87D90100000090000000C07A27D864C3E5D954C3E5D90835ACDA0000000004000000ACC5E5D920DD95DE00040000803684D901000000003784D988FFFFFFA08BA3D888FFFFFF0000000082FFFFFFF03AACDAA08BA3D8907A27D8607A27D80000000087FFFFFFA00F83D9307A27D8607A27D8606D91D8E0BBF8D580020000C03684D9020000000000000082FFFFFFA00F83D988FFFFFF307A27D888FFFFFF10C4E5D9307A27D8D07927D8007A27D8FCDEF8D580020000003784D900000000D07927D888FFFFFF
08-29 10:14:07.130  6023  5692 W google-breakpad: S D9E5C400 00FA2AD88A0000000700000010FA2AD8A09FC7DE40B082D9B06B2FD8003784D920C85ADD03020000603F87D90100000040B082D988FFFFFFB06B2FD885FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000A09FC7DEC0DE28F7E8C5E5D90100000081FFFFFF40C5E5D9ACC5E5D914D444DA603F87D9000000000000000010C5E5D9C4C4E5D938C75ADD58EBA2DAA09FC7DE00D578D92CD6E5D90000000000000000000000000100000014CDE5D9A09FC7DE0001000000000000B0DDF8D500000000603F87D9A0C9E5D9020000000100000000000000000000000100000081FFFFFF000000000000000078C9E5D9F6FFFFFFAC9FC7DE01000000A09FC7DE40C5E5D9000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000E8C5E5D9A09FC7DE784BACDA00828AD90000000068CAEED8
08-29 10:14:07.131  6023  5692 W google-breakpad: S D9E5C580 ACC5E5D9EA54A99B00000000A09FC7DEE8C5E5D9B0C5E5D9603F87D900828AD90000000068CAEED8D4C5E5D92C7562DA000000000000000000000000C0DE28F701000000A09FC7DEA8C9E5D9E0C5E5D95CC9E5D9247662DA5224DFD5FB25DFD5A8C9E5D901000000E81CA2DA0100000000828AD9E0C5E5D9000000000026DFD50200000002000000010000000000000080CAA1DA5C000000060000000000000018D5E5D900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.131  6023  5692 W google-breakpad: S D9E5C700 000000000000000000000000000000000000000000000000000000000000000000000000001CDFD500000000000000000100000002000000C06C91D800838AD9254C9ADE0000000000000000EA54A99B00000000C0DE28F700000000A09FC7DEC8CA54DA78C7E5D9F4CAE5D9A87662DA000000000000000098CBE5D90000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.131  6023  5692 W google-breakpad: S D9E5C880 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99BC0DE28F798C9E5D9A09FC7DE48CAE5D9A8C9E5D968CAEED804CAE5D9E47A62DA00000000000000000000000040B082D9A8C9E5D90100000088D6E5D9F6FFFFFFAC9FC7DE00000000A09FC7DE98C9E5D90300000008000000603F87D988FFFFFF40B082D988FFFFFFB06B2FD885FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99B00000000A09FC7DE58CAE5D948CAE5D950CAE5D944CAE5D982FFFFFF60CAEED8
08-29 10:14:07.132  6023  5692 W google-breakpad: S D9E5CA00 34CAE5D9386552DA60CAEED850CAE5D940B082D988FFFFFFB8CAE5D9C8CAE5D9A8CBE5D90100000060CAE5D90000000094CAE5D920FB73DA50CAE5D9000000001800000040B082D9603F87D988FFFFFF0000000082FFFFFF0100000060CAEED80000000082FFFFFFA09FC7DE000000006C278DDAC8CAE5D9B8CAE5D9805AB3DB185DB3DBA09FC7DEA8CBE5D96C278DDA04CBE5D9B80A6BDAC8CAE5D91CCBE5D9070000004F0000004C1FF6D71CBF1DD80000000010BF1DD840B082D988FFFFFFA09FC7DE00000000B06B2FD885FFFFFFA09FC7DE0000000018CBE5D918808EDA3DBF1DD838CBE5D9A8CBE5D928CBE5D9A09FC7DE1CCBE5D922000000805AB3DB6CCBE5D9EC7A6CDAE4E88CDA50EC8CDA58EBA2DA220000001CBF1DD88CC3F0D7000000003CCBE5D92200000000000000C0CCE5D90000000054CBE5D914452ADAF0CBE5D9C0CCE5D918D1A3DAB8CBE5D90000000001000000A8CBE5D998CBE5D922000000A09FC7DEFCCCE5D928A46FDA50CAEED800000000A09FC7DE88CBE5D9
08-29 10:14:07.132  6023  5692 W google-breakpad: S D9E5CB80 02000000D0CBE5D9508BA3D8F0CBE5D9207527D888FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000A09FC7DE0100000020CDE5D930CDE5D90100000050CAEED8070000000700000001000000506A2FD800000000A09FC7DE0000000000000000060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF0000000058CAEED822000000586A2FD8070000000000000001000000180090D9509083D7010000005CCCE5D9E0BA5CDA07000000506A2FD8A09FC7DE00000000100090D968CCE5D99CCCE5D9E8FC5CDAF46229F7E3C825F70C0918D70CB2F8D5D0CCE5D901000000FC0C60D6A07927D8E01B91D9506A2FD800000000FFFFFFFF509083D70100000038CDE5D9B0B2F8D590CDE5D9ACCCE5D9F8CCE5D9000000000000000078B2F8D54003000001000000FFFFFFFF81FFFFFF506A2FD885FFFFFF100090D985FFFFFFE40134F5604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D70100000038CDE5D9388F5BDD
08-29 10:14:07.133  6023  5692 W google-breakpad: S D9E5CD00 000000000CCDE5D98C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFF506A2FD885FFFFFF94CDE5D9C09083D788FCFAD501050000506A2FD885FFFFFF00EA82D988FFFFFF604986D988FFFFFF0000000082FFFFFF0000000028017DD440020000000000005000000030BD82D9F0D991D985FFFFFFC4CDE5D9DCCDE5D900000000B8CDE5D98C995BDD82010000808686D9010000000000000082FFFFFF506A2FD885FFFFFF64CEE5D9C08C13D82CACF9D5010A0000506A2FD885FFFFFF0000000082FFFFFF808686D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF300790D985FFFFFFF0D991D985FFFFFF82FFFFFF5828ACDAF0FB91D9DC9E00DCA000000030BD82D90000000083FFFFFF507827D8030200000000000090CEE5D98C995BDD02020000C04C86D902000000A0C685D988FFFFFF
08-29 10:14:07.133  6023  5692 W google-breakpad: S D9E5CE80 506A2FD885FFFFFF406D91D888FFFFFF04CFE5D9803839E0ACE000DC81060000F0D991D985FFFFFF506A2FD885FFFFFFA0C685D988FFFFFFC04C86D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000E8CEE5D90000000083FFFFFF6800000040906AD5586A2FD8010000003000000040906AD50000000028CFE5D98C995BDD8201000020917BD8010000000000000082FFFFFF506A2FD885FFFFFFACCFE5D9703139E0ECD800DC81070000506A2FD885FFFFFF0000000082FFFFFF20917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC8CFE5D9C0CFE5D9B8CFE5D92CD0E5D97800000040906AD50000000016A075D958EBA2DAA09FC7DE00000000D0CFE5D98C995BDD8201000060917BD8010000000000000082FFFFFF506A2FD885FFFFFF3CD0E5D9988791DECCCE00DC01060000506A2FD885FFFFFF0000000082FFFFFF60917BD888FFFFFF0000000082FFFFFF
08-29 10:14:07.134  6023  5692 W google-breakpad: S D9E5D000 0000000082FFFFFF0000000082FFFFFF0000000048D0E5D960D0E5D9040000006000000040906AD5E0C78DDE01000000CCD0E5D9F84F5BDD0000000060D0E5D98C995BDD8201000080917BD8010000000000000082FFFFFF506A2FD885FFFFFFCCD0E5D9988191DED0C500DC01060000506A2FD885FFFFFF0000000082FFFFFF80917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000407927D800000000306D0DD860000000707927D804000000507827D8DCD0E5D978143FDA04000000F0D0E5D98C995BDD82010000A0917BD8010000000000000082FFFFFF407927D888FFFFFF6CD1E5D990C68DDEE4BC00DC01070000407927D888FFFFFF0000000082FFFFFFA0917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF801391D985FFFFFF506A2FD885FFFFFF0000000060D1E5D95CD1E5D988FFFFFF70000000107927D8002B2AD884F151DA00000000000000000400000090D1E5D98C995BDD8201000020927BD801000000
08-29 10:14:07.134  6023  5692 W google-breakpad: S D9E5D180 B0F2D7D888FFFFFF807527D888FFFFFFECD1E5D9608C8ADE50B600DC01050000807527D888FFFFFFB0F2D7D888FFFFFF20927BD888FFFFFFC0D391D985FFFFFF002B2AD8010000001CD2E5D934D2E5D950000000C034CED703020000705AFED60CD2E5D9C8133FDA0000000020D2E5D9DC6D96DE82020000206FC4D8030000000000000082FFFFFF807527D888FFFFFF0000000081FFFFFF002B2AD888FFFFFFBCD2E5D9D051FED6E83236D501090000002B2AD888FFFFFF0000000081FFFFFF807527D888FFFFFF0000000082FFFFFF206FC4D888FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF905F2BD788FFFFFF0000000082FFFFFF0900000081FFFFFF002B2AD888FFFFFF502B2AD800000000ECD2E5D9C0D682D99000000020C082D9507827D80302000070838ADE0100000000000000E0D2E5D98C995BDD82010000B00283D901000000002B2AD888FFFFFF206FC4D888FFFFFF64D3E5D928888ADEC0AF00DC81070000206FC4D888FFFFFF002B2AD888FFFFFF
08-29 10:14:07.135  6023  5692 W google-breakpad: S D9E5D300 B00283D988FFFFFF502B2AD888FFFFFFC0D682D988FFFFFFC0D082D988FFFFFF0000000082FFFFFF502B2AD888FFFFFF0000000082FFFFFF88D3E5D9388F5BDD000000004CD3E5D978000000C034CED70000000014A600DC42030000030000000000000090D3E5D98C995BDD02020000406FC4D80200000040EC8DD488FFFFFF508BA3D888FFFFFF002B2AD888FFFFFFFCD3E5D9788DC1DBE0AA00DC01060000002B2AD888FFFFFF508BA3D888FFFFFF40EC8DD488FFFFFF406FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFFCCB15BDD44D4E5D948D4E5D90000000060000000C034CED730D4E5D900000000507827D8030200000000000028D4E5D98C995BDD02020000806FC4D802000000003784D988FFFFFF508BA3D888FFFFFF10252AD888FFFFFFC4D4E5D95881DAD9FC34FAD50109000010252AD888FFFFFF508BA3D888FFFFFF003784D988FFFFFF806FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFF906B2FD885FFFFFFB02A2AD888FFFFFF0900000081FFFFFF
08-29 10:14:07.135  6023  5692 W google-breakpad: S D9E5D480 0900000081FFFFFF0900000081FFFFFFE06C91D888FFFFFF507827D888FFFFFF603F87D90100000090000000507527D8CCD4E5D9BCD4E5D90835ACDA000000000400000014D7E5D920DD95DE00040000803684D901000000003784D988FFFFFF508BA3D888FFFFFF0000000082FFFFFFF03AACDA508BA3D8207527D8F07427D80000000087FFFFFFA00F83D9C07427D8F07427D8C06C91D8E0BBF8D580020000C03684D9020000000000000082FFFFFFA00F83D988FFFFFFC07427D888FFFFFF78D5E5D9C07427D8607427D8907427D8FCDEF8D580020000003784D900000000607427D888FFFFFFF0782ED88A0000000700000000792ED8A09FC7DE40B082D9F0F92AD8003784D920C85ADD03020000603F87D90100000040B082D988FFFFFFF0F92AD885FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000A09FC7DEC0DE28F750D7E5D901000000
08-29 10:14:07.136  6023  5692 W google-breakpad: S D9E5D600 81FFFFFFA8D6E5D914D7E5D914D444DA603F87D9000000000000000078D6E5D92CD6E5D938C75ADD58EBA2DAA09FC7DE00D578D994E7E5D9000000000000000000000000010000007CDEE5D9A09FC7DE0001000000000000B0DDF8D500000000603F87D908DBE5D9020000000100000000000000000000000100000081FFFFFF0000000000000000E0DAE5D9F6FFFFFFAC9FC7DE01000000A09FC7DEA8D6E5D900000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000050D7E5D9A09FC7DE784BACDA00828AD90000000048CAEED814D7E5D9EA54A99B00000000A09FC7DE50D7E5D918D7E5D9603F87D900828AD90000000048CAEED83CD7E5D92C7562DA000000000000000000000000C0DE28F701000000A09FC7DE10DBE5D948D7E5D9C4DAE5D9247662DA5224DFD5FB25DFD510DBE5D901000000E81CA2DA0100000000828AD948D7E5D9000000000026DFD50200000002000000010000000000000080CAA1DA5C000000
08-29 10:14:07.136  6023  5692 W google-breakpad: S D9E5D780 060000000000000080E6E5D900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001CDFD500000000000000000100000002000000206C91D800838AD9254C9ADE0000000000000000EA54A99B00000000C0DE28F700000000A09FC7DEC8CA54DAE0D8E5D95CDCE5D9A87662DA000000000000000000DDE5D900000000000000000000000000000000000000000000000000000000
08-29 10:14:07.137  6023  5692 W google-breakpad: S D9E5D900 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.137  6023  5692 W google-breakpad: S D9E5DA80 000000000000000000000000000000000000000000000000000000000000000000000000EA54A99BC0DE28F700DBE5D9A09FC7DEB0DBE5D910DBE5D948CAEED86CDBE5D9E47A62DA00000000000000000000000040B082D910DBE5D901000000F0E7E5D9F6FFFFFFAC9FC7DE00000000A09FC7DE00DBE5D90300000008000000603F87D988FFFFFF40B082D988FFFFFFF0F92AD885FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000EA54A99B04000000A09FC7DEC0DBE5D9B0DBE5D9B8DBE5D9ACDBE5D982FFFFFF40CAEED89CDBE5D9386552DA40CAEED8B8DBE5D940B082D988FFFFFF20DCE5D930DCE5D910DDE5D901000000C8DBE5D900000000FCDBE5D920FB73DAB8DBE5D9000000001800000040B082D9603F87D988FFFFFF0000000082FFFFFF0100000040CAEED80000000082FFFFFFA09FC7DE000000006C278DDA30DCE5D920DCE5D9805AB3DB185DB3DBA09FC7DE10DDE5D96C278DDA6CDCE5D9B80A6BDA
08-29 10:14:07.138  6023  5692 W google-breakpad: S D9E5DC00 30DCE5D984DCE5D9070000004F0000004C1FF6D7CCBE1DD800000000C0BE1DD840B082D988FFFFFFA09FC7DE00000000F0F92AD885FFFFFFA09FC7DE0000000080DCE5D918808EDAEDBE1DD8A0DCE5D910DDE5D990DCE5D9A09FC7DE84DCE5D922000000805AB3DBD4DCE5D9EC7A6CDAE4E88CDA50EC8CDA58EBA2DA22000000CCBE1DD85CC3F0D7E80134F5A4DCE5D9220000000000000028DEE5D900000000BCDCE5D914452ADA58DDE5D928DEE5D918D1A3DA20DDE5D9000000000100000010DDE5D900DDE5D922000000A09FC7DE64DEE5D928A46FDA30CAEED8FFFFFFFF3C12A8D401000000E80134F538DDE5D9008BA3D858DDE5D9A05F24D888FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000A09FC7DE0100000088DEE5D998DEE5D90100000030CAEED807000000070000000100000090F82AD800000000A09FC7DE0000000000000000060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF0000000038CAEED8
08-29 10:14:07.138  6023  5692 W google-breakpad: S D9E5DD80 2200000098F82AD8070000000000000001000000180090D9509083D701000000C4DDE5D9E0BA5CDA0700000090F82AD8A09FC7DE00000000100090D9D0DDE5D904DEE5D9E8FC5CDAF46229F7E3C825F70C0918D70CB2F8D538DEE5D901000000280288DE307427D8E01B91D990F82AD800000000FFFFFFFF509083D701000000A0DEE5D9B0B2F8D5F8DEE5D914DEE5D960DEE5D9000000000000000078B2F8D54003000001000000FFFFFFFF81FFFFFF90F82AD885FFFFFF100090D985FFFFFFE40134F5604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D701000000A0DEE5D9388F5BDD0000000074DEE5D98C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFF90F82AD885FFFFFFFCDEE5D9C09083D788FCFAD50105000090F82AD885FFFFFF00EA82D988FFFFFF604986D988FFFFFF0000000082FFFFFF0000000028017DD440020000000000005000000030BD82D9F0D991D985FFFFFF2CDFE5D944DFE5D90000000020DFE5D9
08-29 10:14:07.138  6023  5692 W google-breakpad: S D9E5DF00 8C995BDD82010000808686D9010000000000000082FFFFFF90F82AD885FFFFFFCCDFE5D9C08C13D82CACF9D5010A000090F82AD885FFFFFF0000000082FFFFFF808686D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF300790D985FFFFFFF0D991D985FFFFFF82FFFFFF5828ACDAF0FB91D9DC9E00DCA000000030BD82D90000000083FFFFFFE07227D80302000000000000F8DFE5D98C995BDD02020000C04C86D902000000A0C685D988FFFFFF90F82AD885FFFFFFA06C91D888FFFFFF6CE0E5D9803839E0ACE000DC81060000F0D991D985FFFFFF90F82AD885FFFFFFA0C685D988FFFFFFC04C86D988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000050E0E5D90000000083FFFFFF6800000040906AD598F82AD8010000003000000040906AD50000000090E0E5D98C995BDD8201000020917BD801000000
08-29 10:14:07.139  6023  5692 W google-breakpad: S D9E5E080 0000000082FFFFFF90F82AD885FFFFFF14E1E5D9703139E0ECD800DC8107000090F82AD885FFFFFF0000000082FFFFFF20917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF30E1E5D928E1E5D920E1E5D994E1E5D97800000040906AD50000000016A075D958EBA2DAA09FC7DE0000000038E1E5D98C995BDD8201000060917BD8010000000000000082FFFFFF90F82AD885FFFFFFA4E1E5D9988791DECCCE00DC0106000090F82AD885FFFFFF0000000082FFFFFF60917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000B0E1E5D9C8E1E5D9040000006000000040906AD5E0C78DDE0100000034E2E5D9F84F5BDD00000000C8E1E5D98C995BDD8201000080917BD8010000000000000082FFFFFF90F82AD885FFFFFF34E2E5D9988191DED0C500DC0106000090F82AD885FFFFFF0000000082FFFFFF80917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 10:14:07.139  6023  5692 W google-breakpad: S D9E5E200 0000000082FFFFFF00000000D07327D800000000306D0DD860000000007427D804000000E07227D844E2E5D978143FDA0400000058E2E5D98C995BDD82010000A0917BD8010000000000000082FFFFFFD07327D888FFFFFFD4E2E5D990C68DDEE4BC00DC01070000D07327D888FFFFFF0000000082FFFFFFA0917BD888FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF801391D985FFFFFF90F82AD885FFFFFF00000000C8E2E5D9C4E2E5D988FFFFFF70000000A07327D870242AD884F151DA000000000000000004000000F8E2E5D98C995BDD8201000020927BD801000000B0F2D7D888FFFFFF107027D888FFFFFF54E3E5D9608C8ADE50B600DC01050000107027D888FFFFFFB0F2D7D888FFFFFF20927BD888FFFFFFC0D391D985FFFFFF70242AD80100000084E3E5D99CE3E5D950000000C034CED703020000705AFED674E3E5D9C8133FDA0000000088E3E5D9DC6D96DE82020000206FC4D8030000000000000082FFFFFF107027D888FFFFFF0000000081FFFFFF
08-29 10:14:07.140  6023  5692 W google-breakpad: S D9E5E380 70242AD888FFFFFF24E4E5D9D051FED6E83236D50109000070242AD888FFFFFF0000000081FFFFFF107027D888FFFFFF0000000082FFFFFF206FC4D888FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF205F2BD788FFFFFF0000000082FFFFFF0900000081FFFFFF70242AD888FFFFFFC0242AD80000000054E4E5D9C0D682D99000000020C082D9E07227D80302000070838ADE010000000000000048E4E5D98C995BDD82010000B00283D90100000070242AD888FFFFFF206FC4D888FFFFFFCCE4E5D928888ADEC0AF00DC81070000206FC4D888FFFFFF70242AD888FFFFFFB00283D988FFFFFFC0242AD888FFFFFFC0D682D988FFFFFFC0D082D988FFFFFF0000000082FFFFFFC0242AD888FFFFFF0000000082FFFFFFF0E4E5D9388F5BDD00000000B4E4E5D978000000C034CED70000000014A600DC420300000300000000000000F8E4E5D98C995BDD02020000406FC4D80200000040EC8DD488FFFFFF008BA3D888FFFFFF70242AD888FFFFFF64E5E5D9788DC1DB
08-29 10:14:07.140  6023  5692 W google-breakpad: S D9E5E500 E0AA00DC0106000070242AD888FFFFFF008BA3D888FFFFFF40EC8DD488FFFFFF406FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFFCCB15BDDACE5E5D9B0E5E5D90000000060000000C034CED798E5E5D900000000E07227D8030200000000000090E5E5D98C995BDD02020000806FC4D802000000003784D988FFFFFF008BA3D888FFFFFF707E24D888FFFFFF2CE6E5D95881DAD9FC34FAD501090000707E24D888FFFFFF008BA3D888FFFFFF003784D988FFFFFF806FC4D888FFFFFF0000000082FFFFFF0000000082FFFFFFD0F92AD885FFFFFF20242AD888FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF406C91D888FFFFFFE07227D888FFFFFF603F87D90100000090000000D05F24D834E6E5D924E6E5D90835ACDA00000000040000007CE8E5D920DD95DE00040000803684D901000000003784D988FFFFFF008BA3D888FFFFFF0000000082FFFFFFF03AACDA008BA3D8A05F24D8705F24D80000000087FFFFFFA00F83D9405F24D8705F24D8206C91D8
08-29 10:14:07.141  6023  5692 W google-breakpad: S D9E5E680 E0BBF8D580020000C03684D9020000000000000082FFFFFFA00F83D988FFFFFF405F24D888FFFFFFE0E6E5D9405F24D8E05E24D8105F24D8FCDEF8D580020000003784D900000000E05E24D888FFFFFF907820D88A00000007000000A07820D8A09FC7DE40B082D9E0782ED8003784D920C85ADD03020000603F87D90100000040B082D988FFFFFFE0782ED885FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000A09FC7DEC0DE28F7B8E8E5D90100000081FFFFFF10E8E5D97CE8E5D914D444DA603F87D90000000000000000E0E7E5D994E7E5D938C75ADD58EBA2DAA09FC7DE00D578D9FCF8E5D900000000000000000000000001000000E4EFE5D9A09FC7DE0001000000000000B0DDF8D500000000603F87D970ECE5D9020000000100000000000000000000000100000081FFFFFF000000000000000048ECE5D9F6FFFFFFAC9FC7DE01000000
08-29 10:14:07.141  6023  5692 W google-breakpad: S D9E5E800 A09FC7DE10E8E5D9000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000B8E8E5D9A09FC7DE784BACDA00828AD90000000028CAEED87CE8E5D9EA54A99B00000000A09FC7DEB8E8E5D980E8E5D9603F87D900828AD90000000028CAEED8A4E8E5D92C7562DA000000000000000000000000C0DE28F701000000A09FC7DE78ECE5D9B0E8E5D92CECE5D9247662DA5224DFD5FB25DFD578ECE5D901000000E81CA2DA0100000000828AD9B0E8E5D9000000000026DFD50200000002000000010000000000000080CAA1DA5C0000000600000000000000E8F7E5D90000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.142  6023  5692 W google-breakpad: S D9E5E980 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001CDFD500000000000000000100000002000000806B91D800838AD9254C9ADE0000000000000000EA54A99B00000000C0DE28F700000000A09FC7DEC8CA54DA48EAE5D9C4EDE5D9A87662DA000000000000000068EEE5D9000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.142  6023  5692 W google-breakpad: S D9E5EB00 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99BC0DE28F768ECE5D9A09FC7DE18EDE5D978ECE5D928CAEED8D4ECE5D9E47A62DA00000000000000000000000040B082D978ECE5D90100000058F9E5D9F6FFFFFFAC9FC7DE00000000A09FC7DE68ECE5D90300000008000000603F87D988FFFFFF40B082D988FFFFFFE0782ED885FFFFFF
08-29 10:14:07.143  6023  5692 W google-breakpad: S D9E5EC80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EA54A99B00000000A09FC7DE28EDE5D918EDE5D920EDE5D914EDE5D982FFFFFF20CAEED804EDE5D9386552DA20CAEED820EDE5D940B082D988FFFFFF88EDE5D998EDE5D978EEE5D90100000030EDE5D90000000064EDE5D920FB73DA20EDE5D9000000001800000040B082D9603F87D988FFFFFF0000000082FFFFFF0100000020CAEED80000000082FFFFFFA09FC7DE000000006C278DDA98EDE5D988EDE5D9805AB3DB185DB3DBA09FC7DE78EEE5D96C278DDAD4EDE5D9B80A6BDA98EDE5D9ECEDE5D9070000004F0000004C1FF6D7DCBD1DD800000000D0BD1DD840B082D988FFFFFFA09FC7DE00000000E0782ED885FFFFFFA09FC7DE00000000E8EDE5D918808EDAFDBD1DD808EEE5D978EEE5D9F8EDE5D9A09FC7DEECEDE5D922000000805AB3DB3CEEE5D9EC7A6CDAE4E88CDA50EC8CDA58EBA2DA22000000DCBD1DD82CC3F0D7000000000CEEE5D92200000000000000
08-29 10:14:07.143  6023  5692 W google-breakpad: S D9E5EE00 90EFE5D90000000024EEE5D914452ADAC0EEE5D990EFE5D918D1A3DA88EEE5D9000000000100000078EEE5D968EEE5D922000000A09FC7DECCEFE5D928A46FDA10CAEED800000000A09FC7DE58EEE5D902000000A0EEE5D9B08AA3D8C0EEE5D9305A24D888FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000A09FC7DE01000000F0EFE5D900F0E5D90100000010CAEED807000000070000000100000080772ED800000000A09FC7DE0000000000000000060000003CD1A3DA3CD1A3DA0600000018D1A3DA00000000FFFFFFFF0000000018CAEED82200000088772ED8070000000000000001000000180090D9509083D7010000002CEFE5D9E0BA5CDA0700000080772ED8A09FC7DE00000000100090D938EFE5D96CEFE5D9E8FC5CDAF46229F7E3C825F70C0918D70CB2F8D5A0EFE5D901000000FC0C60D6B05E24D8E01B91D980772ED800000000FFFFFFFF509083D70100000008F0E5D9B0B2F8D560F0E5D97CEFE5D9C8EFE5D900000000
08-29 10:14:07.143  6023  5692 W google-breakpad: S D9E5EF80 0000000078B2F8D54003000001000000FFFFFFFF81FFFFFF80772ED885FFFFFF100090D985FFFFFFE40134F5604986D988FFFFFF88FCFAD500000000FFFFFFFFC09083D70100000008F0E5D9388F5BDD00000000DCEFE5D98C995BDD000000000000000088FCFAD54202000001000000604986D988FFFFFF00EA82D988FFFFFF
08-29 10:14:07.144  6023  5692 W google-breakpad: C 0600004000F0B5DB00000000B473E5D93074E5D98873E5D9DC73E5D9A09FC7DEB473E5D9003F28D885FFFFFF805AB3DBAC73E5D97073E5D97873E5D9783952DA7C3952DA10000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 10:14:07.145  6023  5692 W google-breakpad: M AAC76000 00000000 00005000 B11131ACAEA04730E8812A7546019DD70 app_process32
08-29 10:14:07.146  6023  5692 W google-breakpad: M D9FDC000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-29 10:14:07.146  6023  5692 W google-breakpad: M E2AA5000 03716000 01AE1000 488126E5C3908224A6BF664CC97A94320 libwebviewchromium.so
08-29 10:14:07.147  6023  5692 W google-breakpad: M E8EA5000 00000000 00006000 FEC9541933ACE52D7B868116F343FB2B0 libwebviewchromium_loader.so
08-29 10:14:07.147  6023  5692 W google-breakpad: M E8F49000 00000000 00005000 6CB98C1690A536CF6709829EEDA3C7A70 libjnigraphics.so
08-29 10:14:07.147  6023  5692 W google-breakpad: M E8F4E000 00000000 0000A000 59CFF69D627F008A007192B16466AFF20 libcompiler_rt.so
08-29 10:14:07.147  6023  5692 W google-breakpad: M E8F58000 00000000 00011000 A6E0E0D6EF4E15F73B6783FF2AC2715C0 libandroid.so
08-29 10:14:07.147  6023  5692 W google-breakpad: M E8F69000 00000000 0000A000 EABA3CAEE4AB859D45B6B87B097F2F9C0 libqservice.so
08-29 10:14:07.147  6023  5692 W google-breakpad: M E8F73000 00000000 0000C000 1FCA747711C8BDD16393F4588722AC960 libqdutils.so
08-29 10:14:07.147  6023  5692 W google-breakpad: M E8F7F000 00000000 00005000 1F826A318101A4B04F55FD18535335C90 libqdMetaData.so
08-29 10:14:07.148  6023  5692 W google-breakpad: M E8F84000 00000000 00008000 D46562F0AE9DB55BCE3313FEDEDFA6590 libmemalloc.so
08-29 10:14:07.148  6023  5692 W google-breakpad: M E8F8C000 00000000 00009000 432140AB4199275DE0BF613C7AB038050 gralloc.msm8994.so
08-29 10:14:07.148  6023  5692 W google-breakpad: M E8F95000 00000000 0000C000 2A67CCECB355562E420451AD4B9811A90 eglSubDriverAndroid.so
08-29 10:14:07.148  6023  5692 W google-breakpad: M E8FA1000 00000000 00026000 9F49D01DD4FBB5FFCF3613150881B4500 libGLESv1_CM_adreno.so
08-29 10:14:07.148  6023  5692 W google-breakpad: M E8FC7000 00000000 0073D000 2076F62BFFE762262BDB09FC9D5564F90 libllvm-glnext.so
08-29 10:14:07.149  6023  5692 W google-breakpad: M E9715000 00000000 00495000 5E66A8AF513BAEC4DDD22A5E486CA5740 libGLESv2_adreno.so
08-29 10:14:07.149  6023  5692 W google-breakpad: M E9BAC000 00000000 0003D000 93AC4CD274A1E3BCEBF3CE5F949EB5780 libgsl.so
08-29 10:14:07.149  6023  5692 W google-breakpad: M E9BE9000 00000000 00007000 970ACFD9475F636B156547BA7CB914970 libadreno_utils.so
08-29 10:14:07.149  6023  5692 W google-breakpad: M E9BF2000 00000000 00012000 2E578A88F58C311E721035666D5653FF0 libEGL_adreno.so
08-29 10:14:07.149  6023  5692 W google-breakpad: M EB781000 00000000 0001B000 E439051B61677F9DFD3F42CE220CD6BF0 libkeymaster1.so
08-29 10:14:07.150  6023  5692 W google-breakpad: M EB79C000 00000000 0000B000 E8088E2F98915A39B7E6BB1A2AE039FC0 libkeymaster_messages.so
08-29 10:14:07.150  6023  5692 W google-breakpad: M EB7A7000 00000000 00017000 99D07246332625058656EB559772107B0 libsoftkeymasterdevice.so
08-29 10:14:07.150  6023  5692 W google-breakpad: M EB7BE000 00000000 0000E000 AAC8B8364869B51CC4A97DD5C714EC090 libkeystore_binder.so
08-29 10:14:07.150  6023  5692 W google-breakpad: M EB7CC000 00000000 00006000 7124D8564C80C3094310ABA6614DAB910 libkeystore-engine.so
08-29 10:14:07.150  6023  5692 W google-breakpad: M EB7D2000 00000000 00018000 C9BCB517EF2F7870833E2F3C429DB9F40 libjavacrypto.so
08-29 10:14:07.150  6023  5692 W google-breakpad: M EB7EA000 00000000 00010000 A30E9C5A862E832BBFAF3B434C76D0E60 libstagefright_amrnb_common.so
08-29 10:14:07.150  6023  5692 W google-breakpad: M EB7FA000 00000000 0002C000 F966FB2BA53F2EA33FE2DC60D471CD690 libexif.so
08-29 10:14:07.151  6023  5692 W google-breakpad: M EB826000 00000000 0000D000 D496E3E66F10D038A0738EF56F5D28450 libjhead.so
08-29 10:14:07.151  6023  5692 W google-breakpad: M EB834000 00000000 00018000 854FF85550BC71CA99F164BBFC01DAF70 libmtp.so
08-29 10:14:07.151  6023  5692 W google-breakpad: M EB84C000 00000000 00048000 A51AEB9B46575764C3EAA336E538D1080 libmedia_jni.so
08-29 10:14:07.151  6023  5692 W google-breakpad: M EF42E000 00000000 00005000 C6914C460B039E1DD0A076573642AD390 memtrack.msm8994.so
08-29 10:14:07.151  6023  5692 W google-breakpad: M F0C8A000 00000000 00036000 CB9619B03795746AAA7B2060E3A7BE720 libjavacore.so
08-29 10:14:07.151  6023  5692 W google-breakpad: M F3CC7000 00000000 00007000 6C110E4E29910EB42E10D6F6540BB0DA0 libwebviewchromium_plat_support.so
08-29 10:14:07.152  6023  5692 W google-breakpad: M F4E40000 00000000 0043E000 32304ECAD6A88D7903804F1C66435D9D0 libart.so
08-29 10:14:07.152  6023  5692 W google-breakpad: M F53A6000 00000000 00005000 75AF6776553AB98F3136C4BB66B9B8350 libsigchain.so
08-29 10:14:07.152  6023  5692 W google-breakpad: M F53CE000 00000000 00A5C000 DAB3693CB3D62A215B4DF68A97016FE10 libLLVM.so
08-29 10:14:07.152  6023  5692 W google-breakpad: M F5E33000 00000000 00038000 40CAD887423CB4B9F2FCBD2F28DA0F9C0 libbcinfo.so
08-29 10:14:07.152  6023  5692 W google-breakpad: M F5E6B000 00000000 0005B000 E3C922410FBE6C53FB58D9CC11445D590 libbcc.so
08-29 10:14:07.152  6023  5692 W google-breakpad: M F5EC6000 00000000 0000E000 0A07F40D33AB1AB4FE7F49FCEF1123210 libcommon_time_client.so
08-29 10:14:07.153  6023  5692 W google-breakpad: M F5ED5000 00000000 0001A000 6E54DD91A07BB3BA2B3A1101AA80A6CA0 libprotobuf-cpp-lite.so
08-29 10:14:07.153  6023  5692 W google-breakpad: M F5EEF000 00000000 00009000 2B5487ACE2353DD06BBCE0A5EDD1743B0 libstagefright_avc_common.so
08-29 10:14:07.153  6023  5692 W google-breakpad: M F5EF8000 00000000 00005000 BF77B7B0D8CB1C05D4D9E3FCCB1170B80 libstagefright_enc_common.so
08-29 10:14:07.153  6023  5692 W google-breakpad: M F5EFD000 00000000 00007000 64ADBA13487D816709EFE00E09533FE90 libpowermanager.so
08-29 10:14:07.153  6023  5692 W google-breakpad: M F5F04000 00000000 0001F000 E8E48A8A038C3906547FF85CB5705F080 libvorbisidec.so
08-29 10:14:07.153  6023  5692 W google-breakpad: M F5F23000 00000000 00007000 D691E3BDC885CAD2755A032365DBA9F60 libstagefright_yuv.so
08-29 10:14:07.153  6023  5692 W google-breakpad: M F5F2B000 00000000 00031000 FB9D7DEA0FD7FF5CBDC2193B99563E240 libstagefright_omx.so
08-29 10:14:07.154  6023  5692 W google-breakpad: M F5F5C000 00000000 0003B000 8BEDD672CFE24C6501C062987355048F0 libopus.so
08-29 10:14:07.154  6023  5692 W google-breakpad: M F5F97000 00000000 0000A000 243D48365B04A9984861FE1070F7D5EA0 libmediautils.so
08-29 10:14:07.154  6023  5692 W google-breakpad: M F5FA1000 00000000 0001A000 2B8DFBC34A301BBCD2EACC1D4EC5F87C0 libdrmframework.so
08-29 10:14:07.154  6023  5692 W google-breakpad: M F5FBB000 00000000 00021000 DDFFAC3DD86DC2CDE3524D60A3B79A770 libRScpp.so
08-29 10:14:07.154  6023  5692 W google-breakpad: M F5FDC000 00000000 00042000 4C6ADF2D12ED95F098C3825836A121780 libRS.so
08-29 10:14:07.154  6023  5692 W google-breakpad: M F601E000 00000000 00009000 B86B8D56E3DAFE2157FD5DABA96EECD80 libspeexresampler.so
08-29 10:14:07.155  6023  5692 W google-breakpad: M F6027000 00000000 0000B000 2F133C88A93CB2F0DE77E2B7DE1536B00 libnbaio.so
08-29 10:14:07.155  6023  5692 W google-breakpad: M F6032000 00000000 00014000 CC12E7EDBFEC6E454AE9494ABEE9EFDA0 libpcre.so
08-29 10:14:07.155  6023  5692 W google-breakpad: M F6048000 00000000 00007000 EC71E0A1B0B0C3D56D0E65A52AC0DF840 libwpa_client.so
08-29 10:14:07.155  6023  5692 W google-breakpad: M F604F000 00000000 00070000 E287C2E859528ABFED0B89978D77CF7D0 libGLES_trace.so
08-29 10:14:07.155  6023  5692 W google-breakpad: M F60BF000 00000000 00060000 417F31D47E493B04948253130232ECE40 libft2.so
08-29 10:14:07.155  6023  5692 W google-breakpad: M F611F000 00000000 00029000 ABE88CF058C41846BB868531DE4AE9270 libpng.so
08-29 10:14:07.155  6023  5692 W google-breakpad: M F6148000 00000000 00005000 2BD3C7B1FFED399A80E1738CA98FE5C90 libsync.so
08-29 10:14:07.156  6023  5692 W google-breakpad: M F614D000 00000000 00007000 5BA2119D7F6CE5C6D136A605F8A56A760 libstdc++.so
08-29 10:14:07.156  6023  5692 W google-breakpad: M F6154000 00000000 00012000 EFE46990D315C91EA8CE5B49CBA412590 libunwind.so
08-29 10:14:07.156  6023  5692 W google-breakpad: M F61AC000 00000000 0000B000 4BA181B986621E95CD896678406AB92E0 libbase.so
08-29 10:14:07.156  6023  5692 W google-breakpad: M F61B7000 00000000 00007000 590072798B82D2C632B663BC840870A40 libeffects.so
08-29 10:14:07.156  6023  5692 W google-breakpad: M F61BF000 00000000 00006000 9D67808340C0D180BDA4867A48D94B2D0 libstagefright_http_support.so
08-29 10:14:07.156  6023  5692 W google-breakpad: M F61C5000 00000000 0001B000 663413A116109C22EE8494845825536F0 libstagefright_foundation.so
08-29 10:14:07.156  6023  5692 W google-breakpad: M F61E0000 00000000 0015E000 A5EE56A98E44C772CFBBAA4A6B7185880 libstagefright.so
08-29 10:14:07.157  6023  5692 W google-breakpad: M F633E000 00000000 0006B000 4B0D691415E871CE1C146B803882B32A0 libhwui.so
08-29 10:14:07.157  6023  5692 W google-breakpad: M F63A9000 00000000 00005000 1C55C2519DE085BB2728F75F1C3ACAB20 libradio_metadata.so
08-29 10:14:07.157  6023  5692 W google-breakpad: M F63AE000 00000000 00006000 3A1BD9CA3B4C87A52BDEB8D62DD9ACEA0 libnativebridge.so
08-29 10:14:07.157  6023  5692 W google-breakpad: M F63B4000 00000000 00006000 FFE62BC8EFC1E49D563F7792851B9F0D0 libprocessgroup.so
08-29 10:14:07.157  6023  5692 W google-breakpad: M F63BA000 00000000 00010000 D5843C716D5C4F5F562F1948BE023FAA0 libminikin.so
08-29 10:14:07.157  6023  5692 W google-breakpad: M F63CA000 00000000 0000E000 26EDA16D972D3FDC0D0364150028368F0 libsoundtrigger.so
08-29 10:14:07.158  6023  5692 W google-breakpad: M F63D9000 00000000 0000E000 A086A6E27F856978984805A3AFAEB7F50 libradio.so
08-29 10:14:07.158  6023  5692 W google-breakpad: M F63E7000 00000000 00006000 DE9A49AB4F78A68C19AB05800ED168E50 libnetd_client.so
08-29 10:14:07.158  6023  5692 W google-breakpad: M F63ED000 00000000 00010000 400219A7C4C5F24D08144D12DB0292170 libimg_utils.so
08-29 10:14:07.158  6023  5692 W google-breakpad: M F63FD000 00000000 00409000 F680938ABD551E5D7E41D6701CEED06F0 libpdfium.so
08-29 10:14:07.158  6023  5692 W google-breakpad: M F6807000 00000000 00009000 3725DB0D6CA8B7874343971EB9ED487E0 libaudioutils.so
08-29 10:14:07.158  6023  5692 W google-breakpad: M F6810000 00000000 0001C000 8B733D3C558331A0B76E1467AD5AA35B0 libz.so
08-29 10:14:07.158  6023  5692 W google-breakpad: M F682D000 00000000 0004B000 0A6EC0834FC5D471152B11EA5E634B4A0 libharfbuzz_ng.so
08-29 10:14:07.159  6023  5692 W google-breakpad: M F6878000 00000000 00007000 CD1C791909DD4926B8BA079AD31C4A700 libusbhost.so
08-29 10:14:07.159  6023  5692 W google-breakpad: M F687F000 00000000 00037000 C51C43C302671B6EE317F355493C6DAD0 libjpeg.so
08-29 10:14:07.159  6023  5692 W google-breakpad: M F68B7000 00000000 000AD000 B8DC39B4673BFD20555C95A00834F3E90 libmedia.so
08-29 10:14:07.159  6023  5692 W google-breakpad: M F6964000 00000000 00170000 AA15D547E8579895F3DDC3800384EBD20 libicui18n.so
08-29 10:14:07.159  6023  5692 W google-breakpad: M F6AD4000 00000000 0011A000 B5A7AC2059E716204605A25A1BC628A50 libicuuc.so
08-29 10:14:07.159  6023  5692 W google-breakpad: M F6BF2000 00000000 00026000 2AA07E155C9E8E7BF9F2CA2B81E068620 libssl.so
08-29 10:14:07.159  6023  5692 W google-breakpad: M F6C18000 00000000 0009D000 723D1653E2ACC92122DED61EEE06856D0 libcrypto.so
08-29 10:14:07.160  6023  5692 W google-breakpad: M F6CB5000 00000000 00054000 B57AE8285AF41584C7E0DC597498D0A10 libsonivox.so
08-29 10:14:07.160  6023  5692 W google-breakpad: M F6D0E000 00000000 00011000 4B209B82F0F22AAF185DA504078CB3680 libselinux.so
08-29 10:14:07.160  6023  5692 W google-breakpad: M F6D1F000 00000000 00008000 592DED42C8EF235A6E18FBD9FF1706A90 libhardware_legacy.so
08-29 10:14:07.160  6023  5692 W google-breakpad: M F6D28000 00000000 00005000 E6C2C99F72B5E5958A42FEBEB06F31170 libhardware.so
08-29 10:14:07.160  6023  5692 W google-breakpad: M F6D2D000 00000000 00006000 C64AEDD38F51FD36501D25CD0BFDE6720 libETC1.so
08-29 10:14:07.160  6023  5692 W google-breakpad: M F6D33000 00000000 0000F000 C42685E5A1F9AB31F90772E6DB8720610 libGLESv2.so
08-29 10:14:07.160  6023  5692 W google-breakpad: M F6D42000 00000000 0000A000 E8739084961F72CD83CED9F365AB20590 libGLESv1_CM.so
08-29 10:14:07.161  6023  5692 W google-breakpad: M F6D4C000 00000000 00068000 DE0DC45A2E4287CCFA86E5AE61ECC9D90 libEGL.so
08-29 10:14:07.161  6023  5692 W google-breakpad: M F6DB7000 00000000 00065000 642980B0D28CD75F45C9A9F9D7CCEB770 libsqlite.so
08-29 10:14:07.161  6023  5692 W google-breakpad: M F6E1D000 00000000 0026E000 DB552323AD4C176BE69BAB79954B923A0 libskia.so
08-29 10:14:07.161  6023  5692 W google-breakpad: M F708F000 00000000 0000A000 3AD6F174CB8F4031C21F4D1B5A80F7250 libcamera_metadata.so
08-29 10:14:07.161  6023  5692 W google-breakpad: M F7099000 00000000 0002D000 7E6E915F8253B61FF8C812F873A2DA560 libcamera_client.so
08-29 10:14:07.161  6023  5692 W google-breakpad: M F70C6000 00000000 0003F000 7AEBC1C9683A7A6A864B7374C7F76A0E0 libinputflinger.so
08-29 10:14:07.161  6023  5692 W google-breakpad: M F7105000 00000000 0001F000 1A399C51F7284B5F858A09C1C2E3E01F0 libinput.so
08-29 10:14:07.162  6023  5692 W google-breakpad: M F7124000 00000000 0005A000 8F0C986C217D3D2C0158FDB14E0C60670 libgui.so
08-29 10:14:07.162  6023  5692 W google-breakpad: M F717E000 00000000 00010000 EA05E3FC7057E2C072FF1B3027067F090 libui.so
08-29 10:14:07.162  6023  5692 W google-breakpad: M F718E000 00000000 00009000 214A3A38E289ED4F1F9CEE388493A7B90 libnetutils.so
08-29 10:14:07.162  6023  5692 W google-breakpad: M F7197000 00000000 00009000 DE14DD2D1F9705EEF5017113E22C06C70 libnativehelper.so
08-29 10:14:07.162  6023  5692 W google-breakpad: M F71A0000 00000000 00017000 DC0DA3BACECC3083775C728D9B8614B50 libexpat.so
08-29 10:14:07.162  6023  5692 W google-breakpad: M F71B7000 00000000 0002A000 9512A24B3BDCD0227B91F9706E6116600 libandroidfw.so
08-29 10:14:07.162  6023  5692 W google-breakpad: M F71E1000 00000000 00005000 643BA116A83C0A166C61B94D49CC532A0 libmemtrack.so
08-29 10:14:07.163  6023  5692 W google-breakpad: M F71E6000 00000000 0000B000 FE53EEFC2205BD79BADE2A6EBDFCFDE50 libbacktrace.so
08-29 10:14:07.163  6023  5692 W google-breakpad: M F71F1000 00000000 00022000 6D303961A1FAFDA6B15029FAC5AB18480 libm.so
08-29 10:14:07.163  6023  5692 W google-breakpad: M F7213000 00000000 0007A000 0F8B5F2ADE384B2AFE6CE1AF2F492B450 libc.so
08-29 10:14:07.163  6023  5692 W google-breakpad: M F7297000 00000000 0008E000 CDB486C99025F7F8D15E2F0F1A2F89C30 libc++.so
08-29 10:14:07.163  6023  5692 W google-breakpad: M F7326000 00000000 0002D000 B149677799DE5B6A31BE6776BB3B82990 libwilhelm.so
08-29 10:14:07.163  6023  5692 W google-breakpad: M F7353000 00000000 000DA000 CAC6EB6C03DC6A2765A7E1F27BCD50B30 libandroid_runtime.so
08-29 10:14:07.163  6023  5692 W google-breakpad: M F7432000 00000000 0002E000 D4E3CEEA7F93590D640F5F0D28CEFD540 libbinder.so
08-29 10:14:07.164  6023  5692 W google-breakpad: M F7460000 00000000 0000A000 6A03EA629609C40EC6B3DCC07B26D0570 liblog.so
08-29 10:14:07.164  6023  5692 W google-breakpad: M F746A000 00000000 0001B000 CE0B322AF9DA5065B2550F65897133970 libutils.so
08-29 10:14:07.164  6023  5692 W google-breakpad: M F7485000 00000000 00011000 A6929D93790B0B6C0AFA91E53F1D52540 libcutils.so
08-29 10:14:07.164  6023  5692 W google-breakpad: M F74C1000 00000000 00020000 544467D601D3951FF72DAA303DB6B4650 linker
08-29 10:14:07.164  6023  5692 W google-breakpad: -----END BREAKPAD MICRODUMP-----
,08-29 10:14:07.189  5646  5692 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-29 10:14:07.189  5646  5692 W google-breakpad: Chrome build fingerprint:
08-29 10:14:07.189  5646  5692 W google-breakpad: 0.0.1
08-29 10:14:07.189  5646  5692 W google-breakpad: 19
08-29 10:14:07.189  5646  5692 W google-breakpad: 0ac25ff3-fa94-4ee3-b183-8999384c3b93
08-29 10:14:07.189  5646  5692 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-29 10:14:07.189  5646  5692 E chromium: ### WebView Version 44.0.2403.117 (code 246011750)
--------- beginning of crash
08-29 10:14:07.189  5646  5692 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 5692 (Thread-57)
,08-29 10:14:07.311   508   508 I SELinux : SELinux: Loaded file_contexts contexts from /file_contexts.
,08-29 10:14:07.316   508   508 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,08-29 10:14:07.317   508   508 F DEBUG   : Build fingerprint: 'google/angler/angler:6.0.1/MMB29M/2431559:user/release-keys'
08-29 10:14:07.317   508   508 F DEBUG   : Revision: '0'
08-29 10:14:07.317   508   508 F DEBUG   : ABI: 'arm'
08-29 10:14:07.318   508   508 F DEBUG   : pid: 5646, tid: 5692, name: Thread-57  >>> com.test.thalitest <<<
08-29 10:14:07.318   508   508 F DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,08-29 10:14:07.348   508   508 F DEBUG   :     r0 dbb5f000  r1 00000000  r2 d9e573b4  r3 d9e57430
08-29 10:14:07.349   508   508 F DEBUG   :     r4 d9e57388  r5 d9e573dc  r6 dec79fa0  r7 d9e573b4
08-29 10:14:07.349   508   508 F DEBUG   :     r8 d8283f00  r9 ffffff85  sl dbb35a80  fp d9e573ac
,08-29 10:14:07.349   508   508 F DEBUG   :     ip d9e57370  sp d9e57378  lr da523978  pc da52397c  cpsr 200f0010
08-29 10:14:07.352   508   508 F DEBUG   : 
08-29 10:14:07.352   508   508 F DEBUG   : backtrace:
,08-29 10:14:07.352   508   508 F DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_SetPropertyById(JSContext*, JS::Handle<JSObject*>, JS::Handle<jsid>, JS::Handle<JS::Value>)+44)
08-29 10:14:07.352   508   508 F DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_SetProperty(JSContext*, JS::Handle<JSObject*>, char const*, JS::Handle<JS::Value>)+132)
08-29 10:14:07.353   508   508 F DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::SetProperty(char const*, JS::Handle<JS::Value>)+88)
,08-29 10:14:07.869   508   508 F DEBUG   : 
08-29 10:14:07.869   508   508 F DEBUG   : Tombstone written to: /data/tombstones/tombstone_00
08-29 10:14:07.869   508   508 E DEBUG   : AM write failed: Broken pipe
,08-29 10:14:07.870   929   945 I BootReceiver: Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
08-29 10:14:07.872   929  6024 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
08-29 10:14:07.873   380   380 E lowmemorykiller: Error writing /proc/5646/oom_score_adj; errno=22
08-29 10:14:07.874   929  6024 I ActivityManager: Killing 5531:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 10:14:07.918   929  3047 W InputDispatcher: channel 'c60ebd7 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-29 10:14:07.918   929  3047 E InputDispatcher: channel 'c60ebd7 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-29 10:14:07.921   929   939 I WindowState: WIN DEATH: Window{c60ebd7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 10:14:07.921   929   939 W InputDispatcher: Attempted to unregister already unregistered input channel 'c60ebd7 com.test.thalitest/com.test.thalitest.MainActivity (server)'
08-29 10:14:07.922   929  3235 D GraphicsStats: Buffer count: 2
08-29 10:14:07.922   929  3068 D WifiService: Client connection lost with reason: 4
,08-29 10:14:07.936   527   527 I Zygote  : Process 5646 exited due to signal (11)
,08-29 10:14:07.941   929  3624 I ActivityManager: Process com.test.thalitest (pid 5646) has died
,08-29 10:14:21.202   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:14:22.203   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:14:23.205   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:14:24.206   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:14:25.207   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:14:26.195   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=420020, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:14:26.208   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:14:51.210   605   605 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:14:51.210   605   605 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:15:11.212   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:12.215   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:13.217   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:14.219   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:15.221   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:16.222   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:15:21.223   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:22.225   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:23.226   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:24.227   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:25.229   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:26.230   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:15:36.232   605   605 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:15:37.234   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:38.236   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:39.237   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:40.238   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:41.239   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:15:56.241   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:57.243   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:58.245   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:15:59.247   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:16:00.249   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:16:01.251   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:16:21.253   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:16:22.255   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:16:23.258   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:16:24.260   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:16:25.261   605   605 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:16:26.262   605   605 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:16:51.263   605   605 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:16:51.263   605   605 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:17:16.277   605  1028 E QC-QMI  : qmi_client [605] a: failed to locate client data
,08-29 10:17:16.280   519   519 E QC-QMI  : qmuxd: RX on fd=15 returned error=0 errno[2:No such file or directory]
08-29 10:17:16.280   519   519 E QC-QMI  : QMUX qmux_client_id=a not found in qmux client list, unable to remove
08-29 10:17:16.281   605   605 I Atfwd_Daemon: Stop the daemon....
,08-29 10:17:16.318  6029  6029 W ATFWD-daemon: type=1400 audit(0.0:73): avc: denied { read write } for name="diag" dev="tmpfs" ino=12554 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,08-29 10:17:16.329  6029  6029 I libmdmdetect: ESOC framework not supported
08-29 10:17:16.330  6029  6029 I libmdmdetect: Found internal modem: modem
08-29 10:17:16.331  6029  6029 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 10:17:16.339  6029  6029 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 10:17:16.340  6029  6029 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,08-29 10:17:16.341  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:17.344  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:18.345  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:19.346  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:20.347  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:21.347  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:17:26.349  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:27.350  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:28.352  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:29.353  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:30.355  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:31.356  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:17:41.357  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:42.359  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:43.360  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:44.362  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:45.363  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:17:46.364  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:17:46.537   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=620362, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 10:18:01.366  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:02.368  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:03.370  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:04.372  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:05.375  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:06.377  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:18:26.379  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:27.381  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:28.383  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:29.385  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:30.386  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:18:31.135   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=664960, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:18:31.387  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:18:46.326   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=680151, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 10:18:56.388  6029  6029 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:18:56.388  6029  6029 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:19:01.389  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:02.391  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:03.392  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:04.394  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:05.395  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:06.396  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:19:11.398  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:12.399  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:13.401  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:14.402  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:15.403  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:16.404  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:19:26.406  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:27.407  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:28.409  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:29.410  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:30.412  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:30.976   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=724801, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:19:31.413  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:19:45.346   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=739171, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 10:19:46.414  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:47.415  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:48.416  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:49.417  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:50.418  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:19:51.419  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:20:11.421  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:12.422  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:13.423  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:14.424  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:15.425  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:16.425  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:20:29.856   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=783681, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:20:41.426  6029  6029 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:20:41.427  6029  6029 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:20:51.428  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:52.430  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:53.431  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:54.432  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:55.434  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:20:56.435  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:21:01.436  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:02.438  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:03.439  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:04.441  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:05.442  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:06.443  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:21:16.445  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:17.446  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:18.448  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:19.449  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:20.451  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:21.452  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:21:36.454  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:37.456  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:38.458  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:39.460  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:40.462  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:21:41.463  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:22:01.465  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:02.467  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:03.469  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:04.470  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:05.471  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:06.472  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:22:31.473  6029  6029 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:22:31.474  6029  6029 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:22:46.475  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:47.477  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:48.478  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:49.480  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:50.481  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:51.482  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:22:56.483  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:57.485  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:58.486  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:22:59.488  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:00.489  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:01.490  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:23:11.492  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:12.495  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:13.497  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:14.498  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:15.499  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:16.500  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:23:31.502  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:32.504  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:33.506  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:34.508  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:35.510  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:36.512  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:23:56.514  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:57.516  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:58.518  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:59.521  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:00.522  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:01.522  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:24:26.524  6029  6029 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:24:26.524  6029  6029 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:24:46.526  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:47.528  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:48.530  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:49.533  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:50.535  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:51.537  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:24:56.538  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:57.539  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:58.541  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:59.542  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:00.544  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:01.545  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:25:11.546  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:12.548  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:13.549  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:14.550  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:15.552  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:16.553  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:25:31.555  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:32.557  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:33.559  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:34.561  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:35.563  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:36.564  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:25:56.566  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:57.568  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:58.570  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:25:59.571  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:26:00.572  6029  6029 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:26:01.572  6029  6029 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:26:26.574  6029  6029 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:26:26.575  6029  6029 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:26:51.586  6029  6031 E QC-QMI  : qmi_client [6029] 1d: failed to locate client data
,08-29 10:26:51.589   519   519 E QC-QMI  : qmuxd: RX on fd=15 returned error=0 errno[2:No such file or directory]
,08-29 10:26:51.590   519   519 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
08-29 10:26:51.591  6029  6029 I Atfwd_Daemon: Stop the daemon....
,08-29 10:26:51.638  6044  6044 W ATFWD-daemon: type=1400 audit(0.0:74): avc: denied { read write } for name="diag" dev="tmpfs" ino=12554 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,08-29 10:26:51.645  6044  6044 I libmdmdetect: ESOC framework not supported
08-29 10:26:51.645  6044  6044 I libmdmdetect: Found internal modem: modem
08-29 10:26:51.646  6044  6044 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-29 10:26:51.655  6044  6044 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,08-29 10:26:51.655  6044  6044 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,08-29 10:26:51.656  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:26:52.660  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:26:53.662  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:26:54.664  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:26:55.666  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:26:56.668  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:27:01.669  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:02.671  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:03.672  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:04.674  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:05.675  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:06.676  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:27:16.677  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:17.679  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:18.680  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:19.682  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:20.683  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:21.684  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:27:36.686  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:37.688  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:38.691  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:39.693  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:40.695  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:27:41.695  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:27:47.135   929   941 I UsageStatsService: User[0] Flushing usage stats to disk
,08-29 10:28:01.698  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:02.700  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:03.702  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:04.704  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:05.706  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:06.708  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:28:27.283   929  3218 I ActivityManager: Start proc 6048:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-29 10:28:27.340  6048  6048 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,08-29 10:28:27.360  6048  6048 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 10:28:27.360  6048  6048 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 10:28:27.360  6048  6048 I GAv4    :   adb logcat -s GAv4
,08-29 10:28:27.375  6048  6048 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:28:27.380  6048  6048 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:28:27.392  6048  6063 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:28:31.708  6044  6044 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:28:31.709  6044  6044 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:28:36.710  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:37.712  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:38.713  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:39.715  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:40.716  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:41.621   929  3517 I ActivityManager: Start proc 6066:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-29 10:28:41.667  6066  6066 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,08-29 10:28:41.686  3670  6078 I VacuumService: Vacuum at: now=1472480921686 tag=VacuumService
,08-29 10:28:41.717  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:28:41.774  6066  6079 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,08-29 10:28:41.853  6066  6079 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 10:28:41.906  6066  6079 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 10:28:41.927  6092  6092 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads1414445248.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1414445248.dex
,08-29 10:28:41.935  6066  6066 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-29 10:28:41.963  6092  6092 I dex2oat : dex2oat took 36.987ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1258KB free=1045KB
,08-29 10:28:42.053  6066  6066 W InstanceID/Rpc: Found 10012
,08-29 10:28:42.103   929  3517 I ActivityManager: Killing 5448:android.process.acore/u0a2 (adj 15): empty #17
,08-29 10:28:42.177  3670  6149 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,08-29 10:28:42.217  3670  6145 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-29 10:28:42.220  3670  6145 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 10:28:42.236  3670  6145 W Uploader:  no longer exists, so no auth token.
,08-29 10:28:42.244  3670  6149 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 10:28:42.672  3670  6151 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 10:28:42.782  3670  6149 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 10:28:42.871  3670  6145 W Uploader:  no longer exists, so no auth token.
,08-29 10:28:42.882  3670  6151 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 10:28:42.972  3670  6149 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,08-29 10:28:46.645   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1280470, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:28:46.717  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:47.718  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:48.720  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:49.721  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:50.722  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:28:51.723  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:29:01.725  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:02.616   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1296441, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:29:02.726  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:03.727  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:04.729  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:05.730  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:06.731  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:29:21.733  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:22.735  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:23.737  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:24.739  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:25.741  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:26.743  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:29:46.745  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:47.746  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:48.749  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:49.751  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:50.752  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:29:51.752  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:30:16.754  6044  6044 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:30:16.755  6044  6044 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:30:26.756  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:27.757  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:28.759  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:29.760  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:30.762  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:31.763  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:30:36.765  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:37.766  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:38.767  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:39.769  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:40.770  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:41.771  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:30:51.773  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:52.775  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:53.777  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:54.779  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:55.780  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:30:56.780  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:31:11.782  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:12.784  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:13.786  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:14.789  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:15.791  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:16.792  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:31:36.795  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:37.797  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:38.799  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:39.801  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:40.802  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:31:41.803  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:32:06.804  6044  6044 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:32:06.805  6044  6044 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:32:21.806  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:22.807  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:23.809  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:24.810  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:25.811  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:26.812  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:32:31.814  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:32.816  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:33.817  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:34.818  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:35.820  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:36.821  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:32:46.822  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:47.824  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:48.166   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1521992, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 10:32:48.825  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:49.826  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:50.828  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:32:51.829  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:33:06.831  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:07.776   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1541601, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:33:07.833  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:08.835  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:09.837  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:10.839  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:11.840  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:33:31.842  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:32.845  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:33.847  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:34.848  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:35.849  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:33:36.850  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-29 10:33:47.225   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1581051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 10:34:01.851  6044  6044 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,08-29 10:34:01.851  6044  6044 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:34:02.296   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1596121, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 10:34:21.853  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:22.855  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:23.857  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:24.858  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:25.858  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:26.859  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 10:34:31.860  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:32.862  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:33.863  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:34.865  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:35.866  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:36.867  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:34:46.869  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:47.870  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:48.872  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:49.873  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:50.875  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:34:51.875  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 10:35:06.878  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:07.880  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:08.882  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:09.884  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:10.886  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:11.887  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 10:35:31.889  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:32.891  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:33.893  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:34.894  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:35.895  6044  6044 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:35:36.896  6044  6044 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,TIME-OUT KILL (timeout was 1400000ms)
```
