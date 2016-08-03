#### Test 7968977505886a0_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-03 19:13:21.468   872  2009 D NetlinkSocketObserver: NeighborEvent{elapsedMs=379944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 19:13:22.216  3716  3716 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 19:13:22.226  3716  3716 D AndroidRuntime: CheckJNI is OFF
08-03 19:13:22.272  3716  3716 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 19:13:22.315  3716  3716 I Radio-JNI: register_android_hardware_Radio DONE
08-03 19:13:22.335  3716  3716 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-03 19:13:22.339   872  1735 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 19:13:22.400   872  1735 I ActivityManager: Start proc 3726:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-03 19:13:22.405  3716  3716 D AndroidRuntime: Shutting down VM
08-03 19:13:22.536  3726  3726 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-03 19:13:22.565  3726  3726 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-03 19:13:22.576  3726  3726 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1048-1052)
08-03 19:13:22.576  3726  3726 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:13:22.596  3726  3726 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {507b125}
08-03 19:13:22.597  3726  3726 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 19:13:22.597  3726  3726 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 19:13:22.604  3726  3726 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-03 19:13:22.605  3726  3726 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 19:13:22.638  3726  3726 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 19:13:22.659  3726  3726 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 19:13:22.659  3726  3726 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 19:13:22.659  3726  3726 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 19:13:22.659  3726  3726 I Adreno  : Build Date                       : 10/20/15
08-03 19:13:22.659  3726  3726 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 19:13:22.659  3726  3726 I Adreno  : Local Branch                     : M14
08-03 19:13:22.659  3726  3726 I Adreno  : Remote Branch                    : 
08-03 19:13:22.659  3726  3726 I Adreno  : Remote Branch                    : 
08-03 19:13:22.659  3726  3726 I Adreno  : Reconstruct Branch               : 
,08-03 19:13:22.746   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32f24cb:true
,08-03 19:13:22.786  3726  3726 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 19:13:22.798  3726  3726 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-03 19:13:22.849  3726  3763 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 19:13:22.861  3726  3750 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-03 19:13:22.898  3726  3763 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 19:13:22.995   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +527ms (total +616ms)
,08-03 19:13:23.002  1658  1658 I Keyboard.Facilitator: onFinishInput()
,08-03 19:13:23.073  3726  3726 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3726
,08-03 19:13:23.162  3726  3726 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 19:13:23.346  3726  3765 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1681000144
,08-03 19:13:23.355  3726  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 19:13:23.355  3726  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 19:13:23.355  3726  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 19:13:23.355  3726  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 19:13:23.355  3726  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 19:13:23.355  3726  3765 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33e87e0 added. We now have 1 listener(s)
,08-03 19:13:23.360  3726  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-03 19:13:23.362  3726  3765 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 19:13:23.363  3726  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 19:13:23.363  3726  3765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 19:13:23.368  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 19:13:23.369  3726  3765 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@662b93f added. We now have 1 listener(s)
,08-03 19:13:23.370  3726  3765 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:13:23.374   872  1307 D WifiService: New client listening to asynchronous messages
,08-03 19:13:23.375  3726  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 19:13:23.375  3726  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 19:13:23.375  3726  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 19:13:23.376  3726  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 19:13:23.376  3726  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 19:13:23.381  3726  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:13:23.381  3726  3765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-03 19:13:23.390  3726  3765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:23.390  3726  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:13:23.390  3726  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 19:13:23.390  3726  3765 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:13:23.392  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:23.395  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:23.396  3726  3765 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 19:13:23.433  3726  3726 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 19:13:25.102  3726  3772 W jxcore-log: Initializing JXcore engine
,08-03 19:13:25.102  3726  3772 W jxcore-log: JXcore engine is ready
,08-03 19:13:25.135  3772  3772 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8798 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-03 19:13:25.139  3772  3772 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10659]" dev="sockfs" ino=10659 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-03 19:13:25.139  3772  3772 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-03 19:13:25.139  3772  3772 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24811]" dev="sockfs" ino=24811 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-03 19:13:25.149  3726  3772 W jxcore-log: Starting JXcore engine
,08-03 19:13:25.226  3726  3772 W jxcore-log: Platform android
08-03 19:13:25.226  3726  3772 W jxcore-log: 
,08-03 19:13:25.226  3726  3772 W jxcore-log: Process ARCH arm
08-03 19:13:25.226  3726  3772 W jxcore-log: 
,08-03 19:13:25.439  3726  3772 I jxcore-log: JXcore Cordova bridge is ready!
08-03 19:13:25.439  3726  3772 I jxcore-log: 
08-03 19:13:25.439  3726  3772 W jxcore-log: JXcore engine is started
,08-03 19:13:25.451  3726  3765 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 19:13:25.458  3726  3726 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 19:13:31.974   872  2009 D NetlinkSocketObserver: NeighborEvent{elapsedMs=390450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 19:13:40.847  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 19:13:40.847  3726  3772 I jxcore-log: 
,08-03 19:13:40.849  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 19:13:40.849  3726  3772 I jxcore-log: 
,08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:40.859  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:13:40.864  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:13:40.870  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 19:13:40.870  3726  3772 I jxcore-log: 
,08-03 19:13:40.877  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 19:13:40.877  3726  3772 I jxcore-log: 
,08-03 19:13:41.232  3726  3772 D ExecuteNativeTests: Running unit tests
,08-03 19:13:41.292  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 19:13:41.292  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 added. We now have 2 listener(s)
,08-03 19:13:41.293  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 19:13:41.293  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:13:41.293  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:13:41.293  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:13:41.294  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e added. We now have 2 listener(s)
08-03 19:13:41.294  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:13:41.295  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 19:13:41.300  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:41.320  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:13:41.326  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:13:41.327  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:13:41.334  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.337  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-03 19:13:41.337  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:13:41.337  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 19:13:41.341  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.345  3726  3772 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-03 19:13:41.346  3726  3772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-03 19:13:41.348  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-03 19:13:41.351  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 19:13:41.351  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 19:13:41.351  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.352  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:13:41.353  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.353  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 19:13:41.353  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.354  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:13:41.354  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:13:41.354  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 removed from the list
08-03 19:13:41.354  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.354  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e removed from the list
08-03 19:13:41.354  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.355  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.355  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.355  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.356  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.357  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.357  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.357  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.359  3726  3772 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 19:13:41.359  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.359  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.360  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.360  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.360  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.360  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.360  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.360  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.360  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.360  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.360  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.360  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.360  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.360  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.362  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.362  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.362  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.363  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.377  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 19:13:41.377  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 19:13:41.377  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 19:13:41.377  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 19:13:41.378  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 19:13:41.378  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 19:13:41.378  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 19:13:41.378  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 19:13:41.378  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 19:13:41.379  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 19:13:41.379  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 19:13:41.379  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 19:13:41.379  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 19:13:41.379  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 19:13:41.380  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 19:13:41.380  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 19:13:41.380  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 19:13:41.380  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 19:13:41.380  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 19:13:41.380  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 19:13:41.381  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 19:13:41.381  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 19:13:41.381  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 19:13:41.381  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 19:13:41.381  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 19:13:41.382  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 19:13:41.382  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 19:13:41.382  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 19:13:41.382  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 19:13:41.382  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 19:13:41.383  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 19:13:41.383  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.383  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.383  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.384  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.384  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.384  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.384  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.385  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.385  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.385  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.385  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.385  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.385  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.386  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.388  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.388  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.388  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.389  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.390  3726  3772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 19:13:41.401  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:41.412  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:13:41.418  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.418  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:13:41.419  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:13:41.419  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:13:41.419  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:13:41.420  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:13:41.420  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:13:41.424  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.431  3726  3772 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 19:13:41.431  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:13:41.433  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.439  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:13:41.442  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 19:13:41.444  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 19:13:41.451  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-03 19:13:41.456  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-03 19:13:41.456  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 19:13:41.458  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 19:13:41.460  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 19:13:41.462  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:13:41.474  2538  2753 D BtGatt.GattService: registerClient() - UUID=6532e603-3fcc-451a-9c7a-36dd065395e0
,08-03 19:13:41.478  2538  2590 D BtGatt.GattService: onClientRegistered() - UUID=6532e603-3fcc-451a-9c7a-36dd065395e0, clientIf=5
,08-03 19:13:41.480  3726  3737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 19:13:41.483  2538  2549 D BtGatt.GattService: start scan with filters
,08-03 19:13:41.492  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 19:13:41.493  2538  2593 D BtGatt.ScanManager: handling starting scan
08-03 19:13:41.493  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 19:13:41.494  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 19:13:41.494  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 19:13:41.498  2538  2593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:13:41.504  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:13:41.505  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 19:13:41.506  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 19:13:41.510  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 19:13:41.513  2538  2590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 19:13:41.514  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:13:41.516  2538  2593 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 19:13:41.518  3726  3772 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 19:13:41.527  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 19:13:41.528  3726  3772 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-03 19:13:41.528  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:13:41.528  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-03 19:13:41.528  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.529  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 19:13:41.529  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-03 19:13:41.529  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:13:41.529  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 19:13:41.529  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-03 19:13:41.531  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 19:13:41.531  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 19:13:41.533  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:13:41.534  2538  2549 D BtGatt.GattService: stopScan() - queue size =1
08-03 19:13:41.536  2538  2745 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 19:13:41.536  2538  2590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 19:13:41.536  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.537  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:13:41.537  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 19:13:41.537  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-03 19:13:41.537  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 19:13:41.537  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 19:13:41.538  2538  2593 D BtGatt.ScanManager: Starting BLE batch scan
,08-03 19:13:41.538  2538  2593 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 19:13:41.539  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 19:13:41.540  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 19:13:41.540  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 19:13:41.541  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:13:41.542  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:13:41.544  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.544  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.544  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:13:41.544  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.544  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:13:41.545  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.545  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.545  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.545  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:13:41.545  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:13:41.545  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:13:41.546  3726  3772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 19:13:41.548  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:41.554  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:13:41.556  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:13:41.557  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:13:41.557  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:13:41.557  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:13:41.557  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:13:41.557  2538  2590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 19:13:41.558  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:13:41.558  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.558  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:13:41.561  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.564  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.564  3726  3772 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 19:13:41.564  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 19:13:41.565  2538  2590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 19:13:41.565  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:13:41.571  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:13:41.573  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 19:13:41.573  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 19:13:41.573  2538  2590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 19:13:41.573  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.574  2538  2593 D BtGatt.ScanManager: stopping BLe Batch
,08-03 19:13:41.578  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 19:13:41.578  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 19:13:41.578  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 19:13:41.579  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:13:41.582  2538  2549 D BtGatt.GattService: registerClient() - UUID=0e57830f-f993-4eeb-94ec-b6c19ca41c20
,08-03 19:13:41.583  2538  2590 D BtGatt.GattService: onClientRegistered() - UUID=0e57830f-f993-4eeb-94ec-b6c19ca41c20, clientIf=5
08-03 19:13:41.583  2538  2590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 19:13:41.583  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.583  3726  3737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 19:13:41.584  2538  2555 D BtGatt.GattService: start scan with filters
08-03 19:13:41.584  2538  2593 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 19:13:41.587  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 19:13:41.587  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 19:13:41.587  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 19:13:41.587  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 19:13:41.590  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:13:41.590  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 19:13:41.591  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:13:41.591  2538  2590 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 19:13:41.591  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.592  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 19:13:41.594  2538  2593 D BtGatt.ScanManager: handling starting scan
,08-03 19:13:41.595  3726  3772 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 19:13:41.599  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 19:13:41.599  3726  3772 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-03 19:13:41.599  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:13:41.599  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 19:13:41.599  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.599  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 19:13:41.600  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 19:13:41.600  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-03 19:13:41.600  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-03 19:13:41.600  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 19:13:41.600  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-03 19:13:41.600  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 19:13:41.601  3726  3772 D BluetoothAdapter: STATE_ON
08-03 19:13:41.602  2538  2745 D BtGatt.GattService: stopScan() - queue size =1
,08-03 19:13:41.602  2538  2753 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 19:13:41.603  2538  2590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 19:13:41.603  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-03 19:13:41.603  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:13:41.603  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,08-03 19:13:41.603  2538  2593 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 19:13:41.603  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 19:13:41.603  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-03 19:13:41.604  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 19:13:41.605  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:13:41.605  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 19:13:41.605  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 19:13:41.605  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:13:41.606  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:13:41.607  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.607  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:13:41.607  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.607  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:13:41.607  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:13:41.607  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.607  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.607  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:13:41.608  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.608  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.608  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.608  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.608  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.609  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.609  2538  2590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 19:13:41.610  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.609  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:13:41.610  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.610  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.610  2538  2593 D BtGatt.ScanManager: Starting BLE batch scan
08-03 19:13:41.610  2538  2593 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 19:13:41.611  3726  3772 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 19:13:41.613  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:41.618  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:13:41.622  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:13:41.622  2538  2590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-03 19:13:41.622  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:13:41.622  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.623  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 19:13:41.623  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-03 19:13:41.623  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:13:41.623  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:13:41.623  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 19:13:41.625  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.630  2538  2590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-03 19:13:41.630  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:13:41.633  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.634  3726  3772 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-03 19:13:41.634  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 19:13:41.639  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:13:41.639  2538  2590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 19:13:41.639  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.639  2538  2593 D BtGatt.ScanManager: stopping BLe Batch
,08-03 19:13:41.641  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 19:13:41.641  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 19:13:41.646  2538  2590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 19:13:41.646  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.646  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 19:13:41.646  2538  2593 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 19:13:41.647  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 19:13:41.647  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 19:13:41.648  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:13:41.650  2538  2745 D BtGatt.GattService: registerClient() - UUID=e0adc5eb-969e-4777-b14c-283f28367cea
08-03 19:13:41.651  2538  2590 D BtGatt.GattService: onClientRegistered() - UUID=e0adc5eb-969e-4777-b14c-283f28367cea, clientIf=5
,08-03 19:13:41.651  3726  3736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 19:13:41.652  2538  2753 D BtGatt.GattService: start scan with filters
,08-03 19:13:41.653  2538  2590 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 19:13:41.653  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:13:41.656  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 19:13:41.656  2538  2593 D BtGatt.ScanManager: handling starting scan
08-03 19:13:41.656  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 19:13:41.656  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 19:13:41.656  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 19:13:41.660  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:13:41.661  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 19:13:41.661  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 19:13:41.663  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 19:13:41.664  2538  2590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 19:13:41.664  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.664  2538  2593 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 19:13:41.667  3726  3772 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 19:13:41.667  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.667  3726  3772 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 19:13:41.667  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.667  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-03 19:13:41.667  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.668  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 19:13:41.668  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 19:13:41.668  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:13:41.668  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-03 19:13:41.668  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 19:13:41.668  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 19:13:41.668  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 19:13:41.669  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:13:41.670  2538  2753 D BtGatt.GattService: stopScan() - queue size =1
,08-03 19:13:41.671  2538  2549 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 19:13:41.671  2538  2590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 19:13:41.671  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.671  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:13:41.671  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 19:13:41.671  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 19:13:41.671  2538  2593 D BtGatt.ScanManager: Starting BLE batch scan
08-03 19:13:41.672  2538  2593 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 19:13:41.672  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 19:13:41.672  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 19:13:41.673  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:13:41.673  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 19:13:41.673  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 19:13:41.674  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 19:13:41.674  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:13:41.675  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:13:41.675  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 19:13:41.675  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:13:41.676  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.676  3726  3772 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-03 19:13:41.676  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.676  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 19:13:41.677  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.677  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.677  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:13:41.677  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.677  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:13:41.677  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.677  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.677  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.678  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.678  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.679  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.679  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.679  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.680  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.680  3726  3772 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 19:13:41.681  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.681  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.681  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 19:13:41.681  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.681  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.681  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.682  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.682  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:13:41.682  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.682  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.682  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.682  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.682  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.682  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:13:41.683  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.684  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.684  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.684  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.684  2538  2590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 19:13:41.684  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:13:41.685  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 19:13:41.685  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 19:13:41.685  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.685  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.686  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.686  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.686  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.686  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.686  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.686  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.686  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.686  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.686  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.686  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.686  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.687  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.687  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:13:41.688  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.688  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.688  3726  3772 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 19:13:41.688  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.689  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.689  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 19:13:41.689  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.689  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.689  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.689  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.689  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.689  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.689  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.689  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.690  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.690  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.690  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.691  2538  2590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 19:13:41.691  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.691  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 19:13:41.692  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.692  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:13:41.692  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.692  3726  3772 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 19:13:41.692  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.693  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:13:41.693  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.693  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.693  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.693  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.693  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.693  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.693  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.693  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.694  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.694  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.694  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.694  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.695  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.695  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.695  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:13:41.695  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.695  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:13:41.697  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 19:13:41.697  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:13:41.697  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:13:41.697  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 19:13:41.698  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 19:13:41.698  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 19:13:41.698  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:13:41.698  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 19:13:41.698  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 19:13:41.698  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.698  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-03 19:13:41.698  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
,08-03 19:13:41.698  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.699  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.699  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 19:13:41.699  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.699  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:13:41.699  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.699  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.700  2538  2590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 19:13:41.700  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:13:41.700  2538  2593 D BtGatt.ScanManager: stopping BLe Batch
08-03 19:13:41.700  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 19:13:41.701  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.701  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.701  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.701  3726  3772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:13:41.702  3726  3772 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 19:13:41.702  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-03 19:13:41.705  3726  3772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-03 19:13:41.705  3726  3772 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 19:13:41.706  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 19:13:41.707  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-03 19:13:41.708  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 19:13:41.708  3726  3772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 19:13:41.709  3726  3772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-03 19:13:41.709  3726  3772 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 19:13:41.709  3726  3772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:13:41.709  3726  3772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:13:41.709  3726  3772 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 19:13:41.709  3726  3772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 19:13:41.709  3726  3772 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 19:13:41.709  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 19:13:41.712  2538  2590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 19:13:41.712  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:13:41.712  2538  2593 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 19:13:41.714  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 19:13:41.715  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 19:13:41.715  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 19:13:41.715  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 19:13:41.715  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 19:13:41.716  3726  3772 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 19:13:41.716  3726  3772 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-03 19:13:41.716  3726  3772 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 19:13:41.717  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.717  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.717  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.718  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.718  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.718  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.718  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 19:13:41.718  3726  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-03 19:13:41.719  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.719  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.719  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.719  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 19:13:41.719  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.719  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.719  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.719  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.719  3726  3776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-03 19:13:41.720  2538  2590 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 19:13:41.720  2538  2590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:13:41.721  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.721  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:13:41.721  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.721  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.721  3726  3775 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:13:41.722  3726  3772 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 19:13:41.723  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.723  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:13:41.723  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.724  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.724  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.724  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.724  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.724  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.724  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.724  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.724  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.724  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.724  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.724  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.725  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.725  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.725  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.725  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.726  3726  3772 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-03 19:13:41.726  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.726  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.726  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.727  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.727  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.727  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.727  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.727  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:13:41.727  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.727  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.727  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.727  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.727  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.727  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.728  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 19:13:41.728  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.728  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.728  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.729  3726  3772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 19:13:41.729  3726  3772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 19:13:41.729  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:13:41.729  3726  3772 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 19:13:41.729  3726  3772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 19:13:41.729  3726  3772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 19:13:41.729  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:13:41.729  3726  3772 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-03 19:13:41.730  3726  3772 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 19:13:41.730  3726  3772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 19:13:41.730  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:13:41.730  3726  3772 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 19:13:41.730  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.730  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:13:41.730  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.730  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.730  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.730  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.730  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.730  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.730  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.731  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 19:13:41.731  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.731  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.731  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.731  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.732  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.732  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:13:41.732  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.732  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.733  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.733  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.733  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.733  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.733  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.733  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.733  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.733  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.733  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.733  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.733  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.733  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.734  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.734  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:13:41.734  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.734  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.734  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.734  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.734  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.734  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:13:41.734  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.734  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.734  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.734  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.734  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.734  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.735  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:13:41.735  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.735  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.736  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.736  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.736  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.736  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
,08-03 19:13:41.737  3726  3772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 19:13:41.737  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:13:41.738  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 19:13:41.739  3726  3772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 19:13:41.739  3726  3772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 19:13:41.739  3726  3726 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 19:13:41.739  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-03 19:13:41.739  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 19:13:41.740  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.740  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 19:13:41.740  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-03 19:13:41.740  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 19:13:41.740  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.740  3726  3772 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 19:13:41.740  3726  3777 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:13:41.740  3726  3726 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-03 19:13:41.740  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.740  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.740  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:13:41.741  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 19:13:41.741  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 19:13:41.741  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.741  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.742  3726  3777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-03 19:13:41.742  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:13:41.742  3726  3777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 19:13:41.742  3726  3777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 19:13:41.742  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:13:41.742  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:13:41.742  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:13:41.742  3726  3726 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 19:13:41.742  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.743  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 19:13:41.743  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.743  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.743  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.743  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.743  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.743  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.743  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.743  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.743  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 19:13:41.743  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.743  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.743  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.744  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.745  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.745  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.745  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.745  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.746  3726  3772 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 19:13:41.746  3726  3772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-03 19:13:41.746  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 19:13:41.746  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 19:13:41.747  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.747  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.747  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.747  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.747  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.747  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.747  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
,08-03 19:13:41.747  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.747  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.747  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.747  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.747  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.747  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.748  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.748  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.748  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:13:41.748  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.748  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.751  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.751  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.751  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.751  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.752  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.752  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.752  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
08-03 19:13:41.752  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:13:41.752  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.752  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.752  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.752  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.752  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.752  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.753  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.753  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:13:41.753  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.753  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.754  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:13:41.754  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:13:41.754  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:13:41.754  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:13:41.754  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.754  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.754  3726  3772 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9acf59 not in the list
,08-03 19:13:41.754  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.754  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.754  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:41.754  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.754  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:13:41.755  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:13:41.755  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:13:41.755  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:13:41.755  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:13:41.755  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:13:41.756  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ed971e not in the list
08-03 19:13:41.756  3726  3772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 19:13:41.756  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:13:41.757  3726  3772 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-03 19:13:41.757  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 19:13:41.757  3726  3772 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 19:13:41.757  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 19:13:41.759  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 19:13:41.759  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-03 19:13:41.762  3726  3772 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-03 19:13:41.762  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 19:13:41.762  3726  3772 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 19:13:41.762  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 19:13:41.762  3726  3772 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 19:13:41.762  3726  3772 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-03 19:13:41.763  3726  3772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 19:13:41.763  3726  3772 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 19:13:41.763  3726  3772 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-03 19:13:41.764  3726  3772 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 19:13:41.764  3726  3772 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 19:13:41.764  3726  3772 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-03 19:13:41.765  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:13:41.765  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bafb8d0 added. We now have 2 listener(s)
08-03 19:13:41.765  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:13:41.767  3726  3772 D BluetoothAdapter: enable(): BT is already enabled..!
,08-03 19:13:41.767   872  1803 D WifiService: setWifiEnabled: true pid=3726, uid=10000
08-03 19:13:41.767   872  1803 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:13:41.768  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:13:41.768  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@50140c9 added. We now have 3 listener(s)
08-03 19:13:41.768  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:13:41.774  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:13:41.774  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7bc03ce added. We now have 4 listener(s)
08-03 19:13:41.774  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:13:41.776  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:13:41.776  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38a92ef added. We now have 5 listener(s)
08-03 19:13:41.776  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:13:41.779   872   883 D WifiService: setWifiEnabled: false pid=3726, uid=10000
,08-03 19:13:41.779   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:13:41.786  2538  2586 D BluetoothAdapterState: Current state: ON, message: 23
,08-03 19:13:41.787  2538  2586 D BluetoothAdapterProperties: Setting state to 13
08-03 19:13:41.787  2538  2586 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-03 19:13:41.790  2538  2586 D BluetoothAdapterProperties: onBluetoothDisable()
,08-03 19:13:41.794  2538  2586 I BluetoothAdapterState: Entering PendingCommandState
,08-03 19:13:41.796  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 19:13:41.798   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-03 19:13:41.798   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-03 19:13:41.798   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 19:13:41.799   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 19:13:41.798  2538  2590 D BluetoothAdapterProperties: Scan Mode:20
,08-03 19:13:41.801  2538  2586 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 19:13:41.802  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:13:41.804  2538  2538 D HeadsetService: Received stop request...Stopping profile...
,08-03 19:13:41.805   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:41.805  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:41.805  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:13:41.805  1354  1390 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:41.805  1354  1354 D HeadsetProfile: Bluetooth service disconnected
,08-03 19:13:41.806   872   872 D BluetoothHeadset: Proxy object disconnected
,08-03 19:13:41.806  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.806  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.806  1720  1732 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:41.806   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:41.809  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:41.809  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:13:41.810  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.810  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:41.810  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:13:41.810  2538  2538 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:41.810  2538  2538 V BluetoothAdapterState: isTurningOn()=false
,08-03 19:13:41.811  2538  2538 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 19:13:41.811  2538  2538 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:41.811   872  1306 E native  : do suspend true
08-03 19:13:41.812  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.812  2538  2538 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 19:13:41.812  2538  2538 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-03 19:13:41.812  2538  2590 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-03 19:13:41.813  2538  2734 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:41.813  2538  2734 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:41.813  2538  2734 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:41.813  2538  2590 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-03 19:13:41.814  2538  2538 D A2dpService: Received stop request...Stopping profile...
,08-03 19:13:41.814  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.814  2538  2748 D A2dpStateMachine: Exit Disconnected: -1
08-03 19:13:41.817  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-03 19:13:41.817   872   872 D BluetoothA2dp: Proxy object disconnected
08-03 19:13:41.818  2538  2538 D HidService: Received stop request...Stopping profile...
08-03 19:13:41.818  2538  2538 D HidService: Stopping Bluetooth HidService
,08-03 19:13:41.818  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-03 19:13:41.819  1354  1354 D HidProfile: Bluetooth service disconnected
08-03 19:13:41.819  2538  2538 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:41.819  2538  2538 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:41.819  2538  2538 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 19:13:41.819  2538  2538 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:41.821  2538  2734 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:41.821  2538  2734 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:41.821  2538  2734 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-03 19:13:41.821  2538  2734 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:13:41.821  2538  2734 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:13:41.821  2538  2734 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-03 19:13:41.821  2538  2590 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-03 19:13:41.821  2538  2538 D HealthService: Received stop request...Stopping profile...
08-03 19:13:41.822   872  2014 D DhcpClient: Clearing IP address
08-03 19:13:41.823   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-03 19:13:41.824  2538  2538 V BluetoothAdapterState: isTurningOff()=true
,08-03 19:13:41.824  2538  2538 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:41.824  2538  2538 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:41.824  2538  2538 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:41.825  2538  2538 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 19:13:41.825  2538  2590 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 19:13:41.825  2538  2538 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 19:13:41.825   371   870 D CommandListener: Setting iface cfg
08-03 19:13:41.826  2538  2538 D PanService: Received stop request...Stopping profile...
08-03 19:13:41.827  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-03 19:13:41.827  1354  1354 D PanProfile: Bluetooth service disconnected
08-03 19:13:41.827  2538  2538 V BluetoothAdapterState: isTurningOff()=true
,08-03 19:13:41.827  2538  2538 V BluetoothAdapterState: isTurningOn()=false
,08-03 19:13:41.827  2538  2538 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:41.827  2538  2538 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:41.828  2538  2538 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-03 19:13:41.828  2538  2590 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-03 19:13:41.828  2538  2538 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-03 19:13:41.828  2538  2538 D BluetoothMapService: Received stop request...Stopping profile...
08-03 19:13:41.828  2538  2538 D BluetoothMapService: stop()
08-03 19:13:41.829  2538  2538 D BluetoothMapAppObserver: deinitObservers()
,08-03 19:13:41.829  2538  2538 D BluetoothMapAppObserver: removeReceiver()
08-03 19:13:41.830   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-03 19:13:41.830  1354  1354 D BluetoothMap: Proxy object disconnected
08-03 19:13:41.830   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-03 19:13:41.830  1354  1354 D MapProfile: Bluetooth service disconnected
08-03 19:13:41.830  2538  2538 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:41.830  2538  2538 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:41.830  2538  2538 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:41.830  2538  2538 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:41.831  2538  2538 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 19:13:41.831  2538  2538 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 19:13:41.831  2538  2538 D BluetoothMapService: MAP Service closeService in
08-03 19:13:41.831  2538  2538 D BluetoothMapMasInstance0: MAP Service shutdown
,08-03 19:13:41.831  2538  2538 D ObexServerSockets0: shutdown(block = true)
,08-03 19:13:41.832  2538  2754 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 19:13:41.832   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
08-03 19:13:41.833  2538  2538 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 19:13:41.833  2538  2538 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 19:13:41.834  2538  2755 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-03 19:13:41.834  2538  2538 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:41.834  2538  2538 V BluetoothAdapterState: isTurningOn()=false
,08-03 19:13:41.834  2538  2742 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-03 19:13:41.834  2538  2538 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:41.834  2538  2538 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:41.834  2538  2538 D BluetoothMapService: cleanup()
08-03 19:13:41.834  2538  2538 D BluetoothMapService: MAP Service closeService in
,08-03 19:13:41.835  2538  2586 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 19:13:41.835  2538  2586 D BluetoothAdapterProperties: Setting state to 15
08-03 19:13:41.835  2538  2586 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 19:13:41.835   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 19:13:41.836   872  1306 E native  : do suspend true
,08-03 19:13:41.836  2538  2586 I BluetoothAdapterState: Entering BleOnState
,08-03 19:13:41.836  1517  2293 V NativeCrypto: Read error: ssl=0x9ae16c00: I/O error during system call, Connection timed out
08-03 19:13:41.836   395   395 E Parcel  : Reading a NULL string not supported here.
08-03 19:13:41.838   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100],
08-03 19:13:41.843  2538  2538 I BtOppRfcommListener: stopping Accept Thread
08-03 19:13:41.843  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:41.843  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:41.843  2538  3286 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-03 19:13:41.844  2538  3286 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 19:13:41.844  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.844  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:41.846  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:41.846  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:13:41.846  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:41.846  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:41.847   872  2019 D DhcpClient: Receive thread stopped
08-03 19:13:41.849  1517  2293 V NativeCrypto: SSL shutdown failed: ssl=0x9ae16c00: I/O error during system call, Broken pipe
08-03 19:13:41.857   872   885 I ActivityManager: Start proc 3782:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-03 19:13:41.858  1354  2074 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 19:13:41.859  1354  1368 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 19:13:41.860   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 19:13:41.860  1354  1390 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:13:41.860   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:13:41.860  1354  3725 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 19:13:41.860   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:13:41.860   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:13:41.861  1720  1730 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:13:41.861  1354  2074 D BluetoothMap: onBluetoothStateChange: up=false
08-03 19:13:41.861  1354  1368 D BluetoothPan: onBluetoothStateChange on: false
08-03 19:13:41.862  2538  2586 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-03 19:13:41.862  2538  2586 D BluetoothAdapterProperties: Setting state to 16
,08-03 19:13:41.862  2538  2586 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-03 19:13:41.863  2538  2586 D BluetoothAdapterProperties: onBleDisable
08-03 19:13:41.863  2538  2586 I BluetoothAdapterState: Entering PendingCommandState
08-03 19:13:41.863  2538  2587 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-03 19:13:41.864  2538  2590 D BluetoothAdapterProperties: Scan Mode:20
,08-03 19:13:41.864  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.865  2538  2734 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-03 19:13:41.865  2538  2734 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:41.865  3726  3775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
,08-03 19:13:41.866  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.867  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.868  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:41.874   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-03 19:13:41.901   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-03 19:13:41.901   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 19:13:41.901   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 19:13:41.901   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:13:41.903   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-03 19:13:41.906  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.907  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:41.909  3236  3236 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6464a99 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-03 19:13:41.910  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-03 19:13:41.919  3782  3782 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-03 19:13:41.928  3782  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 19:13:41.932  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:13:41.934   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c9e9e4:true
,08-03 19:13:41.945   872  1393 I ActivityManager: Start proc 3800:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-03 19:13:41.947   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-03 19:13:41.949   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 19:13:41.959  3782  3782 D LocalBluetoothProfileManager: Adding local MAP profile
,08-03 19:13:41.963  3782  3782 D BluetoothMap: Create BluetoothMap proxy object
,08-03 19:13:41.967   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 19:13:41.970  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.970  1868  2070 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:41.970  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:13:41.971  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.971  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:41.971   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-03 19:13:41.972  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:41.972  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:13:41.972  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:41.973  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:13:41.985  3782  3782 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-03 19:13:41.993  3800  3800 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-03 19:13:42.000  3782  3782 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:13:42.005   872  1718 I ActivityManager: Killing 3236:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-03 19:13:42.070  2538  2590 I bt_hci  : shut_down
,08-03 19:13:42.070  2538  2594 D bt_hwcfg: hw_epilog_process
,08-03 19:13:42.071  2538  2594 I bt_vendor: low_power_mode_cb
,08-03 19:13:42.097  2538  2594 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-03 19:13:42.097  2538  2594 I bt_vendor: epilog_cb
08-03 19:13:42.098  2538  2594 I bt_hci  : epilog_finished_callback
,08-03 19:13:42.103  2538  2590 I bt_hci_h4: hal_close
,08-03 19:13:42.105  2538  2590 I bt_userial_vendor: device fd = 51 close
,08-03 19:13:42.178  3800  3800 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 19:13:42.178  3800  3800 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 19:13:42.178  3800  3800 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 19:13:42.178  3800  3800 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 19:13:42.178  3800  3800 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.k.d(PG:583)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:13:42.178  3800  3800 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:13:42.178  3800  3800 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.178  3800  3800 D StrictMod,e: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.178  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:13:42.179  3800  3800 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:13:42.179  3800  3800 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:13:42.184  3782  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 19:13:42.199  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 19:13:42.207  3782  3782 D DockEventReceiver: finishStartingService: stopping service
08-03 19:13:42.222   872  1540 I ActivityManager: Killing 3430:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-03 19:13:42.243  3726  3726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 19:13:42.262  1853  1853 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 19:13:42.276  1853  1853 D SystemUpdateService: onCreate
,08-03 19:13:42.278  2538  2587 D bt_stack_manager: event_shut_down_stack finished.
,08-03 19:13:42.279  2538  2586 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-03 19:13:42.280  1853  1853 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 19:13:42.288  1853  3832 I SystemUpdateService: active receiver: enabled
,08-03 19:13:42.289  2538  2538 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 19:13:42.294  2538  2586 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-03 19:13:42.294  2538  2538 D BtGatt.GattService: Received stop request...Stopping profile...
,08-03 19:13:42.294  2538  2538 D BtGatt.GattService: stop()
08-03 19:13:42.295  2538  2538 D BtGatt.AdvertiseManager: advertise clients cleared
,08-03 19:13:42.301  2538  2538 V BluetoothAdapterState: isTurningOff()=false
08-03 19:13:42.301  2538  2538 V BluetoothAdapterState: isTurningOn()=false
,08-03 19:13:42.302  1853  1853 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-03 19:13:42.302  2538  2538 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:42.302  2538  2538 V BluetoothAdapterState: isBleTurningOff()=true,
08-03 19:13:42.302  2538  2586 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-03 19:13:42.303  2538  2586 D BluetoothAdapterProperties: Setting state to 10
08-03 19:13:42.303  2538  2586 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-03 19:13:42.305  2538  2586 I BluetoothAdapterState: Entering OffState
,08-03 19:13:42.305   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-03 19:13:42.307  1853  2329 I iu.UploadsManager: num queued entries: 0
,08-03 19:13:42.307  1853  2329 I iu.UploadsManager: num updated entries: 0
,08-03 19:13:42.308  1853  2329 I iu.SyncManager: NEXT; no task
,08-03 19:13:42.312  1853  3832 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 19:13:42.314  1853  1853 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 19:13:42.315  1853  1853 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 19:13:42.325  2538  2538 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-03 19:13:42.325  2538  2538 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 19:13:42.325  2538  2538 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 19:13:42.326  2538  2587 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 19:13:42.327  2538  2587 D bt_stack_manager: event_clean_up_stack finished.
,08-03 19:13:42.329  1853  3832 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-03 19:13:42.329  1853  3832 I SystemUpdateService: now status is 0 (complete)
,08-03 19:13:42.330  1853  3832 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 19:13:42.330  1853  3832 I SystemUpdateService: file has been verified
08-03 19:13:42.330  1853  3832 I SystemUpdateService: OTA package size = 12249756
,08-03 19:13:42.335  2538  2538 I art     : System.exit called, status: 0
,08-03 19:13:42.335  2538  2538 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 19:13:42.346  1853  3832 I SystemUpdateService: showing system update notification
,08-03 19:13:42.358   872  1804 I ActivityManager: Start proc 3835:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-03 19:13:42.378   872   883 I ActivityManager: Process com.android.bluetooth (pid 2538) has died
,08-03 19:13:42.388  3835  3835 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-03 19:13:42.390  3835  3835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:13:42.400  3835  3835 D SprintDMHelper: simOperator: 
08-03 19:13:42.400  3835  3835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 19:13:42.410  3800  3825 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-03 19:13:42.421   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eff367b:true
,08-03 19:13:42.423   872   882 I ActivityManager: Start proc 3849:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-03 19:13:42.437  1853  1853 D SystemUpdateService: onDestroy
,08-03 19:13:42.530  2362  3863 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-03 19:13:42.543   872  1718 I ActivityManager: Start proc 3864:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-03 19:13:42.545   872   883 I ActivityManager: Killing 3301:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-03 19:13:42.600  3864  3864 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-03 19:13:42.646  3864  3864 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-03 19:13:42.646  3864  3864 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-03 19:13:42.646  3864  3864 I GAv4    :   adb logcat -s GAv4
,08-03 19:13:42.671  3864  3864 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-03 19:13:42.677  3864  3864 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-03 19:13:42.707  3864  3881 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-03 19:13:42.814  3864  3864 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-03 19:13:42.857  3864  3864 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-03 19:13:42.869  3864  3864 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1339-1345)
,08-03 19:13:42.869  3864  3864 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 19:13:42.880  3864  3864 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3220c09}
,08-03 19:13:42.880  3864  3864 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 19:13:42.881  3864  3864 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 19:13:42.890  3864  3864 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-03 19:13:42.892  3864  3864 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 19:13:42.909  3864  3864 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 19:13:42.925  3864  3864 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 19:13:42.925  3864  3864 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 19:13:42.925  3864  3864 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 19:13:42.925  3864  3864 I Adreno  : Build Date                       : 10/20/15
08-03 19:13:42.925  3864  3864 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 19:13:42.925  3864  3864 I Adreno  : Local Branch                     : M14
08-03 19:13:42.925  3864  3864 I Adreno  : Remote Branch                    : 
08-03 19:13:42.925  3864  3864 I Adreno  : Remote Branch                    : 
08-03 19:13:42.925  3864  3864 I Adreno  : Reconstruct Branch               : 
,08-03 19:13:42.994  3864  3864 I NSApplication: Starting up...
,08-03 19:13:43.006  3864  3910 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-03 19:13:43.042   872  1805 I ActivityManager: Start proc 3915:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-03 19:13:43.043   872  1805 I ActivityManager: Killing 3357:android.process.acore/u0a5 (adj 15): empty #17
,08-03 19:13:43.151  3915  3915 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-03 19:13:43.345   872  1735 I ActivityManager: Killing 3550:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-03 19:13:43.451   872   883 I ActivityManager: Start proc 3929:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-03 19:13:43.521  3929  3929 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-03 19:13:43.578  3929  3929 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-03 19:13:43.634   872  1540 I ActivityManager: Killing 3565:com.android.musicfx/u0a18 (adj 15): empty #17
,08-03 19:13:44.812   872   882 D WifiService: setWifiEnabled: true pid=3726, uid=10000
,08-03 19:13:44.813   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:13:44.826   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-03 19:13:44.834  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:44.835  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:44.835  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:44.835  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:13:44.838  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:44.839  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:44.839  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:44.839  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:13:44.857   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-03 19:13:44.858   872  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 19:13:44.858   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 19:13:44.859   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 19:13:44.860   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 19:13:44.861   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-03 19:13:44.861   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 19:13:44.861   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 19:13:44.882   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 19:13:44.883   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 19:13:44.885   371   870 D CommandListener: Setting iface cfg
,08-03 19:13:44.887   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-03 19:13:44.888   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 19:13:44.898   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 19:13:44.899   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 19:13:44.901   872  1306 E native  : do suspend true
,08-03 19:13:44.939   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 19:13:46.312   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 19:13:46.349   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.88 rxSuccessRate=11.88 delta 1000 -> 994
,08-03 19:13:46.352   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-03 19:13:46.353   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 19:13:46.373   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 19:13:46.438   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 19:13:46.440  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 19:13:46.859  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 19:13:46.900  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 19:13:46.901  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 19:13:46.912   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 19:13:46.928   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-03 19:13:46.929   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:13:46.929   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 19:13:46.947   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 19:13:46.963   371   870 D CommandListener: Setting iface cfg
,08-03 19:13:46.964   872  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-03 19:13:46.969   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 19:13:47.000   872  3964 D DhcpClient: Receive thread started
,08-03 19:13:47.080   872  1306 E native  : do suspend false
,08-03 19:13:47.090   872  2014 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 19:13:47.102   872  3964 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172417, domain null
,08-03 19:13:47.102   872  2014 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172417 seconds
,08-03 19:13:47.105   872  2014 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 19:13:47.117   872  3964 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 19:13:47.118   872  2014 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 19:13:47.122   371   870 D CommandListener: Setting iface cfg
,08-03 19:13:47.132   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-03 19:13:47.132   872  2014 D DhcpClient: Scheduling renewal in 86399s
,08-03 19:13:47.135   872  1306 E native  : do suspend true
,08-03 19:13:47.152   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 19:13:47.153   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-03 19:13:47.154   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 19:13:47.156   872  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-03 19:13:47.161   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 19:13:47.206   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 19:13:47.206   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-03 19:13:47.208   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-03 19:13:47.209   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-03 19:13:47.211   872  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-03 19:13:47.227   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 19:13:47.243   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-03 19:13:47.243   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-03 19:13:47.244   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-03 19:13:47.244   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-03 19:13:47.244   872  1308 D ConnectivityService:    accepting network in place of null
08-03 19:13:47.246   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 19:13:47.248   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 19:13:47.261   872  3963 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405736, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 19:13:47.289   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 19:13:47.325   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 19:13:47.334   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-03 19:13:47.335   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 19:13:47.337   872  3962 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-03 19:13:47.342   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-03 19:13:47.343   872   889 D Tethering: MasterInitialState.processMessage what=3
08-03 19:13:47.362  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:47.362  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:13:47.362  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:47.362  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:47.364  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:13:47.364  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:13:47.364  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:47.364  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:13:47.371  1853  1853 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 19:13:47.373  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-03 19:13:47.374  1853  1853 D SystemUpdateService: onCreate
,08-03 19:13:47.377  1853  1853 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 19:13:47.379  1853  3974 I SystemUpdateService: active receiver: enabled
,08-03 19:13:47.382  1853  3974 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 19:13:47.387  1853  3974 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-03 19:13:47.387  1853  3974 I SystemUpdateService: now status is 0 (complete)
08-03 19:13:47.387  1853  3974 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 19:13:47.388  1853  3974 I SystemUpdateService: file has been verified
,08-03 19:13:47.388  1853  3974 I SystemUpdateService: OTA package size = 12249756
,08-03 19:13:47.395  1853  3974 I SystemUpdateService: showing system update notification
,08-03 19:13:47.399  1853  1853 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-03 19:13:47.400  1853  2329 I iu.UploadsManager: num queued entries: 0
08-03 19:13:47.401  1853  2329 I iu.UploadsManager: num updated entries: 0
,08-03 19:13:47.402  1853  2329 I iu.SyncManager: NEXT; no task
,08-03 19:13:47.406  1853  1853 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-03 19:13:47.407  1853  1853 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 19:13:47.407  1853  3979 I MDM     : [209] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-03 19:13:47.407  1853  3979 W BaseAppContext: Using Auth Proxy for data requests.
08-03 19:13:47.409  3835  3835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:13:47.410  1853  3979 V GoogleAuthProtoRequest: [209] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 19:13:47.416  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 19:13:47.418  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 19:13:47.418  1853  1853 D SystemUpdateService: onDestroy
,08-03 19:13:47.440  3835  3835 I art     : Waiting for a blocking GC DisableMovingGc
,08-03 19:13:47.440  3835  3835 I art     : Starting a blocking GC DisableMovingGc
,08-03 19:13:47.441  3835  3835 D SprintDMHelper: simOperator: 
08-03 19:13:47.441  3835  3835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 19:13:47.448   872  3962 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 17:13:47 GMT], X-Android-Received-Millis=[1470244427447], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470244427404]}
,08-03 19:13:47.450   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 19:13:47.450   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-03 19:13:47.450   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 19:13:47.451   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 19:13:47.454  1517  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 19:13:47.454  1517  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-03 19:13:47.454  1517  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 19:13:47.454  1517  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 19:13:47.475  1853  3979 E MDM     : [209] SitrepService.a: Error sending sitrep.
,08-03 19:13:47.591  2362  3982 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 19:13:47.593   872  1735 I ActivityManager: Killing 2040:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-03 19:13:47.819   872  1807 D WifiService: setWifiEnabled: false pid=3726, uid=10000
08-03 19:13:47.820   872  1807 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:13:47.848  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 19:13:47.856   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-03 19:13:47.857   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-03 19:13:47.857   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 19:13:47.858   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 19:13:47.885   872  1306 E native  : do suspend true
,08-03 19:13:47.896   872  2014 D DhcpClient: Clearing IP address
,08-03 19:13:47.897   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 19:13:47.901   371   870 D CommandListener: Setting iface cfg
,08-03 19:13:47.905  1517  3986 V NativeCrypto: Read error: ssl=0x9ae16c00: I/O error during system call, Connection timed out
,08-03 19:13:47.909  1517  3986 V NativeCrypto: SSL shutdown failed: ssl=0x9ae16c00: I/O error during system call, Broken pipe
,08-03 19:13:47.917   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-03 19:13:47.918   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-03 19:13:47.922   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-03 19:13:47.923   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 19:13:47.923   872  1306 E native  : do suspend true
,08-03 19:13:47.925   395   395 E Parcel  : Reading a NULL string not supported here.
,08-03 19:13:47.930   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-03 19:13:47.934   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 19:13:47.947   872  3964 D DhcpClient: Receive thread stopped
,08-03 19:13:47.963   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 19:13:47.989   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 19:13:47.990   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 19:13:47.990   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:13:47.994   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-03 19:13:47.998  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:47.998  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:47.998  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:47.998  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:13:47.999  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:47.999  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:47.999  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:47.999  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:13:48.003  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-03 19:13:48.008   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-03 19:13:48.013  1853  1853 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-03 19:13:48.019  1853  1853 D SystemUpdateService: onCreate
08-03 19:13:48.023   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 19:13:48.023  1853  1853 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-03 19:13:48.025  1868  2070 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 19:13:48.026  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:48.026  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:48.026  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:48.026   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 19:13:48.026  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:48.036  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:48.036  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:48.036  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:48.037  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:48.043  1853  1853 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-03 19:13:48.045  1853  2329 I iu.UploadsManager: num queued entries: 0
08-03 19:13:48.045  1853  2329 I iu.UploadsManager: num updated entries: 0
08-03 19:13:48.045  1853  2329 I iu.SyncManager: NEXT; no task
,08-03 19:13:48.050  1853  1853 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 19:13:48.052  1853  1853 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 19:13:48.054  3835  3835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:13:48.068  3835  3835 D SprintDMHelper: simOperator: 
,08-03 19:13:48.068  3835  3835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 19:13:48.078  1853  3996 I SystemUpdateService: active receiver: enabled
,08-03 19:13:48.081  2362  4001 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-03 19:13:48.082  1853  3996 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 19:13:48.083  1853  3996 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-03 19:13:48.083  1853  3996 I SystemUpdateService: now status is 0 (complete)
08-03 19:13:48.083  1853  3996 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 19:13:48.083  1853  3996 I SystemUpdateService: file has been verified
08-03 19:13:48.084  1853  3996 I SystemUpdateService: OTA package size = 12249756
,08-03 19:13:48.087   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-03 19:13:48.087   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-03 19:13:48.115  1853  3996 I SystemUpdateService: showing system update notification
,08-03 19:13:48.126  1853  1853 D SystemUpdateService: onDestroy
,08-03 19:13:48.331   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-03 19:13:50.876   872   889 I ActivityManager: Start proc 4006:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 19:13:50.970  4006  4006 D AdapterServiceConfig: Adding HeadsetService
,08-03 19:13:50.970  4006  4006 D AdapterServiceConfig: Adding A2dpService
08-03 19:13:50.970  4006  4006 D AdapterServiceConfig: Adding HidService
,08-03 19:13:50.971  4006  4006 D AdapterServiceConfig: Adding HealthService
,08-03 19:13:50.971  4006  4006 D AdapterServiceConfig: Adding PanService
,08-03 19:13:50.971  4006  4006 D AdapterServiceConfig: Adding GattService,
,08-03 19:13:50.971  4006  4006 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 19:13:50.984   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e9f0f7:true
08-03 19:13:50.984  4006  4006 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 19:13:50.989  4006  4006 I bt_bluedroid: init
,08-03 19:13:50.989  4006  4018 I BluetoothAdapterState: Entering OffState
,08-03 19:13:50.995  4006  4019 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 19:13:50.995  4006  4019 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-03 19:13:50.995  4006  4019 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 19:13:50.996  4006  4019 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-03 19:13:50.997  4006  4006 I bt_bluedroid: get_profile_interface socket
,08-03 19:13:50.999  4006  4006 I bt_bluedroid: get_profile_interface sdp
,08-03 19:13:51.003  4006  4022 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-03 19:13:51.003  4006  4017 I bt_bluedroid: config_hci_snoop_log
,08-03 19:13:51.007   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-03 19:13:51.006  4006  4022 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 19:13:51.012  4006  4018 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 19:13:51.013  4006  4018 D BluetoothAdapterProperties: Setting state to 14
08-03 19:13:51.014  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 19:13:51.017  4006  4018 D BluetoothBondStateMachine: make
,08-03 19:13:51.022  4006  4023 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 19:13:51.027  4006  4018 I BluetoothAdapterState: Entering PendingCommandState
,08-03 19:13:51.028  4006  4006 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 19:13:51.031  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
08-03 19:13:51.032  4006  4006 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 19:13:51.032  4006  4006 D BtGatt.GattService: Received start request. Starting profile...
08-03 19:13:51.032  4006  4006 D BtGatt.GattService: start()
08-03 19:13:51.032  4006  4006 I bt_bluedroid: get_profile_interface gatt
08-03 19:13:51.033  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
08-03 19:13:51.033  4006  4006 D BtGatt.AdvertiseManager: advertise manager created
,08-03 19:13:51.042  4006  4006 V BluetoothAdapterState: isTurningOff()=false
08-03 19:13:51.042  4006  4006 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:51.042  4006  4006 V BluetoothAdapterState: isBleTurningOn()=true
08-03 19:13:51.042  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:51.042  4006  4018 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-03 19:13:51.043  4006  4018 I bt_bluedroid: enable
,08-03 19:13:51.044  4006  4019 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-03 19:13:51.044  4006  4019 I bt_hci  : start_up
,08-03 19:13:51.063  4006  4019 I bt_vendor: alloc value 0xb39ad189
08-03 19:13:51.063  4006  4019 I bt_vendor: init
,08-03 19:13:51.063  4006  4019 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-03 19:13:51.064  4006  4019 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 19:13:51.172  4006  4019 D bt_hci  : start_up starting async portion
,08-03 19:13:51.173  4006  4026 I bt_hci  : event_finish_startup
08-03 19:13:51.173  4006  4026 I bt_hci_h4: hal_open
,08-03 19:13:51.173  4006  4026 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 19:13:51.185  4006  4026 I bt_userial_vendor: device fd = 51 open
,08-03 19:13:51.213  4006  4026 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 19:13:51.246  4006  4026 D bt_hwcfg: Chipset BCM4354A2
,08-03 19:13:51.246  4006  4026 D bt_hwcfg: Target name = [BCM4354A2]
08-03 19:13:51.247  4006  4026 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 19:13:51.902  4006  4026 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 19:13:51.903  4006  4026 D bt_hwcfg: Settlement delay -- 100 ms
08-03 19:13:51.903  4006  4026 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 19:13:52.020  4006  4026 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 19:13:52.021  4006  4026 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 19:13:52.051  4006  4026 I bt_hwcfg: vendor lib fwcfg completed
08-03 19:13:52.051  4006  4026 I bt_vendor: firmware callback
08-03 19:13:52.051  4006  4026 I bt_hci  : firmware_config_callback
,08-03 19:13:52.062  4006  4028 I bt_btu  : btu_task pending for preload complete event
,08-03 19:13:52.062  4006  4028 I bt_btu_task: Bluetooth chip preload is complete
,08-03 19:13:52.063  4006  4028 I bt_btu  : btu_task received preload complete event
,08-03 19:13:52.074  4006  4028 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 19:13:52.074  4006  4028 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 19:13:52.075  4006  4028 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-03 19:13:52.075  4006  4028 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 19:13:52.075  4006  4028 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 19:13:52.076  4006  4028 I         : BTE_InitTraceLevels -- TRC_A2D
,08-03 19:13:52.076  4006  4028 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 19:13:52.076  4006  4028 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 19:13:52.076  4006  4028 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 19:13:52.076  4006  4028 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 19:13:52.077  4006  4028 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 19:13:52.077  4006  4028 I         : BTE_InitTraceLevels -- TRC_GATT
,08-03 19:13:52.077  4006  4028 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 19:13:52.078  4006  4028 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-03 19:13:52.078  4006  4028 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 19:13:52.215  4006  4028 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392ad9d
,08-03 19:13:52.215  4006  4028 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392ad9d 
,08-03 19:13:52.227  4006  4022 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-03 19:13:52.228  4006  4022 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 19:13:52.229  4006  4022 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 19:13:52.233  4006  4022 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 19:13:52.237  4006  4022 D BluetoothAdapterProperties: Scan Mode:20
,08-03 19:13:52.237  4006  4022 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 19:13:52.238  4006  4022 D bt_hci  : do_postload posting postload work item
,08-03 19:13:52.238  4006  4026 I bt_hci  : event_postload
,08-03 19:13:52.238  4006  4026 I bt_vendor: sco_config_cb
,08-03 19:13:52.238  4006  4026 I bt_hci  : sco_config_callback postload finished.
,08-03 19:13:52.240  4006  4022 D bt_bte_conf: Device ID record 1 : primary
,08-03 19:13:52.241  4006  4022 D bt_bte_conf:   vendorId            = 000f
,08-03 19:13:52.241  4006  4022 D bt_bte_conf:   vendorIdSource      = 0001
08-03 19:13:52.241  4006  4022 D bt_bte_conf:   product             = 1200
08-03 19:13:52.241  4006  4022 D bt_bte_conf:   version             = 1436
08-03 19:13:52.241  4006  4022 D bt_bte_conf:   clientExecutableURL = 
,08-03 19:13:52.242  4006  4022 D bt_bte_conf:   serviceDescription  = 
08-03 19:13:52.242  4006  4022 D bt_bte_conf:   documentationURL    = 
08-03 19:13:52.242  4006  4022 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 19:13:52.242  4006  4019 D bt_stack_manager: event_start_up_stack finished
08-03 19:13:52.243  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:52.244  4006  4026 I bt_vendor: low_power_mode_cb
08-03 19:13:52.244  4006  4018 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 19:13:52.245  4006  4018 D BluetoothAdapterProperties: Setting state to 15
08-03 19:13:52.245  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-03 19:13:52.246  4006  4018 I BluetoothAdapterState: Entering BleOnState
08-03 19:13:52.247  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:52.252  4006  4018 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-03 19:13:52.252  4006  4018 D BluetoothAdapterProperties: Setting state to 11
08-03 19:13:52.252  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 19:13:52.260  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:13:52.262  4006  4006 D HeadsetService: Received start request. Starting profile...
,08-03 19:13:52.266  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:52.268  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:52.269  4006  4006 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 19:13:52.269  4006  4006 D HeadsetStateMachine: make
,08-03 19:13:52.281  4006  4018 I BluetoothAdapterState: Entering PendingCommandState
,08-03 19:13:52.283  4006  4006 D HeadsetStateMachine: max_hf_connections = 1
,08-03 19:13:52.284  4006  4006 I bt_bluedroid: get_profile_interface handsfree
08-03 19:13:52.284  4006  4022 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-03 19:13:52.284  4006  4022 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 19:13:52.292  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:13:52.293  4006  4006 D A2dpService: Received start request. Starting profile...
,08-03 19:13:52.294  4006  4006 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 19:13:52.294  4006  4006 I bt_bluedroid: get_profile_interface avrcp
,08-03 19:13:52.300  4006  4006 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 19:13:52.300  4006  4006 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:13:52.300  4006  4006 D A2dpStateMachine: make
,08-03 19:13:52.301  4006  4006 I bt_bluedroid: get_profile_interface a2dp
08-03 19:13:52.302  4006  4022 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 19:13:52.303  4006  4037 D A2dpStateMachine: Enter Disconnected: -2
08-03 19:13:52.304  4006  4006 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 19:13:52.304  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:13:52.306  3782  3782 D BluetoothInputDevice: Proxy object connected
,08-03 19:13:52.306  4006  4006 D HidService: Received start request. Starting profile...
08-03 19:13:52.306  4006  4006 I bt_bluedroid: get_profile_interface hidhost
08-03 19:13:52.306  4006  4006 D HidService: setHidService(): set to: null
,08-03 19:13:52.306  4006  4022 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390c3e5
08-03 19:13:52.306  3782  3782 D HidProfile: Bluetooth service connected
08-03 19:13:52.306  4006  4022 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-03 19:13:52.307  4006  4006 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:13:52.307  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
08-03 19:13:52.308  4006  4006 D HealthService: Received start request. Starting profile...
,08-03 19:13:52.309  4006  4006 I bt_bluedroid: get_profile_interface health
,08-03 19:13:52.311  4006  4006 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 19:13:52.312  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
08-03 19:13:52.313  3782  3782 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 19:13:52.314  4006  4006 D PanService: Received start request. Starting profile...
08-03 19:13:52.314  3782  3782 D PanProfile: Bluetooth service connected
08-03 19:13:52.314  4006  4006 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-03 19:13:52.314  4006  4006 I bt_bluedroid: get_profile_interface pan
08-03 19:13:52.315  4006  4022 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-03 19:13:52.319  4006  4006 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:13:52.320  3782  3782 D BluetoothMap: Proxy object connected
,08-03 19:13:52.320  4006  4006 D BluetoothMapService: Received start request. Starting profile...
08-03 19:13:52.320  4006  4006 D BluetoothMapService: start()
08-03 19:13:52.320  3782  3782 D MapProfile: Bluetooth service connected
,08-03 19:13:52.320  3782  3782 D BluetoothMap: getConnectedDevices()
08-03 19:13:52.321  3782  3782 D BluetoothMap: Bluetooth is Not enabled
,08-03 19:13:52.322  4006  4006 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 19:13:52.323  4006  4006 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 19:13:52.323  4006  4006 D BluetoothMapAppObserver: createReceiver()
,08-03 19:13:52.325  4006  4006 D BluetoothMapAppObserver: initObservers()
,08-03 19:13:52.325  4006  4006 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 19:13:52.337  4006  4006 V BluetoothAdapterState: isTurningOff()=false
,08-03 19:13:52.337  4006  4006 V BluetoothAdapterState: isTurningOn()=true
08-03 19:13:52.337  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:52.337  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:52.338  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:13:52.341  4006  4035 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-03 19:13:52.341  4006  4006 V BluetoothAdapterState: isTurningOff()=false
08-03 19:13:52.341  4006  4006 V BluetoothAdapterState: isTurningOn()=true
08-03 19:13:52.342  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:52.342  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:52.342  4006  4006 V BluetoothAdapterState: isTurningOff()=false
08-03 19:13:52.342  4006  4006 V BluetoothAdapterState: isTurningOn()=true
08-03 19:13:52.342  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:52.342  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:52.343  4006  4006 V BluetoothAdapterState: isTurningOff()=false
,08-03 19:13:52.343  4006  4006 V BluetoothAdapterState: isTurningOn()=true
08-03 19:13:52.343  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:52.343  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isTurningOff()=false
08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isTurningOn()=true
08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isTurningOff()=false
08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isTurningOn()=true
,08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:52.344  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:52.344  4006  4018 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-03 19:13:52.344  4006  4018 D BluetoothAdapterProperties: ScanMode =  20
,08-03 19:13:52.345  4006  4018 D BluetoothAdapterProperties: State =  11
,08-03 19:13:52.345  4006  4018 D BluetoothAdapterProperties: Setting state to 12
,08-03 19:13:52.345  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 19:13:52.345  4006  4018 I BluetoothAdapterState: Entering OnState
,08-03 19:13:52.346  3782  3794 D BluetoothPan: onBluetoothStateChange on: true
08-03 19:13:52.346  1354  3725 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 19:13:52.347  4006  4022 D BluetoothAdapterProperties: Scan Mode:21
08-03 19:13:52.348  4006  4022 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 19:13:52.348  1354  1390 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:52.351  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:13:52.351  3782  3793 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 19:13:52.352  3782  3794 D BluetoothMap: onBluetoothStateChange: up=true
08-03 19:13:52.352  1354  1354 D BluetoothA2dp: Proxy object connected
08-03 19:13:52.353   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 19:13:52.354  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:52.354   872   872 D BluetoothA2dp: Proxy object connected
08-03 19:13:52.354  1354  1368 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:13:52.356   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:13:52.356  4006  4006 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 19:13:52.356  1354  3725 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 19:13:52.357  4006  4006 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:52.358  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:13:52.360  3782  3793 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 19:13:52.360  4006  4006 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:13:52.361  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:52.361  1354  1354 D BluetoothInputDevice: Proxy object connected
08-03 19:13:52.361  1354  1354 D HidProfile: Bluetooth service connected
08-03 19:13:52.362   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:13:52.362   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:13:52.362  1720  1912 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:13:52.363  1354  2074 D BluetoothMap: onBluetoothStateChange: up=true
08-03 19:13:52.363  4006  4006 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:13:52.364  4006  4006 D ObexServerSockets: Succeed to create listening sockets 
,08-03 19:13:52.364  4006  4006 D ObexServerSockets0: startAccept()
,08-03 19:13:52.364  4006  4006 D ObexServerSockets0: prepareForNewConnect()
08-03 19:13:52.364  1354  3725 D BluetoothPan: onBluetoothStateChange on: true
,08-03 19:13:52.364  1354  1354 D BluetoothMap: Proxy object connected
08-03 19:13:52.365  1354  1354 D MapProfile: Bluetooth service connected
08-03 19:13:52.365  1354  1354 D BluetoothMap: getConnectedDevices()
08-03 19:13:52.366  4006  4006 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-03 19:13:52.367  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 19:13:52.367   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-03 19:13:52.367  1354  1354 D PanProfile: Bluetooth service connected
08-03 19:13:52.367  4006  4006 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-03 19:13:52.370  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:52.370  4006  4043 D ObexServerSockets0: Accepting socket connection...
,08-03 19:13:52.371  4006  4006 D BluetoothMapService: onReceive
08-03 19:13:52.371  4006  4006 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:13:52.371  4006  4006 D BluetoothMapService: STATE_ON
08-03 19:13:52.371  4006  4044 D ObexServerSockets0: Accepting socket connection...
,08-03 19:13:52.372  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:52.372  3782  3782 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-03 19:13:52.381  3782  3782 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-03 19:13:52.387  3782  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 19:13:52.391  3782  3782 D BluetoothA2dp: Proxy object connected
08-03 19:13:52.391  4006  4006 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 19:13:52.391  4006  4006 D ObexServerSockets0: prepareForNewConnect()
,08-03 19:13:52.395  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:13:52.401  3782  3782 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:13:52.408  1354  1354 D BluetoothPbap: Proxy object connected
,08-03 19:13:52.408  1354  1354 D PbapServerProfile: Bluetooth service connected
08-03 19:13:52.408  3782  3782 D BluetoothPbap: Proxy object connected
08-03 19:13:52.409  3782  3782 D PbapServerProfile: Bluetooth service connected
,08-03 19:13:52.419  4006  4049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:13:52.441  4006  4053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:13:52.442  4006  4053 I BtOppRfcommListener: Accept thread started.
,08-03 19:13:52.457   872   872 D BluetoothHeadset: Proxy object connected
,08-03 19:13:52.458  1354  3725 D BluetoothHeadset: Proxy object connected
08-03 19:13:52.458  1354  1354 D HeadsetProfile: Bluetooth service connected
08-03 19:13:52.458   872   872 D BluetoothHeadset: Proxy object connected
08-03 19:13:52.459  1720  1732 D BluetoothHeadset: Proxy object connected
08-03 19:13:52.459   872   872 D BluetoothHeadset: Proxy object connected
,08-03 19:13:52.462   872   889 D BluetoothHeadset: Proxy object connected
,08-03 19:13:52.462   872   889 D BluetoothHeadset: Proxy object connected
,08-03 19:13:52.463  1720  2085 D BluetoothHeadset: Proxy object connected
,08-03 19:13:52.485  3782  3793 D BluetoothHeadset: Proxy object connected
,08-03 19:13:52.489  3782  3782 D HeadsetProfile: Bluetooth service connected
,08-03 19:13:53.841  4006  4018 D BluetoothAdapterState: Current state: ON, message: 23
,08-03 19:13:53.841  4006  4018 D BluetoothAdapterProperties: Setting state to 13
08-03 19:13:53.841  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-03 19:13:53.843  4006  4018 D BluetoothAdapterProperties: onBluetoothDisable()
,08-03 19:13:53.847  4006  4018 I BluetoothAdapterState: Entering PendingCommandState
,08-03 19:13:53.853  4006  4006 D BluetoothMapService: onReceive
08-03 19:13:53.853  4006  4006 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 19:13:53.854  4006  4006 D BluetoothMapService: STATE_TURNING_OFF
08-03 19:13:53.854  4006  4006 D BluetoothMapService: MAP Service closeService in
08-03 19:13:53.855  4006  4006 D BluetoothMapMasInstance0: MAP Service shutdown
,08-03 19:13:53.855  4006  4006 D ObexServerSockets0: shutdown(block = true)
08-03 19:13:53.856  4006  4043 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 19:13:53.862  4006  4006 D ObexServerSockets0: shutdown called from another thread - interrupt().,
08-03 19:13:53.863  4006  4044 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-03 19:13:53.864  4006  4022 D BluetoothAdapterProperties: Scan Mode:20
,08-03 19:13:53.864  4006  4018 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 19:13:53.864  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:53.864  4006  4030 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:53.865  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:13:53.865  4006  4006 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 19:13:53.867  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:53.867  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:53.866  4006  4006 I BtOppRfcommListener: stopping Accept Thread
,08-03 19:13:53.868  4006  4053 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 19:13:53.869  3782  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 19:13:53.869  4006  4053 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 19:13:53.870  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:13:53.870  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:13:53.872  3726  3726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 19:13:53.872  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:13:53.872  4006  4006 D HeadsetService: Received stop request...Stopping profile...
08-03 19:13:53.874  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:53.874  4006  4006 D A2dpService: Received stop request...Stopping profile...
08-03 19:13:53.875  4006  4037 D A2dpStateMachine: Exit Disconnected: -1
,08-03 19:13:53.875  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:53.876  3782  3793 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:53.877   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:53.877  1354  3725 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:53.877  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-03 19:13:53.877   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:53.877  1354  1354 D BluetoothA2dp: Proxy object disconnected
,08-03 19:13:53.878  1720  1730 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:53.878   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 19:13:53.878  4006  4006 D HidService: Received stop request...Stopping profile...
08-03 19:13:53.878   872   872 D BluetoothA2dp: Proxy object disconnected
,08-03 19:13:53.878  4006  4006 D HidService: Stopping Bluetooth HidService
08-03 19:13:53.879  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-03 19:13:53.880  1354  1354 D HidProfile: Bluetooth service disconnected
,08-03 19:13:53.880  4006  4006 D HealthService: Received stop request...Stopping profile...
08-03 19:13:53.881  3782  3782 D DockEventReceiver: finishStartingService: stopping service
08-03 19:13:53.882  3782  3782 D HeadsetProfile: Bluetooth service disconnected
08-03 19:13:53.882  3782  3782 D BluetoothA2dp: Proxy object disconnected
08-03 19:13:53.882  4006  4006 D PanService: Received stop request...Stopping profile...
08-03 19:13:53.883  3782  3782 D BluetoothInputDevice: Proxy object disconnected
,08-03 19:13:53.883  3782  3782 D HidProfile: Bluetooth service disconnected
08-03 19:13:53.883  3782  3782 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 19:13:53.884  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 19:13:53.884  4006  4006 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:53.884  1354  1354 D PanProfile: Bluetooth service disconnected
08-03 19:13:53.884  4006  4006 V BluetoothAdapterState: isTurningOn()=false
,08-03 19:13:53.884  3782  3782 D PanProfile: Bluetooth service disconnected
08-03 19:13:53.884  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:53.884  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:53.886  4006  4006 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 19:13:53.886  4006  4006 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object,
08-03 19:13:53.886  4006  4022 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 19:13:53.886  4006  4028 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:53.886  4006  4028 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:53.886  4006  4028 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 19:13:53.886  4006  4022 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-03 19:13:53.888  4006  4006 D BluetoothMapService: Received stop request...Stopping profile...
08-03 19:13:53.889  4006  4006 D BluetoothMapService: stop()
08-03 19:13:53.889  4006  4006 D BluetoothMapAppObserver: deinitObservers()
,08-03 19:13:53.889  4006  4006 D BluetoothMapAppObserver: removeReceiver()
08-03 19:13:53.890  1354  1354 D BluetoothMap: Proxy object disconnected
08-03 19:13:53.890  1354  1354 D MapProfile: Bluetooth service disconnected
08-03 19:13:53.891  3782  3782 D BluetoothMap: Proxy object disconnected
,08-03 19:13:53.891  3782  3782 D MapProfile: Bluetooth service disconnected
08-03 19:13:53.892  4006  4006 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:53.892  4006  4006 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:53.892  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 19:13:53.892  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:53.894  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:13:53.895  4006  4022 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-03 19:13:53.895  4006  4028 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:53.895  4006  4028 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 19:13:53.895  4006  4028 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 19:13:53.895  4006  4028 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:13:53.895  4006  4028 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-03 19:13:53.895  4006  4028 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 19:13:53.896  4006  4006 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:53.896  4006  4006 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:53.896  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:53.896  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:53.896  4006  4006 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-03 19:13:53.897  4006  4006 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 19:13:53.897  4006  4022 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 19:13:53.897  4006  4006 V BluetoothAdapterState: isTurningOff()=true
,08-03 19:13:53.897  4006  4006 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:53.897  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:53.897  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:13:53.898  4006  4006 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 19:13:53.898  4006  4022 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-03 19:13:53.898  4006  4006 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 19:13:53.898  4006  4006 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:53.899  4006  4006 V BluetoothAdapterState: isTurningOn()=false
,08-03 19:13:53.899  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:53.899  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:53.899  4006  4006 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-03 19:13:53.899  4006  4006 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 19:13:53.900  4006  4006 D BluetoothMapService: MAP Service closeService in
,08-03 19:13:53.900  4006  4006 V BluetoothAdapterState: isTurningOff()=true
08-03 19:13:53.900  4006  4006 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:53.900  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:53.900  4006  4006 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:13:53.901  4006  4018 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 19:13:53.901  4006  4006 D BluetoothMapService: cleanup()
08-03 19:13:53.901  4006  4018 D BluetoothAdapterProperties: Setting state to 15
,08-03 19:13:53.901  4006  4006 D BluetoothMapService: MAP Service closeService in
08-03 19:13:53.901  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 19:13:53.902  4006  4018 I BluetoothAdapterState: Entering BleOnState
08-03 19:13:53.902  3782  3794 D BluetoothPan: onBluetoothStateChange on: false
08-03 19:13:53.903  1354  1390 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 19:13:53.903  1354  1354 D BluetoothPbap: Proxy object disconnected
08-03 19:13:53.903  1354  1354 D PbapServerProfile: Bluetooth service disconnected
,08-03 19:13:53.905  1354  1368 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 19:13:53.905  3782  3782 D BluetoothPbap: Proxy object disconnected
08-03 19:13:53.906  3782  3782 D PbapServerProfile: Bluetooth service disconnected
08-03 19:13:53.907  3782  3793 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 19:13:53.908  3782  3794 D BluetoothMap: onBluetoothStateChange: up=false
,08-03 19:13:53.909   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 19:13:53.909  1354  2074 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:13:53.909   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:13:53.909  1354  3725 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 19:13:53.912  3782  3793 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:13:53.912  3782  3793 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 19:13:53.912   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:13:53.913   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 19:13:53.913  1720  1912 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 19:13:53.913  1354  1390 D BluetoothMap: onBluetoothStateChange: up=false
08-03 19:13:53.914  3782  3794 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 19:13:53.914  1354  1368 D BluetoothPan: onBluetoothStateChange on: false
08-03 19:13:53.915  4006  4018 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-03 19:13:53.915  4006  4018 D BluetoothAdapterProperties: Setting state to 16
08-03 19:13:53.915  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-03 19:13:53.918  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:53.919  4006  4018 D BluetoothAdapterProperties: onBleDisable
,08-03 19:13:53.920  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:13:53.920  4006  4022 D BluetoothAdapterProperties: Scan Mode:20
08-03 19:13:53.921  4006  4018 I BluetoothAdapterState: Entering PendingCommandState
08-03 19:13:53.921  4006  4019 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-03 19:13:53.921  3782  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 19:13:53.922  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:53.923  4006  4028 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-03 19:13:53.924  4006  4028 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 19:13:53.926  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:53.928  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:13:53.934  3782  3782 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:13:54.124  4006  4022 I bt_hci  : shut_down
,08-03 19:13:54.124  4006  4026 D bt_hwcfg: hw_epilog_process
,08-03 19:13:54.127  4006  4026 I bt_vendor: low_power_mode_cb
,08-03 19:13:54.157  4006  4026 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-03 19:13:54.157  4006  4026 I bt_vendor: epilog_cb
,08-03 19:13:54.157  4006  4026 I bt_hci  : epilog_finished_callback
,08-03 19:13:54.168  4006  4022 I bt_hci_h4: hal_close
,08-03 19:13:54.170  4006  4022 I bt_userial_vendor: device fd = 51 close
,08-03 19:13:54.298  4006  4019 D bt_stack_manager: event_shut_down_stack finished.
,08-03 19:13:54.299  4006  4018 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-03 19:13:54.304  4006  4018 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-03 19:13:54.306  4006  4006 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 19:13:54.308  4006  4006 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 19:13:54.309  4006  4006 D BtGatt.GattService: stop()
,08-03 19:13:54.309  4006  4006 D BtGatt.AdvertiseManager: advertise clients cleared
,08-03 19:13:54.314  4006  4006 V BluetoothAdapterState: isTurningOff()=false
,08-03 19:13:54.314  4006  4006 V BluetoothAdapterState: isTurningOn()=false
08-03 19:13:54.314  4006  4006 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:13:54.315  4006  4006 V BluetoothAdapterState: isBleTurningOff()=true
08-03 19:13:54.315  4006  4018 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-03 19:13:54.316  4006  4018 D BluetoothAdapterProperties: Setting state to 10
08-03 19:13:54.316  4006  4018 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-03 19:13:54.318  4006  4018 I BluetoothAdapterState: Entering OffState
,08-03 19:13:54.319   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-03 19:13:54.339  4006  4006 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-03 19:13:54.339  4006  4006 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-03 19:13:54.340  4006  4019 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 19:13:54.344  4006  4019 D bt_stack_manager: event_clean_up_stack finished.
,08-03 19:13:54.344  4006  4006 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 19:13:54.347  4006  4006 I art     : System.exit called, status: 0
,08-03 19:13:54.347  4006  4006 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 19:13:54.407   872   883 I ActivityManager: Process com.android.bluetooth (pid 4006) has died
,08-03 19:13:55.250   872  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-03 19:13:56.838  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:13:56.838  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:13:59.845  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:13:59.846  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d542085 added. We now have 6 listener(s)
08-03 19:13:59.846  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:13:59.850  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-03 19:13:59.851  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a988eda added. We now have 7 listener(s)
,08-03 19:13:59.851  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:13:59.853  3726  3772 I System.out: IsBluetoothEnabled
,08-03 19:13:59.864  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:13:59.906   872   889 I ActivityManager: Start proc 4065:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 19:14:00.031  4065  4065 D AdapterServiceConfig: Adding HeadsetService
08-03 19:14:00.031  4065  4065 D AdapterServiceConfig: Adding A2dpService
08-03 19:14:00.031  4065  4065 D AdapterServiceConfig: Adding HidService
08-03 19:14:00.032  4065  4065 D AdapterServiceConfig: Adding HealthService
08-03 19:14:00.032  4065  4065 D AdapterServiceConfig: Adding PanService
08-03 19:14:00.032  4065  4065 D AdapterServiceConfig: Adding GattService
08-03 19:14:00.032  4065  4065 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 19:14:00.048   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4811078:true
08-03 19:14:00.048  4065  4065 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 19:14:00.054  4065  4065 I bt_bluedroid: init
,08-03 19:14:00.054  4065  4077 I BluetoothAdapterState: Entering OffState
,08-03 19:14:00.056  4065  4078 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 19:14:00.057  4065  4078 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 19:14:00.057  4065  4078 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-03 19:14:00.057  4065  4078 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 19:14:00.058  4065  4065 I bt_bluedroid: get_profile_interface socket
,08-03 19:14:00.060  4065  4065 I bt_bluedroid: get_profile_interface sdp
,08-03 19:14:00.065  4065  4076 I bt_bluedroid: config_hci_snoop_log,
08-03 19:14:00.065  4065  4081 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-03 19:14:00.068  4065  4081 D BluetoothAdapterProperties: Name is: Nexus 6
08-03 19:14:00.069   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 19:14:00.079  4065  4077 D BluetoothAdapterState: Current state: OFF, message: 0
08-03 19:14:00.079  4065  4077 D BluetoothAdapterProperties: Setting state to 14
08-03 19:14:00.080  4065  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 19:14:00.084  4065  4077 D BluetoothBondStateMachine: make
,08-03 19:14:00.087  4065  4082 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 19:14:00.093  4065  4077 I BluetoothAdapterState: Entering PendingCommandState
,08-03 19:14:00.095  4065  4065 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 19:14:00.098  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:14:00.099  4065  4065 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 19:14:00.100  4065  4065 D BtGatt.GattService: Received start request. Starting profile...
08-03 19:14:00.100  4065  4065 D BtGatt.GattService: start()
08-03 19:14:00.100  4065  4065 I bt_bluedroid: get_profile_interface gatt
,08-03 19:14:00.101  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
08-03 19:14:00.101  4065  4065 D BtGatt.AdvertiseManager: advertise manager created
,08-03 19:14:00.111  4065  4065 V BluetoothAdapterState: isTurningOff()=false
,08-03 19:14:00.111  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-03 19:14:00.111  4065  4065 V BluetoothAdapterState: isBleTurningOn()=true
08-03 19:14:00.111  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:14:00.112  4065  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 19:14:00.112  4065  4077 I bt_bluedroid: enable
08-03 19:14:00.113  4065  4078 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-03 19:14:00.114  4065  4078 I bt_hci  : start_up
,08-03 19:14:00.133  4065  4078 I bt_vendor: alloc value 0xb39ad189
,08-03 19:14:00.133  4065  4078 I bt_vendor: init
08-03 19:14:00.133  4065  4078 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-03 19:14:00.134  4065  4078 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 19:14:00.242  4065  4078 D bt_hci  : start_up starting async portion
,08-03 19:14:00.243  4065  4085 I bt_hci  : event_finish_startup
08-03 19:14:00.243  4065  4085 I bt_hci_h4: hal_open
08-03 19:14:00.244  4065  4085 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 19:14:00.254  4065  4085 I bt_userial_vendor: device fd = 51 open
,08-03 19:14:00.284  4065  4085 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 19:14:00.316  4065  4085 D bt_hwcfg: Chipset BCM4354A2
,08-03 19:14:00.316  4065  4085 D bt_hwcfg: Target name = [BCM4354A2]
,08-03 19:14:00.317  4065  4085 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 19:14:00.971  4065  4085 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 19:14:00.973  4065  4085 D bt_hwcfg: Settlement delay -- 100 ms
08-03 19:14:00.973  4065  4085 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 19:14:01.089  4065  4085 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 19:14:01.091  4065  4085 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 19:14:01.121  4065  4085 I bt_hwcfg: vendor lib fwcfg completed
08-03 19:14:01.121  4065  4085 I bt_vendor: firmware callback
,08-03 19:14:01.121  4065  4085 I bt_hci  : firmware_config_callback
,08-03 19:14:01.132  4065  4087 I bt_btu  : btu_task pending for preload complete event
08-03 19:14:01.132  4065  4087 I bt_btu_task: Bluetooth chip preload is complete
,08-03 19:14:01.132  4065  4087 I bt_btu  : btu_task received preload complete event
,08-03 19:14:01.142  4065  4087 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 19:14:01.142  4065  4087 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 19:14:01.143  4065  4087 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-03 19:14:01.143  4065  4087 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-03 19:14:01.143  4065  4087 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-03 19:14:01.144  4065  4087 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 19:14:01.144  4065  4087 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-03 19:14:01.144  4065  4087 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 19:14:01.144  4065  4087 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 19:14:01.145  4065  4087 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 19:14:01.145  4065  4087 I         : BTE_InitTraceLevels -- TRC_SDP
,08-03 19:14:01.145  4065  4087 I         : BTE_InitTraceLevels -- TRC_GATT
,08-03 19:14:01.145  4065  4087 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 19:14:01.146  4065  4087 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-03 19:14:01.146  4065  4087 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 19:14:01.280  4065  4087 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392ad9d
,08-03 19:14:01.280  4065  4087 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392ad9d 
,08-03 19:14:01.306  4065  4081 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-03 19:14:01.308  4065  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 19:14:01.309  4065  4081 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 19:14:01.312  4065  4081 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 19:14:01.318  4065  4081 D BluetoothAdapterProperties: Scan Mode:20
,08-03 19:14:01.318  4065  4081 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:14:01.319  4065  4081 D bt_hci  : do_postload posting postload work item
08-03 19:14:01.319  4065  4085 I bt_hci  : event_postload
08-03 19:14:01.320  4065  4085 I bt_vendor: sco_config_cb
08-03 19:14:01.320  4065  4085 I bt_hci  : sco_config_callback postload finished.
,08-03 19:14:01.324  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:01.324  4065  4081 D bt_bte_conf: Device ID record 1 : primary
08-03 19:14:01.324  4065  4081 D bt_bte_conf:   vendorId            = 000f
,08-03 19:14:01.324  4065  4081 D bt_bte_conf:   vendorIdSource      = 0001
08-03 19:14:01.326  4065  4081 D bt_bte_conf:   product             = 1200
08-03 19:14:01.327  4065  4081 D bt_bte_conf:   version             = 1436
08-03 19:14:01.327  4065  4081 D bt_bte_conf:   clientExecutableURL = 
08-03 19:14:01.327  4065  4081 D bt_bte_conf:   serviceDescription  = 
08-03 19:14:01.328  4065  4081 D bt_bte_conf:   documentationURL    = 
08-03 19:14:01.328  4065  4081 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 19:14:01.328  4065  4078 D bt_stack_manager: event_start_up_stack finished
08-03 19:14:01.328  4065  4085 I bt_vendor: low_power_mode_cb
08-03 19:14:01.329  4065  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 19:14:01.330  4065  4077 D BluetoothAdapterProperties: Setting state to 15
08-03 19:14:01.330  4065  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-03 19:14:01.331  4065  4077 I BluetoothAdapterState: Entering BleOnState
,08-03 19:14:01.336  4065  4077 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-03 19:14:01.336  4065  4077 D BluetoothAdapterProperties: Setting state to 11
,08-03 19:14:01.337  4065  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 19:14:01.347  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:14:01.350  4065  4065 D HeadsetService: Received start request. Starting profile...
08-03 19:14:01.353  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:01.357  4065  4065 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 19:14:01.358  4065  4065 D HeadsetStateMachine: make
,08-03 19:14:01.365  4065  4077 I BluetoothAdapterState: Entering PendingCommandState
,08-03 19:14:01.372  4065  4065 D HeadsetStateMachine: max_hf_connections = 1
,08-03 19:14:01.372  4065  4065 I bt_bluedroid: get_profile_interface handsfree
,08-03 19:14:01.372  4065  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-03 19:14:01.372  4065  4081 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 19:14:01.377  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:14:01.378  4065  4065 D A2dpService: Received start request. Starting profile...,
08-03 19:14:01.379  4065  4065 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-03 19:14:01.379  4065  4065 I bt_bluedroid: get_profile_interface avrcp
,08-03 19:14:01.387  4065  4065 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 19:14:01.388  4065  4065 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 19:14:01.388  4065  4065 D A2dpStateMachine: make
,08-03 19:14:01.391  4065  4065 I bt_bluedroid: get_profile_interface a2dp
,08-03 19:14:01.392  4065  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 19:14:01.395  4065  4065 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 19:14:01.395  4065  4095 D A2dpStateMachine: Enter Disconnected: -2
,08-03 19:14:01.396  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:14:01.397  4065  4065 D HidService: Received start request. Starting profile...
08-03 19:14:01.397  4065  4065 I bt_bluedroid: get_profile_interface hidhost
,08-03 19:14:01.397  4065  4081 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390c3e5
08-03 19:14:01.397  4065  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-03 19:14:01.398  4065  4065 D HidService: setHidService(): set to: null
08-03 19:14:01.399  4065  4065 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 19:14:01.400  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:14:01.401  4065  4065 D HealthService: Received start request. Starting profile...
,08-03 19:14:01.404  4065  4065 I bt_bluedroid: get_profile_interface health
,08-03 19:14:01.404  4065  4065 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 19:14:01.405  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
08-03 19:14:01.406  4065  4065 D PanService: Received start request. Starting profile...
,08-03 19:14:01.406  4065  4065 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-03 19:14:01.406  4065  4065 I bt_bluedroid: get_profile_interface pan
,08-03 19:14:01.407  4065  4081 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 19:14:01.413  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:14:01.415  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:14:01.416  4065  4065 D BluetoothMapService: Received start request. Starting profile...
,08-03 19:14:01.416  4065  4065 D BluetoothMapService: start()
,08-03 19:14:01.420  4065  4065 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 19:14:01.421  4065  4065 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-03 19:14:01.421  4065  4065 D BluetoothMapAppObserver: createReceiver()
08-03 19:14:01.423  4065  4065 D BluetoothMapAppObserver: initObservers()
08-03 19:14:01.423  4065  4065 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 19:14:01.432  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-03 19:14:01.432  4065  4065 V BluetoothAdapterState: isTurningOn()=true
,08-03 19:14:01.432  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:14:01.432  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:14:01.435  4065  4065 V BluetoothAdapterState: isTurningOff()=false
,08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isTurningOn()=true
08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isTurningOn()=true
08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:14:01.436  4065  4093 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-03 19:14:01.436  4065  4065 V BluetoothAdapterState: isTurningOn()=true
,08-03 19:14:01.437  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:14:01.437  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:14:01.437  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-03 19:14:01.437  4065  4065 V BluetoothAdapterState: isTurningOn()=true
08-03 19:14:01.437  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:14:01.437  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 19:14:01.442  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-03 19:14:01.442  4065  4065 V BluetoothAdapterState: isTurningOn()=true
08-03 19:14:01.442  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-03 19:14:01.442  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-03 19:14:01.443  4065  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-03 19:14:01.443  4065  4077 D BluetoothAdapterProperties: ScanMode =  20
08-03 19:14:01.443  4065  4077 D BluetoothAdapterProperties: State =  11
08-03 19:14:01.447  4065  4081 D BluetoothAdapterProperties: Scan Mode:21
,08-03 19:14:01.447  4065  4081 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 19:14:01.448  4065  4077 D BluetoothAdapterProperties: Setting state to 12
08-03 19:14:01.448  4065  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 19:14:01.450  4065  4077 I BluetoothAdapterState: Entering OnState
,08-03 19:14:01.450  3782  3793 D BluetoothPan: onBluetoothStateChange on: true
,08-03 19:14:01.450  4065  4065 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 19:14:01.451  4065  4065 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-03 19:14:01.453  4065  4065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:14:01.455  1354  2074 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:14:01.455  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 19:14:01.457  4065  4065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 19:14:01.457  1354  1368 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 19:14:01.459  3782  3794 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 19:14:01.459  4065  4065 D ObexServerSockets: Succeed to create listening sockets 
08-03 19:14:01.460  4065  4065 D ObexServerSockets0: startAccept()
08-03 19:14:01.460  4065  4065 D ObexServerSockets0: prepareForNewConnect()
08-03 19:14:01.461  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 19:14:01.461  3782  3793 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 19:14:01.463   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 19:14:01.463  1354  1390 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:14:01.464   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:14:01.464  1354  3725 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 19:14:01.464  4065  4065 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-03 19:14:01.464  4065  4065 D BluetoothSdpJni: SDP Create record success - handle: 0
08-03 19:14:01.465  4065  4101 D ObexServerSockets0: Accepting socket connection...
08-03 19:14:01.466  4065  4102 D ObexServerSockets0: Accepting socket connection...
08-03 19:14:01.466  1354  1354 D BluetoothA2dp: Proxy object connected
,08-03 19:14:01.466   872   872 D BluetoothA2dp: Proxy object connected
,08-03 19:14:01.466  3782  3793 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:14:01.468  3782  3794 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 19:14:01.470   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:14:01.470   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 19:14:01.470  1354  1354 D BluetoothInputDevice: Proxy object connected
08-03 19:14:01.470  1354  1354 D HidProfile: Bluetooth service connected
08-03 19:14:01.470  1720  1912 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 19:14:01.471  1354  3725 D BluetoothMap: onBluetoothStateChange: up=true
08-03 19:14:01.472  1354  1354 D BluetoothMap: Proxy object connected
,08-03 19:14:01.473  1354  1354 D MapProfile: Bluetooth service connected
08-03 19:14:01.473  1354  1354 D BluetoothMap: getConnectedDevices()
08-03 19:14:01.473  3782  3793 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 19:14:01.476  3782  3782 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 19:14:01.476  3782  3782 D PanProfile: Bluetooth service connected
,08-03 19:14:01.476  1354  1390 D BluetoothPan: onBluetoothStateChange on: true
,08-03 19:14:01.476  3782  3782 D BluetoothInputDevice: Proxy object connected
08-03 19:14:01.476  3782  3782 D HidProfile: Bluetooth service connected
,08-03 19:14:01.478  3782  3782 D BluetoothMap: Proxy object connected
08-03 19:14:01.478  3782  3782 D MapProfile: Bluetooth service connected
08-03 19:14:01.478  3782  3782 D BluetoothMap: getConnectedDevices()
,08-03 19:14:01.478  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 19:14:01.478  1354  1354 D PanProfile: Bluetooth service connected
,08-03 19:14:01.480   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-03 19:14:01.481  4065  4065 D BluetoothMapService: onReceive
08-03 19:14:01.481  4065  4065 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 19:14:01.481  4065  4065 D BluetoothMapService: STATE_ON
08-03 19:14:01.481  3782  3782 D BluetoothA2dp: Proxy object connected
08-03 19:14:01.485  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:01.489  3782  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 19:14:01.496  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 19:14:01.501  3782  3782 D DockEventReceiver: finishStartingService: stopping service
,08-03 19:14:01.509  3782  3782 D BluetoothPbap: Proxy object connected
,08-03 19:14:01.509  3782  3782 D PbapServerProfile: Bluetooth service connected
,08-03 19:14:01.512  1354  1354 D BluetoothPbap: Proxy object connected
,08-03 19:14:01.513  1354  1354 D PbapServerProfile: Bluetooth service connected
08-03 19:14:01.515  4065  4065 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 19:14:01.515  4065  4065 D ObexServerSockets0: prepareForNewConnect()
,08-03 19:14:01.520  4065  4109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:14:01.540  4065  4113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 19:14:01.542  4065  4113 I BtOppRfcommListener: Accept thread started.
,08-03 19:14:01.567  3782  3794 D BluetoothHeadset: Proxy object connected
,08-03 19:14:01.567  3782  3782 D HeadsetProfile: Bluetooth service connected
,08-03 19:14:01.567   872   872 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.568  1354  1390 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.568  1354  1354 D HeadsetProfile: Bluetooth service connected
08-03 19:14:01.568   872   872 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.569  3782  4103 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.569  1720  1732 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.569   872   872 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.570  3782  3782 D HeadsetProfile: Bluetooth service connected
08-03 19:14:01.570   872   889 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.570   872   889 D BluetoothHeadset: Proxy object connected
08-03 19:14:01.571  1720  2085 D BluetoothHeadset: Proxy object connected
,08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:14:01.886  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:14:01.894  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:14:01.899  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:14:01.899  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5176f0b added. We now have 8 listener(s)
,08-03 19:14:01.899  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:14:01.905   872  1806 D WifiService: setWifiEnabled: false pid=3726, uid=10000
,08-03 19:14:01.906   872  1806 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:14:01.917  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:14:01.918   872  1807 D WifiService: setWifiEnabled: true pid=3726, uid=10000
,08-03 19:14:01.918   872  1807 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 19:14:01.930   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:14:01.946  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:14:01.951   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-03 19:14:01.952   872  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
,08-03 19:14:01.952   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 19:14:01.953   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 19:14:01.954  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:14:01.954   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 19:14:01.955   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-03 19:14:01.956   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-03 19:14:01.956   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 19:14:01.971   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 19:14:01.971   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device),
08-03 19:14:01.974   371   870 D CommandListener: Setting iface cfg
,08-03 19:14:02.022   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-03 19:14:02.022   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 19:14:02.028   872  1306 E native  : do suspend true
,08-03 19:14:02.044   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 19:14:02.045   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 19:14:02.056   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 19:14:02.940  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 19:14:02.947  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 19:14:02.959  3726  4120 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-03 19:14:02.960  3726  4120 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 19:14:03.466   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 19:14:03.613   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.56 rxSuccessRate=13.38 delta 1000 -> 994
,08-03 19:14:03.616   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-03 19:14:03.616   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 19:14:03.630   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 19:14:03.681   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 19:14:03.685  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 19:14:04.112  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 19:14:04.152  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 19:14:04.153  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 19:14:04.158   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 19:14:04.172   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 19:14:04.172   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 19:14:04.172   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 19:14:04.196   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 19:14:04.208   371   870 D CommandListener: Setting iface cfg
,08-03 19:14:04.209   872  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-03 19:14:04.221   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 19:14:04.258   872  4123 D DhcpClient: Receive thread started
,08-03 19:14:04.345   872  1306 E native  : do suspend false
,08-03 19:14:04.365   872  2014 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 19:14:04.379   872  4123 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-03 19:14:04.380   872  2014 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-03 19:14:04.384   872  2014 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 19:14:04.397   872  4123 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 19:14:04.398   872  2014 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 19:14:04.403   371   870 D CommandListener: Setting iface cfg
,08-03 19:14:04.417   872  2014 D DhcpClient: Scheduling renewal in 86399s
,08-03 19:14:04.417   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-03 19:14:04.420   872  1306 E native  : do suspend true
,08-03 19:14:04.443   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 19:14:04.447   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-03 19:14:04.448   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 19:14:04.453   872  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-03 19:14:04.460   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 19:14:04.525   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 19:14:04.525   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-03 19:14:04.528   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102,
,08-03 19:14:04.531   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-03 19:14:04.538   872  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-03 19:14:04.547   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-03 19:14:04.552   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-03 19:14:04.552   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-03 19:14:04.552   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-03 19:14:04.552   872  1308 D ConnectivityService:    accepting network in place of null
08-03 19:14:04.552   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-03 19:14:04.553   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 19:14:04.554   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 19:14:04.560   872  4122 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423036, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 19:14:04.581   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 19:14:04.612   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 19:14:04.617   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-03 19:14:04.618   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:14:04.625   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-03 19:14:04.625   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-03 19:14:04.638   872  4121 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:14:04.640  3726  3726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:14:04.642  3726  3726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:14:04.650  1817  1817 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-03 19:14:04.654  1853  1853 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 19:14:04.665  1853  1853 D SystemUpdateService: onCreate
,08-03 19:14:04.669  1853  1853 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 19:14:04.693  1853  4134 I SystemUpdateService: active receiver: enabled
,08-03 19:14:04.695  1853  1853 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 19:14:04.710  1853  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 19:14:04.711  1853  2329 I iu.UploadsManager: num queued entries: 0
,08-03 19:14:04.711  1853  2329 I iu.UploadsManager: num updated entries: 0
,08-03 19:14:04.712  1853  2329 I iu.SyncManager: NEXT; no task
,08-03 19:14:04.714  1853  1853 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-03 19:14:04.715  1853  1853 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 19:14:04.718  3835  3835 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 19:14:04.727  1853  4136 I MDM     : [214] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-03 19:14:04.727  1853  4136 W BaseAppContext: Using Auth Proxy for data requests.
,08-03 19:14:04.728  1853  4136 V GoogleAuthProtoRequest: [214] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 19:14:04.734  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 19:14:04.737  3835  3835 D SprintDMHelper: simOperator: 
,08-03 19:14:04.738  3835  3835 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-03 19:14:04.739  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 19:14:04.744   872  4121 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 17:14:04 GMT], X-Android-Received-Millis=[1470244444743], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470244444698]}
,08-03 19:14:04.748   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 19:14:04.749   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-03 19:14:04.749   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-03 19:14:04.756   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 19:14:04.765  1853  4134 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-03 19:14:04.765  1853  4134 I SystemUpdateService: now status is 0 (complete)
08-03 19:14:04.770  1853  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 19:14:04.770  1853  4134 I SystemUpdateService: file has been verified
08-03 19:14:04.770  1853  4134 I SystemUpdateService: OTA package size = 12249756
,08-03 19:14:04.803  1853  4134 I SystemUpdateService: showing system update notification
,08-03 19:14:04.829  1853  1853 D SystemUpdateService: onDestroy
,08-03 19:14:04.834  1517  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 19:14:04.834  1517  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-03 19:14:04.834  1517  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 19:14:04.834  1517  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 19:14:04.859  1853  4136 E MDM     : [214] SitrepService.a: Error sending sitrep.
,08-03 19:14:04.907  2362  4140 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 19:14:05.967  3726  4146 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-03 19:14:05.968  3726  4120 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-03 19:14:05.969  3726  4120 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:14:05.969  3726  4146 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:14:05.971  3726  4120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:14:05.972  3726  4146 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:14:05.973  3726  4120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 19:14:05.975  3726  4120 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-03 19:14:05.976  3726  4146 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:14:05.977  3726  4148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: OutgoingSocketThread/Sender)
,08-03 19:14:05.978  3726  4149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Receiver)
,08-03 19:14:05.979  3726  4146 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-03 19:14:05.981  3726  4149 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: OutgoingSocketThread/Receiver)
,08-03 19:14:05.982  3726  4149 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 19:14:05.982  3726  4149 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 19:14:05.984  3726  4150 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Sender)
,08-03 19:14:05.987  3726  4151 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: IncomingSocketThread/Receiver)
,08-03 19:14:05.989  3726  4151 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: IncomingSocketThread/Receiver)
,08-03 19:14:05.989  3726  4151 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 19:14:05.990  3726  4151 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 19:14:08.966  3726  3772 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-03 19:14:08.968  3726  3772 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-03 19:14:08.974  3726  3772 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fda23 Bundle[{}]
,08-03 19:14:08.975  3726  3772 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 19:14:08.975  3726  3772 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-03 19:14:08.976  3726  3772 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-03 19:14:08.976  3726  3772 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-03 19:14:08.977  3726  3772 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 19:14:08.978  3726  3772 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-03 19:14:08.982  3726  3772 I System.out: Running OutgoingSocketThread
,08-03 19:14:08.986  3726  4153 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-03 19:14:08.987  3726  4153 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 19:14:11.994  3726  4154 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-03 19:14:11.995  3726  4154 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:14:11.995  3726  4154 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:14:11.996  3726  4153 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-03 19:14:11.996  3726  4153 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 19:14:11.996  3726  4153 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 19:14:11.996  3726  4154 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 19:14:11.999  3726  4156 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: IncomingSocketThread/Sender)
08-03 19:14:12.000  3726  4154 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-03 19:14:12.002  3726  4153 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 19:14:12.006  3726  4153 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 19:14:12.007  3726  4157 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Receiver)
08-03 19:14:12.007  3726  4157 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: IncomingSocketThread/Receiver)
08-03 19:14:12.007  3726  4157 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-03 19:14:12.007  3726  4157 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 19:14:12.009  3726  4159 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Receiver)
08-03 19:14:12.010  3726  4158 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: OutgoingSocketThread/Sender)
,08-03 19:14:12.011  3726  4159 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: OutgoingSocketThread/Receiver)
08-03 19:14:12.011  3726  4159 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-03 19:14:12.012  3726  4159 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 19:14:12.560   872  1308 D ConnectivityService: handlePromptUnvalidated 102
,08-03 19:14:14.997  3726  3772 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 447)
,08-03 19:14:15.000  3726  3772 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-03 19:14:15.000  3726  3772 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448)
,08-03 19:14:15.007  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 19:14:15.007  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c51d1e8 added. We now have 2 listener(s)
08-03 19:14:15.009  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 19:14:15.009  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:14:15.009  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:14:15.009  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.009  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b4001 added. We now have 9 listener(s)
,08-03 19:14:15.009  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.010  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 19:14:15.014  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:14:15.027  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:14:15.031  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:14:15.032  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:14:15.032  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 19:14:15.032  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14bf0e7 added. We now have 3 listener(s)
08-03 19:14:15.034  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 19:14:15.034  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:14:15.034  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:14:15.034  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.034  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a662494 added. We now have 10 listener(s)
08-03 19:14:15.034  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:14:15.035  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:14:15.035  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:14:15.035  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:14:15.035  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 19:14:15.035  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.035  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 19:14:15.035  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:14:15.035  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c51d1e8 removed from the list
08-03 19:14:15.035  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.035  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b4001 removed from the list
,08-03 19:14:15.037  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:15.040  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:15.040  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:14:15.040  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.041  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:14:15.041  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.043  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.043  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:14:15.043  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.043  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b4001 not in the list
08-03 19:14:15.043  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.043  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:14:15.045  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:14:15.045  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.045  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.045  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a662494 removed from the list
08-03 19:14:15.045  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:14:15.045  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.045  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:14:15.045  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:14:15.046  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14bf0e7 removed from the list
08-03 19:14:15.046  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.046  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1adb3d added. We now have 2 listener(s)
,08-03 19:14:15.048  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 19:14:15.048  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:14:15.048  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:14:15.049  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.049  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76a1f32 added. We now have 9 listener(s)
08-03 19:14:15.049  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.049  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 19:14:15.053  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:14:15.066  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:14:15.070  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:14:15.071  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:14:15.071  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.072  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6caf600 added. We now have 3 listener(s)
,08-03 19:14:15.073  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:14:15.076  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:14:15.078  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 19:14:15.078  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 19:14:15.078  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:14:15.079  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.079  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5eee39 added. We now have 10 listener(s)
08-03 19:14:15.080  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.080  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 19:14:15.080  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:14:15.081  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:14:15.081  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:14:15.081  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 19:14:15.090  3726  3772 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 19:14:15.090  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 19:14:15.100  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:14:15.102  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 19:14:15.103  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 19:14:15.115  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 19:14:15.115  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 19:14:15.116  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 19:14:15.118  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:14:15.128  4065  4076 D BtGatt.GattService: registerClient() - UUID=51b6279a-9342-4e9e-8dd1-aaf1afcc0f01
,08-03 19:14:15.129  4065  4081 D BtGatt.GattService: onClientRegistered() - UUID=51b6279a-9342-4e9e-8dd1-aaf1afcc0f01, clientIf=5
,08-03 19:14:15.131  3726  3737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 19:14:15.134  4065  4100 D BtGatt.GattService: start scan with filters
,08-03 19:14:15.143  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 19:14:15.144  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 19:14:15.144  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 19:14:15.144  4065  4084 D BtGatt.ScanManager: handling starting scan,
08-03 19:14:15.144  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 19:14:15.149  4065  4084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e99fc87
,08-03 19:14:15.158  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:14:15.159  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 19:14:15.159  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:14:15.168  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 19:14:15.168  4065  4081 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 19:14:15.168  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.170  4065  4084 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 19:14:15.178  3726  3772 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 19:14:15.178  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 19:14:15.178  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 19:14:15.178  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.178  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 19:14:15.178  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 19:14:15.179  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:14:15.179  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 19:14:15.179  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 19:14:15.179  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 19:14:15.179  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 19:14:15.180  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:14:15.182  4065  4076 D BtGatt.GattService: stopScan() - queue size =1
,08-03 19:14:15.182  4065  4100 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 19:14:15.183  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:14:15.183  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 19:14:15.184  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 19:14:15.184  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-03 19:14:15.184  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 19:14:15.185  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 19:14:15.185  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-03 19:14:15.185  4065  4081 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 19:14:15.185  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 19:14:15.185  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.185  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 19:14:15.186  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:14:15.186  4065  4084 D BtGatt.ScanManager: Starting BLE batch scan
08-03 19:14:15.187  4065  4084 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 19:14:15.187  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:14:15.187  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:14:15.187  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 19:14:15.193  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:14:15.193  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:14:15.193  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:14:15.194  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:14:15.194  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.194  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:14:15.195  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:14:15.195  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1adb3d removed from the list
08-03 19:14:15.195  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.195  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76a1f32 removed from the list,
08-03 19:14:15.196  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:14:15.196  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:14:15.197  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:14:15.198  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:14:15.199  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.199  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:14:15.199  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.200  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76a1f32 not in the list
08-03 19:14:15.200  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.200  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.201  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:14:15.201  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.201  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.201  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5eee39 removed from the list
08-03 19:14:15.201  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:14:15.201  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.201  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.201  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:14:15.202  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6caf600 removed from the list
08-03 19:14:15.202  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.202  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73734f5 added. We now have 2 listener(s)
08-03 19:14:15.205  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 19:14:15.205  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:14:15.205  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 19:14:15.206  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.206  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f22628a added. We now have 9 listener(s)
08-03 19:14:15.206  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.207  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 19:14:15.207  4065  4081 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 19:14:15.207  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.210  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:14:15.217  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:14:15.219  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:14:15.219  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 19:14:15.219  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.220  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7918518 added. We now have 3 listener(s)
08-03 19:14:15.221  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 19:14:15.222  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:14:15.222  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 19:14:15.222  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:14:15.222  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8132b71 added. We now have 10 listener(s)
,08-03 19:14:15.222  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.222  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:14:15.223  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:14:15.224  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 19:14:15.224  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-03 19:14:15.224  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:14:15.224  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:14:15.224  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:15.224  4065  4081 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 19:14:15.224  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.228  3726  3772 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 19:14:15.229  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 19:14:15.231  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 19:14:15.235  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:14:15.235  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 19:14:15.235  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 19:14:15.241  4065  4081 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 19:14:15.241  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.241  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 19:14:15.241  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 19:14:15.241  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 19:14:15.241  4065  4084 D BtGatt.ScanManager: stopping BLe Batch
,08-03 19:14:15.242  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:14:15.245  4065  4076 D BtGatt.GattService: registerClient() - UUID=b6a9be26-bfeb-4d55-a47d-cd7fe5a0c3d6
08-03 19:14:15.246  4065  4081 D BtGatt.GattService: onClientRegistered() - UUID=b6a9be26-bfeb-4d55-a47d-cd7fe5a0c3d6, clientIf=5
,08-03 19:14:15.247  3726  3737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 19:14:15.247  4065  4105 D BtGatt.GattService: start scan with filters
08-03 19:14:15.248  4065  4081 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 19:14:15.249  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.249  4065  4084 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 19:14:15.253  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 19:14:15.254  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 19:14:15.254  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 19:14:15.254  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 19:14:15.258  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:14:15.258  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 19:14:15.258  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 19:14:15.258  4065  4081 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 19:14:15.259  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.259  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 19:14:15.262  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 19:14:15.262  3726  3772 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-03 19:14:15.262  4065  4084 D BtGatt.ScanManager: handling starting scan
08-03 19:14:15.262  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:14:15.263  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:14:15.263  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:14:15.263  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:14:15.263  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.263  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-03 19:14:15.263  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:14:15.263  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73734f5 removed from the list
08-03 19:14:15.263  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.263  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f22628a removed from the list
08-03 19:14:15.263  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
08-03 19:14:15.263  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 19:14:15.264  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.264  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-03 19:14:15.264  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.264  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:14:15.265  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.265  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:14:15.265  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.265  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f22628a not in the list
08-03 19:14:15.265  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:14:15.265  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 19:14:15.265  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-03 19:14:15.266  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 19:14:15.266  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 19:14:15.267  3726  3772 D BluetoothAdapter: STATE_ON
08-03 19:14:15.268  4065  4105 D BtGatt.GattService: stopScan() - queue size =1
,08-03 19:14:15.270  4065  4104 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 19:14:15.271  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 19:14:15.271  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 19:14:15.271  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-03 19:14:15.272  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 19:14:15.272  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 19:14:15.274  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 19:14:15.275  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 19:14:15.275  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 19:14:15.275  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:14:15.275  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.275  4065  4081 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 19:14:15.276  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.276  4065  4084 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 19:14:15.278  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:14:15.278  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.278  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:14:15.279  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:14:15.279  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8132b71 removed from the list
,08-03 19:14:15.279  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:14:15.279  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 19:14:15.279  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.279  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 19:14:15.279  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.280  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:14:15.280  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7918518 removed from the list
,08-03 19:14:15.282  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.284  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4de0dad added. We now have 2 listener(s)
,08-03 19:14:15.284  4065  4081 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 19:14:15.284  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:14:15.287  4065  4084 D BtGatt.ScanManager: Starting BLE batch scan
08-03 19:14:15.287  4065  4084 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 19:14:15.287  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 19:14:15.287  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 19:14:15.287  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:14:15.287  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.287  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b84b8e2 added. We now have 9 listener(s)
08-03 19:14:15.288  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 19:14:15.295  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 19:14:15.298  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:14:15.307  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 19:14:15.314  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 19:14:15.314  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:14:15.315  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.315  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@787df30 added. We now have 3 listener(s)
08-03 19:14:15.318  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 19:14:15.319  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 19:14:15.319  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 19:14:15.319  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:15.323  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.324  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fad7a9 added. We now have 10 listener(s)
08-03 19:14:15.324  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.324  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:15.324  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:14:15.324  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-03 19:14:15.324  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 19:14:15.324  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:14:15.324  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 19:14:15.325  4065  4081 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 19:14:15.325  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:14:15.327  3726  3772 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 19:14:15.327  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 19:14:15.331  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 19:14:15.332  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 19:14:15.332  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 19:14:15.339  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 19:14:15.339  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 19:14:15.339  3726  3772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 19:14:15.340  3726  3772 D BluetoothAdapter: STATE_ON
,08-03 19:14:15.343  4065  4076 D BtGatt.GattService: registerClient() - UUID=0f172fc0-5f06-4d8c-af8a-a06e4d65277a
,08-03 19:14:15.343  4065  4081 D BtGatt.GattService: onClientRegistered() - UUID=0f172fc0-5f06-4d8c-af8a-a06e4d65277a, clientIf=5
08-03 19:14:15.344  3726  3737 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 19:14:15.344  4065  4081 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-03 19:14:15.344  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.344  4065  4105 D BtGatt.GattService: start scan with filters
,08-03 19:14:15.348  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 19:14:15.348  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 19:14:15.348  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-03 19:14:15.348  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 19:14:15.351  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 19:14:15.351  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 19:14:15.351  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 19:14:15.353  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 19:14:15.361  4065  4081 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 19:14:15.361  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:14:15.361  4065  4084 D BtGatt.ScanManager: stopping BLe Batch
,08-03 19:14:15.364  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 19:14:15.364  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:14:15.364  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:14:15.364  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 19:14:15.364  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.364  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 19:14:15.364  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 19:14:15.364  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4de0dad removed from the list
08-03 19:14:15.364  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.364  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b84b8e2 removed from the list
,08-03 19:14:15.365  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop,
,08-03 19:14:15.365  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:14:15.367  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:14:15.367  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 19:14:15.367  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:14:15.367  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 19:14:15.368  4065  4081 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 19:14:15.368  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.368  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:14:15.368  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:14:15.368  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b84b8e2 not in the list
,08-03 19:14:15.368  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 19:14:15.368  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-03 19:14:15.368  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.368  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 19:14:15.368  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-03 19:14:15.368  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-03 19:14:15.368  4065  4084 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 19:14:15.369  3726  3772 D BluetoothAdapter: STATE_ON
08-03 19:14:15.370  4065  4105 D BtGatt.GattService: stopScan() - queue size =0
08-03 19:14:15.370  4065  4076 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 19:14:15.370  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-03 19:14:15.371  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 19:14:15.371  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 19:14:15.371  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 19:14:15.371  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 19:14:15.374  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 19:14:15.374  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 19:14:15.374  3726  3772 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 19:14:15.374  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 19:14:15.374  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.375  4065  4081 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 19:14:15.375  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:14:15.375  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:14:15.375  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.376  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:14:15.376  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 19:14:15.376  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fad7a9 removed from the list
08-03 19:14:15.376  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 19:14:15.376  3726  3726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 19:14:15.376  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:14:15.376  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:14:15.376  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 19:14:15.376  3726  3726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 19:14:15.376  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@787df30 removed from the list
,08-03 19:14:15.377  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.377  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d004565 added. We now have 2 listener(s)
08-03 19:14:15.377  4065  4084 D BtGatt.ScanManager: handling starting scan
,08-03 19:14:15.379  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 19:14:15.379  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 19:14:15.379  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 19:14:15.379  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 19:14:15.379  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f60823a added. We now have 9 listener(s)
08-03 19:14:15.379  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.379  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 19:14:15.382  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 19:14:15.383  4065  4081 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 19:14:15.384  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.384  4065  4084 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 19:14:15.386  3726  3772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 19:14:15.387  3726  3772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 19:14:15.388  3726  3772 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 19:14:15.388  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 19:14:15.389  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7c6448 added. We now have 3 listener(s)
,08-03 19:14:15.389  4065  4081 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 19:14:15.389  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.390  4065  4084 D BtGatt.ScanManager: Starting BLE batch scan
08-03 19:14:15.390  4065  4084 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 19:14:15.391   872   881 I art     : Background partial concurrent mark sweep GC freed 45345(2MB) AllocSpace objects, 7(184KB) LOS objects, 33% free, 29MB/43MB, paused 2.191ms total 105.816ms
08-03 19:14:15.392  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 19:14:15.392  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-03 19:14:15.392  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 19:14:15.392  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 19:14:15.393  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c34d2e1 added. We now have 10 listener(s)
,08-03 19:14:15.393  3726  3772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 19:14:15.393  3726  3772 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 19:14:15.393  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 19:14:15.393  3726  3772 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 19:14:15.393  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:14:15.393  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 19:14:15.393  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 19:14:15.393  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 19:14:15.393  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:15.393  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d004565 removed from the list
08-03 19:14:15.393  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:14:15.393  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f60823a removed from the list
08-03 19:14:15.395  3726  3726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 19:14:15.396  3726  3772 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 19:14:15.396  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.396  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.396  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 19:14:15.397  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.397  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 19:14:15.397  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 19:14:15.397  3726  3772 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f60823a not in the list
08-03 19:14:15.397  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.397  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.398  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 19:14:15.398  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 19:14:15.398  3726  3772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 19:14:15.398  3726  3772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c34d2e1 removed from the list
08-03 19:14:15.398  3726  3772 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 19:14:15.399  3726  3772 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 19:14:15.399  3726  3772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 19:14:15.399  4065  4081 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 19:14:15.399  3726  3772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 19:14:15.399  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.399  3726  3772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7c6448 removed from the list
08-03 19:14:15.399  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 19:14:15.399  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 19:14:15.400  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 19:14:15.400  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:14:15.400  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-03 19:14:15.400  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 19:14:15.404  4065  4081 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 19:14:15.405  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.405  3726  4160 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
,08-03 19:14:15.411  4065  4081 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 19:14:15.411  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.412  4065  4084 D BtGatt.ScanManager: stopping BLe Batch
,08-03 19:14:15.418  4065  4081 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 19:14:15.418  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 19:14:15.418  4065  4084 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 19:14:15.423  4065  4081 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 19:14:15.423  4065  4081 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 19:14:15.689  3726  3726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 19:14:15.780  3726  3726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 19:14:15.876  3726  3726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 19:14:17.405  3726  3772 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 456
,08-03 19:14:17.405  3726  3772 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 456, name: My test thread name)
,08-03 19:14:17.411  3726  4161 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: My test thread name)
,08-03 19:14:17.412  3726  4161 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 457, thread name: My test thread name)
08-03 19:14:17.412  3726  4161 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-03 19:14:17.416  3726  4160 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-03 19:14:17.418  3726  3772 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 19:14:17.427  3726  4162 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,08-03 19:14:17.428  3726  4162 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 461, thread name: My test thread name): Test exception.
,08-03 19:14:17.429  3726  4162 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-03 19:14:17.432  3726  3772 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
,08-03 19:14:17.432  3726  3772 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
,08-03 19:14:17.433  3726  3772 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-03 19:14:17.433  3726  3772 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-03 19:14:17.434  3726  3772 D com.test.thalitest.ThaliTestRunner: Total duration: 36141 ms
08-03 19:14:17.441  3726  3772 I jxcore-log: Total number of executed tests:  82
08-03 19:14:17.441  3726  3772 I jxcore-log: 
,08-03 19:14:17.444  3726  3772 I jxcore-log: Number of passed tests:  82
08-03 19:14:17.444  3726  3772 I jxcore-log: 
08-03 19:14:17.445  3726  3772 I jxcore-log: Number of failed tests:  0
08-03 19:14:17.445  3726  3772 I jxcore-log: 
,08-03 19:14:17.445  3726  3772 I jxcore-log: Number of ignored tests:  0
08-03 19:14:17.445  3726  3772 I jxcore-log: 
08-03 19:14:17.446  3726  3772 I jxcore-log: Total duration:  36141
08-03 19:14:17.446  3726  3772 I jxcore-log: 
,08-03 19:14:17.453  3726  3772 I jxcore-log: Unit Test app is loaded
08-03 19:14:17.453  3726  3772 I jxcore-log: 
,08-03 19:14:17.460  1517  1943 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-03 19:14:17.466  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.466  3726  3772 I jxcore-log: 
,08-03 19:14:17.471  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.471  3726  3772 I jxcore-log: 
,08-03 19:14:17.472  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.472  3726  3772 I jxcore-log: 
,08-03 19:14:17.474  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.474  3726  3772 I jxcore-log: 
,08-03 19:14:17.476  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.476  3726  3772 I jxcore-log: 
,08-03 19:14:17.478  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.478  3726  3772 I jxcore-log: 
,08-03 19:14:17.481  3726  3726 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-03 19:14:17.482  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.482  3726  3772 I jxcore-log: 
,08-03 19:14:17.485  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.485  3726  3772 I jxcore-log: 
,08-03 19:14:17.486  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.486  3726  3772 I jxcore-log: 
,08-03 19:14:17.487  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.487  3726  3772 I jxcore-log: 
,08-03 19:14:17.489  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.489  3726  3772 I jxcore-log: 
,08-03 19:14:17.491  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 19:14:17.491  3726  3772 I jxcore-log: 
,08-03 19:14:17.493  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.493  3726  3772 I jxcore-log: 
,08-03 19:14:17.494  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.494  3726  3772 I jxcore-log: 
,08-03 19:14:17.495  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.495  3726  3772 I jxcore-log: 
,08-03 19:14:17.496  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.496  3726  3772 I jxcore-log: 
,08-03 19:14:17.497  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.497  3726  3772 I jxcore-log: 
,08-03 19:14:17.499  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.499  3726  3772 I jxcore-log: 
,08-03 19:14:17.500  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.500  3726  3772 I jxcore-log: 
,08-03 19:14:17.501  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.501  3726  3772 I jxcore-log: 
,08-03 19:14:17.503  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.503  3726  3772 I jxcore-log: 
,08-03 19:14:17.505  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.505  3726  3772 I jxcore-log: 
,08-03 19:14:17.505  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.505  3726  3772 I jxcore-log: 
08-03 19:14:17.506  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.506  3726  3772 I jxcore-log: 
08-03 19:14:17.506  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.506  3726  3772 I jxcore-log: 
,08-03 19:14:17.507  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 19:14:17.507  3726  3772 I jxcore-log: 
,08-03 19:14:17.507  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.507  3726  3772 I jxcore-log: 
08-03 19:14:17.508  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 19:14:17.508  3726  3772 I jxcore-log: 
,08-03 19:14:17.508  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.508  3726  3772 I jxcore-log: 
08-03 19:14:17.509  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.509  3726  3772 I jxcore-log: 
,08-03 19:14:17.509  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.509  3726  3772 I jxcore-log: 
,08-03 19:14:17.510  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.510  3726  3772 I jxcore-log: 
,08-03 19:14:17.510  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.510  3726  3772 I jxcore-log: 
08-03 19:14:17.511  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 19:14:17.511  3726  3772 I jxcore-log: 
,08-03 19:14:17.511  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 19:14:17.511  3726  3772 I jxcore-log: 
08-03 19:14:17.512  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 19:14:17.512  3726  3772 I jxcore-log: 
,08-03 19:14:17.512  3726  3772 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 19:14:17.512  3726  3772 I jxcore-log: 
08-03 19:14:17.515  3726  3772 I jxcore-log: My device name is: motorola-Nexus 6
08-03 19:14:17.515  3726  3772 I jxcore-log: 
08-03 19:14:17.516  3726  3772 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 19:14:17.516  3726  3772 I jxcore-log: 
,08-03 19:14:19.768  3726  3772 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 19:14:19.768  3726  3772 I jxcore-log: 
,08-03 19:14:20.403  3726  3772 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 19:14:20.403  3726  3772 I jxcore-log: 
,08-03 19:14:20.428  3726  3772 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 19:14:20.428  3726  3772 I jxcore-log: 
,08-03 19:14:21.818  3726  3772 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 19:14:21.818  3726  3772 I jxcore-log: 
,08-03 19:14:22.050  3726  3772 I jxcore-log: ERROR runTests: 
08-03 19:14:22.050  3726  3772 I jxcore-log: 
,08-03 19:14:22.052  3726  3772 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-03 19:14:22.052  3726  3772 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-03 19:14:22.053  3726  3772 I jxcore-log: WARN testUtils: logCallback not set!
08-03 19:14:22.053  3726  3772 I jxcore-log: 
,08-03 19:14:22.066  3726  3772 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _functionName: 'loadFile',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _lineNumber: '26',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _columnNumber: '11',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-03 19:14:22.066  3726  3772 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _functionName: '',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _lineNumber: '39',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _columnNumber: '7',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-03 19:14:22.066  3726  3772 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _functionName: '',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _lineNumber: '35',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _columnNumber: '3',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-03 19:14:22.066  3726  3772 I jxcore-log:   { _fileName: 'module.js',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _functionName: '$w.prototype._compile',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _lineNumber: '621',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _columnNumber: '8',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-03 19:14:22.066  3726  3772 I jxcore-log:   { _fileName: 'module.js',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _lineNumber: '651',
08-03 19:14:22.066  3726  3772 I jxcore-log:     _columnNumber: '1',
08-03 19:14:22.066  3726  3772 I jxcore-log:    
,08-03 19:14:22.066  3726  3772 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-03 19:14:22.066  3726  3772 I jxcore-log: 
,08-03 19:14:22.066  3726  3772 E jxcore-log: Error: 
08-03 19:14:22.067  3726  3772 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-03 19:14:22.067  3726  3772 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-03 19:14:22.067  3726  3772 E jxcore-log: 
08-03 19:14:22.068  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 19:14:22.068  3726  3772 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-03 19:14:22.068  3726  3772 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 19:14:22.068  3726  3772 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-03 19:14:22.733  4163  4163 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-03 19:14:22.750  4163  4163 D AndroidRuntime: CheckJNI is OFF
,08-03 19:14:22.805  4163  4163 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-03 19:14:22.850  4163  4163 I Radio-JNI: register_android_hardware_Radio DONE
,08-03 19:14:22.872  4163  4163 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 19:14:22.884   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-03 19:14:22.885   872   885 I ActivityManager: Killing 3726:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-03 19:14:23.010   872  1733 D GraphicsStats: Buffer count: 2
,08-03 19:14:23.010   872  1803 I WindowState: WIN DEATH: Window{5b6d6bb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 19:14:23.014   872  1307 D WifiService: Client connection lost with reason: 4
,08-03 19:14:23.028   872   895 W PackageSettings: Skipping PackageSetting{2b84458 com.example.hello/10273} due to missing metadata
,08-03 19:14:23.034  1658  1752 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-03 19:14:23.036  1658  1752 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-03 19:14:23.069   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-03 19:14:23.069   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-03 19:14:23.070   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-03 19:14:23.070   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-03 19:14:23.070   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.070   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.070   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 19:14:23.070   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-03 19:14:23.070   872   885 I ActivityManager:   Force finishing activity ActivityRecord{ae47924 u0 com.test.thalitest/.MainActivity t2}
,08-03 19:14:23.073   872   895 I art     : Starting a blocking GC Explicit
,08-03 19:14:23.079   872  1734 W ActivityManager: Spurious death for ProcessRecord{1a3bc9d 0:com.test.thalitest/u0a0}, curProc for 3726: null
,08-03 19:14:23.089  1517  1517 I ConfigService: onCreate
,08-03 19:14:23.127   872   895 I art     : Explicit concurrent mark sweep GC freed 16251(1100KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 804us total 53.100ms
,08-03 19:14:23.148   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-03 19:14:23.150  4163  4163 I art     : System.exit called, status: 0
,08-03 19:14:23.150  4163  4163 I AndroidRuntime: VM exiting with result code 0.
,08-03 19:14:23.156   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-03 19:14:23.168   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-03 19:14:23.172  4065  4065 D BluetoothMapAppObserver: onReceive
08-03 19:14:23.172  4065  4065 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-03 19:14:23.173  1658  1658 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-03 19:14:23.177  1868  2024 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-03 19:14:23.182   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 19:14:23.183  3536  3536 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-03 19:14:23.190  1658  4176 I Keyboard.Facilitator.DecoderInitializer: run()
,08-03 19:14:23.192  1658  4176 I Decoder : createOrResetDecoder
,08-03 19:14:23.223  1720  1720 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-03 19:14:23.224   872  1540 I ActivityManager: Start proc 4179:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-03 19:14:23.247  1658  4176 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-03 19:14:23.250   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-03 19:14:23.273  4179  4179 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-03 19:14:23.291   872  1540 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3726 uid 10000
,08-03 19:14:23.292  1658  1658 I Keyboard.Facilitator: onFinishInput()
,08-03 19:14:23.302  1658  4176 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-03 19:14:23.303  1658  4176 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-03 19:14:23.303  1658  4176 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-03 19:14:23.305  1658  4176 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-03 19:14:23.305  1658  4176 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-03 19:14:23.306  1658  4176 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-03 19:14:23.306  1658  4176 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-03 19:14:23.307  1658  4176 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-03 19:14:23.307  1658  4176 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-03 19:14:23.307  1658  4176 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-03 19:14:23.307  1658  4176 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-03 19:14:23.307  1658  4176 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-03 19:14:23.307  1658  4176 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-03 19:14:23.330  4179  4179 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-03 19:14:23.342  4179  4196 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-03 19:14:23.374   872  1805 I ActivityManager: Start proc 4197:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-03 19:14:23.378  1736  1824 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-03 19:14:23.382   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-03 19:14:23.382   872   884 E PackageManager: Failed to write settings, restoring backup
08-03 19:14:23.382   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-03 19:14:23.382   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
,08-03 19:14:23.382   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-03 19:14:23.382   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-03 19:14:23.382   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-03 19:14:23.382   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.382   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.382   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 19:14:23.387   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-03 19:14:23.387   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 19:14:23.387   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 19:14:23.387   872   885 E DropBoxManagerService: 	... 13 more
08-03 19:14:23.391   872  1807 I ActivityManager: Start proc 4209:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-03 19:14:23.391  1736  1824 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 19:14:23.391  1736  1824 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1736
08-03 19:14:23.391  1736  1824 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.391  1736  1824 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 19:14:23.396   872  1734 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-03 19:14:23.399  1736  1824 I Process : Sending signal. PID: 1736 SIG: 9
08-03 19:14:23.402   872  4219 E DropBoxManagerService: Can't write: system_app_crash
08-03 19:14:23.402   872  4219 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 19:14:23.402   872  4219 E DropBoxManagerService: 	... 5 more
,08-03 19:14:23.421  4197  4197 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-03 19:14:23.428  4179  4194 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.428  4179  4194 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.428  4179  4194 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 19:14:23.448  1517  1517 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-03 19:14:23.449  1517  1517 D AndroidRuntime: Shutting down VM
,08-03 19:14:23.450  1517  1517 E AndroidRuntime: FATAL EXCEPTION: main
08-03 19:14:23.450  1517  1517 E AndroidRuntime: Process: com.google.process.gapps, PID: 1517
08-03 19:14:23.450  1517  1517 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-03 19:14:23.450  1517  1517 E AndroidRuntime: 	... 8 more
,08-03 19:14:23.453   872  4224 E DropBoxManagerService: Can't write: system_app_crash
08-03 19:14:23.453   872  4224 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 19:14:23.453   872  4224 E DropBoxManagerService: 	... 5 more
,08-03 19:14:23.456  1517  1517 I Process : Sending signal. PID: 1517 SIG: 9
,08-03 19:14:23.461   872  1540 D GraphicsStats: Buffer count: 1
,08-03 19:14:23.462   872  1734 I WindowState: WIN DEATH: Window{45e22de u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-03 19:14:23.477   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1736) has died
,08-03 19:14:23.478   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-03 19:14:23.480   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-03 19:14:23.499   872   885 I ActivityManager: Start proc 4227:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-03 19:14:23.518   872  1307 D WifiService: Client connection lost with reason: 4
,08-03 19:14:23.522   872  1718 I ActivityManager: Process com.google.process.gapps (pid 1517) has died
,08-03 19:14:23.522   872  1718 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-03 19:14:23.522   872  1718 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 11000ms
08-03 19:14:23.523   872  1718 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-03 19:14:23.523   872  1718 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,08-03 19:14:23.541   872  1804 I ActivityManager: Start proc 4240:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-03 19:14:23.541  1853  1853 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-03 19:14:23.563  4227  4227 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:14:23.563  4227  4227 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 19:14:23.563  4227  4227 D AndroidRuntime: Shutting down VM
,08-03 19:14:23.574  4227  4227 E AndroidRuntime: FATAL EXCEPTION: main
08-03 19:14:23.574  4227  4227 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4227
08-03 19:14:23.574  4227  4227 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 19:14:23.574  4227  4227 E AndroidRuntime: 	... 10 more
08-03 19:14:23.576   872  1540 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 19:14:23.577   872  4253 E DropBoxManagerService: Can't write: system_app_crash
08-03 19:14:23.577   872  4253 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 19:14:23.577   872  4253 E DropBoxManagerService: 	... 5 more
08-03 19:14:23.579  4227  4227 I Process : Sending signal. PID: 4227 SIG: 9
08-03 19:14:23.580  4240  4240 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-03 19:14:23.585   872  1719 I ActivityManager: Killing 3588:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-03 19:14:23.603  4240  4240 I MultiDex: VM with version 2.1.0 has multidex support
08-03 19:14:23.603  4240  4240 I MultiDex: install
08-03 19:14:23.603  4240  4240 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-03 19:14:23.616  4179  4194 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-03 19:14:23.622  4179  4196 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.622  4179  4196 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 19:14:23.622  4179  4196 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-03 19:14:23.622  4179  4196 E AndroidRuntime: Process: android.process.acore, PID: 4179
08-03 19:14:23.622  4179  4196 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.622  4179  4196 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 19:14:23.623  4179  4194 I Process : Sending signal. PID: 4179 SIG: 9
,08-03 19:14:23.635   872  1718 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4227) has died
,08-03 19:14:23.636   872  1718 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-03 19:14:23.636  4240  4240 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-03 19:14:23.640  1853  1853 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-03 19:14:23.640  1853  1853 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-03 19:14:23.645  4240  4240 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-03 19:14:23.647  4240  4240 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:14:23.647  4240  4240 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:14:23.647  4240  4240 D AndroidRuntime: Shutting down VM
08-03 19:14:23.647   872  4256 E DropBoxManagerService: Can't write: system_app_crash
08-03 19:14:23.647   872  4256 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at lib,core.io.IoBridge.open(IoBridge.java:452)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 19:14:23.647   872  4256 E DropBoxManagerService: 	... 5 more
08-03 19:14:23.648  4240  4240 E AndroidRuntime: FATAL EXCEPTION: main
08-03 19:14:23.648  4240  4240 E AndroidRuntime: Process: com.google.process.gapps, PID: 4240
08-03 19:14:23.648  4240  4240 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 19:14:23.648  4240  4240 E AndroidRuntime: 	... 10 more

```
