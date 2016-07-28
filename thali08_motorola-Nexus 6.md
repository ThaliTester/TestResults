#### Test 776224163c26f5f_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-28 09:45:21.235   875  1994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-28 09:45:21.877  3673  3673 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-28 09:45:21.881  3673  3673 D AndroidRuntime: CheckJNI is OFF
07-28 09:45:21.916  3673  3673 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-28 09:45:21.959  3673  3673 I Radio-JNI: register_android_hardware_Radio DONE
07-28 09:45:21.979  3673  3673 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-28 09:45:21.984   875  1735 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 09:45:22.047   875  1735 I ActivityManager: Start proc 3682:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-28 09:45:22.058  3673  3673 D AndroidRuntime: Shutting down VM
07-28 09:45:22.152  3682  3682 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-28 09:45:22.183  3682  3682 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-28 09:45:22.195  3682  3682 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8102-8107)
07-28 09:45:22.195  3682  3682 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 09:45:22.216  3682  3682 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {53ff6e2}
07-28 09:45:22.216  3682  3682 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 09:45:22.217  3682  3682 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 09:45:22.222  3682  3682 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-28 09:45:22.223  3682  3682 E SysUtils: ApplicationContext is null in ApplicationStatus
07-28 09:45:22.243  3682  3682 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-28 09:45:22.253  3682  3682 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 09:45:22.253  3682  3682 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 09:45:22.253  3682  3682 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-28 09:45:22.253  3682  3682 I Adreno  : Build Date                       : 10/20/15
07-28 09:45:22.253  3682  3682 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-28 09:45:22.253  3682  3682 I Adreno  : Local Branch                     : M14
07-28 09:45:22.253  3682  3682 I Adreno  : Remote Branch                    : 
07-28 09:45:22.253  3682  3682 I Adreno  : Remote Branch                    : 
07-28 09:45:22.253  3682  3682 I Adreno  : Reconstruct Branch               : 
,07-28 09:45:22.349   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5368258:true
,07-28 09:45:22.385  3682  3682 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-28 09:45:22.399  3682  3682 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-28 09:45:22.441  3682  3719 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-28 09:45:22.452  3682  3706 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-28 09:45:22.497  3682  3719 I OpenGLRenderer: Initialized EGL, version 1.4
,07-28 09:45:22.547  1653  1653 I Keyboard.Facilitator: onFinishInput()
,07-28 09:45:22.595   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +488ms (total +585ms)
,07-28 09:45:22.668  3682  3682 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3682
,07-28 09:45:22.807  3682  3682 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-28 09:45:22.981  3682  3722 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1679881936
,07-28 09:45:22.989  3682  3722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 09:45:22.989  3682  3722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 09:45:22.989  3682  3722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 09:45:22.989  3682  3722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 09:45:22.989  3682  3722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-28 09:45:22.990  3682  3722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1e5ea1 added. We now have 1 listener(s)
,07-28 09:45:22.994  3682  3722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-28 09:45:22.996  3682  3722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 09:45:22.997  3682  3722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 09:45:22.997  3682  3722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-28 09:45:23.001  3682  3722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9984bb4 added. We now have 1 listener(s)
,07-28 09:45:23.002  3682  3722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:23.007   875  1308 D WifiService: New client listening to asynchronous messages
,07-28 09:45:23.011  3682  3722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 09:45:23.011  3682  3722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-28 09:45:23.011  3682  3722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-28 09:45:23.012  3682  3722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-28 09:45:23.019  3682  3722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:23.019  3682  3722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-28 09:45:23.029  3682  3722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:23.029  3682  3722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:23.030  3682  3722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 09:45:23.030  3682  3722 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 09:45:23.030  3682  3722 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 09:45:23.035  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:23.040  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:23.064  3682  3682 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 09:45:23.815  3682  3729 W jxcore-log: Initializing JXcore engine
07-28 09:45:23.815  3682  3729 W jxcore-log: JXcore engine is ready
07-28 09:45:23.856  3729  3729 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
07-28 09:45:23.856  3729  3729 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11466]" dev="sockfs" ino=11466 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-28 09:45:23.856  3729  3729 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-28 09:45:23.856  3729  3729 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23213]" dev="sockfs" ino=23213 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-28 09:45:23.872  3682  3729 W jxcore-log: Starting JXcore engine
07-28 09:45:23.953  3682  3729 W jxcore-log: Platform android
07-28 09:45:23.953  3682  3729 W jxcore-log: 
07-28 09:45:23.954  3682  3729 W jxcore-log: Process ARCH arm
07-28 09:45:23.954  3682  3729 W jxcore-log: 
07-28 09:45:24.125  3682  3729 I jxcore-log: JXcore Cordova bridge is ready!
07-28 09:45:24.125  3682  3729 I jxcore-log: 
07-28 09:45:24.126  3682  3729 W jxcore-log: JXcore engine is started
07-28 09:45:24.136  3682  3722 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-28 09:45:24.142  3682  3682 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 09:45:34.480  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 09:45:34.480  3682  3729 I jxcore-log: 
,07-28 09:45:34.482  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 09:45:34.482  3682  3729 I jxcore-log: 
,07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:34.500  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:34.507  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 09:45:34.509  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 09:45:34.509  3682  3729 I jxcore-log: 
,07-28 09:45:34.511  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 09:45:34.511  3682  3729 I jxcore-log: 
,07-28 09:45:34.867  3682  3729 D ExecuteNativeTests: Running unit tests
,07-28 09:45:34.925  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 09:45:34.926  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 added. We now have 2 listener(s)
07-28 09:45:34.927  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 09:45:34.927  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:34.927  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:45:34.927  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:34.927  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 added. We now have 2 listener(s)
07-28 09:45:34.927  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:34.928  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 09:45:34.934  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:34.943  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:34.949  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 09:45:34.949  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:45:34.952  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 09:45:34.953  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 09:45:34.953  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 09:45:34.955  3682  3729 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-28 09:45:34.955  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:34.956  3682  3729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 09:45:34.956  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 09:45:34.956  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:45:34.956  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:45:34.956  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:34.957  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:34.957  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:34.957  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:34.957  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:34.957  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:34.958  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:34.958  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 removed from the list
07-28 09:45:34.958  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:34.958  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 removed from the list
07-28 09:45:34.960  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:34.961  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:34.961  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:34.962  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:34.962  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:34.967  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:34.967  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 09:45:34.967  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 09:45:34.967  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:34.969  3682  3729 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-28 09:45:34.970  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 09:45:34.970  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 09:45:34.970  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 09:45:34.970  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:34.970  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:34.970  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:34.970  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
,07-28 09:45:34.970  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:34.970  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:34.970  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:34.970  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:34.970  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:34.971  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:34.971  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:34.972  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:34.972  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:34.972  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:34.973  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:34.978  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 09:45:34.978  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 09:45:34.978  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-2,8 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 09:45:34.979  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 09:45:34.980  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 09:45:34.980  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:34.980  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:34.980  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:34.981  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:34.981  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:34.981  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:34.982  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:34.982  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:34.982  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:34.982  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:34.982  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:34.983  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:34.983  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:34.983  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:34.985  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:34.986  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:34.986  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:34.986  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:34.988  3682  3729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 09:45:34.992  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:35.004  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:45:35.009  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.009  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:45:35.010  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:45:35.010  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:45:35.010  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:35.010  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 09:45:35.026  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:35.031  3682  3729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 09:45:35.031  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 09:45:35.036  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:35.040  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 09:45:35.043  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 09:45:35.043  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 09:45:35.046  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-28 09:45:35.050  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-28 09:45:35.050  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-28 09:45:35.050  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 09:45:35.051  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 09:45:35.051  3682  3729 D BluetoothAdapter: STATE_ON
07-28 09:45:35.060  2561  2768 D BtGatt.GattService: registerClient() - UUID=918fd314-d9e5-4d80-b776-e54d92f8202d
07-28 09:45:35.062  2561  2612 D BtGatt.GattService: onClientRegistered() - UUID=918fd314-d9e5-4d80-b776-e54d92f8202d, clientIf=5
07-28 09:45:35.063  3682  3692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-28 09:45:35.065  2561  2572 D BtGatt.GattService: start scan with filters
,07-28 09:45:35.070  2561  2615 D BtGatt.ScanManager: handling starting scan
,07-28 09:45:35.070  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 09:45:35.071  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-28 09:45:35.072  2561  2615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:35.072  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-28 09:45:35.072  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 09:45:35.076  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 09:45:35.077  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-28 09:45:35.077  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 09:45:35.080  2561  2612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 09:45:35.080  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.081  2561  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,07-28 09:45:35.081  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 09:45:35.085  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-28 09:45:35.086  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.086  2561  2615 D BtGatt.ScanManager: Starting BLE batch scan
,07-28 09:45:35.086  2561  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-28 09:45:35.088  3682  3729 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 09:45:35.088  3682  3682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 09:45:35.088  3682  3682 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-28 09:45:35.095  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.095  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.096  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.096  2561  2612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
07-28 09:45:35.096  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.096  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-28 09:45:35.096  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-28 09:45:35.096  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 09:45:35.097  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-28 09:45:35.097  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 09:45:35.098  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 09:45:35.098  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 09:45:35.099  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:35.099  2561  2768 D BtGatt.GattService: stopScan() - queue size =1
07-28 09:45:35.100  2561  2572 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 09:45:35.101  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-28 09:45:35.101  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.101  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 09:45:35.102  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 09:45:35.102  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 09:45:35.102  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 09:45:35.102  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 09:45:35.103  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:35.104  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 09:45:35.104  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 09:45:35.104  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:45:35.105  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 09:45:35.107  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 09:45:35.107  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.107  2561  2615 D BtGatt.ScanManager: stopping BLe Batch
07-28 09:45:35.108  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.108  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:35.108  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:35.108  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.108  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.108  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:35.108  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.108  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 09:45:35.108  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.108  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:35.109  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:35.109  3682  3729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 09:45:35.112  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:35.114  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 09:45:35.114  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.114  2561  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 09:45:35.120  2561  2612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 09:45:35.121  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:35.123  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:35.129  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 09:45:35.130  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 09:45:35.130  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:45:35.130  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:45:35.131  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:35.131  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 09:45:35.133  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:35.136  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:35.139  3682  3729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-28 09:45:35.139  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 09:45:35.151  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 09:45:35.153  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-28 09:45:35.153  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 09:45:35.164  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 09:45:35.164  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-28 09:45:35.164  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-28 09:45:35.166  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:35.175  2561  2572 D BtGatt.GattService: registerClient() - UUID=d74bc3b6-81b0-4714-af4d-374d876527b4
,07-28 09:45:35.176  2561  2612 D BtGatt.GattService: onClientRegistered() - UUID=d74bc3b6-81b0-4714-af4d-374d876527b4, clientIf=5
,07-28 09:45:35.177  3682  3692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 09:45:35.178  2561  2768 D BtGatt.GattService: start scan with filters
,07-28 09:45:35.186  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-28 09:45:35.186  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 09:45:35.186  2561  2615 D BtGatt.ScanManager: handling starting scan
,07-28 09:45:35.186  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 09:45:35.187  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 09:45:35.197  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 09:45:35.198  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 09:45:35.199  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-28 09:45:35.203  2561  2612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 09:45:35.203  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.204  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 09:45:35.204  2561  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 09:45:35.211  3682  3729 I io.jxcore.node.ConnectionHelper: start: OK
07-28 09:45:35.211  3682  3682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:45:35.211  3682  3682 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-28 09:45:35.212  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 09:45:35.212  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.213  2561  2615 D BtGatt.ScanManager: Starting BLE batch scan
07-28 09:45:35.214  2561  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-28 09:45:35.217  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 09:45:35.217  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.217  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.218  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 09:45:35.218  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 09:45:35.218  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 09:45:35.218  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 09:45:35.218  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-28 09:45:35.219  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-28 09:45:35.221  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 09:45:35.224  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:35.235  2561  2572 D BtGatt.GattService: stopScan() - queue size =1
,07-28 09:45:35.240  2561  2768 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-28 09:45:35.241  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:45:35.241  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 09:45:35.241  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-28 09:45:35.241  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 09:45:35.241  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 09:45:35.244  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:35.244  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 09:45:35.244  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 09:45:35.244  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:45:35.245  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 09:45:35.247  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:35.247  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.248  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:35.248  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.248  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.248  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.248  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:35.249  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 09:45:35.250  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.251  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 09:45:35.251  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:35.251  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.251  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 09:45:35.252  2561  2612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 09:45:35.252  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.252  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:35.252  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 09:45:35.253  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.253  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.253  3682  3729 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-28 09:45:35.255  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:35.266  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:35.269  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 09:45:35.270  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:45:35.270  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 09:45:35.271  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:45:35.271  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:35.271  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 09:45:35.272  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 09:45:35.273  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.279  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:35.280  3682  3729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 09:45:35.281  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 09:45:35.282  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:35.286  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-28 09:45:35.287  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.287  2561  2615 D BtGatt.ScanManager: stopping BLe Batch
,07-28 09:45:35.289  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 09:45:35.290  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 09:45:35.291  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 09:45:35.296  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-28 09:45:35.297  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 09:45:35.297  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-28 09:45:35.298  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:35.301  2561  2758 D BtGatt.GattService: registerClient() - UUID=3c80630f-c212-44d1-838f-cb6cdadb1b4d
,07-28 09:45:35.302  2561  2612 D BtGatt.GattService: onClientRegistered() - UUID=3c80630f-c212-44d1-838f-cb6cdadb1b4d, clientIf=5
07-28 09:45:35.303  3682  3693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 09:45:35.303  2561  2574 D BtGatt.GattService: start scan with filters
07-28 09:45:35.303  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 09:45:35.303  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.304  2561  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 09:45:35.308  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 09:45:35.308  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 09:45:35.308  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 09:45:35.308  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-28 09:45:35.310  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 09:45:35.310  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 09:45:35.310  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 09:45:35.311  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 09:45:35.315  3682  3682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 09:45:35.316  3682  3682 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-28 09:45:35.316  3682  3729 I io.jxcore.node.ConnectionHelper: start: OK
07-28 09:45:35.316  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.316  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.316  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.317  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 09:45:35.317  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 09:45:35.317  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 09:45:35.318  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 09:45:35.318  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 09:45:35.318  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 09:45:35.318  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 09:45:35.320  3682  3729 D BluetoothAdapter: STATE_ON
07-28 09:45:35.321  2561  2574 D BtGatt.GattService: stopScan() - queue size =0
,07-28 09:45:35.322  2561  2768 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 09:45:35.322  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:45:35.322  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 09:45:35.322  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 09:45:35.323  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 09:45:35.323  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 09:45:35.324  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:35.324  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 09:45:35.324  2561  2612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
07-28 09:45:35.324  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 09:45:35.324  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.324  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 09:45:35.324  2561  2612 D BtGatt.GattService: current time is 281237585837
07-28 09:45:35.325  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:35.328  2561  2615 D BtGatt.ScanManager: handling starting scan
,07-28 09:45:35.328  2561  2612 D BtGatt.GattService: Batch record : [-111, 106, -71, 88, -82, -32, 1, 0, -104, 0, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -41, -99, 80, -91, 54, 55, -87, 70, 116, -52, -62, 2, 3, -25, 24, 63, 46, 60, 114, 28, 6, 8, 116, 105, 115, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 116, -43, -111, -91, -20, -29, 1, -128, -75, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
07-28 09:45:35.328  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:35.329  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 09:45:35.329  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 09:45:35.329  3682  3682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.330  3682  3682 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-28 09:45:35.330  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.330  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.330  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.331  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.331  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.331  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 09:45:35.331  2561  2612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -41, -99, 80, -91, 54, 55, -87, 70, 116, -52, -62, 2, 3, -25, 24, 63, 46, 60, 114, 6, 8, 116, 105, 115, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
07-28 09:45:35.331  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.331  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.331  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.331  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.331  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.332  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.332  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.332  2561  2612 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
07-28 09:45:35.333  2561  2612 E BtGatt.ContextMap: Context not found for ID 5
,07-28 09:45:35.334  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.334  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.334  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.334  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.335  3682  3729 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-28 09:45:35.336  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.336  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.336  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.337  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.337  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:35.337  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.337  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.338  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.338  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.338  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.338  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.338  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.338  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.338  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.339  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.340  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.340  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.340  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.341  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-28 09:45:35.341  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.342  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 09:45:35.342  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 09:45:35.342  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.342  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.343  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.343  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.343  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.343  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.343  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.343  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.343  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.343  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.343  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.344  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.344  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.344  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.344  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.345  2561  2612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-28 09:45:35.345  3682  3729 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 09:45:35.346  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.346  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 09:45:35.346  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 09:45:35.346  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.346  2561  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-28 09:45:35.346  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.347  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.347  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.347  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.347  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.347  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.347  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.347  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.347  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.347  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.347  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.350  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:35.350  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.350  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.350  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.352  3682  3729 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 09:45:35.352  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.352  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.352  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.353  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.353  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:35.353  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.353  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.354  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.354  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.354  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 09:45:35.354  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.354  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.355  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.355  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.355  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-28 09:45:35.355  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.356  2561  2615 D BtGatt.ScanManager: Starting BLE batch scan
07-28 09:45:35.356  2561  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-28 09:45:35.357  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:35.357  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.358  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.358  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.359  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 09:45:35.360  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 09:45:35.360  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 09:45:35.360  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:45:35.360  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 09:45:35.361  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 09:45:35.361  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.361  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.361  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.362  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:35.362  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:35.362  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.362  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
,07-28 09:45:35.363  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.364  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.365  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.365  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.365  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.365  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.366  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.370  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.370  2561  2612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 09:45:35.371  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.370  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 09:45:35.371  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.372  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.375  3682  3729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-28 09:45:35.375  3682  3729 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 09:45:35.376  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-28 09:45:35.378  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-28 09:45:35.378  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:35.385  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-28 09:45:35.385  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.385  2561  2615 D BtGatt.ScanManager: stopping BLe Batch
,07-28 09:45:35.391  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-28 09:45:35.391  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.391  3682  3729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 09:45:35.391  2561  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 09:45:35.392  3682  3729 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 09:45:35.392  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 09:45:35.392  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,07-28 09:45:35.393  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 09:45:35.393  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-28 09:45:35.393  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-28 09:45:35.393  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-28 09:45:35.394  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 09:45:35.395  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,07-28 09:45:35.396  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 09:45:35.396  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 09:45:35.396  3682  3729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 09:45:35.396  2561  2612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 09:45:35.396  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:35.396  3682  3729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 09:45:35.396  3682  3729 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 09:45:35.396  3682  3729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-28 09:45:35.396  3682  3729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 09:45:35.396  3682  3729 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 09:45:35.397  3682  3729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 09:45:35.397  3682  3729 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 09:45:35.397  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 09:45:35.400  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 09:45:35.401  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 09:45:35.401  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 09:45:35.402  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 09:45:35.402  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 09:45:35.402  3682  3729 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 09:45:35.402  3682  3729 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-28 09:45:35.402  3682  3729 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 09:45:35.403  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.403  3682  3731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 381)
07-28 09:45:35.403  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.403  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.403  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.403  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.403  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.403  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,07-28 09:45:35.404  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.404  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.404  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.404  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 09:45:35.404  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.404  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.404  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.404  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.405  3682  3732 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 381
07-28 09:45:35.405  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:35.405  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.405  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.405  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.406  3682  3731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:45:35.406  3682  3729 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 09:45:35.407  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.407  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.407  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.407  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:35.407  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.407  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.407  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.407  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.407  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.407  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.407  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.407  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.407  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.407  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.409  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.409  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.409  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 09:45:35.409  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.410  3682  3729 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 09:45:35.410  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.410  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.410  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 09:45:35.410  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.410  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.410  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.410  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.410  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.410  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.410  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 09:45:35.411  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.411  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.411  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.411  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.412  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:35.412  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.412  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.413  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.413  3682  3729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,07-28 09:45:35.413  3682  3729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 09:45:35.413  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 09:45:35.413  3682  3729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 09:45:35.413  3682  3729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-28 09:45:35.414  3682  3729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 09:45:35.414  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 09:45:35.414  3682  3729 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 09:45:35.414  3682  3729 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-28 09:45:35.414  3682  3729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 09:45:35.414  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 09:45:35.414  3682  3729 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 09:45:35.414  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.414  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 09:45:35.414  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.414  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.414  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.414  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.415  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
,07-28 09:45:35.415  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.415  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.415  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.415  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.415  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.415  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.415  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.416  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:35.416  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.416  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.417  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.417  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.417  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.417  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.417  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.417  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.417  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.417  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.418  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.418  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.418  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 09:45:35.418  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.418  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.418  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.418  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.418  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.418  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 09:45:35.418  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.418  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.418  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.418  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.418  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.419  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
,07-28 09:45:35.419  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.419  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.419  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.419  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.419  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.419  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.419  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.420  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.420  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.420  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.420  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.422  3682  3729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 09:45:35.422  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:35.423  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 09:45:35.424  3682  3729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 09:45:35.424  3682  3729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 09:45:35.424  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 09:45:35.424  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-28 09:45:35.424  3682  3682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 09:45:35.424  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.424  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-28 09:45:35.424  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 09:45:35.425  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 09:45:35.425  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.425  3682  3729 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,07-28 09:45:35.425  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.425  3682  3733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:45:35.425  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.425  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-28 09:45:35.425  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-28 09:45:35.425  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-28 09:45:35.425  3682  3682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 09:45:35.425  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:35.425  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.426  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:35.426  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.426  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.426  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.426  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.426  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:35.427  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.427  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:35.427  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:35.427  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.427  3682  3733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-28 09:45:35.427  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.427  3682  3733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 09:45:35.427  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.427  3682  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 09:45:35.427  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 09:45:35.427  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.427  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.427  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:35.427  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.427  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.427  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.427  3682  3682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 09:45:35.428  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.428  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.429  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.429  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
,07-28 09:45:35.430  3682  3729 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 09:45:35.430  3682  3729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 09:45:35.430  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 09:45:35.430  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 09:45:35.430  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.430  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.430  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.430  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.430  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.431  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.431  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.431  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.431  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.431  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.431  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:35.431  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.431  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.431  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.433  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.433  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.433  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.433  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.436  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.436  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.436  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:35.436  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.436  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.436  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.436  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.436  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.437  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.437  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 09:45:35.437  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.437  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.437  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.437  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.438  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.438  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:35.438  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.438  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.439  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:35.439  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:35.439  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 09:45:35.439  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:35.439  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.439  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.440  3682  3729 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d76523 not in the list
07-28 09:45:35.440  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.440  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.440  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:35.440  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.440  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.440  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:35.440  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:35.441  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:35.441  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 09:45:35.441  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:35.441  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f98ea20 not in the list
07-28 09:45:35.442  3682  3729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 09:45:35.442  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 09:45:35.442  3682  3729 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 09:45:35.442  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 09:45:35.442  3682  3729 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 09:45:35.442  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 09:45:35.444  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 09:45:35.444  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-28 09:45:35.445  3682  3729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 09:45:35.445  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 09:45:35.445  3682  3729 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 09:45:35.445  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 09:45:35.445  3682  3729 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 09:45:35.445  3682  3729 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 09:45:35.446  3682  3729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 09:45:35.446  3682  3729 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-28 09:45:35.446  3682  3729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 09:45:35.446  3682  3729 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 09:45:35.446  3682  3729 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 09:45:35.446  3682  3729 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 09:45:35.447  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 09:45:35.447  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@815002 added. We now have 2 listener(s)
07-28 09:45:35.448  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:35.449  3682  3729 D BluetoothAdapter: enable(): BT is already enabled..!
,07-28 09:45:35.450   875  1720 D WifiService: setWifiEnabled: true pid=3682, uid=10000
07-28 09:45:35.450   875  1720 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:45:35.451  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:35.451  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbdd13 added. We now have 3 listener(s)
07-28 09:45:35.451  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:35.459  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 09:45:35.459  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@84b1b50 added. We now have 4 listener(s)
07-28 09:45:35.459  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:35.462  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 09:45:35.462  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a2d3149 added. We now have 5 listener(s)
07-28 09:45:35.462  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:35.465   875  1735 D WifiService: setWifiEnabled: false pid=3682, uid=10000
,07-28 09:45:35.465   875  1735 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:45:35.469  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:35.469  2561  2608 D BluetoothAdapterState: Current state: ON, message: 23
07-28 09:45:35.470  2561  2608 D BluetoothAdapterProperties: Setting state to 13
,07-28 09:45:35.470  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-28 09:45:35.470  2561  2608 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 09:45:35.471  2561  2608 I BluetoothAdapterState: Entering PendingCommandState
07-28 09:45:35.472  2561  2561 D BluetoothMapService: onReceive
07-28 09:45:35.472  2561  2561 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:45:35.472  2561  2561 D BluetoothMapService: STATE_TURNING_OFF
07-28 09:45:35.472  2561  2561 D BluetoothMapService: MAP Service closeService in
07-28 09:45:35.472  2561  2561 D BluetoothMapMasInstance0: MAP Service shutdown
07-28 09:45:35.472  2561  2561 D ObexServerSockets0: shutdown(block = true)
07-28 09:45:35.472  2561  2561 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-28 09:45:35.473  2561  2561 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 09:45:35.473  2561  2769 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-28 09:45:35.473  2561  2754 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-28 09:45:35.473  2561  2770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-28 09:45:35.474  2561  2561 I BtOppRfcommListener: stopping Accept Thread
07-28 09:45:35.474  2561  3285 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:45:35.474  2561  3285 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 09:45:35.475  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:35.475  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:35.476  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.476  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.476  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 09:45:35.479  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:35.481  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:35.485  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:35.485  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:35.486  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:35.486  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:35.488  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:35.488   875   888 I ActivityManager: Start proc 3736:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-28 09:45:35.489  2561  2612 D BluetoothAdapterProperties: Scan Mode:20
,07-28 09:45:35.489  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-28 09:45:35.491  2561  2561 D HeadsetService: Received stop request...Stopping profile...
07-28 09:45:35.492  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:35.493  1348  1365 D BluetoothHeadset: Proxy object disconnected
,07-28 09:45:35.493  2561  2561 V BluetoothAdapterState: isTurningOff()=true
,07-28 09:45:35.493  2561  2561 V BluetoothAdapterState: isTurningOn()=false
,07-28 09:45:35.493   875   875 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:35.493  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:35.493  1721  1900 D BluetoothHeadset: Proxy object disconnected
,07-28 09:45:35.493  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:35.494   875   875 D BluetoothHeadset: Proxy object disconnected
,07-28 09:45:35.494   875   875 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:35.494  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:35.496  2561  2561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 09:45:35.496  2561  2561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 09:45:35.496  2561  2612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-28 09:45:35.496  2561  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:35.496  2561  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 09:45:35.497  2561  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:35.497  2561  2612 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-28 09:45:35.497  2561  2561 D A2dpService: Received stop request...Stopping profile...
07-28 09:45:35.497  2561  2763 D A2dpStateMachine: Exit Disconnected: -1
07-28 09:45:35.499   875   875 D BluetoothA2dp: Proxy object disconnected
07-28 09:45:35.500  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 09:45:35.502   875  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 09:45:35.502   875  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-28 09:45:35.502   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-28 09:45:35.502   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 09:45:35.502  2561  2561 D HidService: Received stop request...Stopping profile...
07-28 09:45:35.502  2561  2561 D HidService: Stopping Bluetooth HidService
07-28 09:45:35.504  2561  2561 D HealthService: Received stop request...Stopping profile...
07-28 09:45:35.505  2561  2561 D PanService: Received stop request...Stopping profile...
07-28 09:45:35.506  2561  2561 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:35.506  2561  2561 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:35.506  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:35.507  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:35.508   875  1305 E native  : do suspend true
07-28 09:45:35.508  2561  2612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-28 09:45:35.508  2561  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:35.508  2561  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:35.508  2561  2737 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:45:35.508  2561  2737 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:45:35.508  2561  2737 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:45:35.508  2561  2737 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:45:35.508  2561  2561 D BluetoothMapService: Received stop request...Stopping profile...
07-28 09:45:35.509  2561  2561 D BluetoothMapService: stop()
,07-28 09:45:35.509  2561  2561 D BluetoothMapAppObserver: deinitObservers()
07-28 09:45:35.509  2561  2561 D BluetoothMapAppObserver: removeReceiver()
07-28 09:45:35.509  1348  1348 D HeadsetProfile: Bluetooth service disconnected
07-28 09:45:35.510  1348  1348 D BluetoothA2dp: Proxy object disconnected
07-28 09:45:35.510  1348  1348 D BluetoothInputDevice: Proxy object disconnected
07-28 09:45:35.510  1348  1348 D HidProfile: Bluetooth service disconnected
,07-28 09:45:35.510  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:35.511  1348  1348 D PanProfile: Bluetooth service disconnected
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:35.511  1348  1348 D BluetoothMap: Proxy object disconnected
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:35.511  1348  1348 D MapProfile: Bluetooth service disconnected
,07-28 09:45:35.511  2561  2561 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 09:45:35.511  2561  2561 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:35.511  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:35.512  2561  2612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 09:45:35.512  2561  2561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 09:45:35.512  2561  2612 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-28 09:45:35.512  2561  2561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 09:45:35.513  2561  2561 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:35.513  2561  2561 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:35.513  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:35.513  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:35.513  2561  2561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 09:45:35.513  2561  2561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 09:45:35.515  2561  2561 D BluetoothMapService: MAP Service closeService in
07-28 09:45:35.515  2561  2561 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:35.515  2561  2561 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:35.515  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:35.515  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:35.515  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-28 09:45:35.515  2561  2608 D BluetoothAdapterProperties: Setting state to 15
07-28 09:45:35.515  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-28 09:45:35.516  2561  2608 I BluetoothAdapterState: Entering BleOnState
07-28 09:45:35.516  1721  1734 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:45:35.516  2561  2561 D BluetoothMapService: cleanup()
07-28 09:45:35.516  2561  2561 D BluetoothMapService: MAP Service closeService in
07-28 09:45:35.517  1348  1359 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-28 09:45:35.517  1348  1830 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 09:45:35.518  1348  1365 D BluetoothPan: onBluetoothStateChange on: false
07-28 09:45:35.519  1348  1359 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:45:35.520  1348  1830 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 09:45:35.520   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:45:35.520   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 09:45:35.521  1348  1365 D BluetoothMap: onBluetoothStateChange: up=false
07-28 09:45:35.521   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:45:35.521   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:45:35.521   875  1996 D DhcpClient: Clearing IP address
,07-28 09:45:35.521   373   874 D CommandListener: Clearing all IP addresses on wlan0
07-28 09:45:35.522  2561  2608 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-28 09:45:35.522  2561  2608 D BluetoothAdapterProperties: Setting state to 16
07-28 09:45:35.522  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-28 09:45:35.522  2561  2608 D BluetoothAdapterProperties: onBleDisable
,07-28 09:45:35.522  2561  2608 I BluetoothAdapterState: Entering PendingCommandState
07-28 09:45:35.523  2561  2609 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-28 09:45:35.523  2561  2612 D BluetoothAdapterProperties: Scan Mode:20
07-28 09:45:35.524   373   874 D CommandListener: Setting iface cfg
07-28 09:45:35.525  3682  3731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 381)
07-28 09:45:35.525  2561  2737 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 09:45:35.525  2561  2737 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:35.527  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:35.529  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:35.530   875  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
07-28 09:45:35.531   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 09:45:35.531   875  1305 E native  : do suspend true
,07-28 09:45:35.531   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 09:45:35.531   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-28 09:45:35.532  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:35.532  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:45:35.533  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.533  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:35.537   423   423 E Parcel  : Reading a NULL string not supported here.
07-28 09:45:35.538  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:35.539  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:45:35.539  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:35.539  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:35.541   875  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-28 09:45:35.544   875  2000 D DhcpClient: Receive thread stopped
07-28 09:45:35.551  1502  2308 V NativeCrypto: Read error: ssl=0x9b5b0800: I/O error during system call, Connection timed out
07-28 09:45:35.555  1502  2308 V NativeCrypto: SSL shutdown failed: ssl=0x9b5b0800: I/O error during system call, Broken pipe
,07-28 09:45:35.569  3736  3736 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-28 09:45:35.575   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:35.579  3736  3736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 09:45:35.584  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:45:35.587   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@986953d:true
,07-28 09:45:35.597   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:35.598   373   874 D CommandListener: Clearing all IP addresses on wlan0
,07-28 09:45:35.599   875  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-28 09:45:35.599   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:45:35.609   875  1771 I ActivityManager: Start proc 3752:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-28 09:45:35.611   875  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-28 09:45:35.615   875   892 D Tethering: MasterInitialState.processMessage what=3
,07-28 09:45:35.620  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:35.620  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:35.622  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:35.623  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:35.623  1806  1806 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-28 09:45:35.624  3272  3272 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dbc751c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
07-28 09:45:35.633   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
07-28 09:45:35.635  1849  2078 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:45:35.636  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:35.636  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:35.636  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.636  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:35.639   875  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 09:45:35.641  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:35.641  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:35.641  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:35.641  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:35.649  3736  3736 D LocalBluetoothProfileManager: Adding local MAP profile
,07-28 09:45:35.651  3736  3736 D BluetoothMap: Create BluetoothMap proxy object
,07-28 09:45:35.657  3752  3752 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-28 09:45:35.661  3736  3736 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-28 09:45:35.674  3736  3736 D DockEventReceiver: finishStartingService: stopping service
,07-28 09:45:35.683   875  1771 I ActivityManager: Killing 3073:com.google.android.gm/u0a78 (adj 15): empty #17
,07-28 09:45:35.691   373   874 E Netd    : netlink response contains error (No such file or directory)
,07-28 09:45:35.726  2561  2612 I bt_hci  : shut_down
,07-28 09:45:35.727  2561  2616 D bt_hwcfg: hw_epilog_process
,07-28 09:45:35.784  2561  2616 I bt_vendor: low_power_mode_cb
,07-28 09:45:35.807  2561  2616 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-28 09:45:35.807  2561  2616 I bt_vendor: epilog_cb
,07-28 09:45:35.807  2561  2616 I bt_hci  : epilog_finished_callback
07-28 09:45:35.813  2561  2612 I bt_hci_h4: hal_close
,07-28 09:45:35.814  2561  2612 I bt_userial_vendor: device fd = 51 close
,07-28 09:45:35.858  3752  3752 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:35.858  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.859  3752  3752 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.859  3752  3752 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.859  3752  3752 D StrictMode: 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:35.859  3752  3752 D StrictMode: ,	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
,07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.859  3752  3752 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 09:45:35.859  3752  3752 D StrictMode: ,	at libcore.io.IoBridge.read(IoBridge.java:468)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
,07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23),
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-28 09:45:35.859  3752  3752 D StrictMode: 	,at com.google.r.y.a(PG:2188)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.859  3752  3752 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.k.d(PG:583)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.goo,gle.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.859  3752  3752 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:35.859  3752  3752 D StrictMode: 	,at android.os.Looper.loop(Looper.java:148)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726),
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.859  3752  3752 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.859  3752  3752 D StrictMode: ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.File.doAccess(File.java:281),
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-28 09:45:35.859  3752  3752 D StrictMode: 	,at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.859  3752  3752 D StrictMode: 	,at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
,07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.859  3752  3752 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-28 09:45:35.859  3752  3752 D StrictMode: 	,at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102),
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:35.859  3752  3752 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:35.865  3736  3736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 09:45:35.875  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:45:35.895  3736  3736 D DockEventReceiver: finishStartingService: stopping service
,07-28 09:45:35.908   875  1719 I ActivityManager: Killing 3272:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-28 09:45:36.008  3752  3783 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-28 09:45:36.023   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34a58eb:true
,07-28 09:45:36.035  1862  1862 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 09:45:36.060  1862  1862 D SystemUpdateService: onCreate
07-28 09:45:36.079  1862  1862 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 09:45:36.082  1862  3789 I SystemUpdateService: active receiver: enabled
,07-28 09:45:36.086  1862  3789 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 09:45:36.087  2561  2609 D bt_stack_manager: event_shut_down_stack finished.
07-28 09:45:36.088  1862  3789 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-28 09:45:36.089  1862  3789 I SystemUpdateService: now status is 0 (complete)
07-28 09:45:36.089  1862  3789 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-28 09:45:36.089  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-28 09:45:36.089  1862  3789 I SystemUpdateService: file has been verified
,07-28 09:45:36.089  1862  3789 I SystemUpdateService: OTA package size = 12249756
07-28 09:45:36.092  2561  2561 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 09:45:36.092  2561  2608 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-28 09:45:36.092  2561  2561 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 09:45:36.092  2561  2561 D BtGatt.GattService: stop()
07-28 09:45:36.092  2561  2561 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 09:45:36.095  2561  2561 V BluetoothAdapterState: isTurningOff()=false
07-28 09:45:36.095  2561  2561 V BluetoothAdapterState: isTurningOn()=false
,07-28 09:45:36.096  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:36.096  2561  2561 V BluetoothAdapterState: isBleTurningOff()=true
07-28 09:45:36.096  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-28 09:45:36.097  2561  2608 D BluetoothAdapterProperties: Setting state to 10
07-28 09:45:36.097  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-28 09:45:36.098  2561  2608 I BluetoothAdapterState: Entering OffState
07-28 09:45:36.098   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-28 09:45:36.099  1862  3789 I SystemUpdateService: showing system update notification
,07-28 09:45:36.108  2561  2561 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-28 09:45:36.108  2561  2561 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-28 09:45:36.108  2561  2561 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 09:45:36.109  2561  2609 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-28 09:45:36.112  1862  1862 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-28 09:45:36.112  2561  2609 D bt_stack_manager: event_clean_up_stack finished.
,07-28 09:45:36.116  2561  2561 I art     : System.exit called, status: 0
,07-28 09:45:36.116  2561  2561 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 09:45:36.117  1862  1862 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-28 09:45:36.118  1862  1862 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 09:45:36.121  1862  2336 I iu.UploadsManager: num queued entries: 0
,07-28 09:45:36.124  1862  2336 I iu.UploadsManager: num updated entries: 0
,07-28 09:45:36.126  1862  2336 I iu.SyncManager: NEXT; no task
,07-28 09:45:36.131   875  1719 I ActivityManager: Start proc 3793:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-28 09:45:36.133  1862  1862 D SystemUpdateService: onDestroy
,07-28 09:45:36.155   875   885 I ActivityManager: Process com.android.bluetooth (pid 2561) has died
,07-28 09:45:36.159  3793  3793 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-28 09:45:36.162  3793  3793 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:45:36.171  3793  3793 D SprintDMHelper: simOperator: 
,07-28 09:45:36.171  3793  3793 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 09:45:36.183   875  3059 I ActivityManager: Start proc 3805:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-28 09:45:36.254  2367  3819 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-28 09:45:36.270   875  1375 I ActivityManager: Start proc 3820:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-28 09:45:36.273   875  1375 I ActivityManager: Killing 2634:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-28 09:45:36.352  3820  3820 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-28 09:45:36.412  3820  3820 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-28 09:45:36.412  3820  3820 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-28 09:45:36.412  3820  3820 I GAv4    :   adb logcat -s GAv4
,07-28 09:45:36.428  3820  3820 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-28 09:45:36.436  3820  3820 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-28 09:45:36.467  3820  3837 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-28 09:45:36.578  3820  3820 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-28 09:45:36.619  3820  3820 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-28 09:45:36.633  3820  3820 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 2538-2545)
,07-28 09:45:36.633  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 09:45:36.642  3820  3820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4ebaf76}
,07-28 09:45:36.642  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 09:45:36.642  3820  3820 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 09:45:36.651  3820  3820 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 09:45:36.653  3820  3820 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 09:45:36.669  3820  3820 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-28 09:45:36.682  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-28 09:45:36.682  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 09:45:36.683  3820  3820 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-28 09:45:36.683  3820  3820 I Adreno  : Build Date                       : 10/20/15
07-28 09:45:36.683  3820  3820 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-28 09:45:36.683  3820  3820 I Adreno  : Local Branch                     : M14
07-28 09:45:36.683  3820  3820 I Adreno  : Remote Branch                    : 
07-28 09:45:36.683  3820  3820 I Adreno  : Remote Branch                    : 
07-28 09:45:36.683  3820  3820 I Adreno  : Reconstruct Branch               : 
,07-28 09:45:36.754  3820  3820 I NSApplication: Starting up...
,07-28 09:45:36.761  3820  3866 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-28 09:45:36.791   875  1743 I ActivityManager: Start proc 3871:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-28 09:45:36.792   875  1743 I ActivityManager: Killing 2948:android.process.acore/u0a5 (adj 15): empty #17
,07-28 09:45:36.863  3871  3871 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-28 09:45:37.012   875  1720 I ActivityManager: Killing 3518:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-28 09:45:37.088   875  3059 I ActivityManager: Start proc 3884:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-28 09:45:37.153  3884  3884 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-28 09:45:37.211  3884  3884 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-28 09:45:37.268   875  1708 I ActivityManager: Killing 3535:com.android.musicfx/u0a18 (adj 15): empty #17
,07-28 09:45:38.479   875  1743 D WifiService: setWifiEnabled: true pid=3682, uid=10000
,07-28 09:45:38.479   875  1743 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:45:38.491   875  1305 D WifiConfigStore: Loading config and enabling all networks 
,07-28 09:45:38.500  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:38.501  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:38.501  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:38.502  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:38.506  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:38.506  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:38.507  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:38.507  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:38.534   875  1305 D WifiConfigStore: loaded 0 passpoint configs
,07-28 09:45:38.534   875  1305 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 09:45:38.536   875  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-28 09:45:38.538   875  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-28 09:45:38.541   875  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 09:45:38.542   875  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-28 09:45:38.542   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-28 09:45:38.542   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-28 09:45:38.561   373   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-28 09:45:38.562   373   874 D CommandListener: Setting iface cfg
,07-28 09:45:38.563   875  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-28 09:45:38.563   875  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 09:45:38.563   875  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 09:45:38.578   875  1304 D WifiNative-HAL: p2pGetDeviceAddress
07-28 09:45:38.579   875  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
07-28 09:45:38.579   875  1305 E native  : do suspend true
,07-28 09:45:38.610   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 09:45:39.983   875  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 09:45:40.023   875  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.69 rxSuccessRate=13.56 delta 1000 -> 994
,07-28 09:45:40.027   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-28 09:45:40.028   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:45:40.050   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-28 09:45:40.124   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-28 09:45:40.129  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-28 09:45:40.559  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 09:45:40.607  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-28 09:45:40.607  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-28 09:45:40.613   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 09:45:40.621   875  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 09:45:40.621   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:45:40.622   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-28 09:45:40.645   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:45:40.659   373   874 D CommandListener: Setting iface cfg
,07-28 09:45:40.660   875  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,07-28 09:45:40.666   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-28 09:45:40.687   875  3921 D DhcpClient: Receive thread started
,07-28 09:45:40.768   875  1305 E native  : do suspend false
,07-28 09:45:40.780   875  1996 D DhcpClient: Broadcasting DHCPDISCOVER
,07-28 09:45:40.792   875  3921 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172535, domain null
,07-28 09:45:40.793   875  1996 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172535 seconds
,07-28 09:45:40.796   875  1996 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-28 09:45:40.810   875  3921 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-28 09:45:40.811   875  1996 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-28 09:45:40.815   373   874 D CommandListener: Setting iface cfg
,07-28 09:45:40.824   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-28 09:45:40.825   875  1996 D DhcpClient: Scheduling renewal in 86399s
07-28 09:45:40.828   875  1305 E native  : do suspend true
,07-28 09:45:40.851   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-28 09:45:40.855   875  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,07-28 09:45:40.857   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-28 09:45:40.861   875  1309 D ConnectivityService: Adding iface wlan0 to network 101
,07-28 09:45:40.866   875  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 09:45:40.925   875  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-28 09:45:40.925   875  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-28 09:45:40.926   875  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-28 09:45:40.929   875  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-28 09:45:40.931   875  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-28 09:45:40.949   875  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-28 09:45:40.954   875  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-28 09:45:40.954   875  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,07-28 09:45:40.955   875  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,07-28 09:45:40.955   875  1309 D ConnectivityService:    accepting network in place of null
,07-28 09:45:40.955   875  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-28 09:45:40.956   875  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-28 09:45:40.956   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-28 09:45:40.971   875  3920 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286883, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-28 09:45:41.016   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:41.040   875  3919 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:800::200e
,07-28 09:45:41.062   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:41.073   875  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-28 09:45:41.073   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:45:41.081   875  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-28 09:45:41.082   875   892 D Tethering: MasterInitialState.processMessage what=3
07-28 09:45:41.094  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:41.094  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:45:41.094  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:41.094  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:41.098  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:41.098  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 09:45:41.098  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 09:45:41.098  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 09:45:41.110  1806  1806 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-28 09:45:41.111  1862  1862 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 09:45:41.115  1862  1862 D SystemUpdateService: onCreate
,07-28 09:45:41.118  1862  1862 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 09:45:41.123   875  3919 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 07:45:41 GMT], X-Android-Received-Millis=[1469691941122], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469691941093]}
,07-28 09:45:41.124   875  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-28 09:45:41.125   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,07-28 09:45:41.125   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-28 09:45:41.125  1862  3932 I SystemUpdateService: active receiver: enabled
,07-28 09:45:41.126   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 09:45:41.131  3437  3931 I BooksSync: Starting books sync for 61035162, extras: ade
,07-28 09:45:41.136  1862  3932 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 09:45:41.138  1862  3932 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-28 09:45:41.138  1862  3932 I SystemUpdateService: now status is 0 (complete)
07-28 09:45:41.138  1862  3932 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-28 09:45:41.138  1862  3932 I SystemUpdateService: file has been verified,
07-28 09:45:41.138  1862  3932 I SystemUpdateService: OTA package size = 12249756
,07-28 09:45:41.140  1862  3932 I SystemUpdateService: showing system update notification
,07-28 09:45:41.150  1862  1862 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-28 09:45:41.156  1862  1862 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 09:45:41.157  1862  3937 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-28 09:45:41.157  1862  3937 W BaseAppContext: Using Auth Proxy for data requests.
07-28 09:45:41.158  1862  1862 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 09:45:41.159  1862  3937 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,07-28 09:45:41.159  3793  3793 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
07-28 09:45:41.161  1862  1862 D SystemUpdateService: onDestroy
,07-28 09:45:41.161  1862  2336 I iu.UploadsManager: num queued entries: 0
,07-28 09:45:41.169  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-28 09:45:41.169  1862  2336 I iu.UploadsManager: num updated entries: 0
,07-28 09:45:41.170  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 09:45:41.173  3793  3793 D SprintDMHelper: simOperator: 
,07-28 09:45:41.173  1862  2336 I iu.SyncManager: NEXT; no task
07-28 09:45:41.173  3793  3793 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 09:45:41.199  3437  3941 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
07-28 09:45:41.199  1502  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-28 09:45:41.200  1502  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-28 09:45:41.200  1502  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 09:45:41.200  1502  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 09:45:41.234  1502  2902 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-28 09:45:41.234  1502  2902 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-28 09:45:41.234  1502  2902 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-28 09:45:41.234  1502  2902 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 09:45:41.265  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-28 09:45:41.265  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-28 09:45:41.265  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-28 09:45:41.265  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 09:45:41.279  3437  3941 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-28 09:45:41.279  3437  3931 E BooksSync: Soft error
07-28 09:45:41.279  3437  3931 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-28 09:45:41.279  3437  3931 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-28 09:45:41.279  3437  3931 E BooksSync: Sync error
07-28 09:45:41.279  3437  3931 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-28 09:45:41.279  3437  3931 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-28 09:45:41.279  3437  3931 I BooksSync: Finished books sync
,07-28 09:45:41.286   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286636, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-28 09:45:41.296  2367  3940 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-28 09:45:41.339  1862  3937 E MDM     : [215] SitrepService.a: Error sending sitrep.
,07-28 09:45:41.340   875   885 I ActivityManager: Killing 3314:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-28 09:45:41.485   875  1718 D WifiService: setWifiEnabled: false pid=3682, uid=10000
,07-28 09:45:41.485   875  1718 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:45:41.506  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-28 09:45:41.509   875  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-28 09:45:41.510   875  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,07-28 09:45:41.510   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 09:45:41.511   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:45:41.525   875  1305 E native  : do suspend true
,07-28 09:45:41.531   875  1996 D DhcpClient: Clearing IP address
07-28 09:45:41.531   373   874 D CommandListener: Clearing all IP addresses on wlan0
07-28 09:45:41.534   373   874 D CommandListener: Setting iface cfg
,07-28 09:45:41.540  1502  3945 V NativeCrypto: Read error: ssl=0x9a630800: I/O error during system call, Connection timed out
,07-28 09:45:41.542  1502  3945 V NativeCrypto: SSL shutdown failed: ssl=0x9a630800: I/O error during system call, Broken pipe
,07-28 09:45:41.550   875  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,07-28 09:45:41.551   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 09:45:41.551   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,07-28 09:45:41.552   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-28 09:45:41.552   875  1305 E native  : do suspend true
,07-28 09:45:41.558   423   423 E Parcel  : Reading a NULL string not supported here.
,07-28 09:45:41.566   373   874 D CommandListener: Clearing all IP addresses on wlan0
07-28 09:45:41.568   875  3921 D DhcpClient: Receive thread stopped
,07-28 09:45:41.570   875  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-28 09:45:41.573   875  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 09:45:41.587   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 09:45:41.589   875  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 09:45:41.594  1849  2078 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 09:45:41.595  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:41.595  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:41.595  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:41.596  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:41.601  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:41.601  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:41.601  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:41.601  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:41.608   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:41.637   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:41.638   875  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 09:45:41.638   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:45:41.641   875   892 D Tethering: MasterInitialState.processMessage what=3
,07-28 09:45:41.645  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:41.645  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:41.652  1806  1806 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-28 09:45:41.655  1862  1862 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 09:45:41.658  1862  1862 D SystemUpdateService: onCreate
,07-28 09:45:41.662  1862  1862 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 09:45:41.670  1862  1862 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-28 09:45:41.672  1862  2336 I iu.UploadsManager: num queued entries: 0
,07-28 09:45:41.672  1862  2336 I iu.UploadsManager: num updated entries: 0
07-28 09:45:41.673  1862  2336 I iu.SyncManager: NEXT; no task
,07-28 09:45:41.679  1862  1862 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 09:45:41.681  1862  1862 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 09:45:41.682  3793  3793 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 09:45:41.680  1862  3955 I SystemUpdateService: active receiver: enabled
,07-28 09:45:41.687  3793  3793 D SprintDMHelper: simOperator: 
,07-28 09:45:41.687  3793  3793 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 09:45:41.696  1862  3955 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 09:45:41.707  2367  3959 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-28 09:45:41.715  1862  3955 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-28 09:45:41.715  1862  3955 I SystemUpdateService: now status is 0 (complete)
07-28 09:45:41.715  1862  3955 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-28 09:45:41.715  1862  3955 I SystemUpdateService: file has been verified
07-28 09:45:41.715  1862  3955 I SystemUpdateService: OTA package size = 12249756
,07-28 09:45:41.723  1862  3955 I SystemUpdateService: showing system update notification
,07-28 09:45:41.730   373   874 E Netd    : netlink response contains error (No such file or directory)
,07-28 09:45:41.732  1862  1862 D SystemUpdateService: onDestroy
,07-28 09:45:42.071   875  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-28 09:45:44.543   875   892 I ActivityManager: Start proc 3964:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-28 09:45:44.665  3964  3964 D AdapterServiceConfig: Adding HeadsetService
07-28 09:45:44.665  3964  3964 D AdapterServiceConfig: Adding A2dpService
07-28 09:45:44.665  3964  3964 D AdapterServiceConfig: Adding HidService
07-28 09:45:44.665  3964  3964 D AdapterServiceConfig: Adding HealthService
07-28 09:45:44.666  3964  3964 D AdapterServiceConfig: Adding PanService
07-28 09:45:44.666  3964  3964 D AdapterServiceConfig: Adding GattService
07-28 09:45:44.666  3964  3964 D AdapterServiceConfig: Adding BluetoothMapService
,07-28 09:45:44.683   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@639e44:true
07-28 09:45:44.684  3964  3964 D BluetoothAdapterState: make() - Creating AdapterState
,07-28 09:45:44.689  3964  3964 I bt_bluedroid: init
,07-28 09:45:44.689  3964  3976 I BluetoothAdapterState: Entering OffState
,07-28 09:45:44.693  3964  3977 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-28 09:45:44.693  3964  3977 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 09:45:44.693  3964  3977 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 09:45:44.693  3964  3977 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 09:45:44.694  3964  3964 I bt_bluedroid: get_profile_interface socket
07-28 09:45:44.696  3964  3964 I bt_bluedroid: get_profile_interface sdp
,07-28 09:45:44.699  3964  3980 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 09:45:44.700  3964  3975 I bt_bluedroid: config_hci_snoop_log
,07-28 09:45:44.702   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
07-28 09:45:44.702  3964  3980 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 09:45:44.710  3964  3976 D BluetoothAdapterState: Current state: OFF, message: 0
,07-28 09:45:44.711  3964  3976 D BluetoothAdapterProperties: Setting state to 14
07-28 09:45:44.711  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-28 09:45:44.715  3964  3976 D BluetoothBondStateMachine: make
,07-28 09:45:44.720  3964  3981 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 09:45:44.729  3964  3976 I BluetoothAdapterState: Entering PendingCommandState
,07-28 09:45:44.734  3964  3964 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-28 09:45:44.746  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:44.749  3964  3964 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 09:45:44.752  3964  3964 D BtGatt.GattService: Received start request. Starting profile...
,07-28 09:45:44.753  3964  3964 D BtGatt.GattService: start()
,07-28 09:45:44.753  3964  3964 I bt_bluedroid: get_profile_interface gatt
,07-28 09:45:44.757  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
07-28 09:45:44.758  3964  3964 D BtGatt.AdvertiseManager: advertise manager created
,07-28 09:45:44.772  3964  3964 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:44.772  3964  3964 V BluetoothAdapterState: isTurningOn()=false
,07-28 09:45:44.772  3964  3964 V BluetoothAdapterState: isBleTurningOn()=true
07-28 09:45:44.773  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:44.774  3964  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-28 09:45:44.774  3964  3976 I bt_bluedroid: enable
,07-28 09:45:44.775  3964  3977 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-28 09:45:44.776  3964  3977 I bt_hci  : start_up
,07-28 09:45:44.795  3964  3977 I bt_vendor: alloc value 0xb3a81189
,07-28 09:45:44.796  3964  3977 I bt_vendor: init
07-28 09:45:44.796  3964  3977 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-28 09:45:44.796  3964  3977 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-28 09:45:44.906  3964  3977 D bt_hci  : start_up starting async portion
,07-28 09:45:44.907  3964  3984 I bt_hci  : event_finish_startup
07-28 09:45:44.907  3964  3984 I bt_hci_h4: hal_open
07-28 09:45:44.908  3964  3984 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 09:45:44.916  3964  3984 I bt_userial_vendor: device fd = 51 open
,07-28 09:45:44.948  3964  3984 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 09:45:44.980  3964  3984 D bt_hwcfg: Chipset BCM4354A2
,07-28 09:45:44.980  3964  3984 D bt_hwcfg: Target name = [BCM4354A2]
,07-28 09:45:44.981  3964  3984 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-28 09:45:45.640  3964  3984 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 09:45:45.641  3964  3984 D bt_hwcfg: Settlement delay -- 100 ms
07-28 09:45:45.642  3964  3984 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 09:45:45.758  3964  3984 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 09:45:45.760  3964  3984 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-28 09:45:45.789  3964  3984 I bt_hwcfg: vendor lib fwcfg completed
,07-28 09:45:45.790  3964  3984 I bt_vendor: firmware callback
07-28 09:45:45.790  3964  3984 I bt_hci  : firmware_config_callback
,07-28 09:45:45.803  3964  3986 I bt_btu  : btu_task pending for preload complete event
,07-28 09:45:45.803  3964  3986 I bt_btu_task: Bluetooth chip preload is complete
07-28 09:45:45.803  3964  3986 I bt_btu  : btu_task received preload complete event
,07-28 09:45:45.813  3964  3986 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 09:45:45.813  3964  3986 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 09:45:45.814  3964  3986 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 09:45:45.814  3964  3986 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-28 09:45:45.814  3964  3986 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 09:45:45.815  3964  3986 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 09:45:45.815  3964  3986 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 09:45:45.815  3964  3986 I         : BTE_InitTraceLevels -- TRC_BTM
,07-28 09:45:45.815  3964  3986 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 09:45:45.816  3964  3986 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 09:45:45.816  3964  3986 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 09:45:45.816  3964  3986 I         : BTE_InitTraceLevels -- TRC_GATT
,07-28 09:45:45.816  3964  3986 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 09:45:45.817  3964  3986 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 09:45:45.817  3964  3986 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 09:45:45.950  3964  3986 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fed9d
,07-28 09:45:45.950  3964  3986 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fed9d 
,07-28 09:45:45.960  3964  3980 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
07-28 09:45:45.961  3964  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 09:45:45.962  3964  3980 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 09:45:45.967  3964  3980 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 09:45:45.970  3964  3980 D BluetoothAdapterProperties: Scan Mode:20
07-28 09:45:45.971  3964  3980 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 09:45:45.971  3964  3980 D bt_hci  : do_postload posting postload work item
07-28 09:45:45.971  3964  3984 I bt_hci  : event_postload
07-28 09:45:45.972  3964  3984 I bt_vendor: sco_config_cb
,07-28 09:45:45.972  3964  3984 I bt_hci  : sco_config_callback postload finished.
07-28 09:45:45.977  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:45.977  3964  3980 D bt_bte_conf: Device ID record 1 : primary
07-28 09:45:45.978  3964  3980 D bt_bte_conf:   vendorId            = 000f
07-28 09:45:45.978  3964  3980 D bt_bte_conf:   vendorIdSource      = 0001
07-28 09:45:45.978  3964  3980 D bt_bte_conf:   product             = 1200
07-28 09:45:45.978  3964  3980 D bt_bte_conf:   version             = 1436
07-28 09:45:45.979  3964  3980 D bt_bte_conf:   clientExecutableURL = 
07-28 09:45:45.979  3964  3980 D bt_bte_conf:   serviceDescription  = 
07-28 09:45:45.979  3964  3980 D bt_bte_conf:   documentationURL    = 
,07-28 09:45:45.979  3964  3980 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-28 09:45:45.980  3964  3977 D bt_stack_manager: event_start_up_stack finished
07-28 09:45:45.982  3964  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-28 09:45:45.982  3964  3984 I bt_vendor: low_power_mode_cb
07-28 09:45:45.982  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:45.983  3964  3976 D BluetoothAdapterProperties: Setting state to 15
07-28 09:45:45.983  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-28 09:45:45.987  3964  3976 I BluetoothAdapterState: Entering BleOnState
,07-28 09:45:45.992  3964  3976 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-28 09:45:45.992  3964  3976 D BluetoothAdapterProperties: Setting state to 11
,07-28 09:45:45.993  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-28 09:45:46.005  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:46.012  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:46.014  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:46.016  3964  3964 D HeadsetService: Received start request. Starting profile...
,07-28 09:45:46.019  3964  3964 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-28 09:45:46.019  3964  3964 D HeadsetStateMachine: make
,07-28 09:45:46.022  3964  3976 I BluetoothAdapterState: Entering PendingCommandState
,07-28 09:45:46.027  3964  3964 D HeadsetStateMachine: max_hf_connections = 1
,07-28 09:45:46.028  3964  3964 I bt_bluedroid: get_profile_interface handsfree
,07-28 09:45:46.028  3964  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-28 09:45:46.029  3964  3980 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-28 09:45:46.034  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
07-28 09:45:46.034  3964  3964 D A2dpService: Received start request. Starting profile...
07-28 09:45:46.035  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 09:45:46.035  3964  3964 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 09:45:46.035  3964  3964 I bt_bluedroid: get_profile_interface avrcp
,07-28 09:45:46.043  3964  3964 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 09:45:46.043  3964  3964 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 09:45:46.044  3964  3964 D A2dpStateMachine: make
,07-28 09:45:46.045  3964  3964 I bt_bluedroid: get_profile_interface a2dp
07-28 09:45:46.046  3964  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-28 09:45:46.047  3964  3995 D A2dpStateMachine: Enter Disconnected: -2
,07-28 09:45:46.049  3964  3964 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 09:45:46.051  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:46.054  3736  3736 D BluetoothInputDevice: Proxy object connected
,07-28 09:45:46.054  3964  3964 D HidService: Received start request. Starting profile...
07-28 09:45:46.055  3736  3736 D HidProfile: Bluetooth service connected
,07-28 09:45:46.055  3964  3964 I bt_bluedroid: get_profile_interface hidhost
,07-28 09:45:46.056  3964  3980 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e03e5
07-28 09:45:46.056  3964  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-28 09:45:46.056  3964  3964 D HidService: setHidService(): set to: null
,07-28 09:45:46.059  3964  3964 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 09:45:46.061  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:46.063  3964  3964 D HealthService: Received start request. Starting profile...
,07-28 09:45:46.065  3964  3964 I bt_bluedroid: get_profile_interface health
,07-28 09:45:46.066  3964  3964 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 09:45:46.068  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:46.069  3736  3736 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 09:45:46.069  3964  3964 D PanService: Received start request. Starting profile...
,07-28 09:45:46.069  3964  3964 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 09:45:46.069  3964  3964 I bt_bluedroid: get_profile_interface pan
07-28 09:45:46.070  3736  3736 D PanProfile: Bluetooth service connected
,07-28 09:45:46.070  3964  3980 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 09:45:46.074  3964  3964 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:46.075  3736  3736 D BluetoothMap: Proxy object connected
,07-28 09:45:46.075  3964  3964 D BluetoothMapService: Received start request. Starting profile...
,07-28 09:45:46.075  3964  3964 D BluetoothMapService: start()
07-28 09:45:46.076  3736  3736 D MapProfile: Bluetooth service connected
,07-28 09:45:46.076  3736  3736 D BluetoothMap: getConnectedDevices()
07-28 09:45:46.077  3736  3736 D BluetoothMap: Bluetooth is Not enabled
,07-28 09:45:46.078  3964  3964 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-28 09:45:46.079  3964  3964 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-28 09:45:46.079  3964  3964 D BluetoothMapAppObserver: createReceiver()
,07-28 09:45:46.081  3964  3964 D BluetoothMapAppObserver: initObservers()
,07-28 09:45:46.081  3964  3964 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-28 09:45:46.090  3964  3964 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:46.090  3964  3964 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:46.090  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:46.090  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:46.093  3964  3993 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-28 09:45:46.093  3964  3964 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:46.094  3964  3964 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:46.094  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:46.094  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:46.094  3964  3964 V BluetoothAdapterState: isTurningOff()=false
07-28 09:45:46.095  3964  3964 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:46.095  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:46.095  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:46.095  3964  3964 V BluetoothAdapterState: isTurningOff()=false
07-28 09:45:46.096  3964  3964 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:46.096  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:46.096  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:46.096  3964  3964 V BluetoothAdapterState: isTurningOff()=false
07-28 09:45:46.097  3964  3964 V BluetoothAdapterState: isTurningOn()=true
,07-28 09:45:46.097  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:46.097  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:46.097  3964  3964 V BluetoothAdapterState: isTurningOff()=false
07-28 09:45:46.098  3964  3964 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:46.098  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:46.098  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:46.098  3964  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-28 09:45:46.099  3964  3976 D BluetoothAdapterProperties: ScanMode =  20
07-28 09:45:46.099  3964  3976 D BluetoothAdapterProperties: State =  11
07-28 09:45:46.099  3964  3976 D BluetoothAdapterProperties: Setting state to 12
,07-28 09:45:46.099  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 09:45:46.100  3964  3976 I BluetoothAdapterState: Entering OnState
07-28 09:45:46.100  1721  1900 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:45:46.101  3736  3747 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 09:45:46.102  1348  1359 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 09:45:46.102  3964  3980 D BluetoothAdapterProperties: Scan Mode:21
07-28 09:45:46.103  3964  3980 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 09:45:46.105  1348  1348 D BluetoothInputDevice: Proxy object connected
,07-28 09:45:46.105  1348  1348 D HidProfile: Bluetooth service connected
07-28 09:45:46.106  1348  1830 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:46.107  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:46.111  3964  3964 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-28 09:45:46.111  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:46.111  1348  1365 D BluetoothPan: onBluetoothStateChange on: true
07-28 09:45:46.112  3964  3964 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:46.118  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:46.118  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 09:45:46.118  3964  3964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:45:46.118  1348  1348 D PanProfile: Bluetooth service connected
,07-28 09:45:46.120  1348  1830 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:45:46.122  3964  3964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:45:46.124  1348  1359 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 09:45:46.124  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:46.124  3964  3964 D ObexServerSockets: Succeed to create listening sockets 
07-28 09:45:46.125  3964  3964 D ObexServerSockets0: startAccept()
07-28 09:45:46.125  3964  3964 D ObexServerSockets0: prepareForNewConnect()
,07-28 09:45:46.127  3736  3746 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 09:45:46.128   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:45:46.128   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 09:45:46.129  1348  1365 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 09:45:46.129  3964  4000 D ObexServerSockets0: Accepting socket connection...
,07-28 09:45:46.130  3964  3964 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-28 09:45:46.130  3964  3964 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-28 09:45:46.130  3964  4001 D ObexServerSockets0: Accepting socket connection...
,07-28 09:45:46.131  1348  1348 D BluetoothMap: Proxy object connected
,07-28 09:45:46.131  1348  1348 D MapProfile: Bluetooth service connected
07-28 09:45:46.131  1348  1348 D BluetoothMap: getConnectedDevices()
,07-28 09:45:46.131  3736  3747 D BluetoothMap: onBluetoothStateChange: up=true
07-28 09:45:46.132   875   875 D BluetoothA2dp: Proxy object connected
07-28 09:45:46.132   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:45:46.132  3736  3746 D BluetoothPan: onBluetoothStateChange on: true
07-28 09:45:46.133  1348  1348 D BluetoothA2dp: Proxy object connected
07-28 09:45:46.133   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:45:46.135   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,07-28 09:45:46.136  3964  3964 D BluetoothMapService: onReceive
,07-28 09:45:46.136  3964  3964 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:45:46.136  3964  3964 D BluetoothMapService: STATE_ON
07-28 09:45:46.137  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:46.138  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:46.140  3736  3736 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-28 09:45:46.144  3736  3736 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-28 09:45:46.150  3736  3736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 09:45:46.153  3736  3736 D BluetoothA2dp: Proxy object connected
,07-28 09:45:46.157  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:45:46.159  3736  3736 D DockEventReceiver: finishStartingService: stopping service
,07-28 09:45:46.167  1348  1348 D BluetoothPbap: Proxy object connected
07-28 09:45:46.167  3964  3964 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-28 09:45:46.167  1348  1348 D PbapServerProfile: Bluetooth service connected
07-28 09:45:46.167  3736  3736 D BluetoothPbap: Proxy object connected
07-28 09:45:46.167  3964  3964 D ObexServerSockets0: prepareForNewConnect()
,07-28 09:45:46.168  3736  3736 D PbapServerProfile: Bluetooth service connected
,07-28 09:45:46.176  3964  4007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:45:46.196  3964  4011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:45:46.198  3964  4011 I BtOppRfcommListener: Accept thread started.
,07-28 09:45:46.202  1348  1830 D BluetoothHeadset: Proxy object connected
,07-28 09:45:46.203  1348  1348 D HeadsetProfile: Bluetooth service connected
07-28 09:45:46.203   875   875 D BluetoothHeadset: Proxy object connected
07-28 09:45:46.203  1721  1734 D BluetoothHeadset: Proxy object connected
07-28 09:45:46.204   875   875 D BluetoothHeadset: Proxy object connected
07-28 09:45:46.204   875   875 D BluetoothHeadset: Proxy object connected
,07-28 09:45:46.221  1348  1365 D BluetoothHeadset: Proxy object connected
,07-28 09:45:46.221  1348  1348 D HeadsetProfile: Bluetooth service connected
,07-28 09:45:46.229   875   892 D BluetoothHeadset: Proxy object connected
,07-28 09:45:46.233   875   892 D BluetoothHeadset: Proxy object connected
07-28 09:45:46.233   875   892 D BluetoothHeadset: Proxy object connected
,07-28 09:45:46.248  3736  3746 D BluetoothHeadset: Proxy object connected
,07-28 09:45:46.251  3736  3736 D HeadsetProfile: Bluetooth service connected
,07-28 09:45:46.330  1502  2287 I art     : Waiting for a blocking GC DisableMovingGc
,07-28 09:45:46.340  1502  2287 I art     : WaitForGcToComplete blocked for 10.335ms for cause DisableMovingGc
,07-28 09:45:46.340  1502  2287 I art     : Starting a blocking GC DisableMovingGc
,07-28 09:45:47.501  3964  3976 D BluetoothAdapterState: Current state: ON, message: 23
,07-28 09:45:47.501  3964  3976 D BluetoothAdapterProperties: Setting state to 13
,07-28 09:45:47.501  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-28 09:45:47.503  3964  3976 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 09:45:47.506  3964  3976 I BluetoothAdapterState: Entering PendingCommandState
,07-28 09:45:47.519  3964  3964 D BluetoothMapService: onReceive
07-28 09:45:47.519  3964  3964 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:45:47.520  3964  3964 D BluetoothMapService: STATE_TURNING_OFF
07-28 09:45:47.521  3964  3964 D BluetoothMapService: MAP Service closeService in
07-28 09:45:47.521  3964  3964 D BluetoothMapMasInstance0: MAP Service shutdown
07-28 09:45:47.523  3964  3964 D ObexServerSockets0: shutdown(block = true)
,07-28 09:45:47.523  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:47.524  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:47.524  3964  4000 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-28 09:45:47.526  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:47.527  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:47.527  3964  3964 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-28 09:45:47.529  3964  4001 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-28 09:45:47.530  3964  3980 D BluetoothAdapterProperties: Scan Mode:20
07-28 09:45:47.531  3964  3964 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 09:45:47.532  3964  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,07-28 09:45:47.532  3964  3988 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,07-28 09:45:47.532  3964  3964 I BtOppRfcommListener: stopping Accept Thread
,07-28 09:45:47.533  3964  4011 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 09:45:47.533  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:47.533  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:47.533  3736  3736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 09:45:47.533  3964  4011 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 09:45:47.534  3682  3682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 09:45:47.534  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:47.535  3964  3964 D HeadsetService: Received stop request...Stopping profile...
07-28 09:45:47.536  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:47.537  1348  1830 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:47.537   875   875 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:47.538  1721  1733 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:47.538  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:47.538   875   875 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:47.539  3964  3964 D A2dpService: Received stop request...Stopping profile...
07-28 09:45:47.539  3736  3746 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:47.540  3964  3995 D A2dpStateMachine: Exit Disconnected: -1
07-28 09:45:47.540   875   875 D BluetoothHeadset: Proxy object disconnected
07-28 09:45:47.540  3736  3736 D HeadsetProfile: Bluetooth service disconnected
07-28 09:45:47.541  1348  1348 D HeadsetProfile: Bluetooth service disconnected
07-28 09:45:47.544   875   875 D BluetoothA2dp: Proxy object disconnected
07-28 09:45:47.545  1348  1348 D BluetoothA2dp: Proxy object disconnected
,07-28 09:45:47.546  3964  3964 D HidService: Received stop request...Stopping profile...
07-28 09:45:47.546  3964  3964 D HidService: Stopping Bluetooth HidService,
,07-28 09:45:47.548  3964  3964 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:47.548  3964  3964 V BluetoothAdapterState: isTurningOn()=false,
07-28 09:45:47.548  1348  1348 D BluetoothInputDevice: Proxy object disconnected
07-28 09:45:47.548  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:47.548  1348  1348 D HidProfile: Bluetooth service disconnected
,07-28 09:45:47.548  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:47.549  3736  3736 D DockEventReceiver: finishStartingService: stopping service
07-28 09:45:47.549  3964  3964 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-28 09:45:47.550  3964  3986 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:47.550  3964  3986 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 09:45:47.550  3736  3736 D BluetoothA2dp: Proxy object disconnected
07-28 09:45:47.550  3964  3986 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 09:45:47.550  3736  3736 D BluetoothInputDevice: Proxy object disconnected
,07-28 09:45:47.550  3736  3736 D HidProfile: Bluetooth service disconnected
07-28 09:45:47.550  3964  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,07-28 09:45:47.550  3964  3980 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
07-28 09:45:47.551  3964  3964 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-28 09:45:47.551  3964  3964 D HealthService: Received stop request...Stopping profile...
,07-28 09:45:47.556  3964  3964 D PanService: Received stop request...Stopping profile...
,07-28 09:45:47.558  3964  3964 V BluetoothAdapterState: isTurningOff()=true
,07-28 09:45:47.558  3964  3964 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:47.558  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:45:47.558  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:47.557  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-28 09:45:47.558  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:47.558  1348  1348 D PanProfile: Bluetooth service disconnected
07-28 09:45:47.558  3964  3964 D BluetoothMapService: Received stop request...Stopping profile...
07-28 09:45:47.558  3964  3964 D BluetoothMapService: stop()
07-28 09:45:47.560  3964  3964 D BluetoothMapAppObserver: deinitObservers()
,07-28 09:45:47.560  3736  3736 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 09:45:47.560  3736  3736 D PanProfile: Bluetooth service disconnected
07-28 09:45:47.560  3964  3964 D BluetoothMapAppObserver: removeReceiver()
07-28 09:45:47.561  1348  1348 D BluetoothMap: Proxy object disconnected
,07-28 09:45:47.562  3736  3736 D BluetoothMap: Proxy object disconnected
07-28 09:45:47.562  3736  3736 D MapProfile: Bluetooth service disconnected
07-28 09:45:47.562  1348  1348 D MapProfile: Bluetooth service disconnected
,07-28 09:45:47.562  3964  3986 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:47.563  3964  3986 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 09:45:47.563  3964  3986 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:45:47.563  3964  3986 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:45:47.563  3964  3986 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 09:45:47.563  3964  3986 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 09:45:47.563  3964  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,07-28 09:45:47.563  3964  3964 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:47.563  3964  3964 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:47.563  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:47.564  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:47.564  3964  3964 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 09:45:47.565  3964  3980 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-28 09:45:47.565  3964  3964 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 09:45:47.565  3964  3964 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:47.565  3964  3964 V BluetoothAdapterState: isTurningOn()=false,
07-28 09:45:47.565  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:47.565  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:47.566  3964  3964 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-28 09:45:47.566  3964  3980 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-28 09:45:47.566  3964  3964 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 09:45:47.568  1348  1348 D BluetoothPbap: Proxy object disconnected
07-28 09:45:47.568  1348  1348 D PbapServerProfile: Bluetooth service disconnected
07-28 09:45:47.568  3736  3736 D BluetoothPbap: Proxy object disconnected
07-28 09:45:47.569  3736  3736 D PbapServerProfile: Bluetooth service disconnected
07-28 09:45:47.569  3964  3964 V BluetoothAdapterState: isTurningOff()=true
,07-28 09:45:47.569  3964  3964 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:47.569  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:47.569  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:47.569  3964  3964 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 09:45:47.570  3964  3964 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 09:45:47.572  3964  3964 D BluetoothMapService: MAP Service closeService in
,07-28 09:45:47.573  3964  3964 V BluetoothAdapterState: isTurningOff()=true
07-28 09:45:47.573  3964  3964 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:47.573  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:47.573  3964  3964 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:47.573  3964  3964 D BluetoothMapService: cleanup()
07-28 09:45:47.573  3964  3964 D BluetoothMapService: MAP Service closeService in
,07-28 09:45:47.574  3964  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-28 09:45:47.574  3964  3976 D BluetoothAdapterProperties: Setting state to 15
07-28 09:45:47.574  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-28 09:45:47.574  3964  3976 I BluetoothAdapterState: Entering BleOnState
07-28 09:45:47.575  3736  3746 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 09:45:47.575  3736  3747 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 09:45:47.578  1721  1900 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 09:45:47.578  3736  4015 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-28 09:45:47.579  1348  1359 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 09:45:47.580  1348  1830 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 09:45:47.580  1348  1365 D BluetoothPan: onBluetoothStateChange on: false
,07-28 09:45:47.581  1348  1359 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:45:47.581  1348  1830 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 09:45:47.581  3736  3746 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 09:45:47.582   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 09:45:47.582   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 09:45:47.582  1348  1365 D BluetoothMap: onBluetoothStateChange: up=false
,07-28 09:45:47.582  3736  3747 D BluetoothMap: onBluetoothStateChange: up=false
,07-28 09:45:47.583   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 09:45:47.583  3736  4015 D BluetoothPan: onBluetoothStateChange on: false
07-28 09:45:47.583   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 09:45:47.584  3964  3976 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-28 09:45:47.584  3964  3976 D BluetoothAdapterProperties: Setting state to 16
07-28 09:45:47.584  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-28 09:45:47.585  3964  3976 D BluetoothAdapterProperties: onBleDisable
,07-28 09:45:47.585  3964  3976 I BluetoothAdapterState: Entering PendingCommandState
07-28 09:45:47.585  3964  3977 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-28 09:45:47.586  3964  3986 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 09:45:47.586  3964  3986 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 09:45:47.588  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:47.589  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:47.589  3964  3980 D BluetoothAdapterProperties: Scan Mode:20
,07-28 09:45:47.591  3736  3736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 09:45:47.591  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:47.592  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:47.595  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:45:47.599  3736  3736 D DockEventReceiver: finishStartingService: stopping service
,07-28 09:45:47.787  3964  3980 I bt_hci  : shut_down
,07-28 09:45:47.787  3964  3984 D bt_hwcfg: hw_epilog_process
07-28 09:45:47.789  3964  3984 I bt_vendor: low_power_mode_cb
,07-28 09:45:47.808  3964  3984 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-28 09:45:47.808  3964  3984 I bt_vendor: epilog_cb
,07-28 09:45:47.808  3964  3984 I bt_hci  : epilog_finished_callback
,07-28 09:45:47.818  3964  3980 I bt_hci_h4: hal_close
,07-28 09:45:47.820  3964  3980 I bt_userial_vendor: device fd = 51 close
,07-28 09:45:47.955  3964  3977 D bt_stack_manager: event_shut_down_stack finished.
,07-28 09:45:47.956  3964  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-28 09:45:47.962  3964  3964 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 09:45:47.962  3964  3976 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-28 09:45:47.964  3964  3964 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 09:45:47.964  3964  3964 D BtGatt.GattService: stop()
07-28 09:45:47.965  3964  3964 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 09:45:47.969  3964  3964 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:47.969  3964  3964 V BluetoothAdapterState: isTurningOn()=false
,07-28 09:45:47.970  3964  3964 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:47.970  3964  3964 V BluetoothAdapterState: isBleTurningOff()=true
07-28 09:45:47.972  3964  3976 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-28 09:45:47.973  3964  3976 D BluetoothAdapterProperties: Setting state to 10
07-28 09:45:47.973  3964  3976 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-28 09:45:47.975  3964  3976 I BluetoothAdapterState: Entering OffState
,07-28 09:45:47.977   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-28 09:45:48.004  3964  3964 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-28 09:45:48.004  3964  3964 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-28 09:45:48.005  3964  3977 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-28 09:45:48.011  3964  3977 D bt_stack_manager: event_clean_up_stack finished.
,07-28 09:45:48.012  3964  3964 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-28 09:45:48.015  3964  3964 I art     : System.exit called, status: 0
,07-28 09:45:48.015  3964  3964 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 09:45:48.078   875   886 I ActivityManager: Process com.android.bluetooth (pid 3964) has died
,07-28 09:45:48.962   875  1309 D ConnectivityService: handlePromptUnvalidated 101
,07-28 09:45:50.498  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:50.498  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:53.506  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:53.507  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23d376f added. We now have 6 listener(s)
,07-28 09:45:53.507  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:53.510  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 09:45:53.511  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ce9c7c added. We now have 7 listener(s)
07-28 09:45:53.511  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:53.513  3682  3729 I System.out: IsBluetoothEnabled
,07-28 09:45:53.525  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:53.576   875   892 I ActivityManager: Start proc 4023:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-28 09:45:53.703  4023  4023 D AdapterServiceConfig: Adding HeadsetService
,07-28 09:45:53.703  4023  4023 D AdapterServiceConfig: Adding A2dpService
,07-28 09:45:53.703  4023  4023 D AdapterServiceConfig: Adding HidService
,07-28 09:45:53.703  4023  4023 D AdapterServiceConfig: Adding HealthService,
,07-28 09:45:53.703  4023  4023 D AdapterServiceConfig: Adding PanService,
07-28 09:45:53.704  4023  4023 D AdapterServiceConfig: Adding GattService
,07-28 09:45:53.704  4023  4023 D AdapterServiceConfig: Adding BluetoothMapService
,07-28 09:45:53.720   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af816b1:true
,07-28 09:45:53.720  4023  4023 D BluetoothAdapterState: make() - Creating AdapterState
,07-28 09:45:53.725  4023  4023 I bt_bluedroid: init
,07-28 09:45:53.726  4023  4035 I BluetoothAdapterState: Entering OffState
,07-28 09:45:53.731  4023  4036 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-28 09:45:53.731  4023  4036 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-28 09:45:53.731  4023  4036 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 09:45:53.732  4023  4036 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 09:45:53.733  4023  4023 I bt_bluedroid: get_profile_interface socket
,07-28 09:45:53.735  4023  4023 I bt_bluedroid: get_profile_interface sdp
,07-28 09:45:53.738  4023  4039 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 09:45:53.740  4023  4039 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 09:45:53.742  4023  4034 I bt_bluedroid: config_hci_snoop_log
,07-28 09:45:53.745   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-28 09:45:53.754  4023  4035 D BluetoothAdapterState: Current state: OFF, message: 0
,07-28 09:45:53.754  4023  4035 D BluetoothAdapterProperties: Setting state to 14
07-28 09:45:53.755  4023  4035 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-28 09:45:53.759  4023  4035 D BluetoothBondStateMachine: make
,07-28 09:45:53.764  4023  4040 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 09:45:53.770  4023  4035 I BluetoothAdapterState: Entering PendingCommandState
,07-28 09:45:53.774  4023  4023 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-28 09:45:53.783  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:53.785  4023  4023 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 09:45:53.787  4023  4023 D BtGatt.GattService: Received start request. Starting profile...
,07-28 09:45:53.787  4023  4023 D BtGatt.GattService: start()
07-28 09:45:53.788  4023  4023 I bt_bluedroid: get_profile_interface gatt
,07-28 09:45:53.790  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:53.791  4023  4023 D BtGatt.AdvertiseManager: advertise manager created
,07-28 09:45:53.801  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:53.801  4023  4023 V BluetoothAdapterState: isTurningOn()=false
07-28 09:45:53.801  4023  4023 V BluetoothAdapterState: isBleTurningOn()=true
,07-28 09:45:53.801  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:53.801  4023  4035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-28 09:45:53.802  4023  4035 I bt_bluedroid: enable
07-28 09:45:53.802  4023  4036 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-28 09:45:53.803  4023  4036 I bt_hci  : start_up
,07-28 09:45:53.810  4023  4036 I bt_vendor: alloc value 0xb3a81189
,07-28 09:45:53.811  4023  4036 I bt_vendor: init
07-28 09:45:53.811  4023  4036 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 09:45:53.811  4023  4036 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-28 09:45:53.919  4023  4036 D bt_hci  : start_up starting async portion
,07-28 09:45:53.919  4023  4043 I bt_hci  : event_finish_startup
07-28 09:45:53.919  4023  4043 I bt_hci_h4: hal_open
07-28 09:45:53.920  4023  4043 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 09:45:53.930  4023  4043 I bt_userial_vendor: device fd = 51 open
,07-28 09:45:53.961  4023  4043 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 09:45:53.993  4023  4043 D bt_hwcfg: Chipset BCM4354A2
,07-28 09:45:53.993  4023  4043 D bt_hwcfg: Target name = [BCM4354A2]
07-28 09:45:53.994  4023  4043 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-28 09:45:54.646  4023  4043 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 09:45:54.647  4023  4043 D bt_hwcfg: Settlement delay -- 100 ms
07-28 09:45:54.647  4023  4043 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 09:45:54.764  4023  4043 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 09:45:54.765  4023  4043 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-28 09:45:54.795  4023  4043 I bt_hwcfg: vendor lib fwcfg completed
,07-28 09:45:54.795  4023  4043 I bt_vendor: firmware callback
07-28 09:45:54.795  4023  4043 I bt_hci  : firmware_config_callback
,07-28 09:45:54.806  4023  4045 I bt_btu  : btu_task pending for preload complete event
,07-28 09:45:54.806  4023  4045 I bt_btu_task: Bluetooth chip preload is complete
07-28 09:45:54.807  4023  4045 I bt_btu  : btu_task received preload complete event
,07-28 09:45:54.820  4023  4045 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 09:45:54.820  4023  4045 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 09:45:54.821  4023  4045 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-28 09:45:54.821  4023  4045 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 09:45:54.821  4023  4045 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 09:45:54.822  4023  4045 I         : BTE_InitTraceLevels -- TRC_A2D
,07-28 09:45:54.822  4023  4045 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 09:45:54.823  4023  4045 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 09:45:54.824  4023  4045 I         : BTE_InitTraceLevels -- TRC_GAP
,07-28 09:45:54.825  4023  4045 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 09:45:54.825  4023  4045 I         : BTE_InitTraceLevels -- TRC_SDP
,07-28 09:45:54.827  4023  4045 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 09:45:54.828  4023  4045 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 09:45:54.828  4023  4045 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-28 09:45:54.829  4023  4045 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 09:45:54.965  4023  4045 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fed9d
,07-28 09:45:54.966  4023  4045 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fed9d 
,07-28 09:45:54.978  4023  4039 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-28 09:45:54.985  4023  4039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-28 09:45:54.985  4023  4039 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 09:45:54.989  4023  4039 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 09:45:54.994  4023  4039 D BluetoothAdapterProperties: Scan Mode:20
,07-28 09:45:54.994  4023  4039 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 09:45:54.995  4023  4039 D bt_hci  : do_postload posting postload work item
07-28 09:45:54.995  4023  4043 I bt_hci  : event_postload
07-28 09:45:54.995  4023  4043 I bt_vendor: sco_config_cb
,07-28 09:45:54.996  4023  4043 I bt_hci  : sco_config_callback postload finished.
,07-28 09:45:54.998  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:55.001  4023  4039 D bt_bte_conf: Device ID record 1 : primary
07-28 09:45:55.001  4023  4039 D bt_bte_conf:   vendorId            = 000f
07-28 09:45:55.001  4023  4039 D bt_bte_conf:   vendorIdSource      = 0001
,07-28 09:45:55.001  4023  4039 D bt_bte_conf:   product             = 1200
07-28 09:45:55.001  4023  4039 D bt_bte_conf:   version             = 1436
07-28 09:45:55.002  4023  4039 D bt_bte_conf:   clientExecutableURL = 
07-28 09:45:55.002  4023  4039 D bt_bte_conf:   serviceDescription  = 
07-28 09:45:55.002  4023  4039 D bt_bte_conf:   documentationURL    = 
07-28 09:45:55.002  4023  4043 I bt_vendor: low_power_mode_cb
07-28 09:45:55.002  4023  4039 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-28 09:45:55.003  4023  4036 D bt_stack_manager: event_start_up_stack finished
07-28 09:45:55.003  4023  4035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-28 09:45:55.004  4023  4035 D BluetoothAdapterProperties: Setting state to 15
07-28 09:45:55.005  4023  4035 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-28 09:45:55.006  4023  4035 I BluetoothAdapterState: Entering BleOnState
,07-28 09:45:55.010  4023  4035 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-28 09:45:55.011  4023  4035 D BluetoothAdapterProperties: Setting state to 11
,07-28 09:45:55.011  4023  4035 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-28 09:45:55.023  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:55.024  4023  4023 D HeadsetService: Received start request. Starting profile...
,07-28 09:45:55.025  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:55.029  4023  4023 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 09:45:55.029  4023  4023 D HeadsetStateMachine: make
,07-28 09:45:55.038  4023  4023 D HeadsetStateMachine: max_hf_connections = 1
,07-28 09:45:55.038  4023  4023 I bt_bluedroid: get_profile_interface handsfree
07-28 09:45:55.039  4023  4039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-28 09:45:55.039  4023  4039 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-28 09:45:55.044  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
07-28 09:45:55.045  4023  4023 D A2dpService: Received start request. Starting profile...
07-28 09:45:55.045  4023  4035 I BluetoothAdapterState: Entering PendingCommandState
07-28 09:45:55.046  4023  4023 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 09:45:55.046  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 09:45:55.047  4023  4023 I bt_bluedroid: get_profile_interface avrcp
,07-28 09:45:55.054  4023  4023 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 09:45:55.055  4023  4023 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 09:45:55.055  4023  4023 D A2dpStateMachine: make
,07-28 09:45:55.057  4023  4023 I bt_bluedroid: get_profile_interface a2dp
,07-28 09:45:55.058  4023  4039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-28 09:45:55.060  4023  4054 D A2dpStateMachine: Enter Disconnected: -2
07-28 09:45:55.060  4023  4023 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 09:45:55.063  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:55.065  4023  4023 D HidService: Received start request. Starting profile...
,07-28 09:45:55.065  4023  4023 I bt_bluedroid: get_profile_interface hidhost
,07-28 09:45:55.066  4023  4039 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e03e5
07-28 09:45:55.066  4023  4039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-28 09:45:55.067  4023  4023 D HidService: setHidService(): set to: null
,07-28 09:45:55.070  4023  4023 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 09:45:55.072  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:55.073  4023  4023 D HealthService: Received start request. Starting profile...
,07-28 09:45:55.077  4023  4023 I bt_bluedroid: get_profile_interface health
,07-28 09:45:55.080  4023  4023 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 09:45:55.083  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:55.084  4023  4023 D PanService: Received start request. Starting profile...
,07-28 09:45:55.084  4023  4023 D BluetoothPanServiceJni: initializeNative(L110): pan
,07-28 09:45:55.085  4023  4023 I bt_bluedroid: get_profile_interface pan
,07-28 09:45:55.085  4023  4039 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 09:45:55.088  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:55.088  4023  4023 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:55.088  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:55.088  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:55.091  4023  4051 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-28 09:45:55.093  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:55.093  4023  4023 D BluetoothMapService: Received start request. Starting profile...
,07-28 09:45:55.094  4023  4023 D BluetoothMapService: start()
,07-28 09:45:55.096  4023  4023 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-28 09:45:55.097  4023  4023 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-28 09:45:55.097  4023  4023 D BluetoothMapAppObserver: createReceiver()
,07-28 09:45:55.098  4023  4023 D BluetoothMapAppObserver: initObservers()
07-28 09:45:55.098  4023  4023 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-28 09:45:55.105  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:55.105  4023  4023 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:55.105  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:55.105  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 09:45:55.106  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isTurningOn()=true
07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isTurningOn()=true
,07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
07-28 09:45:55.107  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
07-28 09:45:55.108  4023  4035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-28 09:45:55.108  4023  4035 D BluetoothAdapterProperties: ScanMode =  20
07-28 09:45:55.108  4023  4035 D BluetoothAdapterProperties: State =  11
07-28 09:45:55.109  4023  4035 D BluetoothAdapterProperties: Setting state to 12
,07-28 09:45:55.109  4023  4035 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 09:45:55.110  4023  4035 I BluetoothAdapterState: Entering OnState
07-28 09:45:55.111  3736  3747 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:45:55.111  4023  4039 D BluetoothAdapterProperties: Scan Mode:21
07-28 09:45:55.112  4023  4039 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 09:45:55.112  3736  4015 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 09:45:55.117  1721  1734 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:55.117  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:55.118  3736  3747 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 09:45:55.120  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:55.122  1348  1365 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 09:45:55.125  4023  4023 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-28 09:45:55.125  4023  4023 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-28 09:45:55.126  1348  1348 D BluetoothInputDevice: Proxy object connected
07-28 09:45:55.126  1348  1348 D HidProfile: Bluetooth service connected
07-28 09:45:55.126  1348  1830 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 09:45:55.128  4023  4023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 09:45:55.128  3736  3736 D BluetoothA2dp: Proxy object connected
,07-28 09:45:55.129  1348  1359 D BluetoothPan: onBluetoothStateChange on: true
,07-28 09:45:55.131  1348  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:45:55.132  1348  1830 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 09:45:55.134  3736  3736 D BluetoothInputDevice: Proxy object connected
,07-28 09:45:55.134  3736  3736 D HidProfile: Bluetooth service connected
07-28 09:45:55.134  1348  1348 D BluetoothA2dp: Proxy object connected
07-28 09:45:55.135  3736  3746 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 09:45:55.136  4023  4023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:45:55.137   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 09:45:55.137   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 09:45:55.137  1348  1365 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 09:45:55.138   875   875 D BluetoothA2dp: Proxy object connected
,07-28 09:45:55.138  4023  4023 D ObexServerSockets: Succeed to create listening sockets 
,07-28 09:45:55.138  4023  4023 D ObexServerSockets0: startAccept()
,07-28 09:45:55.138  4023  4023 D ObexServerSockets0: prepareForNewConnect()
,07-28 09:45:55.139  3736  3747 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 09:45:55.141  4023  4023 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-28 09:45:55.141  4023  4023 D BluetoothSdpJni: SDP Create record success - handle: 0
07-28 09:45:55.142   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:45:55.142  3736  4015 D BluetoothPan: onBluetoothStateChange on: true
07-28 09:45:55.142  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 09:45:55.142  1348  1348 D PanProfile: Bluetooth service connected
,07-28 09:45:55.143  1348  1348 D BluetoothMap: Proxy object connected
07-28 09:45:55.144  1348  1348 D MapProfile: Bluetooth service connected
07-28 09:45:55.144  4023  4059 D ObexServerSockets0: Accepting socket connection...
07-28 09:45:55.144  1348  1348 D BluetoothMap: getConnectedDevices()
,07-28 09:45:55.144  4023  4060 D ObexServerSockets0: Accepting socket connection...
07-28 09:45:55.144   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 09:45:55.146  3736  3736 D BluetoothMap: Proxy object connected
07-28 09:45:55.146  3736  3736 D MapProfile: Bluetooth service connected
07-28 09:45:55.146  3736  3736 D BluetoothMap: getConnectedDevices()
,07-28 09:45:55.146   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
07-28 09:45:55.150  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:55.150  4023  4023 D BluetoothMapService: onReceive
07-28 09:45:55.150  4023  4023 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 09:45:55.151  4023  4023 D BluetoothMapService: STATE_ON
07-28 09:45:55.152  3736  3736 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 09:45:55.152  3736  3736 D PanProfile: Bluetooth service connected
07-28 09:45:55.159  3736  3736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 09:45:55.174  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 09:45:55.176  4023  4023 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-28 09:45:55.176  4023  4023 D ObexServerSockets0: prepareForNewConnect()
,07-28 09:45:55.179  3736  3736 D DockEventReceiver: finishStartingService: stopping service
07-28 09:45:55.179  1348  1348 D BluetoothPbap: Proxy object connected
07-28 09:45:55.179  1348  1348 D PbapServerProfile: Bluetooth service connected
,07-28 09:45:55.181  3736  3736 D BluetoothPbap: Proxy object connected
,07-28 09:45:55.181  3736  3736 D PbapServerProfile: Bluetooth service connected
07-28 09:45:55.181  4023  4065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:45:55.210  4023  4071 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 09:45:55.212  4023  4071 I BtOppRfcommListener: Accept thread started.
,07-28 09:45:55.214  1348  1365 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.214  1348  1348 D HeadsetProfile: Bluetooth service connected
07-28 09:45:55.214   875   875 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.215  1721  1733 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.215   875   875 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.216  3736  3747 D BluetoothHeadset: Proxy object connected
07-28 09:45:55.217  3736  3736 D HeadsetProfile: Bluetooth service connected
07-28 09:45:55.217   875   875 D BluetoothHeadset: Proxy object connected
07-28 09:45:55.218  1721  1900 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.231  1348  1359 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.232  1348  1348 D HeadsetProfile: Bluetooth service connected
,07-28 09:45:55.237   875   892 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.241   875   892 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.244   875   892 D BluetoothHeadset: Proxy object connected
,07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:55.549  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:55.556  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:55.560  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 09:45:55.561  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48e9905 added. We now have 8 listener(s)
,07-28 09:45:55.561  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:55.567   875  1743 D WifiService: setWifiEnabled: false pid=3682, uid=10000
,07-28 09:45:55.568   875  1743 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:45:55.580  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:55.581   875  1771 D WifiService: setWifiEnabled: true pid=3682, uid=10000
,07-28 09:45:55.582   875  1771 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 09:45:55.595   875  1305 D WifiConfigStore: Loading config and enabling all networks 
,07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:55.613  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:55.620  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:55.632   875  1305 D WifiConfigStore: loaded 0 passpoint configs
,07-28 09:45:55.632   875  1305 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 09:45:55.633   875  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-28 09:45:55.634   875  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-28 09:45:55.635   875  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-28 09:45:55.635   875  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-28 09:45:55.635   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-28 09:45:55.635   875  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-28 09:45:55.648   875  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 09:45:55.649   373   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-28 09:45:55.652   373   874 D CommandListener: Setting iface cfg
,07-28 09:45:55.701   875  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,07-28 09:45:55.701   875  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 09:45:55.703   875  1305 E native  : do suspend true
,07-28 09:45:55.723   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 09:45:55.732   875  1304 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 09:45:55.740   875  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:56.604  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:56.611  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:56.625  3682  3729 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-28 09:45:56.628  3682  3729 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-28 09:45:56.631  3682  3729 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b749248 Bundle[{}]
,07-28 09:45:56.631  3682  3729 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 09:45:56.631  3682  3729 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-28 09:45:56.632  3682  3729 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-28 09:45:56.632  3682  3729 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-28 09:45:56.633  3682  3729 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-28 09:45:56.634  3682  3729 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-28 09:45:56.638  3682  3729 I System.out: Running OutgoingSocketThread
,07-28 09:45:56.641  3682  4077 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 412)
,07-28 09:45:56.643  3682  4077 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42369
07-28 09:45:56.643  3682  4077 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-28 09:45:57.096   875  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 09:45:57.226   875  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.38 rxSuccessRate=15.00 delta 1000 -> 994
,07-28 09:45:57.228   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-28 09:45:57.228   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:45:57.241   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-28 09:45:57.291   875  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-28 09:45:57.296  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-28 09:45:57.642  3682  3729 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 413)
,07-28 09:45:57.642  3682  3729 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 413)
07-28 09:45:57.643  3682  3729 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 413)
07-28 09:45:57.643  3682  3729 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 413)
,07-28 09:45:57.654  3682  3729 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 418)
,07-28 09:45:57.655  3682  3729 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 418)
07-28 09:45:57.655  3682  3729 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 418)
,07-28 09:45:57.659  3682  3729 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 419)
07-28 09:45:57.662  3682  3729 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 421)
,07-28 09:45:57.667  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 09:45:57.668  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@234dd5a added. We now have 2 listener(s)
,07-28 09:45:57.673  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 09:45:57.674  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 09:45:57.674  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 09:45:57.675  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.676  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98fdb8b added. We now have 9 listener(s)
07-28 09:45:57.676  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:57.677  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 09:45:57.683  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:57.688  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:57.692  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:57.692  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 09:45:57.693  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 09:45:57.693  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de4c081 added. We now have 3 listener(s)
,07-28 09:45:57.695  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 09:45:57.695  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
07-28 09:45:57.695  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 09:45:57.695  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:57.696  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.696  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d37526 added. We now have 10 listener(s)
,07-28 09:45:57.696  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:57.696  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:57.696  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:57.696  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:57.696  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:57.696  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.696  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:57.697  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:57.697  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@234dd5a removed from the list
07-28 09:45:57.697  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.697  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98fdb8b removed from the list
07-28 09:45:57.699  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:57.699  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:57.700  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.700  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.700  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.701  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:57.701  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.702  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.702  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98fdb8b not in the list
07-28 09:45:57.702  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.702  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:57.703  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 09:45:57.703  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:57.703  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.704  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d37526 removed from the list
07-28 09:45:57.704  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
07-28 09:45:57.704  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.704  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:57.704  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:57.704  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de4c081 removed from the list
,07-28 09:45:57.705  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:45:57.705  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61ea567 added. We now have 2 listener(s)
,07-28 09:45:57.707  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 09:45:57.707  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 09:45:57.707  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:45:57.707  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.707  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61bff14 added. We now have 9 listener(s)
,07-28 09:45:57.707  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:57.708  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 09:45:57.712  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:57.718  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:57.721  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:57.721  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:45:57.722  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 09:45:57.722  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f71bdb2 added. We now have 3 listener(s)
,07-28 09:45:57.722  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 09:45:57.723  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 09:45:57.723  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:57.724  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 09:45:57.724  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.724  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e63103 added. We now have 10 listener(s)
07-28 09:45:57.724  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:57.724  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:45:57.724  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:45:57.724  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
07-28 09:45:57.724  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:45:57.728  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:57.732  3682  3729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 09:45:57.732  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 09:45:57.733  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:57.736  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 09:45:57.737  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-28 09:45:57.738  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 09:45:57.744  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 09:45:57.745  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-28 09:45:57.745  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 09:45:57.746  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:57.751  4023  4033 D BtGatt.GattService: registerClient() - UUID=c37e5cdf-c2ed-498b-8e22-3346b28c7a6a
,07-28 09:45:57.752  4023  4039 D BtGatt.GattService: onClientRegistered() - UUID=c37e5cdf-c2ed-498b-8e22-3346b28c7a6a, clientIf=5
,07-28 09:45:57.754  3682  3883 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-28 09:45:57.755  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 09:45:57.755  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
07-28 09:45:57.757  4023  4052 D BtGatt.GattService: start scan with filters
,07-28 09:45:57.759   875  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 09:45:57.766   875  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 09:45:57.766   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:45:57.766   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-28 09:45:57.767  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-28 09:45:57.767  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 09:45:57.767  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 09:45:57.767  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-28 09:45:57.768  4023  4042 D BtGatt.ScanManager: handling starting scan
,07-28 09:45:57.772  4023  4042 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a750c5c
,07-28 09:45:57.779  4023  4039 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-28 09:45:57.779  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:57.780   875  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 09:45:57.780  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 09:45:57.780  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 09:45:57.781  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 09:45:57.782  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-28 09:45:57.782  4023  4042 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 09:45:57.790  4023  4039 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-28 09:45:57.791  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.791  3682  3729 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-28 09:45:57.791  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:57.791  4023  4042 D BtGatt.ScanManager: Starting BLE batch scan
07-28 09:45:57.791  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:57.791  4023  4042 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 09:45:57.791  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-28 09:45:57.792   373   874 D CommandListener: Setting iface cfg
,07-28 09:45:57.791  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-28 09:45:57.793  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-28 09:45:57.793  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 09:45:57.793  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 09:45:57.794  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 09:45:57.794  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 09:45:57.794   875  1305 D WifiStateMachine: Start Dhcp Watchdog 3
07-28 09:45:57.795  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:57.796  4023  4033 D BtGatt.GattService: stopScan() - queue size =1
07-28 09:45:57.798  4023  4052 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 09:45:57.799  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 09:45:57.799  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 09:45:57.800  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 09:45:57.800  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 09:45:57.801  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 09:45:57.802   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-28 09:45:57.804  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 09:45:57.804  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 09:45:57.804  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 09:45:57.805  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:45:57.805  4023  4039 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-28 09:45:57.806  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.806  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 09:45:57.811  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 09:45:57.811  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:57.811  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 09:45:57.813  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 09:45:57.813  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:57.813  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:57.813  4023  4039 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 09:45:57.813  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.814  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:57.814  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.814  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:57.814  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 09:45:57.814  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61ea567 removed from the list
07-28 09:45:57.814  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.814  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61bff14 removed from the list
,07-28 09:45:57.814  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 09:45:57.814  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.814  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.815  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:57.815  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:57.815  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.815  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 09:45:57.815  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61bff14 not in the list
07-28 09:45:57.815  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:57.816  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:57.816  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.816  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:57.816  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.816  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e63103 removed from the list
07-28 09:45:57.816  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:57.817  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:57.817  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.817  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:57.817  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f71bdb2 removed from the list
,07-28 09:45:57.817  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:45:57.817  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c10da5f added. We now have 2 listener(s)
07-28 09:45:57.818   875  4082 D DhcpClient: Receive thread started
,07-28 09:45:57.819  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 09:45:57.819  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:57.819  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:45:57.819  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.819  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a301cac added. We now have 9 listener(s)
,07-28 09:45:57.820  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:57.820  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:45:57.820  4023  4039 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-28 09:45:57.820  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.821  4023  4042 D BtGatt.ScanManager: stopping BLe Batch
07-28 09:45:57.822  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:57.825  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 09:45:57.826  4023  4039 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
07-28 09:45:57.826  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:57.826  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.827  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 09:45:57.827  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 09:45:57.827  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@faf510a added. We now have 3 listener(s)
07-28 09:45:57.827  4023  4042 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 09:45:57.828  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,07-28 09:45:57.829  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 09:45:57.829  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:57.829  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:57.829  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:45:57.829  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.829  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12bd7b added. We now have 10 listener(s),
07-28 09:45:57.829  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:57.830  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:45:57.830  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 09:45:57.831  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:45:57.831  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:57.831  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:45:57.833  4023  4039 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 09:45:57.833  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:57.834  3682  3729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 09:45:57.834  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 09:45:57.836  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 09:45:57.837  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 09:45:57.837  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 09:45:57.839  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-28 09:45:57.839  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-28 09:45:57.840  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 09:45:57.840  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:57.842  4023  4061 D BtGatt.GattService: registerClient() - UUID=6bf2cdc0-b82b-4885-8724-54c1756b4f00
,07-28 09:45:57.842  4023  4039 D BtGatt.GattService: onClientRegistered() - UUID=6bf2cdc0-b82b-4885-8724-54c1756b4f00, clientIf=5
07-28 09:45:57.842  3682  3692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 09:45:57.842  4023  4062 D BtGatt.GattService: start scan with filters
,07-28 09:45:57.844  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 09:45:57.844  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-28 09:45:57.844  4023  4042 D BtGatt.ScanManager: handling starting scan
07-28 09:45:57.844  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 09:45:57.844  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 09:45:57.847  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 09:45:57.847  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 09:45:57.848  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 09:45:57.849  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 09:45:57.851  4023  4039 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 09:45:57.851  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.851  4023  4042 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-28 09:45:57.851  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 09:45:57.851  3682  3729 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-28 09:45:57.852  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:57.852  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 09:45:57.852  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:57.852  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 09:45:57.852  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.852  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 09:45:57.852  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:57.852  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c10da5f removed from the list
,07-28 09:45:57.852  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.852  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a301cac removed from the list
07-28 09:45:57.852  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:57.852  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 09:45:57.853  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.853  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-28 09:45:57.853  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.853  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:57.854  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 09:45:57.854  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.854  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.854  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a301cac not in the list
,07-28 09:45:57.854  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 09:45:57.854  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 09:45:57.855  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 09:45:57.855  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-28 09:45:57.855  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 09:45:57.855  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:57.855  4023  4039 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 09:45:57.856  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.856  4023  4042 D BtGatt.ScanManager: Starting BLE batch scan
07-28 09:45:57.856  4023  4042 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 09:45:57.856  4023  4061 D BtGatt.GattService: stopScan() - queue size =1
07-28 09:45:57.856  4023  4062 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-28 09:45:57.856  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:45:57.857  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 09:45:57.857  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 09:45:57.857  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 09:45:57.857  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 09:45:57.858  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:57.858  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 09:45:57.858  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-28 09:45:57.858  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:45:57.858  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.859  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:57.859  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:57.859  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 09:45:57.860  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.860  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:57.860  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.860  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12bd7b removed from the list
,07-28 09:45:57.860  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:57.860  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.860  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.860  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:57.860  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@faf510a removed from the list
07-28 09:45:57.861  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:45:57.861  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e85b657 added. We now have 2 listener(s)
07-28 09:45:57.862  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 09:45:57.862  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:57.862  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:45:57.863  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.863  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac75544 added. We now have 9 listener(s)
,07-28 09:45:57.863  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:57.864  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:45:57.865  4023  4039 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 09:45:57.865  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.866  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:57.869  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:57.870  4023  4039 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-28 09:45:57.870  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 09:45:57.871  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.871  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 09:45:57.872  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:45:57.872  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:57.873  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:57.873  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f0f762 added. We now have 3 listener(s)
,07-28 09:45:57.875  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 09:45:57.875  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:57.875  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:45:57.875  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.875  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac560f3 added. We now have 10 listener(s)
07-28 09:45:57.875  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 09:45:57.875  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 09:45:57.875  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 09:45:57.875  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 09:45:57.876  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 09:45:57.876  4023  4039 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-28 09:45:57.876  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.876  4023  4042 D BtGatt.ScanManager: stopping BLe Batch
,07-28 09:45:57.878  3682  3729 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-28 09:45:57.878  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 09:45:57.881  4023  4039 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-28 09:45:57.881  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.881  4023  4042 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 09:45:57.882  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 09:45:57.882  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 09:45:57.883  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 09:45:57.885  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 09:45:57.885  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 09:45:57.886  3682  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 09:45:57.886  4023  4039 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 09:45:57.886  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.886  3682  3729 D BluetoothAdapter: STATE_ON
,07-28 09:45:57.888  4023  4061 D BtGatt.GattService: registerClient() - UUID=0f0a887f-e078-4ba3-8f24-256389e019b0
,07-28 09:45:57.888  4023  4039 D BtGatt.GattService: onClientRegistered() - UUID=0f0a887f-e078-4ba3-8f24-256389e019b0, clientIf=5
07-28 09:45:57.889  3682  3692 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 09:45:57.889  4023  4033 D BtGatt.GattService: start scan with filters
,07-28 09:45:57.891  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 09:45:57.891  4023  4042 D BtGatt.ScanManager: handling starting scan
07-28 09:45:57.891  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 09:45:57.891  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 09:45:57.891  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 09:45:57.893  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 09:45:57.893  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 09:45:57.894  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-28 09:45:57.895  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 09:45:57.896  4023  4039 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 09:45:57.896  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.896  4023  4042 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 09:45:57.899  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 09:45:57.899  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:57.899  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:57.899  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:57.899  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.900  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 09:45:57.900  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 09:45:57.900  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e85b657 removed from the list
07-28 09:45:57.900  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.900  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac75544 removed from the list
,07-28 09:45:57.900  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:57.900  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:57.900   875  1305 E native  : do suspend false
,07-28 09:45:57.900  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.900  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-28 09:45:57.901  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.901  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 09:45:57.901  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:57.901  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.901  4023  4039 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 09:45:57.901  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.901  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:57.901  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac75544 not in the list
07-28 09:45:57.902  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 09:45:57.902  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 09:45:57.902  4023  4042 D BtGatt.ScanManager: Starting BLE batch scan
07-28 09:45:57.902  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-28 09:45:57.902  4023  4042 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 09:45:57.902  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 09:45:57.902  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 09:45:57.902  3682  3729 D BluetoothAdapter: STATE_ON
07-28 09:45:57.903  4023  4034 D BtGatt.GattService: stopScan() - queue size =1
,07-28 09:45:57.903  4023  4062 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 09:45:57.904  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 09:45:57.904  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 09:45:57.904  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 09:45:57.904  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 09:45:57.904  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 09:45:57.905  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:57.905  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 09:45:57.905  3682  3729 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-28 09:45:57.905  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 09:45:57.905  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.906  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 09:45:57.906  3682  3682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 09:45:57.906  3682  3682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 09:45:57.907  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.907  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:57.907  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 09:45:57.907  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac560f3 removed from the list
,07-28 09:45:57.907  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:57.907  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.907  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.907  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 09:45:57.907  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f0f762 removed from the list
07-28 09:45:57.908  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:45:57.908  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84b194f added. We now have 2 listener(s)
,07-28 09:45:57.909  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 09:45:57.909  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:57.910  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 09:45:57.910  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.910  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bca08dc added. We now have 9 listener(s)
07-28 09:45:57.910  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:57.910  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 09:45:57.911   875  1996 D DhcpClient: Broadcasting DHCPDISCOVER
07-28 09:45:57.911  4023  4039 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-28 09:45:57.912  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.913  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 09:45:57.916  3682  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 09:45:57.916  4023  4039 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 09:45:57.917  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.918  3682  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 09:45:57.918  3682  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 09:45:57.919  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 09:45:57.920  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 09:45:57.921  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 09:45:57.921  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64610ba added. We now have 3 listener(s)
,07-28 09:45:57.922   875  4082 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,07-28 09:45:57.922   875  1996 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
07-28 09:45:57.922  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 09:45:57.922  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 09:45:57.922  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 09:45:57.922  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 09:45:57.923  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec9fb6b added. We now have 10 listener(s)
,07-28 09:45:57.923  3682  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 09:45:57.923  4023  4039 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 09:45:57.923  3682  3729 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 09:45:57.923  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.923  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 09:45:57.923  3682  3729 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 09:45:57.923  4023  4042 D BtGatt.ScanManager: stopping BLe Batch
07-28 09:45:57.923  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:57.923  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.923  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 09:45:57.923  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:57.923   875  1996 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
07-28 09:45:57.923  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84b194f removed from the list
,07-28 09:45:57.923  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.924  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bca08dc removed from the list
07-28 09:45:57.924  3682  3729 D io.jxcore.node.ConnectivityMonitor: stop
07-28 09:45:57.924  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.924  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.924  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:57.925  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:57.925  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.925  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.925  3682  3729 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bca08dc not in the list
07-28 09:45:57.925  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 09:45:57.925  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 09:45:57.926  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 09:45:57.926  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 09:45:57.926  3682  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 09:45:57.926  3682  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec9fb6b removed from the list
07-28 09:45:57.926  3682  3729 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 09:45:57.926  3682  3729 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 09:45:57.926  3682  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 09:45:57.926  3682  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 09:45:57.926  3682  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64610ba removed from the list
07-28 09:45:57.927  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 09:45:57.927  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,07-28 09:45:57.927  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 09:45:57.928  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 09:45:57.928  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 09:45:57.928  3682  3729 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 09:45:57.929  4023  4039 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 09:45:57.929  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 09:45:57.929  4023  4042 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 09:45:57.933  3682  4083 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: My test thread name)
,07-28 09:45:57.933  3682  4083 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 427, thread name: My test thread name)
07-28 09:45:57.933  3682  4083 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: My test thread name)
,07-28 09:45:57.934  4023  4039 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 09:45:57.934  4023  4039 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 09:45:57.935  3682  4084 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: My test thread name)
,07-28 09:45:57.935  3682  4084 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 429, thread name: My test thread name)
07-28 09:45:57.935  3682  4084 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: My test thread name)
,07-28 09:45:57.937  3682  3729 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,07-28 09:45:57.937  3682  3729 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 09:45:57.937  3682  3729 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 09:45:57.937  3682  3729 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-28 09:45:57.938  3682  3729 D com.test.thalitest.ThaliTestRunner: Total duration: 23013 ms
,07-28 09:45:57.939  3682  3729 I jxcore-log: Total number of executed tests:  80
07-28 09:45:57.939  3682  3729 I jxcore-log: 
,07-28 09:45:57.939  3682  3729 I jxcore-log: Number of passed tests:  80
07-28 09:45:57.939  3682  3729 I jxcore-log: 
07-28 09:45:57.939  3682  3729 I jxcore-log: Number of failed tests:  0
07-28 09:45:57.939  3682  3729 I jxcore-log: 
07-28 09:45:57.939  3682  3729 I jxcore-log: Number of ignored tests:  0
07-28 09:45:57.939  3682  3729 I jxcore-log: 
,07-28 09:45:57.940  3682  3729 I jxcore-log: Total duration:  23013
07-28 09:45:57.940  3682  3729 I jxcore-log: 
07-28 09:45:57.940  3682  3729 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 09:45:57.940  3682  3729 I jxcore-log: 
,07-28 09:45:57.942  3682  3729 I jxcore-log: Unit Test app is loaded
07-28 09:45:57.942  3682  3729 I jxcore-log: 
07-28 09:45:57.948  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.948  3682  3729 I jxcore-log: 
07-28 09:45:57.951  3682  3682 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 09:45:57.952  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.952  3682  3729 I jxcore-log: 
07-28 09:45:57.953  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.953  3682  3729 I jxcore-log: 
07-28 09:45:57.954  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 09:45:57.954  3682  3729 I jxcore-log: 
07-28 09:45:57.954  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:45:57.954  3682  3729 I jxcore-log: 
07-28 09:45:57.956  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.956  3682  3729 I jxcore-log: 
07-28 09:45:57.958  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 09:45:57.958  3682  3729 I jxcore-log: 
,07-28 09:45:57.959  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:45:57.959  3682  3729 I jxcore-log: 
,07-28 09:45:57.960  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.960  3682  3729 I jxcore-log: 
,07-28 09:45:57.960  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 09:45:57.960  3682  3729 I jxcore-log: 
07-28 09:45:57.961  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:45:57.961  3682  3729 I jxcore-log: 
,07-28 09:45:57.962  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-28 09:45:57.962  3682  3729 I jxcore-log: 
,07-28 09:45:57.962  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:45:57.962  3682  3729 I jxcore-log: 
07-28 09:45:57.963  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.963  3682  3729 I jxcore-log: 
,07-28 09:45:57.963  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.963  3682  3729 I jxcore-log: 
,07-28 09:45:57.964  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.964  3682  3729 I jxcore-log: 
,07-28 09:45:57.965  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.965  3682  3729 I jxcore-log: 
,07-28 09:45:57.965  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.965  3682  3729 I jxcore-log: 
07-28 09:45:57.966  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.966  3682  3729 I jxcore-log: 
,07-28 09:45:57.967  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.967  3682  3729 I jxcore-log: 
07-28 09:45:57.968  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.968  3682  3729 I jxcore-log: 
,07-28 09:45:57.968  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.968  3682  3729 I jxcore-log: 
07-28 09:45:57.969  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 09:45:57.969  3682  3729 I jxcore-log: 
,07-28 09:45:57.969  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.969  3682  3729 I jxcore-log: 
,07-28 09:45:57.970  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.970  3682  3729 I jxcore-log: 
07-28 09:45:57.971  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.971  3682  3729 I jxcore-log: 
,07-28 09:45:57.971  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.971  3682  3729 I jxcore-log: 
,07-28 09:45:57.972  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.972  3682  3729 I jxcore-log: 
07-28 09:45:57.972  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.972  3682  3729 I jxcore-log: 
,07-28 09:45:57.973  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.973  3682  3729 I jxcore-log: 
07-28 09:45:57.973  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 09:45:57.973  3682  3729 I jxcore-log: 
07-28 09:45:57.974  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.974  3682  3729 I jxcore-log: 
07-28 09:45:57.974  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.974  3682  3729 I jxcore-log: 
,07-28 09:45:57.975  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.975  3682  3729 I jxcore-log: 
,07-28 09:45:57.975  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.975  3682  3729 I jxcore-log: 
07-28 09:45:57.976  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 09:45:57.976  3682  3729 I jxcore-log: 
,07-28 09:45:57.977  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:45:57.977  3682  3729 I jxcore-log: 
,07-28 09:45:57.977  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.977  3682  3729 I jxcore-log: 
07-28 09:45:57.978  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 09:45:57.978  3682  3729 I jxcore-log: 
,07-28 09:45:57.979  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:45:57.979  3682  3729 I jxcore-log: 
07-28 09:45:57.979  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.979  3682  3729 I jxcore-log: 
,07-28 09:45:57.979  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 09:45:57.979  3682  3729 I jxcore-log: 
07-28 09:45:57.980  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 09:45:57.980  3682  3729 I jxcore-log: 
,07-28 09:45:57.980  3682  3729 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 09:45:57.980  3682  3729 I jxcore-log: 
,07-28 09:45:57.983  3682  3729 I jxcore-log: My device name is: motorola-Nexus 6
07-28 09:45:57.983  3682  3729 I jxcore-log: 
,07-28 09:45:58.008   875  4082 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-28 09:45:58.009   875  1996 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-28 09:45:58.011   373   874 D CommandListener: Setting iface cfg
,07-28 09:45:58.016   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-28 09:45:58.017   875  1996 D DhcpClient: Scheduling renewal in 86399s
,07-28 09:45:58.019   875  1305 E native  : do suspend true
,07-28 09:45:58.033   875  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-28 09:45:58.035   875  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,07-28 09:45:58.036   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-28 09:45:58.037   875  1309 D ConnectivityService: Adding iface wlan0 to network 102,
,07-28 09:45:58.039   875  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 09:45:58.086   875  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 09:45:58.086   875  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-28 09:45:58.088   875  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-28 09:45:58.089   875  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-28 09:45:58.090   875  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-28 09:45:58.097   875  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-28 09:45:58.102   875  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-28 09:45:58.102   875  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-28 09:45:58.102   875  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,07-28 09:45:58.102   875  1309 D ConnectivityService:    accepting network in place of null
07-28 09:45:58.102   875  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-28 09:45:58.103   875  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 09:45:58.103   875  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 09:45:58.109   875  4081 D NetlinkSocketObserver: NeighborEvent{elapsedMs=304021, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-28 09:45:58.138   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:58.161   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 09:45:58.163   875  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-28 09:45:58.163   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 09:45:58.164   875  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-28 09:45:58.166   875   892 D Tethering: MasterInitialState.processMessage what=3
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 09:45:58.171  3682  3682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 09:45:58.174   875  4080 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:80f::200e
,07-28 09:45:58.174  3682  3682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 09:45:58.179  1806  1806 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-28 09:45:58.188  1862  1862 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 09:45:58.193  1862  1862 D SystemUpdateService: onCreate
,07-28 09:45:58.197  1862  1862 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 09:45:58.218  1862  1862 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-28 09:45:58.223  1862  2336 I iu.UploadsManager: num queued entries: 0
,07-28 09:45:58.244  1862  4096 I SystemUpdateService: active receiver: enabled
,07-28 09:45:58.244   875  4080 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 07:45:58 GMT], X-Android-Received-Millis=[1469691958244], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469691958216]}
07-28 09:45:58.245   875  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-28 09:45:58.245   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-28 09:45:58.245   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 09:45:58.246   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 09:45:58.285  1862  1862 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 09:45:58.286  1862  1862 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
07-28 09:45:58.288  3793  3793 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
07-28 09:45:58.296  3793  3793 D SprintDMHelper: simOperator: 
07-28 09:45:58.296  3793  3793 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 09:45:58.304  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 09:45:58.311  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 09:45:58.326  1862  4098 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null],
07-28 09:45:58.326  1862  4098 W BaseAppContext: Using Auth Proxy for data requests.
,07-28 09:45:58.327  1862  4098 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
,07-28 09:45:58.347  1502  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-28 09:45:58.347  1502  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-28 09:45:58.347  1502  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 09:45:58.347  1502  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 09:45:58.359  2464  4099 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-28 09:45:58.359  2464  4099 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jdm.a(PG:82)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jcs.o(PG:406)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jcn.a(PG:1379)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jcs.i(PG:143)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at blb.a(PG:3937)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at czp.a(PG:18188)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at czp.a(PG:9081)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at czq.run(PG:1686)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-28 09:45:58.359  2464  4099 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jdj.a(PG:4091)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jdj.a(PG:1125)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jdm.a(PG:77)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	... 12 more
07-28 09:45:58.359  2464  4099 E HttpOperation: Caused by: faj: BadAuthentication
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at fal.a(PG:38)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	at jdj.a(PG:4089)
07-28 09:45:58.359  2464  4099 E HttpOperation: 	... 14 more
,07-28 09:45:58.351  1862  2336 I iu.UploadsManager: num updated entries: 0
,07-28 09:45:58.447  1862  4096 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 09:45:58.448  1862  2336 I iu.SyncManager: NEXT; no task
,07-28 09:45:58.469  1502  1908 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-28 09:45:58.469  1502  1908 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-28 09:45:58.469  1502  1908 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 09:45:58.469  1502  1908 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 09:45:58.481  2464  4099 E HttpOperation: [getmobileexperiments] Unexpected exception
07-28 09:45:58.481  2464  4099 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jdm.a(PG:82)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jcs.o(PG:406)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jcn.a(PG:1379)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jcs.i(PG:143)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at hec.a(PG:42)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at hee.a(PG:102)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at czr.a(PG:65)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at kka.a(PG:108)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at czp.a(PG:19176)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at czp.a(PG:9081)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at czq.run(PG:1686)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-28 09:45:58.481  2464  4099 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jdj.a(PG:4091)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jdj.a(PG:1125)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jdm.a(PG:77)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	... 15 more
07-28 09:45:58.481  2464  4099 E HttpOperation: Caused by: faj: BadAuthentication
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at fal.a(PG:38)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	at jdj.a(PG:4089)
07-28 09:45:58.481  2464  4099 E HttpOperation: 	... 17 more
,07-28 09:45:58.482  2464  4099 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-28 09:45:58.482  2464  4099 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jdm.a(PG:82)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jcs.o(PG:406)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jcn.a(PG:1379)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jcs.i(PG:143)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at hec.a(PG:42)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at hee.a(PG:102)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at czr.a(PG:65)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at kka.a(PG:108)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at czp.a(PG:19176)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at czp.a(PG:9081)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at czq.run(PG:1686)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jdj.a(PG:4091)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jdj.a(PG:1125)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jdm.a(PG:77)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	... 15 more
07-28 09:45:58.482  2464  4099 E ExperimentLoader: Caused by: faj: BadAuthentication
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at fal.a(PG:38)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	at jdj.a(PG:4089)
07-28 09:45:58.482  2464  4099 E ExperimentLoader: 	... 17 more
,07-28 09:45:58.489  1862  4096 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-28 09:45:58.491  1862  4096 I SystemUpdateService: now status is 0 (complete)
07-28 09:45:58.491  1862  4096 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-28 09:45:58.491  1862  4096 I SystemUpdateService: file has been verified
,07-28 09:45:58.501  1862  4096 I SystemUpdateService: OTA package size = 12249756
,07-28 09:45:58.537  2367  4103 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-28 09:45:58.562   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 291507, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-28 09:45:58.577  1862  4096 I SystemUpdateService: showing system update notification
,07-28 09:45:58.585  1502  2841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-28 09:45:58.585  1502  2841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-28 09:45:58.585  1502  2841 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 09:45:58.585  1502  2841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 09:45:58.612  1862  1862 D SystemUpdateService: onDestroy
,07-28 09:45:58.613  1862  4098 E MDM     : [220] SitrepService.a: Error sending sitrep.
,07-28 09:45:58.629  4085  4085 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-28 09:45:58.632  4085  4085 D AndroidRuntime: CheckJNI is OFF
,07-28 09:45:58.668  4085  4085 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-28 09:45:58.707  4085  4085 I Radio-JNI: register_android_hardware_Radio DONE
,07-28 09:45:58.728  4085  4085 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 09:45:58.739   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,07-28 09:45:58.739   875   888 I ActivityManager: Killing 3682:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,07-28 09:45:58.817   875   898 W PackageSettings: Skipping PackageSetting{8f76ab9 com.example.hello/10273} due to missing metadata
,07-28 09:45:58.829   875  1375 D GraphicsStats: Buffer count: 2
07-28 09:45:58.830   875  1719 I WindowState: WIN DEATH: Window{dfb3188 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-28 09:45:58.831   875  1308 D WifiService: Client connection lost with reason: 4
,07-28 09:45:58.864   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,07-28 09:45:58.864   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-28 09:45:58.865   875   888 E ActivityManager: Failure starting process com.test.thalitest
07-28 09:45:58.865   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-28 09:45:58.865   875   888 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-28 09:45:58.865   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:58.865   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:58.865   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 09:45:58.865   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-28 09:45:58.866   875   888 I ActivityManager:   Force finishing activity ActivityRecord{d42a37d u0 com.test.thalitest/.MainActivity t2}
07-28 09:45:58.867   875   898 I art     : Starting a blocking GC Explicit
,07-28 09:45:58.875   875  1718 W ActivityManager: Spurious death for ProcessRecord{fe688ee 0:com.test.thalitest/u0a0}, curProc for 3682: null
,07-28 09:45:58.906   875   898 I art     : Explicit concurrent mark sweep GC freed 19351(1295KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 650us total 37.614ms
,07-28 09:45:58.935   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-28 09:45:58.941  4085  4085 I art     : System.exit called, status: 0
,07-28 09:45:58.941   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-28 09:45:58.941  4085  4085 I AndroidRuntime: VM exiting with result code 0.
,07-28 09:45:58.957   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,07-28 09:45:58.966  4023  4023 D BluetoothMapAppObserver: onReceive
,07-28 09:45:58.966  4023  4023 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-28 09:45:58.968  1849  2047 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-28 09:45:58.968   875  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-28 09:45:58.970  1653  1653 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-28 09:45:58.978  3506  3506 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,07-28 09:45:58.981  1653  4119 I Keyboard.Facilitator.DecoderInitializer: run()
,07-28 09:45:58.995  1721  1721 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-28 09:45:59.001  1653  4119 I Decoder : createOrResetDecoder
,07-28 09:45:59.001   875  1712 I ActivityManager: Start proc 4121:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-28 09:45:59.043  1502  1502 I ConfigService: onCreate
,07-28 09:45:59.054  4121  4121 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-28 09:45:59.070   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-28 09:45:59.072  1502  4134 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-28 09:45:59.081   875  1735 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3682 uid 10000
,07-28 09:45:59.082  1653  1653 I Keyboard.Facilitator: onFinishInput()
,07-28 09:45:59.092  1736  1829 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,07-28 09:45:59.093   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,07-28 09:45:59.094   875   887 E PackageManager: Failed to write settings, restoring backup
07-28 09:45:59.094   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-28 09:45:59.094   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-28 09:45:59.094   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-28 09:45:59.094   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-28 09:45:59.094   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-28 09:45:59.094   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.094   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.094   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-28 09:45:59.098   875   888 E DropBoxManagerService: Can't write: system_server_wtf
07-28 09:45:59.098   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-28 09:45:59.098   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 09:45:59.098   875   888 E DropBoxManagerService: 	... 13 more
,07-28 09:45:59.104  1653  4119 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-28 09:45:59.108   875  1712 I ActivityManager: Start proc 4135:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
07-28 09:45:59.108  1736  1829 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-28 09:45:59.108  1736  1829 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1736
07-28 09:45:59.108  1736  1829 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.108  1736  1829 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-28 09:45:59.111   875   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-28 09:45:59.112   875  4140 E DropBoxManagerService: Can't write: system_app_crash
07-28 09:45:59.112   875  4140 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 09:45:59.112   875  4140 E DropBoxManagerService: 	... 5 more
07-28 09:45:59.115  1736  1829 I Process : Sending signal. PID: 1736 SIG: 9
,07-28 09:45:59.152   875  1296 W InputDispatcher: channel '736b435 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,07-28 09:45:59.152   875  1296 E InputDispatcher: channel '736b435 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,07-28 09:45:59.152   875  1411 D GraphicsStats: Buffer count: 1
,07-28 09:45:59.153   875  1743 I WindowState: WIN DEATH: Window{736b435 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
07-28 09:45:59.153   875  1743 W InputDispatcher: Attempted to unregister already unregistered input channel '736b435 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,07-28 09:45:59.179   875  3059 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1736) has died
,07-28 09:45:59.180   875  3059 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,07-28 09:45:59.181   875  3059 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,07-28 09:45:59.186  1653  4119 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-28 09:45:59.188  1653  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-28 09:45:59.188  1653  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-28 09:45:59.190  1653  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-28 09:45:59.190  1653  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-28 09:45:59.190  1653  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-28 09:45:59.190  1653  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-28 09:45:59.191  1653  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,07-28 09:45:59.192  1653  4119 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-28 09:45:59.192  1653  4119 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-28 09:45:59.192  1653  4119 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-28 09:45:59.192  1653  4119 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-28 09:45:59.192  1653  4119 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-28 09:45:59.195   875   888 I ActivityManager: Start proc 4152:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-28 09:45:59.211  4121  4121 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-28 09:45:59.231   875  1743 I ActivityManager: Start proc 4167:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,07-28 09:45:59.233  4121  4166 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-28 09:45:59.251  4121  4166 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.251  4121  4166 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-28 09:45:59.251  4121  4166 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-28 09:45:59.251  4121  4166 E AndroidRuntime: Process: android.process.acore, PID: 4121
07-28 09:45:59.251  4121  4166 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.251  4121  4166 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-28 09:45:59.256   875  4180 E DropBoxManagerService: Can't write: system_app_crash
07-28 09:45:59.256   875  4180 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 09:45:59.256   875  4180 E DropBoxManagerService: 	... 5 more
,07-28 09:45:59.253  4121  4166 I Process : Sending signal. PID: 4121 SIG: 9
,07-28 09:45:59.266  4152  4152 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:59.266  4152  4152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 09:45:59.267  4152  4152 D AndroidRuntime: Shutting down VM
,07-28 09:45:59.281  4152  4152 E AndroidRuntime: FATAL EXCEPTION: main
07-28 09:45:59.281  4152  4152 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4152
07-28 09:45:59.281  4152  4152 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 09:45:59.281  4152  4152 E AndroidRuntime: 	... 10 more
,07-28 09:45:59.284   875  4181 E DropBoxManagerService: Can't write: system_app_crash
07-28 09:45:59.284   875  4181 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 09:45:59.284   875  4181 E DropBoxManagerService: 	... 5 more
07-28 09:45:59.285   875   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-28 09:45:59.285  4152  4152 I Process : Sending signal. PID: 4152 SIG: 9
07-28 09:45:59.290  4167  4167 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,07-28 09:45:59.300  1862  4177 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,07-28 09:45:59.303  1862  4177 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,07-28 09:45:59.305   875  1719 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4152) has died
,07-28 09:45:59.306   875  1719 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,07-28 09:45:59.320  1502  1502 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,07-28 09:45:59.321  1502  1502 D AndroidRuntime: Shutting down VM
,07-28 09:45:59.322  1502  1502 E AndroidRuntime: FATAL EXCEPTION: main
07-28 09:45:59.322  1502  1502 E AndroidRuntime: Process: com.google.process.gapps, PID: 1502
07-28 09:45:59.322  1502  1502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-28 09:45:59.322  1502  1502 E AndroidRuntime: 	... 8 more
,07-28 09:45:59.329   875   888 I ActivityManager: Start proc 4185:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-28 09:45:59.331   278   278 E lowmemorykiller: Error writing /proc/4121/oom_score_adj; errno=22
,07-28 09:45:59.332   278   278 E lowmemorykiller: Error writing /proc/4121/oom_score_adj; errno=22
,07-28 09:45:59.337   875  4192 E DropBoxManagerService: Can't write: system_app_crash
07-28 09:45:59.337   875  4192 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 09:45:59.337   875  4192 E DropBoxManagerService: 	... 5 more
07-28 09:45:59.337  1862  4177 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-28 09:45:59.337  1502  1502 I Process : Sending signal. PID: 1502 SIG: 9
,07-28 09:45:59.351  1862  4177 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,07-28 09:45:59.358   875  1718 I ActivityManager: Killing 3563:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-28 09:45:59.402   875  3059 I ActivityManager: Process android.process.acore (pid 4121) has died
,07-28 09:45:59.403   875  3059 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,07-28 09:45:59.407   875  1308 D WifiService: Client connection lost with reason: 4
,07-28 09:45:59.408  4185  4185 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:59.408  4185  4185 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 09:45:59.409  4185  4185 D AndroidRuntime: Shutting down VM
,07-28 09:45:59.413   875   885 I ActivityManager: Process com.google.process.gapps (pid 1502) has died
,07-28 09:45:59.413   875   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,07-28 09:45:59.414   875   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
,07-28 09:45:59.414   875   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
07-28 09:45:59.414   875   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
07-28 09:45:59.417  2464  2464 E GcoreClearcutLogger: ClearcutLogger connection suspended: 1
,07-28 09:45:59.423  1862  1862 W RocketImpressions: ClearcutLogger connection suspended: 1
,07-28 09:45:59.425  4185  4185 E AndroidRuntime: FATAL EXCEPTION: main
07-28 09:45:59.425  4185  4185 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4185
07-28 09:45:59.425  4185  4185 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 09:45:59.425  4185  4185 E AndroidRuntime: 	... 10 more

```
