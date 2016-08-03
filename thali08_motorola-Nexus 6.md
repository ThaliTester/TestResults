#### Test 79689775cf32321_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-03 20:23:12.571   873  1955 D NetlinkSocketObserver: NeighborEvent{elapsedMs=378024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 20:23:13.398  3725  3725 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 20:23:13.402  3725  3725 D AndroidRuntime: CheckJNI is OFF
08-03 20:23:13.437  3725  3725 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 20:23:13.480  3725  3725 I Radio-JNI: register_android_hardware_Radio DONE
08-03 20:23:13.500  3725  3725 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-03 20:23:13.511   873  1751 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 20:23:13.613   873  1751 I ActivityManager: Start proc 3734:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-03 20:23:13.622  3725  3725 D AndroidRuntime: Shutting down VM
08-03 20:23:13.767  3734  3734 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-03 20:23:13.806  3734  3734 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-03 20:23:13.818  3734  3734 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9266-9271)
08-03 20:23:13.819  3734  3734 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:23:13.841  3734  3734 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b077b2}
08-03 20:23:13.842  3734  3734 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:23:13.843  3734  3734 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 20:23:13.854  3734  3734 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-03 20:23:13.858  3734  3734 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 20:23:13.897  3734  3734 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 20:23:13.913  3734  3734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 20:23:13.914  3734  3734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 20:23:13.914  3734  3734 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 20:23:13.914  3734  3734 I Adreno  : Build Date                       : 10/20/15
08-03 20:23:13.914  3734  3734 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 20:23:13.914  3734  3734 I Adreno  : Local Branch                     : M14
08-03 20:23:13.914  3734  3734 I Adreno  : Remote Branch                    : 
08-03 20:23:13.914  3734  3734 I Adreno  : Remote Branch                    : 
08-03 20:23:13.914  3734  3734 I Adreno  : Reconstruct Branch               : 
,08-03 20:23:14.009   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@176b3bb:true
,08-03 20:23:14.092  3734  3734 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 20:23:14.111  3734  3734 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-03 20:23:14.179  3734  3771 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 20:23:14.180   873   886 W ActivityManager: Activity pause timeout for ActivityRecord{29ddc54 u0 com.test.thalitest/.MainActivity t2}
,08-03 20:23:14.196  3734  3758 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-03 20:23:14.237  3734  3771 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 20:23:14.323   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +642ms (total +752ms)
,08-03 20:23:14.334  1638  1638 I Keyboard.Facilitator: onFinishInput()
,08-03 20:23:14.398  3734  3734 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3734
,08-03 20:23:14.541  3734  3734 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 20:23:14.741  3734  3774 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1679357648
,08-03 20:23:14.748  3734  3774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 20:23:14.748  3734  3774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 20:23:14.748  3734  3774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 20:23:14.748  3734  3774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 20:23:14.748  3734  3774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 20:23:14.748  3734  3774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92b13b1 added. We now have 1 listener(s)
,08-03 20:23:14.753  3734  3774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-03 20:23:14.754  3734  3774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:23:14.755  3734  3774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 20:23:14.755  3734  3774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-03 20:23:14.758  3734  3774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25c1004 added. We now have 1 listener(s)
08-03 20:23:14.758  3734  3774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:23:14.766  3734  3774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:23:14.765   873  1308 D WifiService: New client listening to asynchronous messages
08-03 20:23:14.766  3734  3774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 20:23:14.767  3734  3774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 20:23:14.767  3734  3774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 20:23:14.767  3734  3774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 20:23:14.772  3734  3774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:14.772  3734  3774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-03 20:23:14.784  3734  3774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:14.784  3734  3774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:14.784  3734  3774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 20:23:14.784  3734  3774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:23:14.785  3734  3774 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 20:23:14.786  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:14.789  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:14.833  3734  3734 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 20:23:16.088  3734  3780 W jxcore-log: Initializing JXcore engine
,08-03 20:23:16.088  3734  3780 W jxcore-log: JXcore engine is ready
,08-03 20:23:16.124  3780  3780 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-03 20:23:16.124  3780  3780 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9672]" dev="sockfs" ino=9672 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-03 20:23:16.124  3780  3780 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-03 20:23:16.124  3780  3780 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25881]" dev="sockfs" ino=25881 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-03 20:23:16.139  3734  3780 W jxcore-log: Starting JXcore engine
,08-03 20:23:16.216  3734  3780 W jxcore-log: Platform android
08-03 20:23:16.216  3734  3780 W jxcore-log: 
08-03 20:23:16.217  3734  3780 W jxcore-log: Process ARCH arm
08-03 20:23:16.217  3734  3780 W jxcore-log: 
,08-03 20:23:16.432  3734  3780 I jxcore-log: JXcore Cordova bridge is ready!
08-03 20:23:16.432  3734  3780 I jxcore-log: 
08-03 20:23:16.432  3734  3780 W jxcore-log: JXcore engine is started
,08-03 20:23:16.441  3734  3774 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 20:23:16.448  3734  3734 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,08-03 20:23:25.637   873  1955 D NetlinkSocketObserver: NeighborEvent{elapsedMs=391090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 20:23:31.741  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 20:23:31.741  3734  3780 I jxcore-log: 
,08-03 20:23:31.744  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 20:23:31.744  3734  3780 I jxcore-log: 
,08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:31.750  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:23:31.751  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:23:31.754  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 20:23:31.754  3734  3780 I jxcore-log: 
,08-03 20:23:31.756  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 20:23:31.756  3734  3780 I jxcore-log: 
,08-03 20:23:32.088  3734  3780 D ExecuteNativeTests: Running unit tests
,08-03 20:23:32.148  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:23:32.148  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 added. We now have 2 listener(s)
,08-03 20:23:32.149  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:23:32.149  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:23:32.149  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:23:32.149  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-03 20:23:32.149  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 added. We now have 2 listener(s)
08-03 20:23:32.149  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:23:32.150  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-03 20:23:32.152  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:32.162  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:23:32.164  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:23:32.165  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:23:32.167  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-03 20:23:32.167  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 20:23:32.167  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 20:23:32.168  3734  3780 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-03 20:23:32.173  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:32.174  3734  3780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 20:23:32.174  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:23:32.175  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:23:32.175  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 20:23:32.177  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.178  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.178  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.178  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 20:23:32.179  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.179  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.179  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-03 20:23:32.180  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:23:32.181  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 removed from the list
,08-03 20:23:32.181  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.181  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 removed from the list
08-03 20:23:32.181  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.182  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.184  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.184  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:23:32.185  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:23:32.186  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.186  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.186  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
,08-03 20:23:32.192  3734  3780 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-03 20:23:32.194  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 20:23:32.195  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:23:32.195  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.195  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.195  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.196  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.196  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.196  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.196  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list,
08-03 20:23:32.197  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.197  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.197  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.197  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.197  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:23:32.199  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.199  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.199  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.199  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
,08-03 20:23:32.203  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-03 20:23:32.203  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 20:23:32.203  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-03 20:23:32.203  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 20:23:32.203  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 20:23:32.204  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 20:23:32.205  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-03 20:23:32.205  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 20:23:32.205  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 20:23:32.205  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-03 20:23:32.205  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 20:23:32.205  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 20:23:32.205  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.205  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:23:32.205  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.205  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.205  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.205  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:23:32.205  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.205  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.205  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
,08-03 20:23:32.205  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.205  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.205  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.205  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.206  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.207  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:23:32.207  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.207  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.207  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.207  3734  3780 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 20:23:32.209  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:32.212  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:32.214  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.214  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:23:32.214  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:23:32.214  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:23:32.214  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:23:32.214  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.215  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:23:32.220  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.221  3734  3780 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:23:32.221  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 20:23:32.222  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.226  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:23:32.228  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:23:32.228  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 20:23:32.231  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-03 20:23:32.233  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-03 20:23:32.233  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 20:23:32.233  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:23:32.234  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:23:32.236  3734  3780 D BluetoothAdapter: STATE_ON
08-03 20:23:32.242  2544  2557 D BtGatt.GattService: registerClient() - UUID=68a6ca9c-1241-47ab-85f0-fab21d1e7c34
08-03 20:23:32.243  2544  2600 D BtGatt.GattService: onClientRegistered() - UUID=68a6ca9c-1241-47ab-85f0-fab21d1e7c34, clientIf=5
08-03 20:23:32.244  3734  3744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:23:32.244  2544  2556 D BtGatt.GattService: start scan with filters
08-03 20:23:32.247  2544  2630 D BtGatt.ScanManager: handling starting scan
08-03 20:23:32.247  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 20:23:32.248  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:23:32.248  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:23:32.248  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 20:23:32.248  2544  2630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
08-03 20:23:32.251  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:23:32.251  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 20:23:32.251  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:23:32.252  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-03 20:23:32.254  3734  3780 I io.jxcore.node.ConnectionHelper: start: OK
08-03 20:23:32.256  2544  2600 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 20:23:32.257  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.257  2544  2630 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 20:23:32.258  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.258  3734  3780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:23:32.258  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.258  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 20:23:32.258  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.258  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:23:32.258  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:23:32.258  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:23:32.258  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:23:32.258  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:23:32.259  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:23:32.259  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:23:32.259  3734  3780 D BluetoothAdapter: STATE_ON
08-03 20:23:32.260  2544  2556 D BtGatt.GattService: stopScan() - queue size =1
,08-03 20:23:32.262  2544  2756 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:23:32.263  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:23:32.263  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:23:32.263  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:23:32.263  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:23:32.263  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 20:23:32.264  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.265  2544  2600 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 20:23:32.265  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.265  2544  2630 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:23:32.265  2544  2630 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:23:32.265  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 20:23:32.265  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:23:32.266  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:23:32.266  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:23:32.267  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.267  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.268  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.268  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.268  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.268  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:23:32.268  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.268  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.268  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.268  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.268  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.268  3734  3780 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 20:23:32.269  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:32.273  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:32.274  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.274  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:23:32.275  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:23:32.275  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:23:32.275  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:23:32.275  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.275  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:23:32.276  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.278  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.279  2544  2600 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:23:32.279  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.279  3734  3780 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:23:32.279  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 20:23:32.282  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:23:32.282  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:23:32.282  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 20:23:32.284  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 20:23:32.284  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:23:32.284  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:23:32.285  3734  3780 D BluetoothAdapter: STATE_ON
08-03 20:23:32.286  2544  2756 D BtGatt.GattService: registerClient() - UUID=51c8281b-f8a5-4af9-852b-4603c6369934
08-03 20:23:32.285  2544  2600 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:23:32.286  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.287  2544  2600 D BtGatt.GattService: onClientRegistered() - UUID=51c8281b-f8a5-4af9-852b-4603c6369934, clientIf=5
08-03 20:23:32.287  3734  3745 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:23:32.288  2544  2556 D BtGatt.GattService: start scan with filters
08-03 20:23:32.291  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 20:23:32.291  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:23:32.291  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:23:32.291  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 20:23:32.292  2544  2600 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:23:32.292  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.292  2544  2630 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:23:32.293  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:23:32.294  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:23:32.294  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 20:23:32.295  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-03 20:23:32.297  2544  2600 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:23:32.297  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.297  2544  2630 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:23:32.298  3734  3780 I io.jxcore.node.ConnectionHelper: start: OK
08-03 20:23:32.299  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.299  3734  3780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:23:32.300  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.300  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-03 20:23:32.300  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.300  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:23:32.300  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:23:32.300  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:23:32.300  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:23:32.300  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:23:32.300  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:23:32.300  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:23:32.301  3734  3780 D BluetoothAdapter: STATE_ON
08-03 20:23:32.302  2544  2756 D BtGatt.GattService: stopScan() - queue size =0
08-03 20:23:32.302  2544  2556 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:23:32.303  2544  2600 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:23:32.303  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.303  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:23:32.303  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:23:32.303  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:23:32.303  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:23:32.303  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 20:23:32.304  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.304  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 20:23:32.304  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:23:32.305  2544  2630 D BtGatt.ScanManager: handling starting scan
08-03 20:23:32.305  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:23:32.305  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:23:32.306  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.306  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.307  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.307  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.307  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.307  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:23:32.307  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.307  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.307  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.307  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.307  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.308  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.308  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.309  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.309  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.309  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.309  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.310  3734  3780 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 20:23:32.311  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.311  2544  2600 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 20:23:32.311  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.311  2544  2630 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:32.316  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:32.317  2544  2600 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 20:23:32.317  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.318  2544  2630 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:23:32.318  2544  2630 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:23:32.320  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.320  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:23:32.321  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:23:32.322  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:23:32.322  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:23:32.322  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.322  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:23:32.322  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.325  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.326  2544  2600 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:23:32.326  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.327  3734  3780 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:23:32.327  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 20:23:32.331  2544  2600 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:23:32.331  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.333  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:23:32.334  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:23:32.334  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 20:23:32.336  2544  2600 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:23:32.336  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.337  2544  2630 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:23:32.338  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 20:23:32.338  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:23:32.338  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:23:32.339  3734  3780 D BluetoothAdapter: STATE_ON
08-03 20:23:32.340  2544  2557 D BtGatt.GattService: registerClient() - UUID=1b23a1ae-79ec-4ac0-b8ac-9e5257a7c0fc
08-03 20:23:32.341  2544  2600 D BtGatt.GattService: onClientRegistered() - UUID=1b23a1ae-79ec-4ac0-b8ac-9e5257a7c0fc, clientIf=5
08-03 20:23:32.341  3734  3745 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 20:23:32.342  2544  2556 D BtGatt.GattService: start scan with filters
08-03 20:23:32.342  2544  2600 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:23:32.342  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.342  2544  2630 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:23:32.345  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 20:23:32.345  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:23:32.345  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:23:32.345  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 20:23:32.347  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:23:32.347  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:23:32.347  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 20:23:32.348  2544  2600 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:23:32.348  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.348  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-03 20:23:32.349  2544  2630 D BtGatt.ScanManager: handling starting scan
08-03 20:23:32.352  3734  3780 I io.jxcore.node.ConnectionHelper: start: OK
08-03 20:23:32.352  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.352  3734  3780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:23:32.352  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.352  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 20:23:32.352  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.352  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:23:32.352  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:23:32.352  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:23:32.352  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:23:32.352  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:23:32.352  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:23:32.352  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:23:32.353  3734  3780 D BluetoothAdapter: STATE_ON
08-03 20:23:32.353  2544  2556 D BtGatt.GattService: stopScan() - queue size =1
08-03 20:23:32.354  2544  2756 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:23:32.354  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:23:32.354  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:23:32.354  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:23:32.354  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:23:32.354  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 20:23:32.355  2544  2600 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 20:23:32.355  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.355  2544  2630 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 20:23:32.356  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.356  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 20:23:32.356  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:23:32.356  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:23:32.356  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:23:32.357  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.357  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.357  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.358  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.358  3734  3780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:23:32.358  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.358  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.358  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.358  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.358  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:23:32.358  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.358  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.358  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.358  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.358  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.359  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.359  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.360  2544  2600 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 20:23:32.360  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.360  2544  2630 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:23:32.360  2544  2630 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:23:32.360  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.360  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.360  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.360  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.361  3734  3780 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 20:23:32.361  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.361  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.361  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.361  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.361  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.362  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.362  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.362  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.362  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.362  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.362  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.362  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.362  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.362  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.362  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.363  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.363  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.363  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.363  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 20:23:32.363  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.363  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.363  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.364  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.364  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.364  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.364  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.364  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.364  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.364  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.364  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.364  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.364  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.364  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.365  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.365  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.365  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.365  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.365  3734  3780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 20:23:32.365  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.365  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.365  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.366  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 20:23:32.366  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.366  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.366  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.366  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.366  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.366  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.366  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.366  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.366  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.366  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.367  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.367  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.367  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.367  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.367  3734  3780 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 20:23:32.368  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.368  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.368  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.368  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.368  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.368  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.368  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.368  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.368  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.368  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.368  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.368  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.368  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.368  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.369  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.369  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.369  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.369  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.370  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 20:23:32.370  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:23:32.370  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:23:32.370  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:23:32.370  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 20:23:32.370  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:23:32.370  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.370  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.370  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.371  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.371  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.371  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.371  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.371  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.371  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.371  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.371  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.371  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.371  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.371  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.372  2544  2600 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:23:32.372  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.373  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.373  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.373  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.373  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.374  3734  3780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:23:32.374  3734  3780 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 20:23:32.374  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 20:23:32.377  3734  3780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:23:32.377  3734  3780 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 20:23:32.377  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 20:23:32.377  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 20:23:32.377  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 20:23:32.377  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 20:23:32.377  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 20:23:32.377  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 20:23:32.377  2544  2600 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:23:32.377  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 20:23:32.377  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.378  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 20:23:32.379  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 20:23:32.379  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 20:23:32.379  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 20:23:32.379  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 20:23:32.379  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 20:23:32.379  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 20:23:32.380  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 20:23:32.380  3734  3780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 20:23:32.381  3734  3780 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:23:32.381  3734  3780 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 20:23:32.381  3734  3780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:23:32.381  3734  3780 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:23:32.381  3734  3780 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 20:23:32.381  3734  3780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:23:32.381  3734  3780 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:23:32.381  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 20:23:32.384  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 20:23:32.384  2544  2600 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:23:32.384  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.385  2544  2630 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:23:32.385  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 20:23:32.386  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 20:23:32.386  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 20:23:32.386  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 20:23:32.387  3734  3780 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 20:23:32.388  3734  3780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:23:32.388  3734  3780 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 20:23:32.388  3734  3782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-03 20:23:32.388  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.389  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.389  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.389  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.389  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.389  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.389  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 20:23:32.390  2544  2600 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:23:32.390  3734  3782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:23:32.390  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.390  2544  2630 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:23:32.392  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.392  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.392  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.392  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.392  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.392  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.392  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.392  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.393  3734  3783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-03 20:23:32.393  3734  3783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
08-03 20:23:32.393  3734  3782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-03 20:23:32.393  2544  2743 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-03 20:23:32.393  3734  3783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
08-03 20:23:32.394  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.394  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.394  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.394  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.395  3734  3780 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 20:23:32.395  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.396  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.396  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.396  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.396  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.396  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.396  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.396  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.396  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.396  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.396  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.396  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:23:32.396  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.396  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.397  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.397  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.397  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.397  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.397  2544  2600 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:23:32.398  2544  2600 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:23:32.401  3734  3780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 20:23:32.401  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.401  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.401  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.401  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.402  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.402  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.402  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.402  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.402  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.402  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.402  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.402  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.402  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.402  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.403  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.403  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.404  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.404  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.404  3734  3780 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 20:23:32.404  3734  3780 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 20:23:32.404  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:23:32.405  3734  3780 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 20:23:32.405  3734  3780 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 20:23:32.405  3734  3780 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 20:23:32.405  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:23:32.405  3734  3780 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 20:23:32.405  3734  3780 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 20:23:32.405  3734  3780 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 20:23:32.405  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:23:32.405  3734  3780 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 20:23:32.405  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.405  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.405  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.406  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.406  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.406  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.406  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.406  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.406  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.406  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.406  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.406  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.406  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.407  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.408  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.408  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.408  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.408  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.409  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.409  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.409  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.409  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.409  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.409  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.410  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.410  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.410  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.410  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.410  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.410  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.410  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.410  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.410  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.410  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.410  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.410  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.411  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.411  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.411  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.411  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.411  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.411  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.411  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.411  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.411  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.411  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.411  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.413  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.413  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.413  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.413  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.414  3734  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 20:23:32.414  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.415  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 20:23:32.415  3734  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 20:23:32.415  3734  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 20:23:32.416  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 20:23:32.416  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:23:32.416  3734  3734 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 20:23:32.416  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.416  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 20:23:32.416  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 20:23:32.416  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 20:23:32.416  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.416  3734  3780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 20:23:32.416  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.416  3734  3734 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 20:23:32.416  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.417  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:23:32.417  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:23:32.417  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:23:32.417  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.417  3734  3784 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:23:32.417  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.418  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.418  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.418  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.418  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.418  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:23:32.418  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:23:32.418  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.418  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.418  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.418  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.418  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.418  3734  3784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-03 20:23:32.418  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.418  3734  3784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 20:23:32.418  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.418  3734  3784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 20:23:32.418  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.419  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.419  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.419  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.419  3734  3734 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 20:23:32.419  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.419  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.420  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.420  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.420  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.420  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.421  3734  3780 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 20:23:32.421  3734  3780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 20:23:32.421  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:23:32.422  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:23:32.422  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.423  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.423  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.423  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.423  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.423  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.423  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.423  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.423  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.423  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.423  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.423  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.423  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.423  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.425  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.425  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.425  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.425  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.428  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.428  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.428  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.428  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.428  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: Th,e given listener does not exist in the list - probably already removed
08-03 20:23:32.428  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.428  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.428  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.428  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.428  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.429  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.429  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.429  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.429  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.429  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.429  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.430  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.430  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.433  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:23:32.434  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:23:32.434  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:23:32.434  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:23:32.434  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.434  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.434  3734  3780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eee5e56 not in the list
08-03 20:23:32.434  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.434  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.435  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:23:32.435  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.435  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.435  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:23:32.435  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:23:32.436  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:23:32.436  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:23:32.436  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:23:32.436  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c08ed7 not in the list
08-03 20:23:32.437  3734  3780 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 20:23:32.437  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:23:32.437  3734  3780 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 20:23:32.437  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:23:32.438  3734  3780 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 20:23:32.438  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:23:32.440  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 20:23:32.440  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 20:23:32.441  3734  3780 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 20:23:32.441  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 20:23:32.441  3734  3780 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 20:23:32.441  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 20:23:32.441  3734  3780 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 20:23:32.441  3734  3780 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 20:23:32.442  3734  3780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 20:23:32.442  3734  3780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 20:23:32.442  3734  3780 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 20:23:32.442  3734  3780 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 20:23:32.443  3734  3780 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 20:23:32.443  3734  3780 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 20:23:32.444  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:23:32.444  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d6b7e1 added. We now have 2 listener(s)
08-03 20:23:32.444  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:23:32.447  3734  3780 D BluetoothAdapter: enable(): BT is already enabled..!
08-03 20:23:32.447   873  1384 D WifiService: setWifiEnabled: true pid=3734, uid=10000
08-03 20:23:32.447   873  1384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 20:23:32.448  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:23:32.449  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4790906 added. We now have 3 listener(s)
08-03 20:23:32.449  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:23:32.455  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:23:32.455  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ecdbc7 added. We now have 4 listener(s)
08-03 20:23:32.455  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:23:32.462  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:23:32.462  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aba65f4 added. We now have 5 listener(s)
08-03 20:23:32.462  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:23:32.465   873   884 D WifiService: setWifiEnabled: false pid=3734, uid=10000
08-03 20:23:32.465   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 20:23:32.470  2544  2595 D BluetoothAdapterState: Current state: ON, message: 23
08-03 20:23:32.470  2544  2595 D BluetoothAdapterProperties: Setting state to 13
08-03 20:23:32.470  2544  2595 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 20:23:32.470  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:23:32.470  2544  2595 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 20:23:32.471  2544  2595 I BluetoothAdapterState: Entering PendingCommandState
08-03 20:23:32.472  2544  2600 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:23:32.472  2544  2595 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 20:23:32.473  2544  2544 D BluetoothMapService: onReceive
08-03 20:23:32.473  2544  2544 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:23:32.473  2544  2544 D BluetoothMapService: STATE_TURNING_OFF
08-03 20:23:32.473  2544  2544 D BluetoothMapService: MAP Service closeService in
08-03 20:23:32.474  2544  2544 D BluetoothMapMasInstance0: MAP Service shutdown
08-03 20:23:32.474  2544  2544 D ObexServerSockets0: shutdown(block = true)
08-03 20:23:32.474  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.474  2544  2544 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:32.474  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:32.474  2544  2544 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 20:23:32.474  2544  2768 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-03 20:23:32.474  2544  2767 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 20:23:32.475  2544  2743 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-03 20:23:32.475  2544  2544 I BtOppRfcommListener: stopping Accept Thread
08-03 20:23:32.475  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.475  2544  3300 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:23:32.475  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.475  2544  3300 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-03 20:23:32.475  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:23:32.477  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.479  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.481  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:32.481  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:32.482  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.482  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:32.483  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.484   873   886 I ActivityManager: Start proc 3787:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-03 20:23:32.485  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-03 20:23:32.489  2544  2544 D HeadsetService: Received stop request...Stopping profile...
08-03 20:23:32.491   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 20:23:32.491   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 20:23:32.491  1717  1729 D BluetoothHeadset: Proxy object disconnected
,08-03 20:23:32.491  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.492  1354  1371 D BluetoothHeadset: Proxy object disconnected
08-03 20:23:32.492   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 20:23:32.493  2544  2544 D A2dpService: Received stop request...Stopping profile...
,08-03 20:23:32.493  2544  2761 D A2dpStateMachine: Exit Disconnected: -1,
,08-03 20:23:32.493  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 20:23:32.495  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-03 20:23:32.495   873   873 D BluetoothA2dp: Proxy object disconnected
08-03 20:23:32.495  1354  1354 D BluetoothA2dp: Proxy object disconnected
,08-03 20:23:32.495   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 20:23:32.495   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-03 20:23:32.495  2544  2544 D HidService: Received stop request...Stopping profile...
08-03 20:23:32.495   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 20:23:32.495  2544  2544 D HidService: Stopping Bluetooth HidService
08-03 20:23:32.495   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:23:32.496  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-03 20:23:32.496  1354  1354 D HidProfile: Bluetooth service disconnected
08-03 20:23:32.496  2544  2544 D HealthService: Received stop request...Stopping profile...
08-03 20:23:32.498  2544  2544 D PanService: Received stop request...Stopping profile...
08-03 20:23:32.498  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:23:32.499  1354  1354 D PanProfile: Bluetooth service disconnected
,08-03 20:23:32.499  2544  2544 D BluetoothMapService: Received stop request...Stopping profile...
08-03 20:23:32.499  2544  2544 D BluetoothMapService: stop()
08-03 20:23:32.500  2544  2544 D BluetoothMapAppObserver: deinitObservers()
08-03 20:23:32.500  2544  2544 D BluetoothMapAppObserver: removeReceiver()
08-03 20:23:32.500   873  1307 E native  : do suspend true
,08-03 20:23:32.501  1354  1354 D BluetoothMap: Proxy object disconnected
08-03 20:23:32.501  1354  1354 D MapProfile: Bluetooth service disconnected
08-03 20:23:32.501  2544  2544 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:32.501  2544  2544 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:32.501  2544  2544 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:32.501  2544  2544 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:32.502  2544  2544 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 20:23:32.502  2544  2600 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 20:23:32.502  2544  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 20:23:32.502  2544  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:32.503  2544  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:32.503  2544  2600 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-03 20:23:32.503  2544  2544 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:23:32.503  2544  2544 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:32.503  2544  2544 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:32.504  2544  2544 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:32.504  2544  2544 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:32.510  2544  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:32.510  2544  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:32.511   873  1956 D DhcpClient: Clearing IP address
08-03 20:23:32.512  2544  2739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:23:32.512   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-03 20:23:32.512  2544  2739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-03 20:23:32.512  2544  2739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:23:32.512  2544  2739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:23:32.512  2544  2600 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-03 20:23:32.512  2544  2544 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:32.512  2544  2544 V BluetoothAdapterState: isTurningOn()=false
,08-03 20:23:32.512  2544  2544 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:32.512  2544  2544 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:32.513  2544  2544 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 20:23:32.513  2544  2600 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 20:23:32.513  2544  2544 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 20:23:32.516  2544  2544 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:32.516  2544  2544 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:32.516  2544  2544 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:32.516  2544  2544 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:32.516  2544  2544 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 20:23:32.516  2544  2600 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-03 20:23:32.516  2544  2544 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 20:23:32.516   372   870 D CommandListener: Setting iface cfg
08-03 20:23:32.517  2544  2544 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:32.517  2544  2544 V BluetoothAdapterState: isTurningOn()=false
,08-03 20:23:32.517  2544  2544 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:32.517  2544  2544 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:32.517  2544  2544 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 20:23:32.517  2544  2544 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-03 20:23:32.518   873  1957 D DhcpClient: Receive thread stopped
08-03 20:23:32.518  2544  2544 D BluetoothMapService: MAP Service closeService in
08-03 20:23:32.518  2544  2544 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:32.518  2544  2544 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:32.518  2544  2544 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:32.518  2544  2544 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:32.518  2544  2595 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 20:23:32.519  2544  2595 D BluetoothAdapterProperties: Setting state to 15
,08-03 20:23:32.519  2544  2595 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 20:23:32.519  2544  2595 I BluetoothAdapterState: Entering BleOnState
08-03 20:23:32.519  1354  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:23:32.520   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-03 20:23:32.520  1354  1826 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 20:23:32.521   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 20:23:32.521   873  1307 E native  : do suspend true
08-03 20:23:32.521  1717  1949 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 20:23:32.521   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:23:32.521  1354  1371 D BluetoothMap: onBluetoothStateChange: up=false
,08-03 20:23:32.520  2544  2544 D BluetoothMapService: cleanup()
08-03 20:23:32.522  2544  2544 D BluetoothMapService: MAP Service closeService in
08-03 20:23:32.523   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 20:23:32.523   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-03 20:23:32.524  1354  1826 D BluetoothPan: onBluetoothStateChange on: false
08-03 20:23:32.525   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:23:32.525  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:23:32.526   459   459 E Parcel  : Reading a NULL string not supported here.
,08-03 20:23:32.526   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:23:32.526   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:23:32.526  1354  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 20:23:32.527  2544  2595 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-03 20:23:32.527  2544  2595 D BluetoothAdapterProperties: Setting state to 16
08-03 20:23:32.527  2544  2595 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-03 20:23:32.528  2544  2595 D BluetoothAdapterProperties: onBleDisable
08-03 20:23:32.528   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-03 20:23:32.528  2544  2596 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-03 20:23:32.528  2544  2595 I BluetoothAdapterState: Entering PendingCommandState
08-03 20:23:32.529  2544  2739 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-03 20:23:32.529  2544  2739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:32.530  2544  2600 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:23:32.532  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:32.532  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:32.532  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:32.532  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:32.533  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:32.534  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:32.534  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.534  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:32.536  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:32.536  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:32.537  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:32.557   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:32.553  1550  2310 V NativeCrypto: Read error: ssl=0xaa217e00: I/O error during system call, Connection timed out
,08-03 20:23:32.560  1550  2310 V NativeCrypto: SSL shutdown failed: ssl=0xaa217e00: I/O error during system call, Broken pipe
,08-03 20:23:32.575   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:32.575   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 20:23:32.576   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-03 20:23:32.577   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:23:32.578   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-03 20:23:32.578   873   890 D Tethering: MasterInitialState.processMessage what=3
08-03 20:23:32.581  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.582  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:32.583  1796  1796 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-03 20:23:32.584  3248  3248 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@33d8096 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-03 20:23:32.595   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:23:32.597  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:32.597  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:23:32.598  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.598  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:32.598   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-03 20:23:32.599  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:32.599  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:32.600  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:32.600  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:32.603  1961  2132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:23:32.609  3787  3787 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-03 20:23:32.618  3787  3787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:23:32.625  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:23:32.625   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@331fd14:true
,08-03 20:23:32.627   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-03 20:23:32.637   873  1384 I ActivityManager: Start proc 3809:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-03 20:23:32.644  3787  3787 D LocalBluetoothProfileManager: Adding local MAP profile
,08-03 20:23:32.646  3787  3787 D BluetoothMap: Create BluetoothMap proxy object
,08-03 20:23:32.656  3787  3787 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-03 20:23:32.662  3809  3809 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-03 20:23:32.671  3787  3787 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:23:32.681   873  1762 I ActivityManager: Killing 3248:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-03 20:23:32.733  2544  2600 I bt_hci  : shut_down
,08-03 20:23:32.734  2544  2631 D bt_hwcfg: hw_epilog_process
,08-03 20:23:32.735  2544  2631 I bt_vendor: low_power_mode_cb
,08-03 20:23:32.754  2544  2631 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-03 20:23:32.754  2544  2631 I bt_vendor: epilog_cb
08-03 20:23:32.754  2544  2631 I bt_hci  : epilog_finished_callback
,08-03 20:23:32.758  2544  2600 I bt_hci_h4: hal_close
,08-03 20:23:32.758  2544  2600 I bt_userial_vendor: device fd = 51 close
,08-03 20:23:32.840  3809  3809 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 20:23:32.840  3809  3809 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 20:23:32.840  3809  3809 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 20:23:32.840  3809  3809 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:23:32.840  3809  3809 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.k.d(PG:583)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.840  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:23:32.841  3809  3809 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:23:32.841  3809  3809 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:23:32.841  3809  3809 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:23:32.841  3809  3809 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:23:32.847  3787  3787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 20:23:32.859  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:23:32.878  2544  2596 D bt_stack_manager: event_shut_down_stack finished.
08-03 20:23:32.879  2544  2595 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-03 20:23:32.880  3787  3787 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:23:32.882  2544  2595 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-03 20:23:32.882  2544  2544 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 20:23:32.887  2544  2544 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 20:23:32.887  2544  2544 D BtGatt.GattService: stop()
08-03 20:23:32.887  2544  2544 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 20:23:32.895  2544  2544 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:32.895  2544  2544 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:32.895  2544  2544 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:32.895  2544  2544 V BluetoothAdapterState: isBleTurningOff()=true
08-03 20:23:32.896  2544  2595 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-03 20:23:32.896  2544  2595 D BluetoothAdapterProperties: Setting state to 10
08-03 20:23:32.896  2544  2595 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-03 20:23:32.897  2544  2595 I BluetoothAdapterState: Entering OffState
08-03 20:23:32.898   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-03 20:23:32.915  2544  2544 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-03 20:23:32.916  2544  2544 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 20:23:32.916  2544  2596 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-03 20:23:32.916   873  1667 I ActivityManager: Killing 3435:com.google.process.gapps/u0a99 (adj 15): empty #17
08-03 20:23:32.919  3734  3734 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-03 20:23:32.920  2544  2596 D bt_stack_manager: event_clean_up_stack finished.
,08-03 20:23:32.923  2544  2544 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 20:23:32.939  2544  2544 I art     : System.exit called, status: 0
,08-03 20:23:32.939  2544  2544 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 20:23:32.984  2017  2017 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:23:32.989   873  2992 I ActivityManager: Process com.android.bluetooth (pid 2544) has died
,08-03 20:23:32.998  2017  2017 D SystemUpdateService: onCreate
,08-03 20:23:33.002  2017  2017 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 20:23:33.019  2017  3842 I SystemUpdateService: active receiver: enabled
,08-03 20:23:33.034  2017  2017 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-03 20:23:33.035  2017  3842 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 20:23:33.039  2017  2328 I iu.UploadsManager: num queued entries: 0
,08-03 20:23:33.040  2017  2328 I iu.UploadsManager: num updated entries: 0
,08-03 20:23:33.042  2017  3842 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-03 20:23:33.042  2017  3842 I SystemUpdateService: now status is 0 (complete)
08-03 20:23:33.042  2017  3842 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-03 20:23:33.042  2017  3842 I SystemUpdateService: file has been verified
08-03 20:23:33.043  2017  3842 I SystemUpdateService: OTA package size = 12249756
,08-03 20:23:33.050  2017  2328 I iu.SyncManager: NEXT; no task
,08-03 20:23:33.051  2017  3842 I SystemUpdateService: showing system update notification
,08-03 20:23:33.067  2017  2017 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 20:23:33.069  2017  2017 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 20:23:33.093   873   884 I ActivityManager: Start proc 3844:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-03 20:23:33.097  2017  2017 D SystemUpdateService: onDestroy
,08-03 20:23:33.191  3844  3844 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-03 20:23:33.197  3844  3844 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:23:33.217  3844  3844 D SprintDMHelper: simOperator: 
08-03 20:23:33.220  3844  3844 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 20:23:33.230  3809  3832 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-03 20:23:33.250   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44a2b12:true
,08-03 20:23:33.259   873   883 I ActivityManager: Start proc 3858:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-03 20:23:33.366  2353  3872 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-03 20:23:33.371   873  1383 I ActivityManager: Start proc 3873:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-03 20:23:33.374   873  2833 I ActivityManager: Killing 3315:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-03 20:23:33.425  3873  3873 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-03 20:23:33.480  3873  3873 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-03 20:23:33.480  3873  3873 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-03 20:23:33.480  3873  3873 I GAv4    :   adb logcat -s GAv4
,08-03 20:23:33.494  3873  3873 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-03 20:23:33.504  3873  3873 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-03 20:23:33.536  3873  3891 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-03 20:23:33.643  3873  3873 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-03 20:23:33.688  3873  3873 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-03 20:23:33.697  3873  3873 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9148-9151)
,08-03 20:23:33.698  3873  3873 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 20:23:33.712  3873  3873 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f53b46}
,08-03 20:23:33.712  3873  3873 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:23:33.712  3873  3873 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 20:23:33.722  3873  3873 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-03 20:23:33.723  3873  3873 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 20:23:33.740  3873  3873 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 20:23:33.752  3873  3873 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 20:23:33.752  3873  3873 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 20:23:33.752  3873  3873 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 20:23:33.752  3873  3873 I Adreno  : Build Date                       : 10/20/15
08-03 20:23:33.752  3873  3873 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 20:23:33.752  3873  3873 I Adreno  : Local Branch                     : M14
08-03 20:23:33.752  3873  3873 I Adreno  : Remote Branch                    : 
08-03 20:23:33.752  3873  3873 I Adreno  : Remote Branch                    : 
08-03 20:23:33.752  3873  3873 I Adreno  : Reconstruct Branch               : 
,08-03 20:23:33.817  3873  3873 I NSApplication: Starting up...
,08-03 20:23:33.828  3873  3919 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-03 20:23:33.841   873  1673 I ActivityManager: Start proc 3924:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-03 20:23:33.842   873  1673 I ActivityManager: Killing 3365:android.process.acore/u0a5 (adj 15): empty #17
,08-03 20:23:33.951  3924  3924 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-03 20:23:34.127   873  1384 I ActivityManager: Killing 3557:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-03 20:23:34.212   873  1752 I ActivityManager: Start proc 3938:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-03 20:23:34.265  3938  3938 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-03 20:23:34.312  3938  3938 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-03 20:23:34.366   873  1384 I ActivityManager: Killing 3574:com.android.musicfx/u0a18 (adj 15): empty #17
,08-03 20:23:35.478   873  2992 D WifiService: setWifiEnabled: true pid=3734, uid=10000
,08-03 20:23:35.478   873  2992 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:23:35.493   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-03 20:23:35.502  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:35.503  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:35.503  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:35.503  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:35.506  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:35.507  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:35.507  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:35.507  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:35.540   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-03 20:23:35.540   873  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 20:23:35.541   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-03 20:23:35.542   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 20:23:35.543   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 20:23:35.543   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 20:23:35.543   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 20:23:35.543   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 20:23:35.561   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 20:23:35.561   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:23:35.564   372   870 D CommandListener: Setting iface cfg
,08-03 20:23:35.572   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-03 20:23:35.573   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 20:23:35.575   873  1307 E native  : do suspend true
,08-03 20:23:35.590   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 20:23:35.591   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:23:35.591   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 20:23:36.968   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:23:37.040   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.69 rxSuccessRate=14.19 delta 1000 -> 994
,08-03 20:23:37.045   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-03 20:23:37.045   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-03 20:23:37.065   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 20:23:37.148   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 20:23:37.151  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 20:23:37.596  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 20:23:37.633  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 20:23:37.634  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 20:23:37.640   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:23:37.652   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 20:23:37.652   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:23:37.652   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 20:23:37.681   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:23:37.693   372   870 D CommandListener: Setting iface cfg
08-03 20:23:37.696   873  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-03 20:23:37.702   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 20:23:37.735   873  3971 D DhcpClient: Receive thread started
,08-03 20:23:37.817   873  1307 E native  : do suspend false
,08-03 20:23:37.828   873  1956 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 20:23:37.840   873  3971 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172419, domain null
,08-03 20:23:37.841   873  1956 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172419 seconds
,08-03 20:23:37.844   873  1956 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 20:23:37.856   873  3971 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 20:23:37.857   873  1956 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 20:23:37.861   372   870 D CommandListener: Setting iface cfg
,08-03 20:23:37.868   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-03 20:23:37.871   873  1956 D DhcpClient: Scheduling renewal in 86399s
,08-03 20:23:37.871   873  1307 E native  : do suspend true
,08-03 20:23:37.892   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 20:23:37.895   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-03 20:23:37.896   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 20:23:37.900   873  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-03 20:23:37.905   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 20:23:37.969   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 20:23:37.969   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 20:23:37.970   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-03 20:23:37.971   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-03 20:23:37.973   873  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-03 20:23:37.985   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 20:23:37.997   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-03 20:23:37.997   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-03 20:23:37.997   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-03 20:23:37.997   873  1309 D ConnectivityService:    accepting network in place of null
08-03 20:23:37.997   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-03 20:23:37.999   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 20:23:37.999   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 20:23:38.009   873  3970 D NetlinkSocketObserver: NeighborEvent{elapsedMs=403462, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 20:23:38.069   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:38.106   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:38.117   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-03 20:23:38.117   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:23:38.127   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-03 20:23:38.130   873   890 D Tethering: MasterInitialState.processMessage what=3
08-03 20:23:38.153  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:38.153  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:23:38.153  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.153  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:23:38.156  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:38.157  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:23:38.157  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.157  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:23:38.166  1796  1796 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-03 20:23:38.169  2017  2017 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:23:38.172  2017  2017 D SystemUpdateService: onCreate
,08-03 20:23:38.176  2017  2017 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 20:23:38.179  2017  3982 I SystemUpdateService: active receiver: enabled
,08-03 20:23:38.181  2017  3982 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 20:23:38.189  2017  3982 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-03 20:23:38.189  2017  3982 I SystemUpdateService: now status is 0 (complete)
,08-03 20:23:38.189  2017  3982 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-03 20:23:38.189  2017  3982 I SystemUpdateService: file has been verified
,08-03 20:23:38.189  2017  3982 I SystemUpdateService: OTA package size = 12249756
08-03 20:23:38.193  2017  3982 I SystemUpdateService: showing system update notification
,08-03 20:23:38.204  2017  2017 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-03 20:23:38.206  2017  2328 I iu.UploadsManager: num queued entries: 0
,08-03 20:23:38.207   873  3969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-03 20:23:38.208  2017  3986 I MDM     : [223] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-03 20:23:38.208  2017  3986 W BaseAppContext: Using Auth Proxy for data requests.
08-03 20:23:38.209  2017  2017 D SystemUpdateService: onDestroy
08-03 20:23:38.211  2017  3986 V GoogleAuthProtoRequest: [223] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 20:23:38.212  2017  2328 I iu.UploadsManager: num updated entries: 0
,08-03 20:23:38.213  2017  2017 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 20:23:38.215  2017  2017 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 20:23:38.217  2017  2328 I iu.SyncManager: NEXT; no task
,08-03 20:23:38.220  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:23:38.222  3844  3844 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:23:38.223  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:23:38.226  3844  3844 D SprintDMHelper: simOperator: 
08-03 20:23:38.226  3844  3844 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 20:23:38.256  1550  1567 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 20:23:38.256  1550  1567 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-03 20:23:38.256  1550  1567 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 20:23:38.257  1550  1567 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:23:38.272  2017  3986 E MDM     : [223] SitrepService.a: Error sending sitrep.
,08-03 20:23:38.405   873  3969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 18:23:38 GMT], X-Android-Received-Millis=[1470248618404], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470248618345]}
,08-03 20:23:38.406   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 20:23:38.407   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-03 20:23:38.408   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 20:23:38.415   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 20:23:38.485   873  1667 D WifiService: setWifiEnabled: false pid=3734, uid=10000
,08-03 20:23:38.485   873  1667 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:23:38.496  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 20:23:38.498   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-03 20:23:38.498   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-03 20:23:38.498   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 20:23:38.498   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:23:38.511   873  1307 E native  : do suspend true
,08-03 20:23:38.516   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 20:23:38.516   873  1956 D DhcpClient: Clearing IP address
,08-03 20:23:38.518   372   870 D CommandListener: Setting iface cfg
,08-03 20:23:38.524  1550  3984 V NativeCrypto: SSL handshake aborted: ssl=0x9a057000: I/O error during system call, Connection timed out
,08-03 20:23:38.526  2353  3988 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
08-03 20:23:38.528  ,2353  3988 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
08-03 20:23:38.528  2353  3988 W Babel_NetworkConnectionCheckingService: 	... 21 more
08-03 20:23:38.528  2353  3988 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-03 20:23:38.529   873  1384 I ActivityManager: Killing 3523:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-03 20:23:38.549   873  1667 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-03 20:23:38.549   873  3971 D DhcpClient: Receive thread stopped
,08-03 20:23:38.550   873  3969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-03 20:23:38.550   873  3969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-03 20:23:38.555   873  3969 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-03 20:23:38.556   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-03 20:23:38.556   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 20:23:38.557   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 20:23:38.584   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 20:23:38.585   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-03 20:23:38.590   459   459 E Parcel  : Reading a NULL string not supported here.
,08-03 20:23:38.602   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-03 20:23:38.607   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
08-03 20:23:38.611   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 20:23:38.611   873  1307 E native  : do suspend true
,08-03 20:23:38.635   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:38.661   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:38.661   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 20:23:38.662   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-03 20:23:38.662   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:23:38.666   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-03 20:23:38.667  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:38.667  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:38.667  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.667  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:38.668  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:38.668  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:38.669  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.670  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:38.667   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-03 20:23:38.677  1796  1796 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-03 20:23:38.682  2017  2017 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:23:38.687  2017  2017 D SystemUpdateService: onCreate
,08-03 20:23:38.689   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:23:38.692  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:38.692  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.692  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:38.692  1961  2132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:23:38.692  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:38.692  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:23:38.692  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:38.693  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:38.694  2017  2017 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-03 20:23:38.695   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-03 20:23:38.705  2017  2017 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-03 20:23:38.709  2017  2328 I iu.UploadsManager: num queued entries: 0
,08-03 20:23:38.710  2017  2328 I iu.UploadsManager: num updated entries: 0
,08-03 20:23:38.712  2017  2017 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-03 20:23:38.713  2017  2017 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-03 20:23:38.715  3844  3844 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:23:38.711  2017  4001 I SystemUpdateService: active receiver: enabled
,08-03 20:23:38.719  3844  3844 D SprintDMHelper: simOperator: 
,08-03 20:23:38.719  3844  3844 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 20:23:38.731   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-03 20:23:38.732   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 20:23:38.751  2353  4005 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-03 20:23:38.743  2017  2328 I iu.SyncManager: NEXT; no task
,08-03 20:23:38.754  2017  4001 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 20:23:38.762  2017  4001 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-03 20:23:38.762  2017  4001 I SystemUpdateService: now status is 0 (complete)
08-03 20:23:38.762  2017  4001 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 20:23:38.762  2017  4001 I SystemUpdateService: file has been verified
08-03 20:23:38.762  2017  4001 I SystemUpdateService: OTA package size = 12249756
,08-03 20:23:38.766  2017  4001 I SystemUpdateService: showing system update notification
,08-03 20:23:38.774  2017  2017 D SystemUpdateService: onDestroy
,08-03 20:23:39.115   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-03 20:23:41.545   873   890 I ActivityManager: Start proc 4009:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 20:23:41.664  4009  4009 D AdapterServiceConfig: Adding HeadsetService
,08-03 20:23:41.664  4009  4009 D AdapterServiceConfig: Adding A2dpService
08-03 20:23:41.664  4009  4009 D AdapterServiceConfig: Adding HidService
08-03 20:23:41.665  4009  4009 D AdapterServiceConfig: Adding HealthService
08-03 20:23:41.665  4009  4009 D AdapterServiceConfig: Adding PanService
08-03 20:23:41.665  4009  4009 D AdapterServiceConfig: Adding GattService
08-03 20:23:41.665  4009  4009 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 20:23:41.681  4009  4009 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 20:23:41.681   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@50d72e7:true
,08-03 20:23:41.688  4009  4009 I bt_bluedroid: init
,08-03 20:23:41.689  4009  4021 I BluetoothAdapterState: Entering OffState
,08-03 20:23:41.694  4009  4022 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 20:23:41.694  4009  4022 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 20:23:41.694  4009  4022 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-03 20:23:41.695  4009  4022 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 20:23:41.696  4009  4009 I bt_bluedroid: get_profile_interface socket
,08-03 20:23:41.699  4009  4009 I bt_bluedroid: get_profile_interface sdp
,08-03 20:23:41.701  4009  4025 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:23:41.704  4009  4025 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 20:23:41.705  4009  4020 I bt_bluedroid: config_hci_snoop_log
,08-03 20:23:41.708   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 20:23:41.717  4009  4021 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 20:23:41.718  4009  4021 D BluetoothAdapterProperties: Setting state to 14
,08-03 20:23:41.718  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 20:23:41.723  4009  4021 D BluetoothBondStateMachine: make
,08-03 20:23:41.728  4009  4026 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 20:23:41.738  4009  4021 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:23:41.741  4009  4009 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 20:23:41.750  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:41.752  4009  4009 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 20:23:41.754  4009  4009 D BtGatt.GattService: Received start request. Starting profile...
,08-03 20:23:41.754  4009  4009 D BtGatt.GattService: start()
08-03 20:23:41.754  4009  4009 I bt_bluedroid: get_profile_interface gatt
,08-03 20:23:41.757  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
08-03 20:23:41.757  4009  4009 D BtGatt.AdvertiseManager: advertise manager created
,08-03 20:23:41.773  4009  4009 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:23:41.773  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:41.774  4009  4009 V BluetoothAdapterState: isBleTurningOn()=true
08-03 20:23:41.774  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:41.775  4009  4021 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 20:23:41.776  4009  4021 I bt_bluedroid: enable
,08-03 20:23:41.777  4009  4022 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-03 20:23:41.778  4009  4022 I bt_hci  : start_up
,08-03 20:23:41.798  4009  4022 I bt_vendor: alloc value 0xb3a5b189
,08-03 20:23:41.798  4009  4022 I bt_vendor: init
08-03 20:23:41.798  4009  4022 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-03 20:23:41.799  4009  4022 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 20:23:41.908  4009  4022 D bt_hci  : start_up starting async portion
,08-03 20:23:41.909  4009  4029 I bt_hci  : event_finish_startup
08-03 20:23:41.909  4009  4029 I bt_hci_h4: hal_open
08-03 20:23:41.909  4009  4029 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 20:23:41.919  4009  4029 I bt_userial_vendor: device fd = 51 open
,08-03 20:23:41.950  4009  4029 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:23:41.982  4009  4029 D bt_hwcfg: Chipset BCM4354A2
08-03 20:23:41.983  4009  4029 D bt_hwcfg: Target name = [BCM4354A2]
,08-03 20:23:41.983  4009  4029 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 20:23:42.638  4009  4029 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 20:23:42.639  4009  4029 D bt_hwcfg: Settlement delay -- 100 ms
08-03 20:23:42.640  4009  4029 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 20:23:42.757  4009  4029 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:23:42.758  4009  4029 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 20:23:42.787  4009  4029 I bt_hwcfg: vendor lib fwcfg completed
,08-03 20:23:42.788  4009  4029 I bt_vendor: firmware callback
08-03 20:23:42.788  4009  4029 I bt_hci  : firmware_config_callback
,08-03 20:23:42.800  4009  4031 I bt_btu  : btu_task pending for preload complete event
,08-03 20:23:42.800  4009  4031 I bt_btu_task: Bluetooth chip preload is complete
08-03 20:23:42.800  4009  4031 I bt_btu  : btu_task received preload complete event
,08-03 20:23:42.811  4009  4031 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 20:23:42.812  4009  4031 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 20:23:42.812  4009  4031 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 20:23:42.812  4009  4031 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 20:23:42.813  4009  4031 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 20:23:42.813  4009  4031 I         : BTE_InitTraceLevels -- TRC_A2D
,08-03 20:23:42.813  4009  4031 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 20:23:42.813  4009  4031 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 20:23:42.814  4009  4031 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 20:23:42.814  4009  4031 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 20:23:42.814  4009  4031 I         : BTE_InitTraceLevels -- TRC_SDP
,08-03 20:23:42.814  4009  4031 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 20:23:42.815  4009  4031 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 20:23:42.815  4009  4031 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 20:23:42.815  4009  4031 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 20:23:42.954  4009  4031 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d8d9d
,08-03 20:23:42.955  4009  4031 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d8d9d 
,08-03 20:23:42.964  4009  4025 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
08-03 20:23:42.966  4009  4025 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 20:23:42.967  4009  4025 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:23:42.973  4009  4025 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 20:23:42.976  4009  4025 D BluetoothAdapterProperties: Scan Mode:20
,08-03 20:23:42.980  4009  4025 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:23:42.981  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:42.981  4009  4025 D bt_hci  : do_postload posting postload work item
,08-03 20:23:42.982  4009  4029 I bt_hci  : event_postload
08-03 20:23:42.982  4009  4029 I bt_vendor: sco_config_cb
08-03 20:23:42.982  4009  4029 I bt_hci  : sco_config_callback postload finished.
,08-03 20:23:42.984  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:42.989  4009  4029 I bt_vendor: low_power_mode_cb
08-03 20:23:42.989  4009  4025 D bt_bte_conf: Device ID record 1 : primary
,08-03 20:23:42.989  4009  4025 D bt_bte_conf:   vendorId            = 000f
08-03 20:23:42.990  4009  4025 D bt_bte_conf:   vendorIdSource      = 0001
,08-03 20:23:42.990  4009  4025 D bt_bte_conf:   product             = 1200
08-03 20:23:42.991  4009  4025 D bt_bte_conf:   version             = 1436
08-03 20:23:42.991  4009  4025 D bt_bte_conf:   clientExecutableURL = 
,08-03 20:23:42.991  4009  4025 D bt_bte_conf:   serviceDescription  = 
08-03 20:23:42.991  4009  4025 D bt_bte_conf:   documentationURL    = 
08-03 20:23:42.991  4009  4025 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 20:23:42.992  4009  4022 D bt_stack_manager: event_start_up_stack finished
08-03 20:23:42.992  4009  4021 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 20:23:42.993  4009  4021 D BluetoothAdapterProperties: Setting state to 15
08-03 20:23:42.993  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-03 20:23:42.993  4009  4021 I BluetoothAdapterState: Entering BleOnState
,08-03 20:23:42.998  4009  4021 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-03 20:23:42.998  4009  4021 D BluetoothAdapterProperties: Setting state to 11
,08-03 20:23:42.998  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 20:23:43.005  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:43.007  4009  4009 D HeadsetService: Received start request. Starting profile...
,08-03 20:23:43.010  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:43.015  4009  4009 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 20:23:43.015  4009  4009 D HeadsetStateMachine: make
08-03 20:23:43.015  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:43.016  4009  4021 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:23:43.023  4009  4009 D HeadsetStateMachine: max_hf_connections = 1
,08-03 20:23:43.023  4009  4009 I bt_bluedroid: get_profile_interface handsfree
08-03 20:23:43.024  4009  4025 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-03 20:23:43.024  4009  4025 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 20:23:43.028  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:43.029  4009  4009 D A2dpService: Received start request. Starting profile...
,08-03 20:23:43.029  4009  4009 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 20:23:43.029  4009  4009 I bt_bluedroid: get_profile_interface avrcp
,08-03 20:23:43.038  4009  4009 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 20:23:43.038  4009  4009 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:23:43.038  4009  4009 D A2dpStateMachine: make
,08-03 20:23:43.041  4009  4009 I bt_bluedroid: get_profile_interface a2dp
,08-03 20:23:43.041  4009  4025 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 20:23:43.045  4009  4041 D A2dpStateMachine: Enter Disconnected: -2
,08-03 20:23:43.047  4009  4009 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 20:23:43.050  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:43.053  3787  3787 D BluetoothInputDevice: Proxy object connected
,08-03 20:23:43.053  3787  3787 D HidProfile: Bluetooth service connected
,08-03 20:23:43.058  4009  4009 D HidService: Received start request. Starting profile...
,08-03 20:23:43.058  4009  4009 I bt_bluedroid: get_profile_interface hidhost
08-03 20:23:43.059  4009  4025 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ba3e5
08-03 20:23:43.059  4009  4009 D HidService: setHidService(): set to: null
,08-03 20:23:43.059  4009  4025 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-03 20:23:43.060  4009  4009 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-03 20:23:43.063  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:43.065  4009  4009 D HealthService: Received start request. Starting profile...
,08-03 20:23:43.068  4009  4009 I bt_bluedroid: get_profile_interface health
,08-03 20:23:43.070  4009  4009 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 20:23:43.073  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:43.076  3787  3787 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 20:23:43.076  3787  3787 D PanProfile: Bluetooth service connected
08-03 20:23:43.076  4009  4009 D PanService: Received start request. Starting profile...
,08-03 20:23:43.077  4009  4009 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 20:23:43.077  4009  4009 I bt_bluedroid: get_profile_interface pan
08-03 20:23:43.078  4009  4025 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-03 20:23:43.086  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:23:43.090  4009  4009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:43.093  3787  3787 D BluetoothMap: Proxy object connected
,08-03 20:23:43.093  4009  4009 D BluetoothMapService: Received start request. Starting profile...
08-03 20:23:43.094  4009  4009 D BluetoothMapService: start()
08-03 20:23:43.094  3787  3787 D MapProfile: Bluetooth service connected
08-03 20:23:43.094  3787  3787 D BluetoothMap: getConnectedDevices()
,08-03 20:23:43.097  3787  3787 D BluetoothMap: Bluetooth is Not enabled
,08-03 20:23:43.099  4009  4009 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-03 20:23:43.100  4009  4009 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-03 20:23:43.100  4009  4009 D BluetoothMapAppObserver: createReceiver()
,08-03 20:23:43.105  4009  4009 D BluetoothMapAppObserver: initObservers()
,08-03 20:23:43.105  4009  4009 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 20:23:43.128  4009  4009 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:23:43.128  4009  4009 V BluetoothAdapterState: isTurningOn()=true
,08-03 20:23:43.128  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:43.128  4009  4039 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 20:23:43.129  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:23:43.134  4009  4009 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:23:43.134  4009  4009 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:43.134  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false,
08-03 20:23:43.134  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:23:43.135  4009  4009 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:23:43.135  4009  4009 V BluetoothAdapterState: isTurningOn()=true
,08-03 20:23:43.135  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 20:23:43.136  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:23:43.136  4009  4009 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:23:43.136  4009  4009 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:43.137  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:43.137  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:43.138  4009  4009 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:43.138  4009  4009 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:43.138  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:43.138  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:43.143  4009  4009 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:43.143  4009  4009 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:43.144  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:43.144  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:43.144  4009  4021 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-03 20:23:43.144  4009  4021 D BluetoothAdapterProperties: ScanMode =  20
08-03 20:23:43.144  4009  4021 D BluetoothAdapterProperties: State =  11
,08-03 20:23:43.147  4009  4025 D BluetoothAdapterProperties: Scan Mode:21
08-03 20:23:43.147  4009  4025 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 20:23:43.148  4009  4021 D BluetoothAdapterProperties: Setting state to 12
08-03 20:23:43.148  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 20:23:43.148  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:43.148  4009  4021 I BluetoothAdapterState: Entering OnState
08-03 20:23:43.149  1354  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 20:23:43.151  1354  1826 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 20:23:43.151  1354  1354 D BluetoothA2dp: Proxy object connected
,08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:43.152  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:43.153  1717  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:23:43.154   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:23:43.154  1354  1371 D BluetoothMap: onBluetoothStateChange: up=true
08-03 20:23:43.154  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:43.155  1354  1354 D BluetoothMap: Proxy object connected
08-03 20:23:43.155  1354  1354 D MapProfile: Bluetooth service connected
08-03 20:23:43.155  1354  1354 D BluetoothMap: getConnectedDevices()
,08-03 20:23:43.155  1354  1371 D BluetoothPan: onBluetoothStateChange on: true
,08-03 20:23:43.156  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 20:23:43.157  1354  1354 D PanProfile: Bluetooth service connected
08-03 20:23:43.157   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:23:43.157   873   873 D BluetoothA2dp: Proxy object connected
,08-03 20:23:43.157  3787  3797 D BluetoothPan: onBluetoothStateChange on: true
,08-03 20:23:43.158  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:23:43.158   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:23:43.158   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:23:43.159  3787  3798 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 20:23:43.160  1354  1826 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 20:23:43.161  1354  1354 D BluetoothInputDevice: Proxy object connected
,08-03 20:23:43.161  1354  1354 D HidProfile: Bluetooth service connected
08-03 20:23:43.161  3787  3797 D BluetoothMap: onBluetoothStateChange: up=true
08-03 20:23:43.162  3787  3798 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 20:23:43.163   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-03 20:23:43.164  4009  4009 D BluetoothMapService: onReceive
,08-03 20:23:43.164  4009  4009 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:23:43.164  4009  4009 D BluetoothMapService: STATE_ON
08-03 20:23:43.167  3787  3787 D LocalBluetoothProfileManager: Adding local A2DP profile
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:43.168  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:43.169  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:43.170  3787  3787 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 20:23:43.171  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:43.177  3787  3787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:23:43.180  3787  3787 D BluetoothA2dp: Proxy object connected
,08-03 20:23:43.184  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:23:43.190  1354  1354 D BluetoothPbap: Proxy object connected
,08-03 20:23:43.190  1354  1354 D PbapServerProfile: Bluetooth service connected
08-03 20:23:43.191  4009  4009 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 20:23:43.191  4009  4009 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-03 20:23:43.192  4009  4009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:23:43.195  3787  3787 D DockEventReceiver: finishStartingService: stopping service
08-03 20:23:43.195  4009  4009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:23:43.196  4009  4009 D ObexServerSockets: Succeed to create listening sockets 
08-03 20:23:43.196  4009  4009 D ObexServerSockets0: startAccept()
08-03 20:23:43.196  3787  3787 D BluetoothPbap: Proxy object connected
,08-03 20:23:43.196  4009  4009 D ObexServerSockets0: prepareForNewConnect()
08-03 20:23:43.196  3787  3787 D PbapServerProfile: Bluetooth service connected
,08-03 20:23:43.197  4009  4009 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-03 20:23:43.198  4009  4009 D BluetoothSdpJni: SDP Create record success - handle: 0
08-03 20:23:43.198  4009  4049 D ObexServerSockets0: Accepting socket connection...
08-03 20:23:43.199  4009  4050 D ObexServerSockets0: Accepting socket connection...
,08-03 20:23:43.205  4009  4053 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:23:43.218  4009  4057 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:23:43.220  4009  4057 I BtOppRfcommListener: Accept thread started.
,08-03 20:23:43.256   873   873 D BluetoothHeadset: Proxy object connected
,08-03 20:23:43.256   873   873 D BluetoothHeadset: Proxy object connected
08-03 20:23:43.256  1717  1884 D BluetoothHeadset: Proxy object connected
,08-03 20:23:43.257  1354  1365 D BluetoothHeadset: Proxy object connected
,08-03 20:23:43.258  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-03 20:23:43.258   873   873 D BluetoothHeadset: Proxy object connected
08-03 20:23:43.258  1354  1371 D BluetoothHeadset: Proxy object connected,
08-03 20:23:43.258   873   890 D BluetoothHeadset: Proxy object connected
08-03 20:23:43.259   873   890 D BluetoothHeadset: Proxy object connected
08-03 20:23:43.261  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-03 20:23:43.273  3787  3797 D BluetoothHeadset: Proxy object connected
,08-03 20:23:43.275  3787  3787 D HeadsetProfile: Bluetooth service connected
,08-03 20:23:44.504  4009  4021 D BluetoothAdapterState: Current state: ON, message: 23
,08-03 20:23:44.504  4009  4021 D BluetoothAdapterProperties: Setting state to 13
08-03 20:23:44.505  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-03 20:23:44.508  4009  4021 D BluetoothAdapterProperties: onBluetoothDisable()
,08-03 20:23:44.514  4009  4021 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:23:44.528  4009  4009 D BluetoothMapService: onReceive
,08-03 20:23:44.528  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:44.528  4009  4009 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:23:44.529  4009  4009 D BluetoothMapService: STATE_TURNING_OFF
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:44.529  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:23:44.530  4009  4009 D BluetoothMapService: MAP Service closeService in
08-03 20:23:44.530  4009  4009 D BluetoothMapMasInstance0: MAP Service shutdown
08-03 20:23:44.531  4009  4009 D ObexServerSockets0: shutdown(block = true)
08-03 20:23:44.532  4009  4049 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 20:23:44.533  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:44.533  4009  4009 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 20:23:44.533  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:44.534  4009  4034 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-03 20:23:44.534  4009  4009 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 20:23:44.535  4009  4025 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:23:44.536  4009  4021 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 20:23:44.536  3787  3787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 20:23:44.534  4009  4050 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-03 20:23:44.539  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:23:44.539  4009  4009 I BtOppRfcommListener: stopping Accept Thread
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:44.539  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:23:44.540  3734  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:23:44.540  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:23:44.540  4009  4057 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:23:44.540  4009  4057 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 20:23:44.543  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:44.544  4009  4009 D HeadsetService: Received stop request...Stopping profile...
,08-03 20:23:44.547  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:44.548   873   873 D BluetoothHeadset: Proxy object disconnected
,08-03 20:23:44.548   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 20:23:44.548  1717  1730 D BluetoothHeadset: Proxy object disconnected
,08-03 20:23:44.550  3787  3798 D BluetoothHeadset: Proxy object disconnected
,08-03 20:23:44.551  1354  1826 D BluetoothHeadset: Proxy object disconnected
08-03 20:23:44.551   873   873 D BluetoothHeadset: Proxy object disconnected
08-03 20:23:44.551  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-03 20:23:44.553  4009  4009 D A2dpService: Received stop request...Stopping profile...
08-03 20:23:44.553  4009  4041 D A2dpStateMachine: Exit Disconnected: -1
,08-03 20:23:44.555   873   873 D BluetoothA2dp: Proxy object disconnected
,08-03 20:23:44.555  1354  1354 D BluetoothA2dp: Proxy object disconnected
,08-03 20:23:44.556  4009  4009 D HidService: Received stop request...Stopping profile...
08-03 20:23:44.556  4009  4009 D HidService: Stopping Bluetooth HidService
08-03 20:23:44.556  3787  3787 D DockEventReceiver: finishStartingService: stopping service
08-03 20:23:44.557  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-03 20:23:44.557  1354  1354 D HidProfile: Bluetooth service disconnected
08-03 20:23:44.557  4009  4009 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:44.558  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:44.558  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:44.558  3787  3787 D HeadsetProfile: Bluetooth service disconnected
08-03 20:23:44.558  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:23:44.558  3787  3787 D BluetoothA2dp: Proxy object disconnected
08-03 20:23:44.558  3787  3787 D BluetoothInputDevice: Proxy object disconnected
08-03 20:23:44.558  3787  3787 D HidProfile: Bluetooth service disconnected
08-03 20:23:44.562  4009  4009 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-03 20:23:44.562  4009  4025 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 20:23:44.563  4009  4031 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:44.563  4009  4031 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:44.563  4009  4031 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 20:23:44.563  4009  4025 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-03 20:23:44.563  4009  4009 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:23:44.564  4009  4009 D HealthService: Received stop request...Stopping profile...
,08-03 20:23:44.567  4009  4009 D PanService: Received stop request...Stopping profile...
,08-03 20:23:44.570  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:23:44.570  1354  1354 D PanProfile: Bluetooth service disconnected
,08-03 20:23:44.569  3787  3787 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:23:44.570  4009  4009 D BluetoothMapService: Received stop request...Stopping profile...
08-03 20:23:44.570  4009  4009 D BluetoothMapService: stop()
08-03 20:23:44.570  3787  3787 D PanProfile: Bluetooth service disconnected
08-03 20:23:44.570  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:23:44.571  4009  4009 D BluetoothMapAppObserver: deinitObservers()
08-03 20:23:44.571  4009  4009 D BluetoothMapAppObserver: removeReceiver()
,08-03 20:23:44.576  3787  3787 D BluetoothMap: Proxy object disconnected
,08-03 20:23:44.576  3787  3787 D MapProfile: Bluetooth service disconnected
08-03 20:23:44.576  1354  1354 D BluetoothMap: Proxy object disconnected
,08-03 20:23:44.576  4009  4009 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:44.576  1354  1354 D MapProfile: Bluetooth service disconnected
08-03 20:23:44.576  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:44.576  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:44.576  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:44.578  4009  4031 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 20:23:44.578  4009  4025 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-03 20:23:44.578  4009  4031 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:23:44.578  4009  4031 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:23:44.578  4009  4031 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-03 20:23:44.578  4009  4031 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:23:44.578  4009  4031 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-03 20:23:44.580  4009  4009 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:44.580  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:44.580  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:44.580  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:44.581  4009  4009 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-03 20:23:44.581  4009  4009 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 20:23:44.581  4009  4025 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 20:23:44.581  4009  4009 V BluetoothAdapterState: isTurningOff()=true
,08-03 20:23:44.581  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:44.581  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:44.582  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:44.582  4009  4009 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-03 20:23:44.582  4009  4025 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-03 20:23:44.582  4009  4009 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-03 20:23:44.585  1354  1354 D BluetoothPbap: Proxy object disconnected
08-03 20:23:44.585  3787  3787 D BluetoothPbap: Proxy object disconnected
08-03 20:23:44.585  1354  1354 D PbapServerProfile: Bluetooth service disconnected
08-03 20:23:44.585  4009  4009 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:44.585  3787  3787 D PbapServerProfile: Bluetooth service disconnected
08-03 20:23:44.585  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:44.585  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:44.585  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:44.585  4009  4009 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 20:23:44.586  4009  4009 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 20:23:44.587  4009  4009 D BluetoothMapService: MAP Service closeService in
08-03 20:23:44.587  4009  4009 V BluetoothAdapterState: isTurningOff()=true
08-03 20:23:44.587  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:44.587  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:44.587  4009  4009 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:44.588  4009  4021 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 20:23:44.588  4009  4021 D BluetoothAdapterProperties: Setting state to 15
,08-03 20:23:44.588  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 20:23:44.588  4009  4009 D BluetoothMapService: cleanup()
08-03 20:23:44.588  4009  4009 D BluetoothMapService: MAP Service closeService in
08-03 20:23:44.589  1354  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:23:44.588  4009  4021 I BluetoothAdapterState: Entering BleOnState
,08-03 20:23:44.594  1354  1826 D BluetoothPbap: onBluetoothStateChange: up=false
,08-03 20:23:44.597  1717  1949 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 20:23:44.598   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:23:44.598  1354  1365 D BluetoothMap: onBluetoothStateChange: up=false
,08-03 20:23:44.599  1354  1371 D BluetoothPan: onBluetoothStateChange on: false
,08-03 20:23:44.600   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:23:44.601  3787  3797 D BluetoothPan: onBluetoothStateChange on: false
,08-03 20:23:44.602  1354  1826 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 20:23:44.602   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:23:44.602   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:23:44.603  3787  3798 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 20:23:44.604  1354  1365 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-03 20:23:44.605  3787  3797 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 20:23:44.605  3787  3798 D BluetoothMap: onBluetoothStateChange: up=false
08-03 20:23:44.606  3787  3797 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 20:23:44.607  3787  3798 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-03 20:23:44.608  4009  4021 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-03 20:23:44.608  4009  4021 D BluetoothAdapterProperties: Setting state to 16
08-03 20:23:44.608  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-03 20:23:44.609  4009  4021 D BluetoothAdapterProperties: onBleDisable
08-03 20:23:44.609  4009  4021 I BluetoothAdapterState: Entering PendingCommandState
08-03 20:23:44.609  4009  4022 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-03 20:23:44.610  4009  4031 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-03 20:23:44.610  4009  4031 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 20:23:44.613  4009  4025 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:23:44.615  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:44.616  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:44.618  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:44.619  3787  3787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:23:44.620  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:44.623  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:23:44.624  3787  3787 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:23:44.814  4009  4025 I bt_hci  : shut_down
,08-03 20:23:44.831  4009  4029 I bt_vendor: low_power_mode_cb
,08-03 20:23:44.843  4009  4029 D bt_hwcfg: hw_epilog_process
,08-03 20:23:44.856  4009  4029 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-03 20:23:44.856  4009  4029 I bt_vendor: epilog_cb
,08-03 20:23:44.856  4009  4029 I bt_hci  : epilog_finished_callback,
,08-03 20:23:44.863  4009  4025 I bt_hci_h4: hal_close
,08-03 20:23:44.864  4009  4025 I bt_userial_vendor: device fd = 51 close
,08-03 20:23:44.981  4009  4022 D bt_stack_manager: event_shut_down_stack finished.
,08-03 20:23:44.982  4009  4021 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-03 20:23:44.990  4009  4009 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 20:23:44.991  4009  4021 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-03 20:23:44.992  4009  4009 D BtGatt.GattService: Received stop request...Stopping profile...,
,08-03 20:23:44.992  4009  4009 D BtGatt.GattService: stop()
08-03 20:23:44.993  4009  4009 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 20:23:44.998  4009  4009 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:44.998  4009  4009 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:44.999  4009  4009 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:44.999  4009  4009 V BluetoothAdapterState: isBleTurningOff()=true
,08-03 20:23:45.000  4009  4021 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-03 20:23:45.002  4009  4021 D BluetoothAdapterProperties: Setting state to 10
08-03 20:23:45.002  4009  4021 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-03 20:23:45.004  4009  4021 I BluetoothAdapterState: Entering OffState
,08-03 20:23:45.006   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-03 20:23:45.035  4009  4009 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-03 20:23:45.036  4009  4009 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 20:23:45.036  4009  4022 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 20:23:45.039  4009  4022 D bt_stack_manager: event_clean_up_stack finished.
08-03 20:23:45.039  4009  4009 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 20:23:45.041  4009  4009 I art     : System.exit called, status: 0
,08-03 20:23:45.041  4009  4009 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 20:23:45.098   873  1751 I ActivityManager: Process com.android.bluetooth (pid 4009) has died
,08-03 20:23:46.004   873  1309 D ConnectivityService: handlePromptUnvalidated 101,
,08-03 20:23:47.501  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:23:47.501  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:23:50.508  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:23:50.509  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80caf92 added. We now have 6 listener(s)
08-03 20:23:50.509  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:23:50.513  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:23:50.513  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d16d63 added. We now have 7 listener(s)
08-03 20:23:50.514  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:23:50.515  3734  3780 I System.out: IsBluetoothEnabled
,08-03 20:23:50.525  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:50.553   873   890 I ActivityManager: Start proc 4068:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 20:23:50.678  4068  4068 D AdapterServiceConfig: Adding HeadsetService
,08-03 20:23:50.678  4068  4068 D AdapterServiceConfig: Adding A2dpService
08-03 20:23:50.679  4068  4068 D AdapterServiceConfig: Adding HidService
08-03 20:23:50.679  4068  4068 D AdapterServiceConfig: Adding HealthService
,08-03 20:23:50.679  4068  4068 D AdapterServiceConfig: Adding PanService
08-03 20:23:50.679  4068  4068 D AdapterServiceConfig: Adding GattService
,08-03 20:23:50.679  4068  4068 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 20:23:50.698   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b860a8:true
,08-03 20:23:50.699  4068  4068 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 20:23:50.705  4068  4068 I bt_bluedroid: init
,08-03 20:23:50.705  4068  4080 I BluetoothAdapterState: Entering OffState
,08-03 20:23:50.711  4068  4081 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 20:23:50.712  4068  4081 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 20:23:50.712  4068  4081 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 20:23:50.713  4068  4081 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-03 20:23:50.715  4068  4068 I bt_bluedroid: get_profile_interface socket
,08-03 20:23:50.718  4068  4068 I bt_bluedroid: get_profile_interface sdp
,08-03 20:23:50.721  4068  4084 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:23:50.724  4068  4079 I bt_bluedroid: config_hci_snoop_log
,08-03 20:23:50.725  4068  4084 D BluetoothAdapterProperties: Name is: Nexus 6
08-03 20:23:50.726   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 20:23:50.737  4068  4080 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 20:23:50.737  4068  4080 D BluetoothAdapterProperties: Setting state to 14
08-03 20:23:50.738  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 20:23:50.742  4068  4080 D BluetoothBondStateMachine: make
,08-03 20:23:50.750  4068  4085 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 20:23:50.755  4068  4080 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:23:50.759  4068  4068 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 20:23:50.770  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:50.772  4068  4068 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 20:23:50.774  4068  4068 D BtGatt.GattService: Received start request. Starting profile...
,08-03 20:23:50.775  4068  4068 D BtGatt.GattService: start()
08-03 20:23:50.775  4068  4068 I bt_bluedroid: get_profile_interface gatt
,08-03 20:23:50.779  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
08-03 20:23:50.779  4068  4068 D BtGatt.AdvertiseManager: advertise manager created
,08-03 20:23:50.789  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:23:50.789  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:23:50.789  4068  4068 V BluetoothAdapterState: isBleTurningOn()=true
,08-03 20:23:50.789  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:50.790  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-03 20:23:50.790  4068  4080 I bt_bluedroid: enable
,08-03 20:23:50.791  4068  4081 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-03 20:23:50.792  4068  4081 I bt_hci  : start_up
,08-03 20:23:50.812  4068  4081 I bt_vendor: alloc value 0xb3a5b189
08-03 20:23:50.812  4068  4081 I bt_vendor: init
08-03 20:23:50.812  4068  4081 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-03 20:23:50.813  4068  4081 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 20:23:50.922  4068  4081 D bt_hci  : start_up starting async portion
,08-03 20:23:50.923  4068  4088 I bt_hci  : event_finish_startup
08-03 20:23:50.923  4068  4088 I bt_hci_h4: hal_open
08-03 20:23:50.924  4068  4088 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 20:23:50.932  4068  4088 I bt_userial_vendor: device fd = 51 open
,08-03 20:23:50.964  4068  4088 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:23:50.996  4068  4088 D bt_hwcfg: Chipset BCM4354A2
,08-03 20:23:50.996  4068  4088 D bt_hwcfg: Target name = [BCM4354A2]
08-03 20:23:50.997  4068  4088 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 20:23:51.649  4068  4088 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 20:23:51.650  4068  4088 D bt_hwcfg: Settlement delay -- 100 ms
08-03 20:23:51.651  4068  4088 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 20:23:51.767  4068  4088 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:23:51.769  4068  4088 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 20:23:51.799  4068  4088 I bt_hwcfg: vendor lib fwcfg completed
08-03 20:23:51.799  4068  4088 I bt_vendor: firmware callback
,08-03 20:23:51.799  4068  4088 I bt_hci  : firmware_config_callback
,08-03 20:23:51.811  4068  4090 I bt_btu  : btu_task pending for preload complete event
,08-03 20:23:51.811  4068  4090 I bt_btu_task: Bluetooth chip preload is complete
,08-03 20:23:51.811  4068  4090 I bt_btu  : btu_task received preload complete event
,08-03 20:23:51.822  4068  4090 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 20:23:51.823  4068  4090 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 20:23:51.823  4068  4090 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-03 20:23:51.824  4068  4090 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-03 20:23:51.824  4068  4090 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-03 20:23:51.824  4068  4090 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 20:23:51.825  4068  4090 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 20:23:51.825  4068  4090 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 20:23:51.825  4068  4090 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 20:23:51.826  4068  4090 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 20:23:51.826  4068  4090 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 20:23:51.826  4068  4090 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 20:23:51.827  4068  4090 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 20:23:51.827  4068  4090 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 20:23:51.827  4068  4090 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 20:23:51.962  4068  4090 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d8d9d
,08-03 20:23:51.962  4068  4090 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d8d9d 
,08-03 20:23:51.973  4068  4084 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-03 20:23:51.976  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 20:23:51.977  4068  4084 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:23:51.980  4068  4084 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 20:23:51.983  4068  4084 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:23:51.984  4068  4084 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:23:51.985  4068  4084 D bt_hci  : do_postload posting postload work item
,08-03 20:23:51.985  4068  4088 I bt_hci  : event_postload
08-03 20:23:51.985  4068  4088 I bt_vendor: sco_config_cb
08-03 20:23:51.985  4068  4088 I bt_hci  : sco_config_callback postload finished.
,08-03 20:23:51.988  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:51.991  4068  4084 D bt_bte_conf: Device ID record 1 : primary
08-03 20:23:51.991  4068  4084 D bt_bte_conf:   vendorId            = 000f
,08-03 20:23:51.991  4068  4084 D bt_bte_conf:   vendorIdSource      = 0001
08-03 20:23:51.992  4068  4084 D bt_bte_conf:   product             = 1200
08-03 20:23:51.992  4068  4084 D bt_bte_conf:   version             = 1436
,08-03 20:23:51.992  4068  4084 D bt_bte_conf:   clientExecutableURL = 
,08-03 20:23:51.992  4068  4084 D bt_bte_conf:   serviceDescription  = 
08-03 20:23:51.992  4068  4084 D bt_bte_conf:   documentationURL    = 
,08-03 20:23:51.993  4068  4084 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 20:23:51.993  4068  4088 I bt_vendor: low_power_mode_cb
08-03 20:23:51.993  4068  4081 D bt_stack_manager: event_start_up_stack finished
08-03 20:23:51.994  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-03 20:23:51.996  4068  4080 D BluetoothAdapterProperties: Setting state to 15
08-03 20:23:51.997  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-03 20:23:52.000  4068  4080 I BluetoothAdapterState: Entering BleOnState
,08-03 20:23:52.004  4068  4080 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-03 20:23:52.004  4068  4080 D BluetoothAdapterProperties: Setting state to 11
,08-03 20:23:52.004  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 20:23:52.015  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:52.017  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:52.018  4068  4068 D HeadsetService: Received start request. Starting profile...
,08-03 20:23:52.021  4068  4068 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 20:23:52.022  4068  4068 D HeadsetStateMachine: make
,08-03 20:23:52.028  4068  4068 D HeadsetStateMachine: max_hf_connections = 1
08-03 20:23:52.028  4068  4080 I BluetoothAdapterState: Entering PendingCommandState
08-03 20:23:52.028  4068  4068 I bt_bluedroid: get_profile_interface handsfree
,08-03 20:23:52.029  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-03 20:23:52.030  4068  4084 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 20:23:52.036  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:23:52.036  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
08-03 20:23:52.037  4068  4068 D A2dpService: Received start request. Starting profile...
08-03 20:23:52.037  4068  4068 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 20:23:52.037  4068  4068 I bt_bluedroid: get_profile_interface avrcp
,08-03 20:23:52.044  4068  4068 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 20:23:52.044  4068  4068 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:23:52.044  4068  4068 D A2dpStateMachine: make
,08-03 20:23:52.047  4068  4068 I bt_bluedroid: get_profile_interface a2dp
,08-03 20:23:52.047  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 20:23:52.048  4068  4099 D A2dpStateMachine: Enter Disconnected: -2
,08-03 20:23:52.049  4068  4068 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 20:23:52.049  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:52.050  4068  4068 D HidService: Received start request. Starting profile...
08-03 20:23:52.050  4068  4068 I bt_bluedroid: get_profile_interface hidhost
08-03 20:23:52.050  4068  4084 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ba3e5
08-03 20:23:52.050  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-03 20:23:52.050  4068  4068 D HidService: setHidService(): set to: null
08-03 20:23:52.052  4068  4068 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-03 20:23:52.053  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:52.053  4068  4068 D HealthService: Received start request. Starting profile...
,08-03 20:23:52.056  4068  4068 I bt_bluedroid: get_profile_interface health
,08-03 20:23:52.056  4068  4068 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 20:23:52.057  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:52.058  4068  4068 D PanService: Received start request. Starting profile...
08-03 20:23:52.058  4068  4068 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 20:23:52.058  4068  4068 I bt_bluedroid: get_profile_interface pan
,08-03 20:23:52.059  4068  4084 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-03 20:23:52.060  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:23:52.061  4068  4068 D BluetoothMapService: Received start request. Starting profile...
,08-03 20:23:52.061  4068  4068 D BluetoothMapService: start()
,08-03 20:23:52.062  4068  4068 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 20:23:52.063  4068  4068 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 20:23:52.063  4068  4068 D BluetoothMapAppObserver: createReceiver()
,08-03 20:23:52.064  4068  4068 D BluetoothMapAppObserver: initObservers()
,08-03 20:23:52.064  4068  4068 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 20:23:52.069  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:23:52.069  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:52.069  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 20:23:52.069  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:52.070  4068  4097 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-03 20:23:52.072  4068  4068 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:52.072  4068  4068 V BluetoothAdapterState: isTurningOn()=true
,08-03 20:23:52.072  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:52.072  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isTurningOn()=true
,08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:23:52.073  4068  4068 V BluetoothAdapterState: isTurningOff()=false
08-03 20:23:52.074  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:23:52.074  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:23:52.074  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:23:52.074  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-03 20:23:52.074  4068  4080 D BluetoothAdapterProperties: ScanMode =  20
08-03 20:23:52.074  4068  4080 D BluetoothAdapterProperties: State =  11
08-03 20:23:52.074  4068  4080 D BluetoothAdapterProperties: Setting state to 12
,08-03 20:23:52.074  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 20:23:52.075  4068  4080 I BluetoothAdapterState: Entering OnState
08-03 20:23:52.076  1354  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:23:52.079  4068  4084 D BluetoothAdapterProperties: Scan Mode:21
08-03 20:23:52.079  4068  4084 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:23:52.081  1354  1371 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 20:23:52.083  1354  1354 D BluetoothA2dp: Proxy object connected
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:52.085  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:23:52.087  1717  1730 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:23:52.088  4068  4068 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 20:23:52.088   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:23:52.088  4068  4068 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-03 20:23:52.088  1354  1365 D BluetoothMap: onBluetoothStateChange: up=true
08-03 20:23:52.089  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:52.090  4068  4068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:23:52.092  1354  1826 D BluetoothPan: onBluetoothStateChange on: true
,08-03 20:23:52.093  4068  4068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:23:52.093  4068  4068 D ObexServerSockets: Succeed to create listening sockets 
,08-03 20:23:52.093  4068  4068 D ObexServerSockets0: startAccept()
08-03 20:23:52.094   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:23:52.094  4068  4068 D ObexServerSockets0: prepareForNewConnect()
08-03 20:23:52.094   873   873 D BluetoothA2dp: Proxy object connected
,08-03 20:23:52.095  3787  3797 D BluetoothPan: onBluetoothStateChange on: true
08-03 20:23:52.095  4068  4068 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-03 20:23:52.095  4068  4068 D BluetoothSdpJni: SDP Create record success - handle: 0
08-03 20:23:52.096  1354  1354 D BluetoothMap: Proxy object connected
08-03 20:23:52.096  1354  1354 D MapProfile: Bluetooth service connected
08-03 20:23:52.097  1354  1354 D BluetoothMap: getConnectedDevices()
08-03 20:23:52.097  1354  1826 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:23:52.098  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 20:23:52.098  1354  1354 D PanProfile: Bluetooth service connected
,08-03 20:23:52.098   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:23:52.098   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:23:52.098  3787  3798 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 20:23:52.100  4068  4104 D ObexServerSockets0: Accepting socket connection...
08-03 20:23:52.100  1354  1365 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 20:23:52.100  4068  4105 D ObexServerSockets0: Accepting socket connection...
08-03 20:23:52.100  3787  3787 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 20:23:52.102  3787  3797 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:23:52.102  1354  1354 D BluetoothInputDevice: Proxy object connected
08-03 20:23:52.102  1354  1354 D HidProfile: Bluetooth service connected
08-03 20:23:52.103  3787  3798 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 20:23:52.105  3787  3797 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 20:23:52.107  3787  3798 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 20:23:52.109  3787  3787 D PanProfile: Bluetooth service connected
,08-03 20:23:52.109  3787  3787 D BluetoothMap: Proxy object connected
,08-03 20:23:52.109  3787  3787 D MapProfile: Bluetooth service connected
,08-03 20:23:52.109  3787  3787 D BluetoothMap: getConnectedDevices()
08-03 20:23:52.110   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-03 20:23:52.113  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:23:52.113  4068  4068 D BluetoothMapService: onReceive
08-03 20:23:52.113  4068  4068 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 20:23:52.113  4068  4068 D BluetoothMapService: STATE_ON
,08-03 20:23:52.117  3787  3787 D BluetoothA2dp: Proxy object connected
,08-03 20:23:52.120  3787  3787 D BluetoothInputDevice: Proxy object connected
08-03 20:23:52.120  3787  3787 D HidProfile: Bluetooth service connected
,08-03 20:23:52.131  3787  3787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:23:52.135  4068  4068 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 20:23:52.136  4068  4068 D ObexServerSockets0: prepareForNewConnect()
08-03 20:23:52.136  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:23:52.137  3787  3787 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:23:52.156  3787  3787 D BluetoothPbap: Proxy object connected
,08-03 20:23:52.156  3787  3787 D PbapServerProfile: Bluetooth service connected
08-03 20:23:52.156  1354  1354 D BluetoothPbap: Proxy object connected
08-03 20:23:52.156  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-03 20:23:52.168  4068  4111 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:23:52.193   873   873 D BluetoothHeadset: Proxy object connected
,08-03 20:23:52.193   873   873 D BluetoothHeadset: Proxy object connected
08-03 20:23:52.193  4068  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:23:52.193  1717  1949 D BluetoothHeadset: Proxy object connected
,08-03 20:23:52.196  3787  3798 D BluetoothHeadset: Proxy object connected
,08-03 20:23:52.197  3787  3787 D HeadsetProfile: Bluetooth service connected
,08-03 20:23:52.197  1354  1365 D BluetoothHeadset: Proxy object connected
,08-03 20:23:52.197  4068  4115 I BtOppRfcommListener: Accept thread started.
,08-03 20:23:52.197  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-03 20:23:52.197   873   873 D BluetoothHeadset: Proxy object connected
,08-03 20:23:52.198  1354  1371 D BluetoothHeadset: Proxy object connected
08-03 20:23:52.199   873   890 D BluetoothHeadset: Proxy object connected
08-03 20:23:52.199   873   890 D BluetoothHeadset: Proxy object connected
,08-03 20:23:52.200  1354  1354 D HeadsetProfile: Bluetooth service connected
08-03 20:23:52.204  3787  4106 D BluetoothHeadset: Proxy object connected
,08-03 20:23:52.204  3787  3787 D HeadsetProfile: Bluetooth service connected
,08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:52.544  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:23:52.552  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:52.555  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:23:52.556  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@111ed60 added. We now have 8 listener(s)
,08-03 20:23:52.556  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:23:52.561   873  1383 D WifiService: setWifiEnabled: false pid=3734, uid=10000
,08-03 20:23:52.562   873  1383 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:23:52.572  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:23:52.573   873   883 D WifiService: setWifiEnabled: true pid=3734, uid=10000
,08-03 20:23:52.573   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:23:52.586   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:52.603  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:23:52.611  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:52.636   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-03 20:23:52.637   873  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 20:23:52.638   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 20:23:52.640   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 20:23:52.642   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 20:23:52.642   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 20:23:52.643   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-03 20:23:52.643   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 20:23:52.663   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 20:23:52.664   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:23:52.666   372   870 D CommandListener: Setting iface cfg
,08-03 20:23:52.667   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-03 20:23:52.668   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 20:23:52.726   873  1307 E native  : do suspend true
,08-03 20:23:52.726   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 20:23:52.736   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 20:23:52.748   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:23:53.593  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:23:53.600  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:23:53.612  3734  4121 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-03 20:23:53.612  3734  4121 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 20:23:54.152   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:23:54.306   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.06 rxSuccessRate=15.19 delta 1000 -> 994
,08-03 20:23:54.309   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-03 20:23:54.309   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:23:54.329   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 20:23:54.385   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 20:23:54.388  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 20:23:54.810  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 20:23:54.848  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 20:23:54.850  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 20:23:54.852   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:23:54.864   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 20:23:54.864   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:23:54.865   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 20:23:54.886   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:23:54.903   372   870 D CommandListener: Setting iface cfg
,08-03 20:23:54.904   873  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-03 20:23:54.912   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 20:23:54.962   873  4124 D DhcpClient: Receive thread started
,08-03 20:23:55.050   873  1307 E native  : do suspend false
,08-03 20:23:55.070   873  1956 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 20:23:55.083   873  4124 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-03 20:23:55.084   873  1956 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-03 20:23:55.088   873  1956 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 20:23:55.101   873  4124 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 20:23:55.102   873  1956 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 20:23:55.107   372   870 D CommandListener: Setting iface cfg
,08-03 20:23:55.118   873  1956 D DhcpClient: Scheduling renewal in 86399s
,08-03 20:23:55.121   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-03 20:23:55.122   873  1307 E native  : do suspend true
,08-03 20:23:55.134   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-03 20:23:55.135   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
08-03 20:23:55.136   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 20:23:55.137   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 20:23:55.138   873  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-03 20:23:55.207   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 20:23:55.207   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-03 20:23:55.208   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-03 20:23:55.210   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-03 20:23:55.212   873  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-03 20:23:55.230   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-03 20:23:55.244   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-03 20:23:55.244   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-03 20:23:55.245   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-03 20:23:55.245   873  1309 D ConnectivityService:    accepting network in place of null
08-03 20:23:55.245   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-03 20:23:55.246   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-03 20:23:55.247   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 20:23:55.259   873  4123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=420712, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 20:23:55.311   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:55.359   873  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
08-03 20:23:55.360   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:23:55.365   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-03 20:23:55.365   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:23:55.367   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-03 20:23:55.369   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:23:55.384  3734  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:23:55.389  3734  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:23:55.398  1796  1796 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-03 20:23:55.406  2017  2017 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:23:55.413  2017  2017 D SystemUpdateService: onCreate
,08-03 20:23:55.420  2017  2017 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 20:23:55.445  2017  4133 I SystemUpdateService: active receiver: enabled
,08-03 20:23:55.452  2017  2017 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 20:23:55.457  2017  2328 I iu.UploadsManager: num queued entries: 0
,08-03 20:23:55.457  2017  2328 I iu.UploadsManager: num updated entries: 0
,08-03 20:23:55.464  2017  4136 I MDM     : [228] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-03 20:23:55.464  2017  4136 W BaseAppContext: Using Auth Proxy for data requests.
08-03 20:23:55.465  2017  4136 V GoogleAuthProtoRequest: [228] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 20:23:55.468  2017  4133 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 20:23:55.470  2017  2017 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 20:23:55.471  2017  2017 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 20:23:55.473  2017  4133 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-03 20:23:55.474  2017  4133 I SystemUpdateService: now status is 0 (complete)
08-03 20:23:55.474  2017  4133 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-03 20:23:55.474  2017  4133 I SystemUpdateService: file has been verified
,08-03 20:23:55.474  2017  4133 I SystemUpdateService: OTA package size = 12249756
,08-03 20:23:55.474  2017  2328 I iu.SyncManager: NEXT; no task
08-03 20:23:55.477  3844  3844 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:23:55.488  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:23:55.491  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:23:55.498  3844  3844 D SprintDMHelper: simOperator: 
,08-03 20:23:55.498  3844  3844 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-03 20:23:55.498  2017  4133 I SystemUpdateService: showing system update notification
,08-03 20:23:55.504   873  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 18:23:55 GMT], X-Android-Received-Millis=[1470248635503], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470248635415]}
,08-03 20:23:55.508   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 20:23:55.508   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-03 20:23:55.508   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-03 20:23:55.509   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 20:23:55.551  2017  2017 D SystemUpdateService: onDestroy
,08-03 20:23:55.574  1550  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 20:23:55.574  1550  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-03 20:23:55.574  1550  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:23:55.575  1550  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:23:55.592  2017  4136 E MDM     : [228] SitrepService.a: Error sending sitrep.
,08-03 20:23:55.674  2353  4139 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 20:23:56.619  3734  4145 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-03 20:23:56.620  3734  4121 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-03 20:23:56.621  3734  4145 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:23:56.622  3734  4145 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:23:56.623  3734  4121 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:23:56.623  3734  4145 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:23:56.626  3734  4147 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Sender)
08-03 20:23:56.626  3734  4145 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-03 20:23:56.628  3734  4121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:23:56.630  3734  4148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Receiver)
08-03 20:23:56.631  3734  4121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:23:56.631  3734  4148 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: IncomingSocketThread/Receiver)
08-03 20:23:56.632  3734  4148 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-03 20:23:56.632  3734  4148 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-03 20:23:56.633  3734  4149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Sender)
,08-03 20:23:56.635  3734  4121 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 20:23:56.637  3734  4150 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Receiver)
,08-03 20:23:56.639  3734  4150 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: OutgoingSocketThread/Receiver)
08-03 20:23:56.639  3734  4150 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 20:23:56.639  3734  4150 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 20:23:59.619  3734  3780 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-03 20:23:59.622  3734  3780 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-03 20:23:59.628  3734  3780 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bb5e198 Bundle[{}]
,08-03 20:23:59.629  3734  3780 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 20:23:59.629  3734  3780 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 20:23:59.629  3734  3780 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-03 20:23:59.630  3734  3780 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-03 20:23:59.630  3734  3780 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-03 20:23:59.631  3734  3780 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-03 20:23:59.635  3734  3780 I System.out: Running OutgoingSocketThread
08-03 20:23:59.638  3734  4151 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775,
08-03 20:23:59.639  3734  4151 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 20:24:02.648  3734  4154 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-03 20:24:02.648  3734  4154 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-03 20:24:02.649  3734  4154 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:24:02.649  3734  4151 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-03 20:24:02.649  3734  4151 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:24:02.649  3734  4151 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:24:02.650  3734  4154 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:24:02.652  3734  4154 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 20:24:02.654  3734  4151 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:24:02.657  3734  4156 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Sender)
,08-03 20:24:02.660  3734  4158 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Sender)
,08-03 20:24:02.662  3734  4157 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: IncomingSocketThread/Receiver)
,08-03 20:24:02.663  3734  4151 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-03 20:24:02.664  3734  4157 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: IncomingSocketThread/Receiver)
08-03 20:24:02.664  3734  4157 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 20:24:02.664  3734  4157 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 20:24:02.669  3734  4159 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: OutgoingSocketThread/Receiver)
08-03 20:24:02.671  3734  4159 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: OutgoingSocketThread/Receiver)
08-03 20:24:02.672  3734  4159 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 20:24:02.672  3734  4159 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 20:24:03.253   873  1309 D ConnectivityService: handlePromptUnvalidated 102
,08-03 20:24:05.651  3734  3780 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,08-03 20:24:05.653  3734  3780 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-03 20:24:05.654  3734  3780 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,08-03 20:24:05.659  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:24:05.659  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3358219 added. We now have 2 listener(s)
,08-03 20:24:05.661  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:24:05.661  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:24:05.661  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.661  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:05.661  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c232de added. We now have 9 listener(s)
08-03 20:24:05.662  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:05.663  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 20:24:05.667  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:24:05.680  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:24:05.686  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:24:05.686  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:24:05.686  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:24:05.686  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d987f8c added. We now have 3 listener(s)
08-03 20:24:05.688  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 20:24:05.688  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:24:05.688  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.689  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:05.689  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31326d5 added. We now have 10 listener(s)
08-03 20:24:05.689  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:05.689  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:24:05.689  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:24:05.689  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:24:05.689  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:24:05.689  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.689  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:24:05.690  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:24:05.690  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3358219 removed from the list
08-03 20:24:05.690  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:05.690  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c232de removed from the list
08-03 20:24:05.692  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:24:05.693  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:24:05.693  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:05.694  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.694  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:05.696  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:24:05.696  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:24:05.697  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:05.697  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c232de not in the list
08-03 20:24:05.697  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.697  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:24:05.700  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:24:05.701  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:24:05.701  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:05.701  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:24:05.701  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31326d5 removed from the list
08-03 20:24:05.701  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:24:05.702  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.702  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:05.702  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:24:05.702  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d987f8c removed from the list
,08-03 20:24:05.704  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:24:05.705  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba9eea added. We now have 2 listener(s)
,08-03 20:24:05.710  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:24:05.711  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 20:24:05.711  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.712  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:05.712  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dd25db added. We now have 9 listener(s)
08-03 20:24:05.712  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:24:05.714  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 20:24:05.725  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:24:05.740  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:24:05.748  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:24:05.748  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:24:05.749  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:24:05.749  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ec5b51 added. We now have 3 listener(s)
08-03 20:24:05.756  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:24:05.757  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:24:05.756  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:24:05.757  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.758  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:24:05.758  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1bbfb6 added. We now have 10 listener(s)
08-03 20:24:05.759  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:05.759  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:24:05.759  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:24:05.760  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:24:05.760  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:24:05.760  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 20:24:05.764  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:24:05.766  3734  3780 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:24:05.766  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:24:05.774  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:24:05.776  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 20:24:05.776  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:24:05.786  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 20:24:05.786  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-03 20:24:05.787  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 20:24:05.788  3734  3780 D BluetoothAdapter: STATE_ON
,08-03 20:24:05.796  4068  4107 D BtGatt.GattService: registerClient() - UUID=888f2037-493c-4226-b2f6-1d51aedd7aa5
,08-03 20:24:05.798  4068  4084 D BtGatt.GattService: onClientRegistered() - UUID=888f2037-493c-4226-b2f6-1d51aedd7aa5, clientIf=5
,08-03 20:24:05.799  3734  3744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:24:05.800  4068  4096 D BtGatt.GattService: start scan with filters
,08-03 20:24:05.810  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 20:24:05.810  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 20:24:05.810  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:24:05.810  4068  4087 D BtGatt.ScanManager: handling starting scan
08-03 20:24:05.810  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 20:24:05.813  4068  4087 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@46906ac
,08-03 20:24:05.816  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:24:05.816  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 20:24:05.816  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:24:05.820  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 20:24:05.825  4068  4084 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 20:24:05.825  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-03 20:24:05.826  4068  4087 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 20:24:05.826  3734  3780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-03 20:24:05.827  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:24:05.827  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-03 20:24:05.827  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.827  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:24:05.828  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-03 20:24:05.828  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:24:05.828  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:24:05.828  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:24:05.829  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:24:05.829  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-03 20:24:05.830  3734  3780 D BluetoothAdapter: STATE_ON
08-03 20:24:05.832  4068  4079 D BtGatt.GattService: stopScan() - queue size =1
,08-03 20:24:05.833  4068  4078 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 20:24:05.834  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-03 20:24:05.834  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 20:24:05.834  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-03 20:24:05.834  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-03 20:24:05.834  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 20:24:05.835  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:24:05.835  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 20:24:05.835  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 20:24:05.835  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:24:05.835  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 20:24:05.836  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:24:05.837  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:24:05.837  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:24:05.838  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:24:05.838  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:24:05.838  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:24:05.838  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 20:24:05.838  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.838  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:24:05.838  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 20:24:05.838  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba9eea removed from the list
,08-03 20:24:05.838  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:24:05.838  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dd25db removed from the list
08-03 20:24:05.838  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:24:05.838  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:05.839  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:24:05.840  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:24:05.841  4068  4084 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 20:24:05.841  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:05.841  4068  4087 D BtGatt.ScanManager: Starting BLE batch scan
,08-03 20:24:05.841  4068  4087 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:24:05.842  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:24:05.842  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-03 20:24:05.842  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:24:05.842  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dd25db not in the list
08-03 20:24:05.842  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.842  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-03 20:24:05.843  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:24:05.843  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:24:05.844  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:24:05.844  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1bbfb6 removed from the list
08-03 20:24:05.844  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:24:05.844  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:24:05.844  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:05.844  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:24:05.845  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ec5b51 removed from the list
,08-03 20:24:05.846  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:24:05.846  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c2142 added. We now have 2 listener(s)
,08-03 20:24:05.850  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:24:05.850  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 20:24:05.850  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.851  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:24:05.851  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a87553 added. We now have 9 listener(s)
,08-03 20:24:05.851  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:05.852  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 20:24:05.856  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:24:05.868  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:24:05.870  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:24:05.870  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:24:05.870  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:24:05.870  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0e2389 added. We now have 3 listener(s)
08-03 20:24:05.871  4068  4084 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:24:05.871  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:05.872  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:24:05.872  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:24:05.872  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.872  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:05.872  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf0f8e added. We now have 10 listener(s)
08-03 20:24:05.872  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:05.872  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:24:05.873  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:24:05.874  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:24:05.875  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:24:05.875  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:24:05.875  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:24:05.875  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:24:05.875  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 20:24:05.880  3734  3780 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-03 20:24:05.880  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:24:05.883  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:24:05.884  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 20:24:05.884  4068  4084 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-03 20:24:05.884  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:05.884  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:24:05.888  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 20:24:05.888  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:24:05.888  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:24:05.888  3734  3780 D BluetoothAdapter: STATE_ON
,08-03 20:24:05.898  4068  4078 D BtGatt.GattService: registerClient() - UUID=972479e0-f02e-4529-ad06-a9287e91637d
,08-03 20:24:05.898  4068  4084 D BtGatt.GattService: onClientRegistered() - UUID=972479e0-f02e-4529-ad06-a9287e91637d, clientIf=5
08-03 20:24:05.899  3734  3745 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:24:05.899  4068  4107 D BtGatt.GattService: start scan with filters
08-03 20:24:05.899  4068  4084 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:24:05.899  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:05.899  4068  4087 D BtGatt.ScanManager: stopping BLe Batch
,08-03 20:24:05.902  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 20:24:05.902  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:24:05.902  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:24:05.902  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 20:24:05.907  4068  4084 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 20:24:05.907  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:05.908  4068  4087 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:24:05.908  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:24:05.908  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 20:24:05.908  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:24:05.913  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-03 20:24:05.913  4068  4084 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 20:24:05.913  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:05.916  4068  4087 D BtGatt.ScanManager: handling starting scan
,08-03 20:24:05.919  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:24:05.919  3734  3780 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-03 20:24:05.919  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:24:05.919  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:24:05.920  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:24:05.920  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:24:05.920  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:24:05.920  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:24:05.920  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:24:05.921  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9c2142 removed from the list
08-03 20:24:05.921  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:05.921  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a87553 removed from the list
08-03 20:24:05.921  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:24:05.921  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:24:05.922  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.923  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 20:24:05.923  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:05.923  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 20:24:05.925  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:24:05.925  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:24:05.925  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:05.925  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a87553 not in the list
,08-03 20:24:05.925  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:24:05.926  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:24:05.926  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:24:05.926  4068  4084 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 20:24:05.926  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:05.926  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:24:05.926  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:24:05.927  4068  4087 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 20:24:05.928  3734  3780 D BluetoothAdapter: STATE_ON
,08-03 20:24:05.929  4068  4079 D BtGatt.GattService: stopScan() - queue size =1
,08-03 20:24:05.931  4068  4096 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 20:24:05.931  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:24:05.932  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 20:24:05.932  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:24:05.932  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-03 20:24:05.932  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 20:24:05.934  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:24:05.934  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 20:24:05.935  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-03 20:24:05.935  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 20:24:05.936  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:05.937  4068  4084 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-03 20:24:05.937  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:05.937  4068  4087 D BtGatt.ScanManager: Starting BLE batch scan
,08-03 20:24:05.938  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:24:05.938  4068  4087 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:24:05.938  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:24:05.938  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:24:05.938  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:24:05.938  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:24:05.938  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf0f8e removed from the list
08-03 20:24:05.939  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 20:24:05.938  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:24:05.939  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-03 20:24:05.939  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:24:05.939  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 20:24:05.939  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0e2389 removed from the list
08-03 20:24:05.941  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:24:05.941  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@330969a added. We now have 2 listener(s)
,08-03 20:24:05.946  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-03 20:24:05.947  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 20:24:05.947  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.947  4068  4084 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-03 20:24:05.947  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:05.947  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-03 20:24:05.948  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaf3bcb added. We now have 9 listener(s)
,08-03 20:24:05.948  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:05.948  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 20:24:05.960  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:24:05.962  4068  4084 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-03 20:24:05.962  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:24:05.973  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:24:05.975  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:24:05.975  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:24:05.975  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:24:05.975  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29bac1 added. We now have 3 listener(s)
,08-03 20:24:05.977  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:24:05.977  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 20:24:05.977  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:24:05.977  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:05.977  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:05.978  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af18266 added. We now have 10 listener(s)
08-03 20:24:05.978  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:05.978  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:24:05.978  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:24:05.978  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-03 20:24:05.978  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:24:05.978  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:24:05.981  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:24:05.982  3734  3780 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:24:05.983  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:24:05.984  4068  4084 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:24:05.984  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:05.984  4068  4087 D BtGatt.ScanManager: stopping BLe Batch
,08-03 20:24:05.986  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:24:05.986  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:24:05.986  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:24:05.990  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 20:24:05.990  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:24:05.990  3734  3780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:24:05.991  3734  3780 D BluetoothAdapter: STATE_ON
,08-03 20:24:05.991  4068  4084 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:24:05.991  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:05.992  4068  4087 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 20:24:05.995  4068  4078 D BtGatt.GattService: registerClient() - UUID=ca4f6ddb-a949-41a8-9ff3-395fe69c2a47
,08-03 20:24:05.995  4068  4084 D BtGatt.GattService: onClientRegistered() - UUID=ca4f6ddb-a949-41a8-9ff3-395fe69c2a47, clientIf=5
08-03 20:24:05.995  3734  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:24:05.996  4068  4096 D BtGatt.GattService: start scan with filters
,08-03 20:24:05.998  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 20:24:05.998  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:24:05.998  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:24:05.998  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 20:24:05.999  4068  4084 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:24:05.999  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:06.001  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:24:06.001  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 20:24:06.001  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:24:06.002  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 20:24:06.002  4068  4087 D BtGatt.ScanManager: handling starting scan
,08-03 20:24:06.008  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:24:06.008  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:24:06.008  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:24:06.008  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:24:06.008  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:06.008  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:24:06.008  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 20:24:06.008  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@330969a removed from the list
,08-03 20:24:06.008  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:06.009  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaf3bcb removed from the list
08-03 20:24:06.009  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:24:06.009  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 20:24:06.009  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:24:06.009  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-03 20:24:06.009  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:24:06.009  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:24:06.010  4068  4084 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 20:24:06.010  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:06.010  4068  4087 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 20:24:06.011  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:24:06.011  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:24:06.011  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:24:06.011  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eaf3bcb not in the list
,08-03 20:24:06.011  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-03 20:24:06.011  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-03 20:24:06.011  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:24:06.011  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:24:06.011  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:24:06.012  3734  3780 D BluetoothAdapter: STATE_ON
,08-03 20:24:06.012  4068  4107 D BtGatt.GattService: stopScan() - queue size =1
08-03 20:24:06.013  4068  4078 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:24:06.013  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:24:06.013  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 20:24:06.013  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-03 20:24:06.013  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-03 20:24:06.013  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 20:24:06.014  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:24:06.014  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 20:24:06.014  3734  3780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 20:24:06.014  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 20:24:06.015  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:24:06.016  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:24:06.016  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:24:06.016  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:24:06.016  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:24:06.016  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af18266 removed from the list
,08-03 20:24:06.016  3734  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:24:06.016  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 20:24:06.016  3734  3734 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:24:06.016  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:06.016  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:06.016  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:24:06.016  4068  4084 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 20:24:06.016  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:06.016  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29bac1 removed from the list
08-03 20:24:06.016  4068  4087 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:24:06.016  4068  4087 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:24:06.017  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:24:06.017  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2835ef2 added. We now have 2 listener(s)
08-03 20:24:06.018  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 20:24:06.018  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:24:06.019  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:06.019  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:06.019  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a095943 added. We now have 9 listener(s)
,08-03 20:24:06.019  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:06.019  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:24:06.021  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:24:06.026  3734  3780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:24:06.026  4068  4084 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:24:06.026  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:06.028  3734  3780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:24:06.028  3734  3780 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:24:06.028  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:24:06.028  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ca00f9 added. We now have 3 listener(s)
08-03 20:24:06.030  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:24:06.030  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:24:06.030  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:24:06.030  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:24:06.031  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:24:06.031  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4783e added. We now have 10 listener(s)
,08-03 20:24:06.031  3734  3780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:24:06.031  3734  3780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:24:06.031  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:24:06.031  3734  3780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:24:06.031  3734  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:24:06.031  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:24:06.032  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:06.032  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:24:06.032  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:24:06.032  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2835ef2 removed from the list
,08-03 20:24:06.032  4068  4084 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:24:06.032  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:06.032  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:06.032  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a095943 removed from the list
08-03 20:24:06.032  3734  3780 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:24:06.032  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:06.033  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:06.033  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:06.034  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:24:06.034  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:24:06.034  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:24:06.034  3734  3780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a095943 not in the list
08-03 20:24:06.034  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:06.034  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:06.035  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:24:06.035  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:24:06.035  3734  3780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:24:06.035  3734  3780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4783e removed from the list
,08-03 20:24:06.036  3734  3780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:24:06.036  3734  3780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:24:06.036  3734  3780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:24:06.036  3734  3780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:24:06.036  3734  3780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ca00f9 removed from the list
08-03 20:24:06.037  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 20:24:06.037  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 20:24:06.037  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 20:24:06.037  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:24:06.037  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-03 20:24:06.037  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:24:06.038  4068  4084 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:24:06.038  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:06.039  4068  4087 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:24:06.044  3734  4160 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
08-03 20:24:06.044  4068  4084 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:24:06.045  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:24:06.045  4068  4087 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:24:06.050  4068  4084 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:24:06.050  4068  4084 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:24:06.337  3734  3734 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:24:06.440  3734  3734 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:24:06.516  3734  3734 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:24:06.565  1550  1951 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-03 20:24:08.043  3734  3780 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 461
08-03 20:24:08.044  3734  3780 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 461, name: My test thread name)
,08-03 20:24:08.050  3734  4161 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
08-03 20:24:08.050  3734  4161 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 462, thread name: My test thread name)
08-03 20:24:08.050  3734  4161 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-03 20:24:08.055  3734  3780 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:24:08.064  3734  4162 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: My test thread name)
,08-03 20:24:08.065  3734  4162 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 466, thread name: My test thread name): Test exception.
08-03 20:24:08.065  3734  4162 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 466, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-03 20:24:08.067  3734  4160 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
08-03 20:24:08.068  3734  3780 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
08-03 20:24:08.068  3734  3780 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
,08-03 20:24:08.069  3734  3780 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-03 20:24:08.069  3734  3780 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-03 20:24:08.069  3734  3780 D com.test.thalitest.ThaliTestRunner: Total duration: 35921 ms
,08-03 20:24:08.075  3734  3780 I jxcore-log: Total number of executed tests:  82
08-03 20:24:08.075  3734  3780 I jxcore-log: 
,08-03 20:24:08.076  3734  3780 I jxcore-log: Number of passed tests:  82
08-03 20:24:08.076  3734  3780 I jxcore-log: 
08-03 20:24:08.077  3734  3780 I jxcore-log: Number of failed tests:  0
08-03 20:24:08.077  3734  3780 I jxcore-log: 
,08-03 20:24:08.077  3734  3780 I jxcore-log: Number of ignored tests:  0
08-03 20:24:08.077  3734  3780 I jxcore-log: 
08-03 20:24:08.078  3734  3780 I jxcore-log: Total duration:  35921
08-03 20:24:08.078  3734  3780 I jxcore-log: 
,08-03 20:24:08.087  3734  3780 I jxcore-log: Unit Test app is loaded
08-03 20:24:08.087  3734  3780 I jxcore-log: 
,08-03 20:24:08.104  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.104  3734  3780 I jxcore-log: 
,08-03 20:24:08.108  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.108  3734  3780 I jxcore-log: 
,08-03 20:24:08.110  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.110  3734  3780 I jxcore-log: 
,08-03 20:24:08.111  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.111  3734  3780 I jxcore-log: 
08-03 20:24:08.112  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.112  3734  3780 I jxcore-log: 
,08-03 20:24:08.113  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.113  3734  3780 I jxcore-log: 
,08-03 20:24:08.116  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.116  3734  3780 I jxcore-log: 
,08-03 20:24:08.118  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.118  3734  3780 I jxcore-log: 
,08-03 20:24:08.119  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.119  3734  3780 I jxcore-log: 
,08-03 20:24:08.120  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.120  3734  3780 I jxcore-log: 
08-03 20:24:08.121  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.121  3734  3780 I jxcore-log: 
,08-03 20:24:08.123  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:24:08.123  3734  3780 I jxcore-log: 
08-03 20:24:08.124  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.124  3734  3780 I jxcore-log: 
,08-03 20:24:08.125  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.125  3734  3780 I jxcore-log: 
08-03 20:24:08.125  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.125  3734  3780 I jxcore-log: 
,08-03 20:24:08.126  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.126  3734  3780 I jxcore-log: 
08-03 20:24:08.127  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.127  3734  3780 I jxcore-log: 
,08-03 20:24:08.128  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.128  3734  3780 I jxcore-log: 
,08-03 20:24:08.129  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.129  3734  3780 I jxcore-log: 
08-03 20:24:08.130  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.130  3734  3780 I jxcore-log: 
,08-03 20:24:08.130  3734  3734 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 20:24:08.131  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.131  3734  3780 I jxcore-log: 
08-03 20:24:08.132  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.132  3734  3780 I jxcore-log: 
,08-03 20:24:08.133  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.133  3734  3780 I jxcore-log: 
08-03 20:24:08.133  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.133  3734  3780 I jxcore-log: 
08-03 20:24:08.134  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.134  3734  3780 I jxcore-log: 
,08-03 20:24:08.135  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:24:08.135  3734  3780 I jxcore-log: 
08-03 20:24:08.136  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.136  3734  3780 I jxcore-log: 
08-03 20:24:08.136  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 20:24:08.136  3734  3780 I jxcore-log: 
,08-03 20:24:08.137  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.137  3734  3780 I jxcore-log: 
08-03 20:24:08.138  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.138  3734  3780 I jxcore-log: 
08-03 20:24:08.139  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.139  3734  3780 I jxcore-log: 
,08-03 20:24:08.139  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.139  3734  3780 I jxcore-log: 
,08-03 20:24:08.141  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.141  3734  3780 I jxcore-log: 
08-03 20:24:08.141  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:24:08.141  3734  3780 I jxcore-log: 
,08-03 20:24:08.142  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:24:08.142  3734  3780 I jxcore-log: 
08-03 20:24:08.142  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:24:08.142  3734  3780 I jxcore-log: 
08-03 20:24:08.143  3734  3780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:24:08.143  3734  3780 I jxcore-log: 
,08-03 20:24:08.145  3734  3780 I jxcore-log: My device name is: motorola-Nexus 6,
08-03 20:24:08.145  3734  3780 I jxcore-log: 
08-03 20:24:08.146  3734  3780 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 20:24:08.146  3734  3780 I jxcore-log: 
,08-03 20:24:10.357  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 20:24:10.357  3734  3780 I jxcore-log: 
,08-03 20:24:10.965  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 20:24:10.965  3734  3780 I jxcore-log: 
,08-03 20:24:10.989  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 20:24:10.989  3734  3780 I jxcore-log: 
,08-03 20:24:12.334  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 20:24:12.334  3734  3780 I jxcore-log: 
,08-03 20:24:12.560  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-03 20:24:12.560  3734  3780 I jxcore-log: 
,08-03 20:24:12.565  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-03 20:24:12.565  3734  3780 I jxcore-log: 
,08-03 20:24:12.569  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-03 20:24:12.569  3734  3780 I jxcore-log: 
,08-03 20:24:12.586  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-03 20:24:12.586  3734  3780 I jxcore-log: 
,08-03 20:24:12.590  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-03 20:24:12.590  3734  3780 I jxcore-log: 
,08-03 20:24:13.258  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-03 20:24:13.258  3734  3780 I jxcore-log: 
,08-03 20:24:13.272  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-03 20:24:13.272  3734  3780 I jxcore-log: 
,08-03 20:24:13.282  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-03 20:24:13.282  3734  3780 I jxcore-log: 
,08-03 20:24:13.289  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-03 20:24:13.289  3734  3780 I jxcore-log: 
,08-03 20:24:13.338  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-03 20:24:13.338  3734  3780 I jxcore-log: 
,08-03 20:24:13.393  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-03 20:24:13.393  3734  3780 I jxcore-log: 
,08-03 20:24:13.401  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-03 20:24:13.401  3734  3780 I jxcore-log: 
,08-03 20:24:13.565  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
08-03 20:24:13.565  3734  3780 I jxcore-log: 
,08-03 20:24:13.591  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
08-03 20:24:13.591  3734  3780 I jxcore-log: 
,08-03 20:24:13.596  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
08-03 20:24:13.596  3734  3780 I jxcore-log: 
,08-03 20:24:13.602  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
08-03 20:24:13.602  3734  3780 I jxcore-log: 
,08-03 20:24:13.634  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js,
08-03 20:24:13.634  3734  3780 I jxcore-log: 
,08-03 20:24:13.716  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js,
08-03 20:24:13.716  3734  3780 I jxcore-log: 
,08-03 20:24:13.728  3734  3780 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js,
08-03 20:24:13.728  3734  3780 I jxcore-log: 
,08-03 20:24:14.056  3734  3780 I jxcore-log: ERROR runTests: 
,08-03 20:24:14.056  3734  3780 I jxcore-log: 
,08-03 20:24:14.058  3734  3780 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
,08-03 20:24:14.058  3734  3780 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-03 20:24:14.058  3734  3780 I jxcore-log: WARN testUtils: logCallback not set!
08-03 20:24:14.058  3734  3780 I jxcore-log: 
,08-03 20:24:14.069  3734  3780 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _functionName: 'loadFile',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _lineNumber: '26',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _columnNumber: '11',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-03 20:24:14.069  3734  3780 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _functionName: '',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _lineNumber: '39',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _columnNumber: '7',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-03 20:24:14.069  3734  3780 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _functionName: '',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _lineNumber: '35',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _columnNumber: '3',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-03 20:24:14.069  3734  3780 I jxcore-log:   { _fileName: 'module.js',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _functionName: '$w.prototype._compile',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _lineNumber: '621',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _columnNumber: '8',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-03 20:24:14.069  3734  3780 I jxcore-log:   { _fileName: 'module.js',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _lineNumber: '651',
08-03 20:24:14.069  3734  3780 I jxcore-log:     _columnNumber: '1',
08-03 20:24:14.069  3734  3780 I jxcore-log:    
08-03 20:24:14.069  3734  3780 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-03 20:24:14.069  3734  3780 I jxcore-log: 
08-03 20:24:14.069  3734  3780 E jxcore-log: Error: 
,08-03 20:24:14.069  3734  3780 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
08-03 20:24:14.069  3734  3780 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-03 20:24:14.069  3734  3780 E jxcore-log: 
08-03 20:24:14.070  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:24:14.070  3734  3780 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-03 20:24:14.071  3734  3780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:24:14.071  3734  3780 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-03 20:24:14.375  1638  1765 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-03 20:24:14.376  1638  1765 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-03 20:24:14.420  1550  1550 I ConfigService: onCreate
,08-03 20:24:14.751  4163  4163 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-03 20:24:14.756  4163  4163 D AndroidRuntime: CheckJNI is OFF
,08-03 20:24:14.792  4163  4163 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-03 20:24:14.833  4163  4163 I Radio-JNI: register_android_hardware_Radio DONE
,08-03 20:24:14.853  4163  4163 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 20:24:14.868   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-03 20:24:14.869   873   886 I ActivityManager: Killing 3734:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-03 20:24:14.952   873   896 W PackageSettings: Skipping PackageSetting{dd5b9c9 com.example.hello/10273} due to missing metadata
,08-03 20:24:14.984   873   896 I art     : Starting a blocking GC Explicit
,08-03 20:24:15.001   873  1751 D GraphicsStats: Buffer count: 2
,08-03 20:24:15.002   873  2992 I WindowState: WIN DEATH: Window{13801ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 20:24:15.002   873  1308 D WifiService: Client connection lost with reason: 4
,08-03 20:24:15.027   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-03 20:24:15.028   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-03 20:24:15.028   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-03 20:24:15.028   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-03 20:24:15.028   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:24:15.028   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.028   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 20:24:15.028   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 20:24:15.029   873   886 I ActivityManager:   Force finishing activity ActivityRecord{29ddc54 u0 com.test.thalitest/.MainActivity t2}
,08-03 20:24:15.045   873   884 W ActivityManager: Spurious death for ProcessRecord{1f06910 0:com.test.thalitest/u0a0}, curProc for 3734: null
08-03 20:24:15.046   873   896 I art     : Explicit concurrent mark sweep GC freed 17481(1161KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.544ms total 56.203ms
,08-03 20:24:15.073   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-03 20:24:15.076  4163  4163 I art     : System.exit called, status: 0
08-03 20:24:15.076  4163  4163 I AndroidRuntime: VM exiting with result code 0.
,08-03 20:24:15.108   873   896 I ActivityManager: Start proc 4174:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-03 20:24:15.109   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-03 20:24:15.141   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-03 20:24:15.146  1638  1638 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-03 20:24:15.151  4068  4068 D BluetoothMapAppObserver: onReceive
,08-03 20:24:15.151  4068  4068 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-03 20:24:15.157   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 20:24:15.160  1638  4187 I Keyboard.Facilitator.DecoderInitializer: run()
,08-03 20:24:15.162  1961  2052 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-03 20:24:15.165  3543  3543 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-03 20:24:15.168  1638  4187 I Decoder : createOrResetDecoder
,08-03 20:24:15.189   873  1751 I ActivityManager: Start proc 4190:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-03 20:24:15.218  1717  1717 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-03 20:24:15.224   873  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-03 20:24:15.233   873  2992 I ActivityManager: Killing 2086:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-03 20:24:15.244   873   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3734 uid 10000
,08-03 20:24:15.245  1638  1638 I Keyboard.Facilitator: onFinishInput()
,08-03 20:24:15.251  1638  4187 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-03 20:24:15.251   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-03 20:24:15.283  4190  4190 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-03 20:24:15.309  1638  4187 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-03 20:24:15.310  1638  4187 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-03 20:24:15.310  1638  4187 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-03 20:24:15.313  1638  4187 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-03 20:24:15.313  1638  4187 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-03 20:24:15.315  1638  4187 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-03 20:24:15.315  1638  4187 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-03 20:24:15.318  1638  4187 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-03 20:24:15.318  1638  4187 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-03 20:24:15.318  1638  4187 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-03 20:24:15.318  1638  4187 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-03 20:24:15.318  1638  4187 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-03 20:24:15.318  1638  4187 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-03 20:24:15.319  1731  1822 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-03 20:24:15.323   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-03 20:24:15.324   873   885 E PackageManager: Failed to write settings, restoring backup
08-03 20:24:15.324   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-03 20:24:15.324   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-03 20:24:15.324   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-03 20:24:15.324   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-03 20:24:15.324   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-03 20:24:15.324   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:24:15.324   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.324   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 20:24:15.334   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-03 20:24:15.334   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 20:24:15.334   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 20:24:15.334   873   886 E DropBoxManagerService: 	... 13 more
,08-03 20:24:15.336   873  1667 I ActivityManager: Start proc 4206:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-03 20:24:15.337  1731  1822 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 20:24:15.337  1731  1822 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1731
08-03 20:24:15.337  1731  1822 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.337  1731  1822 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 20:24:15.339  4190  4190 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-03 20:24:15.343   873  4211 E DropBoxManagerService: Can't write: system_app_crash
08-03 20:24:15.343   873  4211 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 20:24:15.343   873  4211 E DropBoxManagerService: 	... 5 more
,08-03 20:24:15.344   873  2992 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-03 20:24:15.357  1731  1822 I Process : Sending signal. PID: 1731 SIG: 9
,08-03 20:24:15.377   873  1673 I ActivityManager: Start proc 4220:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-03 20:24:15.385  4190  4225 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-03 20:24:15.409  4190  4204 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.409  4190  4204 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.409  4190  4204 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 20:24:15.452   873  1296 W InputDispatcher: channel '30ec754 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-03 20:24:15.452   873  1296 E InputDispatcher: channel '30ec754 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-03 20:24:15.455   873  1383 D GraphicsStats: Buffer count: 1
,08-03 20:24:15.455   873   883 I WindowState: WIN DEATH: Window{30ec754 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-03 20:24:15.455   873   883 W InputDispatcher: Attempted to unregister already unregistered input channel '30ec754 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,08-03 20:24:15.463   873  1752 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1731) has died
,08-03 20:24:15.465   873  1752 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-03 20:24:15.470   873  1752 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-03 20:24:15.497   873   886 I ActivityManager: Start proc 4235:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-03 20:24:15.507  4220  4220 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-03 20:24:15.541  2017  4246 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-03 20:24:15.545  2017  4246 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-03 20:24:15.546  1550  1550 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-03 20:24:15.547  4235  4235 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:24:15.547  4235  4235 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 20:24:15.547  4235  4235 D AndroidRuntime: Shutting down VM
08-03 20:24:15.549  1550  1550 D AndroidRuntime: Shutting down VM
08-03 20:24:15.550  1550  1550 E AndroidRuntime: FATAL EXCEPTION: main
08-03 20:24:15.550  1550  1550 E AndroidRuntime: Process: com.google.process.gapps, PID: 1550
08-03 20:24:15.550  1550  1550 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-03 20:24:15.550  1550  1550 E AndroidRuntime: 	... 8 more
,08-03 20:24:15.556   873  4251 E DropBoxManagerService: Can't write: system_app_crash
08-03 20:24:15.556   873  4251 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 20:24:15.556   873  4251 E DropBoxManagerService: 	... 5 more
,08-03 20:24:15.561  1550  1550 I Process : Sending signal. PID: 1550 SIG: 9
08-03 20:24:15.561  4235  4235 E AndroidRuntime: FATAL EXCEPTION: main
08-03 20:24:15.561  4235  4235 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4235
08-03 20:24:15.561  4235  4235 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 20:24:15.561  4235  4,235 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 20:24:15.561  4235  4235 E AndroidRuntime: 	... 10 more
08-03 20:24:15.563   873  1667 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-03 20:24:15.564  4235  4235 I Process : Sending signal. PID: 4235 SIG: 9
,08-03 20:24:15.566   873  4252 E DropBoxManagerService: Can't write: system_app_crash
08-03 20:24:15.566   873  4252 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 20:24:15.566   873  4252 E DropBoxManagerService: 	... 5 more
,08-03 20:24:15.575   873  2992 I ActivityManager: Killing 3600:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-03 20:24:15.577  2017  4246 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-03 20:24:15.577  2017  4246 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-03 20:24:15.579   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
